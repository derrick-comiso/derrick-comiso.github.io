---
layout: essay
type: essay
title: Smart Questioning
date: 2016-09-08
labels:
  - Open Source Software
  - Questions
  - Answers
  - StackOverflow
---

Anyone can learn how to code, but when one gets stuck on a certain problem that they encountered, can anyone just ask the experts on how to solve it? Of course, but depending on how one asks a question, or even why one is asking it, can ultimately determine the kind of responses that follow. For example, several times in the past I have been stumped on a part of my code and why it was wrong, but instead of trying to understand the error in my code with the resources I have online, I simply copy and paste chunks of it to boards and hope someone solves it overnight. Of course I learned after that not only was it lazy of me to do so, it was flat out the incorrect and often rule-breaking way of asking questions. Thus, it is important to do things the smart way, and that is to think of a clear and concise question, and try and look for answers using other sources before going on online boards. Most of the time, answers can be found through a simple search, while other people have asked the same questions that lead to given solutions. But in the case that all other resources have been exhausted, that would be the time to directly consult the community. Approaching the community is a careful matter, however. Software engineers need to get most of the information in order to get more knowledge, and to get better information is by asking better, or smarter questions.

StackOverflow is open to everyone, and is a great tool for getting great answers. However, as everyone can use it, there can also be poor questions that can lead to poor answers, such as misleading or irrelevant solutions, and even as poor as having questions as answers. This is why it is important to ask questions in a smart way, such as showing knowledge of what one is doing and how things work, either from their own experience or from what they have learned when searching for answers elsewhere. A great example is shown below, in which the inquirer showcases what he has learned from the manual, and also how he would try and answer the question.

```
Q: Is sizeof(void()) a legal expression?
From [5.3.3/1], I found that:
The sizeof operator shall not be applied to an expression that has function or incomplete type

From [3.9/5] I found that:
Incompletely-defined object types and cv void are incomplete types

Anyway, for sizeof does not evaluate it's operands, I would have said that sizeof(void()) was a 
legal expression (actually GCC compiles it and the result is 1).
On the other side, from here, void is not mentioned while discussing sizeof, neither when the 
types having size 1 are mentioned, nor in the list of the ones having an implementation defined size.

The question is thus: is sizeof(void()) a legal expression?
Is it guaranteed to have size equal to 1?
Or is it a legal expression resulting in an UB and that's all?
```

The inquirer already gives additional information from online documentation as to why his answer would be wrong, thus giving any potential helpers an insight to his/her thinking process. Apart from the main question, he/she offers two other questions that could help clarify what kind of solution is being sought. As a result of this smart and informative question, five answers were given. The first is a simple explanation of the function type in question. Other answers referred to documentations, and others gave specific examples. All in all, this question succeeded in finding appropriate and relevant answers.

