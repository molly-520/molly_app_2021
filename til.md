# TIL

* VSCODE EXTENSION 모음 [https://basketdeveloper.tistory.com/68](https://basketdeveloper.tistory.com/68) 
* JSX tag autocompletion \(태그자동완성\)하는 방법.   extension 에서 emmet live 를 다운받고  \(file - preference - setting \)

![](.gitbook/assets/image%20%2829%29.png)

* 아이콘 다운받는 사이트 ; sharpness , color 변경이 가능!!!!  
  [https://material-ui.com/components/material-icons/](https://material-ui.com/components/material-icons/)  


  ```text
  npm install @material-ui/core
  npm install @material-ui/icons
  ```

* React Hooks!!! [https://velog.io/@velopert/react-hooks](https://velog.io/@velopert/react-hooks)
* 자바스크립트 연산자\(! / !! / \*\* / ~ / IIFE\)즉시실행함수\) [https://medium.com/%EC%98%A4%EB%8A%98%EC%9D%98-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D/%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%97%90%EC%84%9C-%EC%9C%A0%EC%9A%A9%ED%95%A0-%EC%88%98%EB%8F%84-%EC%9E%88%EB%8A%94-%EC%97%B0%EC%82%B0%EC%9E%90%EB%93%A4-%EB%AA%A8%EC%9D%8C-3450083838fb](https://medium.com/%EC%98%A4%EB%8A%98%EC%9D%98-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D/%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%97%90%EC%84%9C-%EC%9C%A0%EC%9A%A9%ED%95%A0-%EC%88%98%EB%8F%84-%EC%9E%88%EB%8A%94-%EC%97%B0%EC%82%B0%EC%9E%90%EB%93%A4-%EB%AA%A8%EC%9D%8C-3450083838fb) 
* && 조건부 렌더링. [https://ko.reactjs.org/docs/conditional-rendering.html](https://ko.reactjs.org/docs/conditional-rendering.html)
* 20
* font 폰트적용.\(index.html에 적용.\)

![](.gitbook/assets/image%20%28100%29.png)



---------------------------------------------------------------------------------------------------------------------------------



* 아예 작동안되는 내 반나절을 날린 대.형.에.러... ERROR
* ```text
  Error: Cannot find module 'C:\Users\USER\pf_mol_2021\node_modules\schema-utils\src\index.js'. Pleas
  e verify that the package.json has a valid "main" entry
  ```

  

![](.gitbook/assets/image%20%28102%29.png)

  
==&gt;maybe원인   


![](.gitbook/assets/image%20%2897%29.png)

==&gt;???maybe solution ??  그래서   
npm uninstall -g yarn 을 했다.

![](.gitbook/assets/image%20%2899%29.png)

---------------------------------------------------------------------------------------------------------------------------------

* 에러 2. import React, from "react";  import React, {component, page} from "react";  괄호안에 저렇게 무언가를 넣어 당장 써줄것이 없다면 안넣어야함. 넣어주는 즉시 에러!!!!!!!!!!!!!!!sh\*\*t!!!!

![](.gitbook/assets/image%20%28103%29.png)

-------------------------------------------------------------------------------------------------------------------------------------  
- 에러 3. sass \(scss\)를 잘 사용했는데 아래 요딴 에러가 난다.   
==&gt; maybe solution .     &gt;npm install sass-loader   

Failed to compile

```text
./src/components/nav/nav.scss (./node_modules/css-loader/dist/cjs.js??ref--5-oneOf-6-1!./node_modules/postcss-loader/src??postcss!./node_modules/resolve-url-loader??ref--5-oneOf-6-3!./node_modules/sass-loader/dist/cjs.js??ref--5-oneOf-6-4!./src/components/nav/nav.scss)
TypeError: this.getOptions is not a function
```



* 이미지 img import 방법

![](.gitbook/assets/image%20%28101%29.png)

* vs code 에 git 연동.  \(ctrl + shift + p 누르고,\) 

![](.gitbook/assets/image%20%2898%29.png)



