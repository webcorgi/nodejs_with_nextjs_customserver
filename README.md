# nodejs와 nextjs 연결하기 (커스텀 서버)
https://nextjs.org/docs/pages/building-your-application/configuring/custom-server

1. server.js 작성, 필요 라이브러리 설치
```
npm i express
```
2. package.json 내용 변경

```
"scripts": {
    "dev": "node server.js",
    "build": "next build",
    "start": "NODE_ENV=production node server.js"
},
```

3. 실험해봐야 할 것 > nodejs 실행이 가능해지면서 vercel이 아닌 다른 호스팅에 정상작동 하는지 ?