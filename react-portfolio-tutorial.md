# react portfolio tutorial



* Component  폴더 안에 reusable component를 categorize하고  jsx, scss폴더를 각각 생성.

![](.gitbook/assets/image%20%2864%29.png)

* install Yarn via npm

![](.gitbook/assets/image%20%2884%29.png)

* node-sass 설치하기.  &gt;yarn add node-sass  SCSS / SASS 는 CSS 를 편리하게 이용할 수 있게 도와주는 확장판 scripting 언어. ;  **SASS보다 SCSS가 뒤에 나왔고 여러가지 문법의 차이가 있지만 SCSS가 더 넓은 범용성과 CSS의 호환성 등의 장점으로 SCSS를 사용하기를 권장하고 있다.**\(공식문법도 SCSS를 기준으로 나와있다고 함\) 따라서 SASS는 통상적으로 SCSS라고 부르기도 하는 것 같다.



* 각 파일마다 경로설정.  \(eg. contanct.jsx 안에는 import "./contact.scss" / & 적힐 내용을 적어주고  contact.scss에는 그리고있는 css를 적는다.\) 

![&#x2605;&#x2605;&#x2605;&#x2605;&#x2605; &#xB2E8;&#xCD95;&#xD0A4; rfc &#xB85C; export default &#xD568;&#xC218;&#xB97C; &#xB9CC;&#xB4E0;&#xB2E4;!!!! ](.gitbook/assets/image%20%2873%29.png)

![](.gitbook/assets/image%20%2876%29.png)

* App.jsx에 import하는 경로를 표시해줘야  import됨!!! \(? App.js에 import React from "react"; 는 안해줘도 상관없는것인가? ==&gt;import React, { useEffect, useState } from "react";   hooks를 쓰기 위해 이렇게 적어줘야함.\) \(? 현재 scss를 쓰지 않는 이유가 있는가~\)



![](.gitbook/assets/image%20%2866%29.png)



* App.jsx는 아래처럼 components 를 나열 / import해주기.

![](.gitbook/assets/image%20%2879%29.png)

* app.scss는 그 안에 속한 sections의 class는 내포시켜 적을 수 있음. 100vh - 70px \(topbar의 height\)로 %처럼 but 반응형으로 코딩 가능. 

![](.gitbook/assets/image%20%2826%29.png)

\(해결? 왜 relative줬는데도 가운데 빵꾸가날까 ==&gt; index.html 's   style에 margin:0을 주니 돌아왔다.   전체에 가해야 하는 무언가는 , index.html's style 에 주는 걸로.  \(font, overflow, margin ... etc.\)\)

![](.gitbook/assets/image%20%2858%29.png)

![](.gitbook/assets/image%20%2835%29.png)

* scroll-snap-type \(스크롤바를 없애주고, y축으로 스크롤할때 각각 화면마다의 start지점으로 가게 훅훅 ! 옮겨주는 것!!!! \) \(???근데 왜이렇게 빠르게 가고 중간 에 있는 것들은스쳐지나가기만하는거지???\)

![](.gitbook/assets/image%20%2840%29.png)

\(???&:: , &:의 정확한 의미는뭘까~\)

* global.scss 를 만들어서 reusable style을 만들어 2번째 이미지처럼 , import 및 사용할 수 있다.   

![](.gitbook/assets/image%20%2830%29.png)

![](.gitbook/assets/image%20%2845%29.png)



* &lt;a href="\#intro"&gt;&lt;/a&gt;  \(문제해결 . ???\)a를 클릭하면 \#intro로 이동하게끔하는게 왜 안될까? / consider adding an error boundary to your tree to customize error handling behavior 이 ,, 예시가 뭐가있을까?   ==&gt; 해결방법 : 

![](.gitbook/assets/image%20%2837%29.png)

\)

![](.gitbook/assets/image%20%2886%29.png)

![](.gitbook/assets/image%20%2850%29.png)

* icon 넣기 

```text
npm install @material-ui/core
npm install @material-ui/icons
```

[https://material-ui.com/components/material-icons/](https://material-ui.com/components/material-icons/)  에서 원하는 아이콘을 찾은 뒤,

원하는 main component import시킨뒤,  
return안 , 본문에 &lt;Person/&gt;  , 이런 식으로 붙이기.

![](.gitbook/assets/image%20%2891%29.png)



* Hamburgur box \(.active 하면 x자로 변하게하기.\)

![](.gitbook/assets/image%20%2889%29.png)

![](.gitbook/assets/image%20%2871%29.png)

\(? 햄버거박스... 100%로 고보니 너 ... 왜이러냐..ㅜㅜ  
==&gt; 서브모니터를 연결했는데 브라우저사이트 기준이 연결된 2번째 모니터 기준으로되서 차이가발생되는듯.\)

![](.gitbook/assets/image%20%2862%29.png)

* onClick 이벤트 적용!!! App.jsx 

![](.gitbook/assets/image%20%2844%29.png)

  **- Topbar.jsx**   


![](.gitbook/assets/image%20%2883%29.png)

* topbar.scss \(아래 사진은 캡처를 위해 &.active를 위로 올린거지 실제로는 scss 제일 하단 부분에 위치해야함. span의 first-chils , last-child의 변경되는 컬러값이 안먹기 때문에.\)

![](.gitbook/assets/image%20%2885%29.png)



* menu [https://www.youtube.com/watch?v=7WwtzsSHdpI](https://www.youtube.com/watch?v=7WwtzsSHdpI) 53.29

