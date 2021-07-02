# useR2021_tutorial
Materials for the useR!2021 tutorial on data validation


## Preparations

Install the following packages, by copying the code below.

```r
install.packages("validate")
install.packages("validatetools")
install.packages("lumberjack")
install.packages("simputation", dependencies=TRUE)
```

## Time outline


### Part 1: Introduction to validate and data validation. (60 min)

- Opening and hands-on introduction to 'validate' workflow (20 min)
- Presentation: theory of data validation + Q & A (20 min)
- Breakout assignment & discussions in groups (20 min)

### Break (10 min)

### Part 2: Expressing data checks (50 minutes)

- Feedback on results of the breakout groups (10 min)
- Focus on different validation tasks. Small programming 
  assignments, from simple to complex tasks.  (40 min)


### Break (10 min)

### Part 3: Automating data quality measurement with lumberjack (50 min)

- Hands-on introduction to lumberjack (15 min)
- Presentation: monitoring data in R and  Q&A (15 min)
- Hands-on: lumberjack and validate  (20 min)

### Break (10 min)

### Part 4: Managing data validation rules (50 min)

- hands-on introduction to the {validatetools} package (20 min)
- Presentation and Q&A validation rule management (20 min)
- Closing and Q&A (10 min)


## Materials for further reading

- [Data validation infrastructure for R](https://www.jstatsoft.org/index.php/jss/article/view/v097i10/v97i10.pdf) van der Loo and de Jonge (JSS, 2021)
- [Monitoring data in R with the lumberjack package](https://www.jstatsoft.org/index.php/jss/article/view/v098i01/v98i01.pdf) van der Loo (JSS, 2021)
- [Data Validation](https://arxiv.org/pdf/2012.12028) van der Loo and de Jonge (Wiley StatsRef Online, 2020)
- [Statistical Data Cleaning with Applications in R](https://www.wiley.com/en-us/Statistical+Data+Cleaning+with+Applications+in+R-p-9781118897157) van der Loo and de Jonge (Wiley, 2018)



