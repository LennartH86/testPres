---
title       : Test Title
subtitle    : Subtest Title
author      : me
job         : messy
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [quiz]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 

## Slide 2

Test slide 2

--- &radio2

## Question 1

What is 1 + 1?

1. 1
2. _2_
3. 3
4. 4

*** .hint This is a hint
*** .explanation This is an explanation

--- 

## Another knitr slide


```r
sum(1:10)
```

```
## [1] 55
```

```r
10 * (11) / 2
```

```
## [1] 55
```

```
1+1
```

