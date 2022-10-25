# REMO Frontend HomeWork
먼저 인터뷰에 응해주셔서 감사합니다.

First of all, thank you for agreeing to the interview.

우리는 당신의 기술 지식에 대해서 조금의 정보가 더 필요해서 이번 과제를 준비했습니다.

We have prepared this assignment because we need a little more information about your technical knowledge.

좋은 인연이 되길 바라며 과제 진행중 질문이 있으시면 <kishe56@gmail.com> 으로 질문 주시면 늦어도 다음날까지 답변 드리도록 하겠습니다.

I hope it will be a good relationship, and if you have any questions during the assignment, please send them to <kishe56@gmail.com> and I will answer them by the next day at the latest.

### Goal

Make a ToDo Plan App.



## Features

- signIn
- signUp
- create ToDoItem
- search  ToDoItem(title, contents 를 keyword 로)
- modify ToDoItem
- delete ToDoItem
- notify ToDoItem(with service worker)

```
ToDoItem 의 Notification 은 remindAt 에 세팅된 Date 에 일어나야하며 Background 에서도 동작되어야합니다.
The ToDoItem notification should also fire in the background on the date set in RemindAt .
```
*Notification 은 앱이 foreground 거나 background 여도 동작해야합니다.*

ToDoItem 의 예시는 다음과 같습니다.

````javascript 
ToDoItem
{
    uuid: UUID v4 format. Unique key,
    author: author's key for reference.
    title: title,
    contents: contents,
    remindAt: Date for notify,
    createdAt: Date,
    updatedAt: Date,
    deletedAt: Date,
}
````

### Notice
```
사용되는 데이터와 API Mock 처리 하셔도 괜찮습니다. 
It is okay to process used data and API Mock.
디자인도 편하신대로 본인이 디자인 하시거나 템플릿을 이용하셔도 괜찮습니다.
You can design your own design or use a template as per your convenience.
단 기능 구현 및 디자인 코드에 대해서 최대한 설명 가능한 코드를 작성해야 합니다.
However, you should be able to describe the functionality and design code.
```


