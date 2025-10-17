프로젝트: index.html 웹페이지

설명
- 이 리포지터리는 단일 `index.html` 파일을 포함합니다.

로컬에서 시작
1. git 초기화
   git init
   git add .
   git commit -m "Initial commit"
2. GitHub 리포지터리 생성 (웹 UI 또는 gh cli 사용)
3. 원격 추가 및 푸시
   git remote add origin <원격-URL>
   git branch -M main
   git push -u origin main

CI/CD
- 깃허브 액션이 `main` 브랜치에 푸시될 때마다 HTML 검증을 실행하고 GitHub Pages에 배포합니다.

참고
- 커스텀 도메인이나 Pages 설정은 GitHub 리포지터리 설정에서 추가하세요.
