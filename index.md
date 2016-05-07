---
title       : Test
subtitle    : sub test
author      : me
job         : internet
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 

## Slide 2

test slide 2



```
## Warning in summary.lm(fit): essentially perfect fit: summary may be
## unreliable
```

```
## 
## Call:
## lm(formula = y ~ x1)
## 
## Residuals:
##        Min         1Q     Median         3Q        Max 
## -5.661e-16 -1.157e-16  4.273e-17  2.153e-16  4.167e-16 
## 
## Coefficients:
##              Estimate Std. Error   t value Pr(>|t|)    
## (Intercept) 1.123e-15  2.458e-16 4.571e+00  0.00182 ** 
## x1          5.000e-01  1.980e-17 2.525e+16  < 2e-16 ***
## ---
## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
## 
## Residual standard error: 3.598e-16 on 8 degrees of freedom
## Multiple R-squared:      1,	Adjusted R-squared:      1 
## F-statistic: 6.374e+32 on 1 and 8 DF,  p-value: < 2.2e-16
```
