# awesomecut

⇧⌘2 로 캡처하고 그 자리에서 손보는 macOS 캡처 도구입니다. 캡처는 편집 창이 뜨기 전에
클립보드에 먼저 담기고, 화살표나 하이라이트를 얹은 뒤 ⌘C 를 한 번 더 누르면 그걸로 끝입니다.

**설치 가이드: https://ottlseo.github.io/awesomecut/**

서명 없는 앱이라 첫 실행 때 macOS 경고를 한 번 넘겨야 하고, 화면 기록 권한을 한 번 켜야 합니다.
둘 다 처음 한 번만 하면 됩니다. 막히는 곳이 대부분 여기라 가이드에 화면과 함께 적어 두었습니다.

## Download

[Releases](https://github.com/ottlseo/awesomecut/releases/latest) 에서 `awesomecut-<버전>.dmg` 를
받습니다. macOS 13 이상, Apple Silicon 과 Intel 모두 됩니다.

이 저장소는 배포용 저장소입니다. 

| 경로 | 용도 |
| --- | --- |
| `docs/` | 소개와 설치 가이드 페이지. 공개로 바꾼 뒤 GitHub Pages(`/docs`)로 게시한다. |
| `updates/latest.json` | 앱이 읽는 업데이트 정보. 새 버전을 릴리스한 뒤 이 파일을 갱신한다. |
| Releases | DMG 파일. |

앱은 실행 중에 `updates/latest.json` 의 `build` 를 자기 빌드 번호와 견주어 새 버전이 있는지
판단합니다. 그러므로 **DMG 를 릴리스에 올린 뒤에** 이 파일을 갱신해야 합니다. 순서를 뒤집으면
업데이트 알림을 받은 사람이 없는 파일을 받으러 갑니다.

저장소가 비공개인 동안에는 이 파일도, 릴리스에 올린 DMG 도 로그인 없이 받을 수 없어서
업데이트 확인이 동작하지 않습니다. 공개로 바꾸면 그대로 동작합니다.
