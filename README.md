# PetTokenBar

Codex와 Claude Code의 오늘 토큰 사용량을 메뉴바에서 보고, 바탕화면에서 픽셀 반려견을 돌보는 macOS 앱입니다. 토큰 사용량은 이 Mac의 로컬 기록에서 집계합니다.

macOS 14 이상이 필요합니다. Apple Silicon과 Intel Mac을 지원합니다.

## 설치

[최신 GitHub Release](https://github.com/hofe7/PetTokenBar/releases/latest)에서 ZIP을 받은 뒤, 압축을 풀고 `PetTokenBar.app`을 응용 프로그램 폴더로 옮기세요.

Homebrew를 쓴다면 다음 명령으로 설치할 수 있습니다. Homebrew 6 이상에서는 처음 한 번 cask 신뢰 설정이 필요합니다.

```sh
brew tap hofe7/tap
brew trust --cask hofe7/tap/pettokenbar
brew install --cask hofe7/tap/pettokenbar
```

앱은 ad-hoc 서명으로 배포합니다. 첫 실행 때 macOS가 확인을 요구할 수 있습니다. [Apple의 앱 실행 안내](https://support.apple.com/ko-kr/102445)를 참고하세요.

## 업데이트

앱을 종료한 다음 아래 명령을 실행하세요.

```sh
brew update
brew upgrade --cask hofe7/tap/pettokenbar
```

ZIP으로 설치했다면 새 릴리스의 앱으로 교체하세요. 이전 이름 MaltiBar로 사용하던 반려견과 설정도 PetTokenBar에서 이어서 사용할 수 있습니다. 이름이 바뀌는 첫 실행 전에는 MaltiBar를 종료하세요.
