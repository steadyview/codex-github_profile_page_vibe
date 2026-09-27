# 김개발 포트폴리오

GitHub Pages에서 동작하는 정적 개발자 포트폴리오입니다. 별도 빌드 과정 없이 `main` 브랜치에 푸시하면 자동으로 배포됩니다.

## 개인 정보 바꾸기

- `index.html`에서 이름, 소개, 기술, 프로젝트, 경력, 이메일과 소셜 링크를 수정합니다.
- `profile.ts`처럼 보이는 첫 화면의 코드 블록도 실제 소개에 맞게 함께 바꿉니다.
- `favicon.svg`는 사이트 탭에 표시되는 아이콘입니다.

## GitHub Pages 자동 배포 설정

1. 이 폴더를 GitHub 저장소에 올리고 기본 브랜치를 `main`으로 설정합니다.
2. 저장소의 **Settings → Pages → Build and deployment**에서 **Source**를 **GitHub Actions**로 선택합니다.
3. `main` 브랜치에 푸시합니다. **Actions** 탭의 `Deploy static site to GitHub Pages` 워크플로가 완료되면 배포 주소가 표시됩니다.

이후에는 `main`에 푸시할 때마다 사이트가 자동으로 갱신됩니다. 필요하면 **Actions** 탭에서 수동으로도 실행할 수 있습니다.
