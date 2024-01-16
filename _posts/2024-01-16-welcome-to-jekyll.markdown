---
layout: post
title: 프로그래머스 - 양꼬치
date: '2024-01-16 15:47:24 +0900'
categories: Programmers Javascript
published: true
permalink: /post/:title
---
문제 설명
머쓱이네 양꼬치 가게는 10인분을 먹으면 음료수 하나를 서비스로 줍니다. 양꼬치는 1인분에 12,000원, 음료수는 2,000원입니다. 정수 n과 k가 매개변수로 주어졌을 때, 양꼬치 n인분과 음료수 k개를 먹었다면 총얼마를 지불해야 하는지 return 하도록 solution 함수를 완성해보세요.

```javascript
function solution(n, k) {
    return (n * 12000) + ((k - Math.floor(n *0.1))* 2000);
}
```