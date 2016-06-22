---
permalink: /R_programs/
layout: default
title: R programs for quantitative investing
type: "pages"
subtitle: R programs for exploring quantitative investing.
---

### Here is some R code:  

```
summary(cars)
plot(cars)
```
---

### Create a plot using ggplot2:  

```
# load ggplot2 silently
set.seed(1)
mydf <- data.frame(x=rnorm(5e4),y=rnorm(5e4))
ggplot(mydf, aes(x,y)) + geom_point(alpha=0.6)
```





