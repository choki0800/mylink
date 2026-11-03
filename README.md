# 마이링크 (MyLink)

자주 찾는 링크를 한곳에 모은 개인 링크 페이지입니다.

## 구성

- `MyLink/`: 마이링크 전용 폴더. `index.html`에 화면, 스타일, 주소 복사 기능이 들어 있습니다.
- `index.html`: 저장소 루트에서 `MyLink/`로 이동합니다.
- `.nojekyll`: 별도 Jekyll 처리 없이 정적 파일을 제공합니다.

별도 설치나 빌드가 필요하지 않습니다. 모바일 화면, 키보드 탐색, 동작 줄이기 설정을 지원합니다. 외부 링크는 새 탭에서 열립니다.

## GitHub Pages 설정

저장소 **Settings → Pages → Build and deployment**에서 다음과 같이 설정합니다.

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/ (root)`

공개 주소: [MyLink 열기](https://choki0800.github.io/mylink/MyLink/)

전용 폴더: [MyLink/](https://github.com/choki0800/mylink/tree/main/MyLink)

2026년 11월 3일 GitHub Pages 배포 성공과 공개 페이지 접속을 확인했습니다. 저장소 루트 주소도 `MyLink/`로 이동합니다.

## 링크 수정

`MyLink/index.html`에서 소개 문구와 각 링크의 `href`, 제목, 설명을 수정하면 됩니다.

## 과제 제출 기간

2026년 11월 9일(월) 00:00 ~ 11월 15일(일) 23:59 (한국 시간).

공식 GitHub Pages 설정 안내: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
