---
title: About Me
layout: page
feature_image: "/assets/resources/image/aboutme_banner.webp"
feature_text:
aside: true
sitemap: true;
---




{::nomarkdown}
</br>
</br>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script>
  
$(function() {
    var string = ["INTP/J","코딩천재","테니스천재","아무튼천재"];
    var i = 1;
    var cnt = 0;
    
    fadein = function () {
        $('#intro').fadeOut("slow");
        flag = false;
    };
    
    fadeout = function(){
        $('#intro').fadeIn("slow");
        flag = true;
    };

    blink = function(){
        if(cnt === 0)
            fadein();
        else if(cnt == 1){
            $('#intro').text(string[i++]);
            i = i%4;
        }
        else
            fadeout();

        cnt = (cnt+1)%3;
    }
    
    setInterval(blink,1000);
    
});
</script>
<center>
  <style>
   .parent{
    font-size: 2em;
    margin: 0.67em 0;
    width: 90%;
}
.first {
    float: left;
    margin-left: 5%;
    width:30%;
}
.second{
  margin-left: 2%;
  float: left;
  width: auto;
}
  </style>
  <div class="parent">
    <div class="first">SJU335 is </div>
    <div id="intro" class="second">INTP/J</div>
  </div>
</center>
{:/}


<br/>
<br/>

### 수상이력
--------------------
2018 군장병 공개SW 역량강화교육 "IoT"부문 육군참모총장상  
2019 충남대학교 컴퓨터공학과 교내프로그래밍대회 동상  
2020 충남대학교 컴퓨터공학과 창의경진대회 우수상  

<br/>
<br/>


### 주요이력
----------------------
충남대학교 컴퓨터공학과 전공  
충남대학교 수학과 복수전공  
세트렉아이 백마인턴십 인공위성 소프트웨어 개발 2020.07 - 2020.08  
포씨게이트 병원 순번 키오스크 소프트웨어 개발 2021.02 - 2022.03  

<br/>
<br/>

