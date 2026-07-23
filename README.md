# Roll20 채팅 매크로 생성기

Roll20 채팅에서 사용할 수 있는 Discord DM 스타일 및 LINE 스타일 매크로 생성기입니다.

## 포함 파일

- `index.html` — 생성기 선택 화면
- `discord.html` — Discord DM 조립식 매크로 생성기 v19
- `line.html` — LINE 메시지 매크로 생성기 v4
- `.nojekyll` — GitHub Pages가 파일을 그대로 배포하도록 지정

## GitHub Pages 배포

1. GitHub에서 새 저장소를 만듭니다.
2. 이 폴더의 파일을 저장소 루트에 업로드합니다.
3. 저장소의 `Settings` → `Pages`로 이동합니다.
4. `Build and deployment`의 Source를 `Deploy from a branch`로 선택합니다.
5. Branch를 `main`, 폴더를 `/(root)`로 선택하고 저장합니다.
6. 표시된 Pages 주소로 접속합니다.

프로젝트 저장소의 기본 주소는 일반적으로 다음 형태입니다.

`https://사용자명.github.io/저장소명/`

## 업데이트

새 HTML 버전으로 `discord.html` 또는 `line.html`을 교체한 뒤 커밋하면 됩니다.

## 데이터

생성기가 저장하는 프로필과 대화 구성은 브라우저 `localStorage`에 보관됩니다.
Discord 생성기와 LINE 생성기는 서로 다른 저장 키를 사용합니다.

## 라이선스

공개 배포 전에 원하는 라이선스를 별도로 선택해 `LICENSE` 파일을 추가하세요.
