[<img src="https://cdn-images-1.medium.com/max/1600/0*MXYivtrvfMI2nZXU." align="center" width="850">](http://flutter.io)


## Contents

- [Articles](#articles)
  - [Videos](#videos)
  - [Patterns](#patterns)
  - [Layout](#layout)
- [Widgets](#widgets)
- [Plugins](#plugins)
- [Examples](#examples)

## Articles

### Patterns

- [MVVM in Flutter using Dart Streams](https://quickbirdstudios.com/blog/mvvm-in-flutter/)
- [MVP 在 flutter 中的應用](https://www.jianshu.com/p/7b2d83f8109f)
### Videos

- [Flutter Widget of the Week (Google Developers)](https://www.youtube.com/watch?v=lkF0TQJO0bA&list=PLOU2XLYxmsIL0pH0zWe_ZOHgGhZ7UasUE) - 官方 Youtube 教學影片, 介紹各種 Widget 使用

### Layout
   - [Updating the UI based on orientation](https://flutter.io/docs/cookbook/design/orientation) - 包覆 OrientationBuilder 取得orientation
  - [How does Flutter handle orientation change](https://stackoverflow.com/questions/49663494/how-does-flutter-handle-orientation-change) - ``MediaQuery.of(context).orientation``取得 orientation
  
## Widgets
  - [數字鍵盤](https://gist.github.com/WarrenLin/c5ef2e73ef5265505e427926aaa4e8bc#file-widget_abacus-dart)

## Plugins

### Scanner
- [flutter_barcode_reader](https://github.com/apptreesoftware/flutter_barcode_reader) - 
A flutter plugin for scanning 2D barcodes and QR codes.不能調整 Camera, 因為是直接呼叫外部原生去處理, Layout 已經固定寫好了.
- [Fast QR Reader View Plugin](https://github.com/facundomedica/fast_qr_reader_view) - A Flutter plugin to scan multiple type of codes. minimum Android sdk version to 21. iphone 6 上跑起來算順, 但是 Camera 畫面有點模糊.
- [QR Mobile Vision](https://github.com/rmtmckenzie/flutter_qr_mobile_vision/) - 使用 Google's Mobile Vision API, 可以自定義 Camera size. 在 iphone 6 上跑起來 Camera fps 不是很順, iphone 8 順暢.

## Examples
- [flutter_architecture_samples](https://github.com/brianegan/flutter_architecture_samples) - 使用各種架構實作 Todo List.
