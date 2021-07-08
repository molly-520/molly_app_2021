# 0.2 deploy배포하는 법

* 브라우저에서 캐시 비우고 강력새로고침하면  맨 오른쪽아래에 1.7mb를 다운로드 받았다는 정보를 알 수 있음. \(create react app가 좀 무겁기에.\) 
* &gt;npm run build    ==&gt; 필요없는 파일들을 minimize해서 용량을 줄임.

![](../../.gitbook/assets/image%20%2887%29.png)



* npm/ npx를 활용한 서브 생성

&gt;npm install -g serve  
               'or'  
&gt;npx serve -s build     \(-s : build 라는 디렉토리를 document 루트로 하겠다.\)  


==&gt;125KB 로 용량 대폭 줄었다.

![](../../.gitbook/assets/image%20%2861%29.png)





