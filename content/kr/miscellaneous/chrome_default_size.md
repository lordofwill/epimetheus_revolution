---
title: "[크롬] 초기 창 크기 설정 방법"
date: 2022-10-16T16:23:47+09:00
description: "크롬브라우저의 실행창 크기 설정 방법"
featured_image: "https://user-images.githubusercontent.com/57059776/196023766-6da3739d-9223-43af-acae-67e4be1dd1e8.jpg"
tags: ["인터넷 창 크기", "크롬 크기 설정", "크롬 창 크기", "크롬 창 사이즈"]
draft: true
---

+ 크롬 웹 브라우저를 설치한 후, 변경사항없이 실행하면 마지막에 종료된 창 크기로 실행됩니다.   

+ 크롬의 창 크기를 원하는 사이즈로 줄여놓고 닫지 않는 이상, 크롬 창은 매번 다른 크기로 실행이 되는데, 선호하는 창 크기가 있던 저로서는 이 부분이 불편했습니다.

+ 찾은 방법은 바로가기에 크기속성을 부여하는 것입니다.
      
+ 설정방법은 다음과 같습니다.   

---
1. 크롬의 바로가기를 우클릭하여 속성창을 엽니다.

2. 속성창의 대상 뒤에 크기 및 위치 옵션을 적습니다.   
##### 	예시: "C:\Program Files\Google\Chrome\Application\chrome.exe" --window-position=200,50 --window-size=1024,768   
![chrome_default_size](https://user-images.githubusercontent.com/57059776/196024454-1c7518d6-ea74-4d28-ad78-c00bd7a7315e.png)   

3. 적용 후에 지정한 창 크기와 위치로 크롬이 실행되는 것을 확인 할 수 있습니다.
---

감사합니다.
