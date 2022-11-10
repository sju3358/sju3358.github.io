---
title: 
layout: home
feature_text: |
excerpt: ""
aside: true
---



{::nomarkdown}
<style>
/*Add custom cursor so it auto inherits font styles*/
/*
.typed-cursor {
  opacity: 1;
  font-weight: 100;
  -webkit-animation: blink 0.7s infinite;
  -moz-animation: blink 0.7s infinite;
  -ms-animation: blink 0.7s infinite;
  -o-animation: blink 0.7s infinite;
  animation: blink 0.7s infinite;
  }
*/
.typed::after {
  color:#404040;
  content: '';
  display: inline;
  -webkit-animation: blink 1s infinite;
  -moz-animation: blink 1s infinite;
  animation: blink 1s infinite;
}

/*Removes cursor that comes with typed.js*/
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


<div>
    <h1 id="text_event">세계 최강의 개발자 <span id="text_hided" class="typed" style="color:#a50509"></span></h1>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
    <script src="https://cdn.bootcss.com/typed.js/1.1.4/typed.min.js" type="text/javascript"></script>
    <script>
        let blink = document.getElementById("text_hided");
        let string_sample = ["(가 되고싶은...)","(가 될꺼임!!)","(아무튼 된다!!!)","(나 조성락)","(한다면 하는남자)","(아무도 막을수 없다!)"];
        let i = 0;

        $(function() {
            blink.addEventListener("mouseenter", function(){
                
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

            blink.addEventListener("mouseleave", function(){
                
                console.log("mouse leave");

                $("#text_hided").fadeOut("slow");
            });
        }); 
    </script>
    
</div>
  
  
{:/}
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

Recent
==============