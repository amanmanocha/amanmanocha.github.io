---
layout: post
title: Blocking is evil
---

### Do not block!

Threads are [expensive](http://stackoverflow.com/questions/5483047/why-is-creating-a-thread-said-to-be-expensive)! 
They consume expensive resources throughtout their life. Clearly, we can not have lots of them. While they are alive, 
they better be doing something useful . We can not afford to have threads being blocked more so when we are running our applications on the cloud. Blocking on threads directly results in losing money.
So be very careful whenever you call any blocking method like Futures.get() or Thread.wait(). Try to find ways around them.

----
****
