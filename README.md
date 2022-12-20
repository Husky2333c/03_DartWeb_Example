# 03_DartWeb_Example

Dart Web的应用示例：与AntV可视化进行集成

## 一、参考资料

- AntV可视化组件 [https://antv.antfin.com/zh-cn/index.html](https://antv.antfin.com/zh-cn/index.html)

- Dart JS文档 [https://api.dart.cn/stable/2.16.2/dart-js/dart-js-library.html](https://api.dart.cn/stable/2.16.2/dart-js/dart-js-library.html)

## 二、练习

找一种你喜欢的AntV可视化组件，然后用Dart来修改其显示数据。

$ brew tap dart-lang/dart && brew install dart && dart pub get

$ dart create -t web-simple name

dart pub add build_runner build_web_compilers --dev
dart pub global activate webdev
export PATH="$PATH":"$HOME/.pub-cache/bin"
dart pub get
webdev serve