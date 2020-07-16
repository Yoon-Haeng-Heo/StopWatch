# StopWatch
StopWatch 구현 프로젝트
*use Android studio with Kotlin*

## 기능
+ 타이머를 시작, 일시정지하고 초기화 가능
+ 타이머 실행 중에 랩타임 측정하여 표시

## 핵심 구성요소
+ timer : 일정 시간 간격으로 코드를 백그라운드 스레드에서 실행
+ runOnUiThread : main Thread에서 UI를 갱신
+ ScrollView : 랩타임을 표시할 때 상하로 scroll가능한 view를 사용
+ FloatingActionButton : material 디자인의 둥근 모양의 버튼

## 라이브러리 설정 
+ vector Drawable 하위 호환 설정 : Android 5.0 미만에서 vector drawable지원하는 라이브러리
+ design 라이브러리 : FloatingActionButton 등 material design을 제공하는 라이브러리

