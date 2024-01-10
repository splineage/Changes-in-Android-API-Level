# Android Gradle 플러그인 4.0.0 이후 버전에서 AIDL 적용 
buildFeatures 블록을 사용하여 원하는 기능만 사용 설정함으로써 프로젝트의 빌드 성능 최적화 가능
모듈 수준의 build.gradle 파일에 옵션 설정 필요

```bash
android{
  ...
  aidl = true
  ...
```
