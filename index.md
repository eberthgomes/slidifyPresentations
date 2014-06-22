---
title       : Standard BMI Calculator
subtitle    : Calculate Your Body Mass Index
author      : Eberth Gomes
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---

## Body Mass Index

The body mass index (BMI) is a measure of relative weight based on an individual's mass and height.

Devised between 1830 and 1850 by the Belgian polymath Adolphe Quetelet during the course of developing "social physics",[2] it is defined as the individual's body mass divided by the square of their height – with the value universally being given in units of kg/m2.

$$ BMI = \frac{mass(kg)}{(height(m))^{2}}$$

The BMI is used in a wide variety of contexts as a simple method to assess how much an individual's body weight departs from what is normal or desirable for a person of his or her height. 

---

## BMI Calculator

The Standard BMI Calculator is a Shiny App that calculate the body mass index based on mass and height.

![alt text](images/example_bmi.png)

---

## How to Use & How it works

To use the BMI Calculator, just fill in the fields with mass and height and the result is shown automatically.

The program receives the input


```r
mass = 70.0
height = 1.8
```

Then calculates the body mass index as follow


```r
mass / (height * height)
```

```
## [1] 21.6
```

The program also shows the category of BMI for the result.

---

## Bibliography

http://en.wikipedia.org/wiki/Body_mass_index

http://www.nhlbi.nih.gov/guidelines/obesity/BMI/bmicalc.htm
