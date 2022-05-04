---
layout: post
title:  "JavaScript Array Functions"
date:   2022-05-04 18:43:40 +0200
categories: jekyll update
---

In this chapter we will look at some important array functions.

**1**. The first function is ***forEach()***

``let numbers = [1, 2, 3, 4, 5];``

  ``numbers.forEach((number, index) => console.log(number, index); });``

*The result would be:*
- 1, 0
- 2, 1
- 3, 2
- 4, 3
- 5, 4

Now let's try to write our own forEach function:
<br>
`` for (let i = 0; i < numbers.length; i++) {``
<br>
``console.log(numbers[i], i);``
<br>
``}``

*The result will be the same.*