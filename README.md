# 박경태 포트폴리오

Hugo와 Markdown으로 작성한 개인 포트폴리오입니다.

## 로컬 실행

Hugo Extended를 설치한 뒤 실행합니다.

```bash
hugo server -D
```

브라우저에서 `http://localhost:1313/portfolio/`를 엽니다.

## 콘텐츠 수정

메인 페이지는 `content/_index.md`에서 수정합니다. 프로젝트, 경력, 소개, 이메일 주소의 placeholder를 실제 내용으로 바꿔주세요.

## GitHub Pages 배포

`main` 브랜치에 push하면 `.github/workflows/deploy.yml`이 자동으로 사이트를 빌드합니다. GitHub 저장소의 `Settings → Pages → Build and deployment → Source`를 `GitHub Actions`로 설정하면 됩니다.
