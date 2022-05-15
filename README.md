# flutter_js
플로터로 앱을 만들 때 자바스크립트 오류 나거나 버전테스트 오류 날 때 해결하는 방법
1. google 에서 'techwithsam ' 검색
2. 소스 파일을 main.dart 파일에 넣어준다.
3. pubspec.yaml 소스에 추가
  cupertino_icons: ^1.0.2
  flutter_inappwebview: ^5.2.1
  webview_flutter:
  connectivity: ^3.0.3
  url_launcher:
dev_dependencies:
  flutter_test:
    sdk: flutter
  integration_test:
    sdk: flutter

4. android>app>main> AndroidManifest.xml

   <application
        android:label="ailotto"
        android:icon="@mipmap/ic_launcher"
        android:name="io.flutter.app.FlutterApplication"
        android:usesCleartextTraffic="true">

5. android>app>build.gradle 에서 minsdkversion을 16에서 17로 변경해줌

