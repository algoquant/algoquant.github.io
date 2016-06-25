---
title: R programs and packages
subtitle: R programs and packages for exploring quantitative investing.
permalink: /R_programs/
layout: default
type: page
---

### Here is some R code:  

```r
summary(cars)
plot(cars)
```
---

### Create a plot using ggplot2:  

```r
# load ggplot2 silently
set.seed(1)
mydf <- data.frame(x=rnorm(5e4),y=rnorm(5e4))
ggplot(mydf, aes(x,y)) + geom_point(alpha=0.6)
```





