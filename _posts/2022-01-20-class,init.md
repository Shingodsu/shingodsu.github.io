---
layout: post
title: Class 와 __init__, self
date: 2022-01-21
---

## 1. 파이썬의 Class <br/>
 ### Class: 객체를 만드는데 사용되는 문법, 컴퓨터에서 객체는 스크롤 바, 버튼등과 같이 특정한 개념이나 모양으로 존재하는것을 의미<br/>
  ex) 스타크래프트에서 '하이템플러'라는 유닛(인스턴스)을 생성할때, 하템의 마나,쉴드,체력등의 데이터를 "속성", 할루시네이션, 스톰등의 기능을     '메소드' 라고   할수있다. 이 하이템플러(객체)를 만드는 게이트웨이를 '클래스'라고 볼수있다. 
  (*정확히 말하자면 메소드는 클래스 내부에서 정의된 함수이다.) 
 
## 2. __init__ <br/>
 ### __init__: 클래스의 "속성"을 생성한다(생성자) 즉, 인스턴스를 생성한다. init은 초기화(initialization)의 약자이다.<br/>
  ex) def __init__(self,name,mana,shield,hp): <br/>
       self.name = name <br/>
       self.hp = hp <br/>
       self.mana = mana <br/>
       self.shield = shield <br/>
       위와같이 self(자기자신)에 hp,name,mana,shield 정보(속성)를 생성할수있음 <br/>
 
  *self: 클래스에서 자기자신을 의미함<br/>
  
*출처: (https://wikidocs.net/1740), (https://jonhyuk0922.tistory.com/125) <br/>
