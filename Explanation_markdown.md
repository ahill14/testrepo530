---
title: "Intro to R Markdown"
author: "ahill14"
date: "6/3/2019"
output: 
  html_document:
    keep_md: yes
---



# R Markdown
This is a Markdown document in RStudio.   
It is a great way to distribute finalized code and findings. 

### Code
Here is a chunk of code that I will include in my report: 

```r
str(cars)
```

```
## 'data.frame':	50 obs. of  2 variables:
##  $ speed: num  4 4 7 7 8 9 10 10 10 11 ...
##  $ dist : num  2 10 4 22 16 10 18 26 34 17 ...
```

```r
mean(cars$speed)
```

```
## [1] 15.4
```

```r
mean(cars$dist)
```

```
## [1] 42.98
```
 
### Equations
You can also embed mathematical equations like this:  
Add 3 and 5: 
$$ 3 + 5 = 8 $$. 

### Displaying code
You can customize how code and results show up in your .Rmd:

* echo = FALSE hides code, shows results 
* eval = FALSE 
* message = FALSE hides messages, shows and evalutates code

For example. 

* echo = FALSE 

```
## 'data.frame':	50 obs. of  2 variables:
##  $ speed: num  4 4 7 7 8 9 10 10 10 11 ...
##  $ dist : num  2 10 4 22 16 10 18 26 34 17 ...
```

* eval = FALSE

```r
str(cars)
```




