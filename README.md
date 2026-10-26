# SOP 배달 Android 데모

안드로이드 WebView 기반의 오프라인 시제품입니다. 주문은 기기 내 localStorage에만 저장됩니다. 실제 배달 주문, 결제, 서버 연동, 사용자 인증은 구현되지 않았습니다.

## GitHub에서 APK 만들기
1. 이 프로젝트의 파일 및 폴더 구조를 GitHub 저장소 루트에 업로드합니다.
2. 저장소의 Actions 탭에서 `Build SOP APK` 워크플로를 실행합니다 (`Run workflow`).
3. 성공한 실행의 Artifacts에서 `SOP-Delivery-debug-APK`를 다운로드하고 압축을 풉니다.
4. `app-debug.apk`를 안드로이드에 설치합니다. 설치 전 파일 출처를 확인하세요.

`app/src/main/assets/index.html`이 앱 화면입니다. 저장소 루트의 `index.html`은 Android APK 빌드에 사용되지 않습니다.
