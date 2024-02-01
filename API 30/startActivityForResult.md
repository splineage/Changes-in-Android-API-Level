# startActivityForResult

## androidx.activity 1.2.0-alpha02

### ActivityResultRegistry

- `ComponentActivity` 가 `ActivityResultRegistry` 를 제공하여 `Activity` 또는 `Fragment` 내 메서드를 재정의하지 않고도 `startActivityForResult()` + `onActivityResult()` 뿐 아니라 `requestPermissions()` + `onRequestPermissionsResult()` 플로우를 처리하도록 지원하고 ActivityResultContract 를 통해 유형 안정성을 높임.

### Activity 에서 결과 가져오기 참조 링크

[활동에서 결과 가져오기  |  Android 개발자  |  Android Developers](https://developer.android.com/training/basics/intents/result?authuser=1&hl=ko)

기존 `startActivityForResult()` 및 `onActivityResult()` API 는 모든 API 수준의 `Activity` 클래스에서 사용할 수 있지만 AndroidX `Activity` 및 `Fragment` 클래스에 도입된  Activity Result API 를 사용하는 것을 추천. 

Activity Result API 는 시스템에서 결과가 전달되면 이를 등록, 실행, 처리하기 위한 구성요소를 제공함.

> 주의사항
**참고:** 프래그먼트나 활동을 만들기 전에 **`registerForActivityResult()`**를 호출해야 합니다.
>
