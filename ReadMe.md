## 폴더 분류

- Views 폴더
  - Views 폴더는 말그대로 사용자가 처음 접하는 화면입니다.
  - 여기서 그리드 레이아웃을 이용해서 디자인을 하고 데이터바인딩을 통해 ViewModel과 연결하는 코드들이 작성되는 곳입니다.

- Models 폴더
  - Models 폴더에서는 해당 프로젝트의 비즈니스로직이 작성되는 곳입니다.
  - 예를 들어 주소록이라면 이름, 나이, 이메일 등의 가장 기본적인 변수들을 생성하는 곳이라고 보시면 됩니다.

- ViewModels 폴더
  - ViewModels 폴더에서는 Model의 비즈니스 로직과 Command 폴더의 ICommand 인터페이스를 받아와서 처리하는 곳입니다.
  - 여기서 작성된 코드가 View와 데이터 바인딩이 되신다고 보면 될 것 같습니다.

- Command 폴더
  - Command 폴더에서는 버튼, 메뉴아이템, 리스트 뷰등의 상황에 맞게 데이터바인딩과의 관계를 정의해주는 공간입니다.

- Resources 폴더
  - Resources 폴더는 View에서 보여지는 Style을 정의하는 곳입니다.
  - 해당 프로젝트의 App.xaml이 가장 먼저 실행되면서 MainWindow를 호출하고, 다양한 스타일 리소스들을 연결하는 것입니다.
