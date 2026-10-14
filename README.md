# 홍길동 프로필 웹사이트

## 로컬에서 실행

Node.js 18 이상이 설치되어 있으면 패키지 설치 없이 실행할 수 있습니다.

```sh
npm start
```

브라우저에서 <http://localhost:3000>을 여세요. 기본 포트를 바꾸려면 `PORT=4000 npm start`처럼 실행합니다.

## Vercel 정적 배포

프로젝트 루트를 Vercel에 연결해 배포하면 `vercel.json`이 `public/`을 정적 출력 디렉터리로 사용합니다. 빌드 단계나 외부 패키지는 필요하지 않습니다. 웹사이트 파일은 `public/index.html`에 있습니다.
