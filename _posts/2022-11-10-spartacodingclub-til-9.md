---
title: "내일배움캠프 TIL #9"
excerpt: ""
categories:
- SpartaCodingClub
---

오늘은 jeckyll을 이용해서 블로그를 파보았다.  
앞으로 til은 여기다쓸예정이다.  
~~aboutme만 쓰는데 하루종일 걸렸다는건 함정~~  

내일은 홈화면을 꾸미고  
본격적으로 포스팅을 할 예정이다.  

{% if post.image %}
      <div class="post-image">
        <a href="{{ post.url | prepend: site.baseurl }}">
          <img src="{{ post.image }}">
        </a>
      </div>
      {% endif %}

