# 작업 규칙

- 사용자에게는 항상 한국어로 답한다.
- 변경을 마치면 작업 브랜치에 커밋 · 푸시한 뒤, PR을 만들어 `main`에 머지까지 한다.
- 사이트(GitHub Pages)는 현재 `claude/epic-bohr-5tesx1` 브랜치에서 배포된다. `main`에 머지한 뒤 그 브랜치도 `main`과 같게 맞춰(fast-forward 푸시) 사이트에 반영한다.
  - 저장소 Settings → Pages → Source를 **GitHub Actions**로 바꾸면 `main`에 푸시할 때 `.github/workflows/deploy-pages.yml`로 배포되며, 이 단계는 필요 없어진다.
