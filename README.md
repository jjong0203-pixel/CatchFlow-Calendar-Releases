# CatchFlow Calendar 배포

캐치플로우 캘린더(CatchFlow Calendar): 로그인 없이 폴더째 들고 다니는 Windows 포터블 캘린더의 배포 파일만 있는 저장소입니다.

## 받기

[최신 버전 받기](https://github.com/jjong0203-pixel/CatchFlow-Calendar-Releases/releases/latest) → `CatchFlow_Calendar_…_Portable_Windows_x64.exe`

- 원하는 폴더에 두고 실행하면 같은 폴더에 `Data`가 생기고 거기에 일정이 저장됩니다.
- 앱을 켤 때 새 버전을 알려 줍니다. 누르면 바뀐 파일만 받아 EXE 옆 `App` 폴더에 두고 다시 켭니다(Data는 그대로).
- 다른 PC나 USB로 옮길 때는 EXE와 `Data`(있으면 `App`도)를 함께 옮깁니다.

## 이 저장소

- `channels/stable.json`: 앱이 확인하는 업데이트 목록(서명됨). 앱은 서명이 맞는 목록만 믿습니다.
- 릴리즈의 `f-….gz`: 업데이트 때 앱이 받는 부분 파일입니다. 여러 버전에서 함께 쓰므로 옛 릴리즈를 지우지 않습니다.
- 소스는 이곳에 없습니다.
