---
layout: post
title: Blocking is evil
---

### Do not block

Threads are [expensive](http://stackoverflow.com/questions/5483047/why-is-creating-a-thread-said-to-be-expensive)! 
They consume expensive resources throughtout their life. Clearly, we can not have lots of them and since we they are eating resources while they are alive, 
they better be doing something useful while they are alive. We can not afford to have threads being blocked. 

----
****
