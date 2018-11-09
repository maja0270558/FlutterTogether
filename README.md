[<img src="https://cdn-images-1.medium.com/max/1600/0*MXYivtrvfMI2nZXU." align="center" width="850">](http://flutter.io)


## Contents

- [Articles](#articles)
  - [Videos](#videos)
  - [Patterns](#patterns)
  - [Layout](#layout)
- [Widgets](#widgets)
- [Plugins](#plugins)

## Articles

### Patterns

- [MVVM in Flutter using Dart Streams](https://quickbirdstudios.com/blog/mvvm-in-flutter/)
- [MVP 在 flutter 中的應用](https://www.jianshu.com/p/7b2d83f8109f)
### Videos

- [Flutter Widget of the Week (Google Developers)](https://www.youtube.com/watch?v=lkF0TQJO0bA&list=PLOU2XLYxmsIL0pH0zWe_ZOHgGhZ7UasUE) - 官方Youtube教學影片,介紹各種Widget使用

### Layout
   - [Updating the UI based on orientation](https://flutter.io/docs/cookbook/design/orientation) - 包覆OrientationBuilder取得orientation
  - [How does Flutter handle orientation change](https://stackoverflow.com/questions/49663494/how-does-flutter-handle-orientation-change) - ``MediaQuery.of(context).orientation``取得orientation
  
## Widgets

## Plugins

### Scanner
- [flutter_barcode_reader](https://github.com/apptreesoftware/flutter_barcode_reader) - 
A flutter plugin for scanning 2D barcodes and QR codes.不能調整Camera, 因為是直接呼叫外部原生去處理, Layout已經固定寫好了.
- [Fast QR Reader View Plugin](https://github.com/facundomedica/fast_qr_reader_view) - A Flutter plugin to scan multiple type of codes. minimum Android sdk version to 21. iphone 6 上跑起來算順, 但是Camera畫面有點模糊.
- [QR Mobile Vision](https://github.com/rmtmckenzie/flutter_qr_mobile_vision/) - 使用 Google's Mobile Vision API, 可以自定義Camera size. 在iphone 6上跑起來 Camera fps 不是很順, iphone 8 順暢.
