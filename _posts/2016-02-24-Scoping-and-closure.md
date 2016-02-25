---
layout: post
title: Scoping, Scoping, Scoping ...
tags:
- jekyll
- code
- javascript
- TIL
---

This morning at Metis, our pair-programming problem was a simple (yet interesting) one about javacript scoping.

```javascript
var add = (function () {
    var counter = 0;
    return function () {return counter += 1;}
})();

add();
add();
add();
```

Turns out, you could do scoping in Python as well. But not as straight forward. 
In python 3.x



# Today I learned:
```
Variables created without the keyword var, are always global, even if they are created inside a function.
javascript functions run immediately when you put () after their names. Self-invoking analymous function has () at the end, so they immediately
```
