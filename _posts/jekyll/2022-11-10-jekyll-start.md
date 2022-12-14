---
title: "jekyll로 블로그 만들기 #1"
excerpt: "Hosting Blog with Jekyll & Github Pages"
categories:
- jekyll
sitemap: true
---

### 목차  
-----------
1. [jekyll](#jekyll)  
2. [테마 정하기](#테마정하기)  
3. [Github Pages로 배포하기](#github-pages로-배포하기)

<br/>

### jekyll
-----------
jekyll과 github pages를 이용하면 쉽게 자신의 홈페이지를 팔 수 있다.  
물론 네이버블로그,velog,티스토리 등 훨씬 편한 블로그가 있지만  
직접 JS,HTML,CSS를 조작해서 쉽게 커스텀이 가능하다는 장점이 있다.  
~~사실 그것보단 뭔가 이렇게 하면 찐개발자 같이 보여서 간지가 극대화 된다는것이 최대 장점~~

그리고 github pages는 정적페이지만 올릴수있는데,  
물론 vue.js react.js 등등으로 사이트를 꾸밀수있지만  
jekyll은 기본적인 레이아웃과 테마를 제공해줘서 쉽게 꾸밀수있다.  
미적감각이 없는 나에게 이보다 편한 도구가 없었기 때문에 jekyll을 선택하게 되었다.  

<br/>
<br/>

### 테마 정하기
------------
기본적인 설명은 모두 https://jekyllrb.com/ 공식홈페이지에 나와있다.
먼저 테마를 골라야하는데 아래와 같은 사이트에서 고를 수 있다.

- <https://github.com/topics/jekyll-theme>  
- <https://jamstackthemes.dev/ssg/jekyll/>  
- <http://jekyllthemes.org/>  
- <https://jekyllthemes.io/>  
- <https://jekyll-themes.com/>
<br/>

본인은 <https://jekyllthemes.io/theme/alembic> 테마를 사용했다. 
<br/>
<br/>

![Screenshot](/assets/resources/image/jekyll/2022-11-10/jeckll-theme-selection.png) 
위 사진과 같이 GitHub과 연동하는 버튼을 누르면   
1. 자동으로 깃헙에 레포지를 파주는 페이지로 넘어가거나  
2. 깃허브 레포지로 넘어가는데, fork하거나 알아서 다운받으면된다.  

레포지 이름은 {github id}.github.io로 해야한다.  
깃헙 독스에 그렇게 하라고 나와있당

<br/>
<br/>

### Github Pages로 배포하기
------------------------
그리고 이것을 Github Pages로 연동을 해야하는데  

![Screenshot](/assets/resources/image/jekyll/2022-11-10/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202022-11-11%20%EC%98%A4%EC%A0%84%208.02.27.png)
![Screenshot](/assets/resources/image/jekyll/2022-11-10/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202022-11-11%20%EC%98%A4%EC%A0%84%208.04.39.png)
Setting ---> Branch ---> main / root save클릭 하면  
상단에 your site is live at {호스팅주소}가 뜬다.

들어가서 기본화면이 뜨는걸 확인하면 일단 배포는 성공한것이다.  



