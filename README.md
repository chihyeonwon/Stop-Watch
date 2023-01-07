# stopwatch
```
개발 툴 : Flutter
개발 언어 : Dart
개발 일시 : 2023-01-07 ~
개발자 : Won Chi Hyeon
```

### 앱소개
```
앱 이름 : StopWatch
앱 기능 : 타이머를 시작, 일시정지하고 초기화할 수 있습니다.
          타이머 실행 중에 랩타임을 측정하여 표시합니다.
핵심 구성 요소 : Timer : 일정 시간 간격으로 지정한 동작을 수행하게 하는 클래스
```

### 화면 구성
```
스톱워치는 화면이 하나인 앱입니다.
화면에 표시되는 시간은 계속 변화하기 때문에 상태가 있는 StatefulWidget으로 구성하였습니다.
```
![image](https://user-images.githubusercontent.com/58906858/211133203-5ea38b67-57e4-454a-880d-9be4dce7ec9e.png)

#### 화면 하단 AppBar 생성
```
높이 50의 하단 AppBar를 생성하였습니다.
```
![image](https://user-images.githubusercontent.com/58906858/211133368-0566cc82-58da-4601-b662-3ca8b1b72b10.png)

#### 시작 또는 일시정지 클릭 버튼 생성
```
시작 또는 일시정지 클릭 버튼을 floatingActionButton을 생성하였습니다.
클릭했을 때 작동하는 이벤트 메서드는 나중에 작성합니다.
```
![image](https://user-images.githubusercontent.com/58906858/211133428-498bc578-b04b-4e16-af8f-e91e71e62bdc.png)