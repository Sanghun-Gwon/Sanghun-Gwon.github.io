---
layout: post
title: "Sorting Algorithm"
author: "Sanghun"
tags: Algorithm
excerpt_separator: <!--more-->
typora-root-url: ../
---

**Sorting**이란, 순서없이 나열된 요소들(elements,key)을 **특정한 기준(내림차순 or 오름차순)**에 따라 비교하여 **재배열(rearrange)**하는 것을 말한다.<!--more-->

# Sorting Algorithm

정렬알고리즘은 왜 사용할까?
정렬알고리즘은 자료탐색에 있어서 필수적인 요소이다.

**사전**의 경우를 예로 든다면, 단어를 찾고자 할 때 정렬되어 있지 않다면 찾고자 하는 단어를 구하기까지 오랜 시간이 걸리게 된다.(**비효율**, 양이 많아지면 불가능-너무 오래걸림)

다만 정렬되어 있는 경우에는 이진탐색과 같은 탐색알고리즘을 이용하여 더욱 **효율적**으로 탐색할 수 있게 된다.

하지만, 정렬알고리즘의 종류는 매우 많으며 각각의 특색(장단점)이 있어 해당 알고리즘의 특징을 이해하여 상황에 맞는 효율적인 알고리즘을 선택할 수 있어야 한다.

## Sorting 기준
1. 오름차순(Ascending) : 요소들이 증가하는 순서로 재배열
2. 내림차순(Descending) : 요소들이 감소하는 순서로 재배열



## 정렬 알고리즘 분류

1. 정렬이 **수행되는 공간**에 따른 분류
2. 정렬을 **실행하는 방법**에 따른 분류



### 정렬알고리즘 복잡도

![sorting_complexity](/assets/img/sorting-algorithm/sorting_complexity.png)


### 정렬알고리즘 속도

![sorting_speed](/assets/img/sorting-algorithm/sorting_speed.gif)

