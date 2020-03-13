# DS4Free
Mac OS에서 PS4 Remote Play 사용 시 DualShock4 없이 키보드, 마우스를 이용하여 게임을 플레이 할 수 있습니다.

최근에 라스트 오브 어스를 플레이 하기 시작하면서 밖에서 잠깐씩 맥북만 가지고 게임을 하고 싶은 마음에 시작한 일이 이제야 눈에 보이기 시작했네요.

현재는 플레이에 필요한 기본적인 기능들이 구현되어 있으며, 프리셋 공유나 버튼 연타, 자이로 액션 등 여러가지 키보드,마우스 만으로 부족한 기능들을 구상하고 있으나 아직 미흡한 점이 많습니다. 

개인 시간을 조금씩 투자하여 개발하고 있으므로 버그 등은 이슈를 등록하여 주시면 천천히 수정해보도록 하겠습니다.

다운로드 : (https://github.com/akirose/ds4free-release/releases)


## 사용법
DS4Free.app을 실행하면 PS4 Remote Play(/Application/RemotePlay.app)를 실행합니다.

정상 실행되면 아래 이미지와 같이 메뉴바에 십자키 모양의 메뉴가 추가 됩니다.

![Menu](https://user-images.githubusercontent.com/6344563/76392805-a82d6880-63b5-11ea-9d0a-0d7b65e1a9e5.png)

Remote Play 첫 화면은 듀얼쇼크4가 연결된 상태로 실행이 됩니다.

초기 설정된 키는 L-Stick (WASD), R-Stick (Mouse), DPad (방향키), Share (Z), Options (C), PS (P), Touchpad (T), L1 (Q), R1 (E), L2 (Mouse R), R2 (Mouse L), L3 (X), R3 (V) 입니다.

'시작하기' 버튼 또는 'C (Options)' 키를 눌러 리모트 플레이를 시작합니다.

리모트 플레이가 연결되면 마우스 사용을 위해 마우스 커서가 사라지며 Remote Play 창에 자동으로 고정됩니다. 마우스 커서 잠금키(기본값 : 우측 Option키)를 이용하여 마우스 커서를 해제하거나 고정할 수 있습니다.

## 환경설정

### 일반 (미지원)
현재 게임패드 관련은 적용이 되고 있지 않습니다.

### 마우스
![Mouse](https://user-images.githubusercontent.com/6344563/76393983-09eed200-63b8-11ea-83f4-2f46cb9935e6.png)

1. 마우스를 아날로그 스틱으로 사용 : 마우스를 아날로그 스틱으로 사용할 지 여부를 결정
2. 마우스 커서 잠금키 : 마우스를 게임 내에서 사용 시 커서를 리모트 플레이 창에 고정 / 해제
3. 마우스 감도 : 마우스 이동 감도
4. 마우스 감도 저항 : 마우스 이동 감도에 대한 저항으로 값이 커질 수록 저항이 커져 이동량이 줄어듬
5. 아날로그 스틱 데드존 : 리모트 플레이가 받아들이는 아날로그 스틱에 대한 데드존 설정

### 조작
![Control](https://user-images.githubusercontent.com/6344563/76393998-12dfa380-63b8-11ea-96bb-8c6a9433c43c.png)

1. 프리셋
좌측 상단의 '+', '-' 버튼으로 프리셋을 추가/제거할 수 있으며, '기본값' 또는 현재 사용중인 프리셋은 삭제되지 않습니다.
프리셋의 이름 변경은 변경할 프리셋을 선택한 후 콤보박스에 변경할 이름을 작성 후 엔터키를 입력하면 수정 됩니다.

2. 키 (버튼)
좌측 하단의 '추가', '삭제' 버튼으로 키를 추가할 수 있으며, '입력키' 컬럼을 더블클릭하여 사용할 키를 입력하고 대응할 게임패드의 버튼을 '버튼' 컬럼에 선택합니다.
여러 개의 버튼을 선택하면 해당 버튼이 동시에 입력 됩니다.

설정된 프리셋은 상단의 메뉴에서 프리셋 메뉴에 추가되며, 프리셋 선택 시 현재 선택된 프리셋 앞에 체크 표시 됩니다.

환경설정 창을 닫으면 해당 설정이 저장 됩니다.


## 후원
이 프로그램이 유용하셨다면 개발자에게 커피 한잔을 후원할 수 있습니다! :)

<a href="https://ko-fi.com/ds4free" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 21px;width: 90px;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>
