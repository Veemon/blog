---
title: "Welcome Post"
date: 2023-06-27
tags: ["first"]
showToc: true
TocOpen: false
draft: true
math: true
description: "Can we create a Hugo site?"
---

# An introduction with Hugo.
## Can we do equations?

This is a test using Hugo. Ideally, I would like to be able to render things like in-text math, such that 
$f$ and $f(x)$ and $f(x) = \frac{1}{2}$.
And also bigger equations ...

$$
f(x) = \int_\Omega \frac{sin(x)}{x} d \mu
$$


## Can we do code?

```c
#include "stdio.h"

#define today_heat 36

void log(const u8* string) {
    // ... stuff ...
}

void main() {
    // This is friendly :)
    log("G'day mate!\n");

    // Gotta crack open a cold one when its hot
    int beers = 12;
    if (today_heat > 36 - 1) {
        beers--;
    }
}
```
