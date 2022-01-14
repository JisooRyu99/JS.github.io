---
layout : post
title : "[자료구조] stack & queue"
last_modified_at: 2021-01-14

---


# Stack (LIFO)
*****
### __< stack특징 >__

![stack](https://user-images.githubusercontent.com/90206705/149521899-41f95b57-ed56-4771-91e4-eefdcc1e434e.jpg)

+ 같은 구조와 크기의 자료를 정해진 방향으로만 쌓을 수 있음
+ top에는 가장 위에 있는 자료, 가장 최근에 들어온 자료
+ stack에서 자료를 삭제할 때도 top을 통해서만 가능
+ top을 통해 삽입하는 연산 -> 'push'
+ top을 통해 삭제하는 연산 -> 'pop'
+ 비어있는 stack에서 원소 추출할 때 -> 'stack underflow'
+ 스택이 넘치는 경우 -> 'stack overflow'
<br><br/>
+ stack은 순서에 따라 자료가 쌓여서 가장 마지막에 삽입된 자료가 가장 먼저 삭제 <br/>
__--> LIFO (Last-In-First-Out) 구조__
<br/>

### __< stack의 활용 예시 >__
- 역순 문자열 만들기
- 후위 표기법 계산
- 수식의 괄호 검사 (연산자 우선순위 표현을 위한 괄호 검사)


# Queue (FIFO)
****
![queue](https://user-images.githubusercontent.com/90206705/149521916-e7bf9539-e7d7-4422-a1cf-cead1ccc0e82.jpg)

#### 한쪽 끝에서 삽입 작업이, 다른 쪽 끝에서 삭제 작업이 양쪽으로 이루어짐. <br/>
#### queue의 rear에서 이루어지는 삽입연산 -> enQueue
#### front에서 이루어지는 삭제연산 -> deQueue


### __< queue특징 >__
- queue 의 가장 첫 원소 -> front
- 가장 끝 원소 -> rear
- rear로 들어오지만 front부터 빠지는 특성
- 가장 먼저 들어온 front 원소가 가장 먼저 삭제 
__ -> front 원소는 가장 먼저 queue에 들어왔던 첫 번째 원소가 되는 것이며, rear 원소는 가장 늦게 queue에 들어온 마지막 원소가 되는 것

<br/>

### __< queue의 활용 예시 >__
주로 데이터가 입력된 시간 순서대로 처리해야 할 필요가 있는 상황
- 너비 우선 탐색 (BFS, Breadth-First Search) 구현


********

### < stack과 queue의 비교 >
![img1 daumcdn](https://user-images.githubusercontent.com/90206705/149522118-4df4c75b-5369-432a-9bd4-447995e06d38.png)




