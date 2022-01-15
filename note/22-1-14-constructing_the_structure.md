---
layout: post
title: Structure of each Blocks.  
---  

## Web page의 각 block들의 tag들을 어떻게 구성하여 structure를 만들 것인가?  

### 막막함  

kokoa clone을 하면서 여러 tag(`li, ol, header, span`)들 중 어떤 것을 사용해서 구조를 짜야하는지가 막막했다. 이 post는 web page내 block들의 기능에 따라서 구조를 어떤 식으로 개발자들이 짜는지를 정리한 post이다.  

#### 1. Navigator  

<img src="img/22-1-14-navigator.png"/>  

위 사진에 사이트 link아래로 보이는 것들이 navigator가 제시하는 link들이다. 이렇게 searching 엔진에 의해서 발견되어야하는 navigator의 특성상, 서칭 엔진이 찾는 구조를 따라 주어야한다.  

아래 코드는 kokoa clone에서 다음 nav-bar를 clone하기 위해 짠 html 구조이다.  

<img src="img/22-1-14-nav_goal.png" />  

```html
<nav>
    <ul>
        <li>
            <a href="#">
                <!-- icon: user -->
            </a>
        </li>
        <li>
            <a href="#">
                <!-- icon: message -->
            </a>
        </li>
        <li>
            <!-- icon: search -->
            <a href="#"></a>
        </li>
        <li>
            <!-- icon: elipsis -->
            <a href="#"></a>
        </li>
    </ul>
</nav>
```  

`nav>ul>li*4>a`구조이다.  

Q. 나는 짜면서 왜 ul에 담고 각 anchor와 img들을 li에 담아야 하는지 잘이해하지 못했다. 왜일까?  

A. **Need to be updated**  





