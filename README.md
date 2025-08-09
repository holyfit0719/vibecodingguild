# 다오랩 바이브코딩길드

자발적 DAO로 움직이는 바이브코딩 실험 길드 홈페이지

## 배포 방법

### Vercel로 배포하기

1. GitHub에 코드 푸시
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin [your-github-repo-url]
git push -u origin main
```

2. Vercel 배포
```bash
npx vercel
```

또는 Vercel 대시보드에서:
- https://vercel.com 접속
- "New Project" 클릭
- GitHub 저장소 연결
- Deploy 클릭

### 로컬에서 실행하기

```bash
npx serve .
```

브라우저에서 http://localhost:3000 접속

## 프로젝트 구조

```
├── index.html      # 메인 HTML 파일
├── styles.css      # CSS 스타일
├── script.js       # JavaScript 인터랙션
├── services.md     # 서비스 내용 문서
├── package.json    # 프로젝트 설정
└── vercel.json     # Vercel 배포 설정
```