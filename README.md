# 우주 한 조각 · 우주 탐사 퀴즈

우주 탐사 지식을 확인하는 한국어 10문항 퀴즈입니다. 정답마다 10점을 얻고, 문제별 정답·오답 해설과 진행률을 확인할 수 있습니다. 완료 후에는 이모지 결과 화면과 틀린 문제 복습을 볼 수 있으며, 다시 시작할 수 있습니다.

## 웹사이트

[우주 탐사 퀴즈 열기](https://qkdrmawll.github.io/space-quiz/)

## 로컬 실행

1. 이 저장소를 다운로드하거나 복제합니다.
2. `index.html`을 웹 브라우저에서 직접 엽니다.

설치, 서버, 빌드 도구, 외부 라이브러리 및 네트워크 연결 없이 실행됩니다. macOS에서는 저장소 폴더에서 `open index.html`로 열 수도 있습니다.

보기는 마우스나 키보드의 숫자 `1`–`4`로 선택할 수 있습니다. 라이트·다크 테마, 작은 화면, 키보드 포커스 및 동작 줄이기 설정을 지원합니다.

## GitHub Pages 배포

저장소의 **Settings → Pages → Build and deployment → Source**는 **GitHub Actions**를 사용합니다.

`.github/workflows/pages.yml`은 `main` 대상 PR에서 사이트를 패키징합니다. `main`에 변경 사항이 반영되면 `index.html`만 배포 아티팩트에 담아 GitHub Pages에 자동 게시합니다. 별도의 빌드 단계는 필요하지 않습니다. **Actions → GitHub Pages 배포 → Run workflow**에서 `main` 브랜치를 선택해 수동으로 다시 배포할 수도 있습니다.

배포 상태와 게시 주소는 Actions 실행 내역의 `Pages 게시` 작업 및 `github-pages` 환경에서 확인할 수 있습니다.
