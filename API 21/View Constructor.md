# View Constructor

Android API 21 (Android 5.0 Lollipop) 이상부터 View 클래스의 생성자에 매개변수가 추가됨.   
따라서 CustomView 를 만들때 API 21 미만인 경우,   
@JvmOverloads 어노테이션으로 매개변수 4개를 사용하는 생성자를 생성하는 경우 컴파일 에러가 발생함.
