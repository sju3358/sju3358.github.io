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

#### Who am I  
-------------

{::nomarkdown}
<div style="font-size : 10px">
    <style>
    /*Add custom cursor so it auto inherits font styles*/
    .aaa {
        font-size: 1em;
    }
    .typed::after {
    color:#404040;
    content: '';
    display: inline;
    -webkit-animation: blink 1s infinite;
    -moz-animation: blink 1s infinite;
    animation: blink 1s infinite;
    }
    .typed-cursor{
    opacity: 0;
    display: none;
    }
    /*Custom cursor animation*/
    @keyframes blink{
        0% { opacity:1; }
        50% { opacity:0; }
        100% { opacity:1; }
    }
    @-webkit-keyframes blink{
        0% { opacity:1; }
        50% { opacity:0; }
        100% { opacity:1; }
    }
    @-moz-keyframes blink{
        0% { opacity:1; }
        50% { opacity:0; }
        100% { opacity:1; }
    }
    </style>

    <h2 id="text_event" class="aaa">세계 최강의 개발자 <span id="text_hided" class="typed aaa" style="color:#a50509"></span></h2>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
    <script src="https://cdn.bootcss.com/typed.js/1.1.4/typed.min.js" type="text/javascript"></script> 
    <script>
        let hover = document.getElementById("text_event");
        let string_sample = ["(가 되고싶은...)","(가 될꺼임!!)","(아무튼 된다!!!)","(나 조성락)","(한다면 하는남자)","(아무도 못막음!!)"];
        let i = 0;
        $(function() {
            hover.addEventListener("mouseenter", function(){
                
                console.log("mouse over");
                
                let cur_string = string_sample[i++];
                console.log(cur_string);
                i = i % 6;
                $("#text_hided").show();

                $("#text_hided").typed({
                    strings : [cur_string,],
                    typeSpeed: 0,
                    fadeOut : true,
                });

            },false);

            hover.addEventListener("mouseleave", function(){
                
                console.log("mouse leave");

                $("#text_hided").fadeOut("slow");
            });
        }); 
    
    </script>
</div>
  
  
{:/}

##### ~~지구를 정복할 예정~~


<br/>

#### Contents  
-------------
Back-End  
Projects  
Algorhitm  
Computer Science  
스파르타코딩클럽 내일배움캠프  
and more..  



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

