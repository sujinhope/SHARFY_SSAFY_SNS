# Vue.js 시작하기 

개발 환경 구축 하기



0. node.js 설치하기

   브라우저가 아닌 환경에서 JavaScript를 사용하기 위해 [node.js](https://nodejs.org/en/)를 설치한다.

   node.js 설치 시 npm도 함께 설치된다. 

   npm이 기본적으로 설치 되지만, [yarn](https://yarnpkg.com/en/docs/install#windows-stable)을 이용하면 더 빨리 빌드 할 수있다.

	```
// 버전확인 
node - v 
npm - v
yarn -v
	```


1. vue CLI 설치하기

   ```
   //CLI 설치
   yarn global add @vue/cli 
   // 새 프로젝트 만들기
   vue create [Project-name]
   // 서버 실행
   yarn serve
   ```

2. Sass 설정

   ```
   yarn add node-sass sass-loader
   ```

3. Vue-router, Vuex 설치

	```
    yarn add vue-router vuex
	```

4. Chrome extension  `Vue.js devtools` 설치
5. Vscode extension `Vetur` , `'Vue VSCode Snippets' `설치



---

참고 링크

[yarn docs](https://yarnpkg.com/en/docs/)

[npm과yarn](https://happygrammer.tistory.com/154)



-----

작성자 : 이수진 

일자 : 2020-01-20