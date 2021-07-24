# React-Practice

Practice React.

I learned that What component, props, state, jsx, render is.

1. state는 변수설정
2. jsx는 JavaScripteXtention -> html을 js안에서 사용할 수 있는 문법
3. render는 화면상에 보이게 하는 것

시작할 때 npm start (이때 cd(chagne directory)로 파일 위치 맞추기)

\***\* gh-page 만들기 \*\***

1. npm i gh pages
2. pakage.json 마지막 줄에 "homepage": "https://dudgns2947.github.io/{File name}/ 추가
3. script에 "deploy":"gh-pages" , "predeploy": "npm run build" 추가
4. 이후 서버 내리고 npm run build
5. 생성된 build 폴더 안에 있는 html 문서안에 원하는 title로 변경 후 npm run deploy 실행
6. 완성
