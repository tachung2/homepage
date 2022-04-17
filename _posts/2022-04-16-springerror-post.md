---
layout: post
title: 스프링부트하면서 업데이트로 바뀐 점
date: 2022-04-16 00:00:00 +0800
category: springboot
thumbnail: ../style/image/thumbnail.png
icon: book
---


* content
{:toc}









## 스프링부트하면서 업데이트로 바뀐 점

"스프링부트와 AWS로 혼자 구현하는 웹 서비스"라는 책을 오랜만에 꺼내 공부하는데 처음부터 막히는 구간이 있다.
먼저 인텔리제이를 사용하는데 버전이 바뀌어 gradle.build부터 다시 손을 보게 되었다.


![gradle](https://user-images.githubusercontent.com/40621278/163697769-25eb5623-6c74-4e12-bba3-da5a7a1c63d9.png)


## 자료 확인

https://github.com/tachung2/vele-springboot2-webservice/blob/master/build.gradle
<https://github.com/tachung2/vele-springboot2-webservice/blob/master/build.gradle>










## 주요 내용

- repositories에 jcenter가 2021년 3월 31일부터 종료 되어 업데이트 된 라이브러리에서 사용 불가능하다.

- compile이 지원 중단 되어 implementation으로 대체 되었다.