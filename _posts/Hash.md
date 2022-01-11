---
layout : post
title : "Hash"
---

![img1 daumcdn](https://user-images.githubusercontent.com/90206705/148952795-fbc17000-7930-4d1d-b07a-7972cb3f40a6.png)

# [ Hash Table 이란? ] 
key-value로 이루어진 자료구조 중 하나로 빠르게 데이터를 검색할 수 있는 자료구조

해시 테이블이 빠른 검색 속도를 제공하는 이유 -> 내부적으로 배열(버킷)을 사용하여 데이터를 저장하기 때문.
<br/>해시 테이블은 각각의 Key값이 해시함수를 적용해 배열의 고유한 index를 생성하고, 이 index를 생성하고, 이 index를 활용해 값을 저장하거나 검색하게 됨.
<br/>(여기서 실제값이 저장된느 장소 -> bucket 또는 slot)

