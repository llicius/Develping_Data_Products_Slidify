---
title       : Tax Calculator
subtitle    : 
author      : Fabricio Loayza
job         : Tax calculator
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
logo        : logo.png
---

## 30% ruling in The Netherlands


1. The 30 percent reimbursement ruling is a tax advantage for foreign employees working in the Netherlands
2. If a number of conditions are met, the employer is allowed to grant a tax free allowance amounting to 30 percent times 100/70 of the gross salary subject to Dutch payroll tax
3. This results in a maximum (effective) tax rate of approximately 36.4 percent
4. The tax free allowance is considered a compensation for the expenses that a foreign employee has by working outside his or her home country

--- .class #id 

## Purpose of the Tax calculator


If you want to benefit from the 30% ruling certain requirements need to be met, but calculating your net salary might be difficult

 
Here, we developed a simple tax calculator, where you can input the gross salary and find out what the net salary is with the 30% tax break

--- .class #id 

## Tax deduction
 
So to calculate the net montly salary of a person who earns 45,000 euro a year, we can use the web application and run the following


```r
((45000- ((45000 * 0.7))*(42/100))/12)
```

```
## [1] 2648
```

In this way you can easily calculate the net amount you'll receive at the end of the month

--- .class #id 

## Thanks!
 
I hope this helps you with your tax deductions while working in Holland.

Thanks for your time and feedback

--- .class #id 
