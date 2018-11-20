[<img src="https://cdn-images-1.medium.com/max/1600/0*MXYivtrvfMI2nZXU." align="center" width="850">](http://flutter.io)


## Contents

- [Articles](#articles)
  - [Videos](#videos)
  - [Patterns](#patterns)
  - [Layout](#layout)
- [Widgets](#widgets)
- [Plugins](#plugins)
- [Examples](#examples)
- [IDEs](#ides)

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
  - [數字鍵盤](https://gist.github.com/WarrenLin/c5ef2e73ef5265505e427926aaa4e8bc#file-widget_abacus-dart) - 須自行添加或更換 'assets/backspace.png' 圖檔.
  - [帳密登入](https://gist.github.com/WarrenLin/785a98fdad3b15a9567b0df0d00a63ee) - Add dependencies: shared_preferences: ^0.4.3 fluttertoast: ^2.1.0

## Plugins

### Scanner
- [flutter_barcode_reader](https://github.com/apptreesoftware/flutter_barcode_reader) - 
A flutter plugin for scanning 2D barcodes and QR codes.不能調整 Camera, 因為是直接呼叫外部原生去處理, Layout 已經固定寫好了.
- [Fast QR Reader View Plugin](https://github.com/facundomedica/fast_qr_reader_view) - A Flutter plugin to scan multiple type of codes. minimum Android sdk version to 21. iphone 6 上跑起來算順, 但是 Camera 畫面有點模糊.
- [QR Mobile Vision](https://github.com/rmtmckenzie/flutter_qr_mobile_vision/) - 使用 Google's Mobile Vision API, 可以自定義 Camera size. 在 iphone 6 上跑起來 Camera fps 不是很順, iphone 8 順暢.

### WebView
- [flutter_webview_plugin](https://github.com/fluttercommunity/flutter_webview_plugin) - 在Flutter可以內嵌Native Webview
WebView效能不是很好，可以監聽到事件start loading, loading, finish loading，但無法從中截斷，兩個平台有些差異
- [flutter_inappbrowser](https://github.com/pichillilorenzo/flutter_inappbrowser) - 看起來非常完整

### HTML Viewer
- [parse HTML tag into widget](https://gist.github.com/Katarn/da6c45795247c4e882e337317a1050bd)
- [FlutterHTMLView](https://proandroiddev.com/flutter-render-html-2a51f73f9db)
- [flutter_html](https://github.com/Sub6Resources/flutter_html) - 目前看來支援度最高
- [html_widget](https://github.com/google/flutter.widgets/tree/master/lib/src/html_widget) - 這是Google自己出的

### Deeplink
- [url_launcher](https://github.com/flutter/plugins/tree/master/packages/url_launcher) - 可以從Flutter依照Deeplink啟動App
兩個平台使用上有些坑，Android的deep link常常是intent://gomaji://...，這個必須得過濾成gomaji://且不能大寫。iOS的canOpenUrl()總是回傳false

### Shared preferences (數據儲存)
- [Shared preferences](https://github.com/flutter/plugins/tree/master/packages/shared_preferences) - Wraps NSUserDefaults (on iOS) and SharedPreferences (on Android).

### Toast
- [FlutterToast](https://github.com/PonnamKarthik/FlutterToast)

### Route
- [navigate](https://github.com/ravipatel147/navigate) -A new Flutter package for Byutifull navigation.

## Examples
- [flutter_architecture_samples](https://github.com/brianegan/flutter_architecture_samples) - 使用各種架構實作 Todo List.

## IDEs
- [Android Studio / IntelliJ](https://flutter.io/docs/development/tools/ide/android-studio)
- [Visual Studio Code](https://flutter.io/docs/development/tools/ide/vs-code)
