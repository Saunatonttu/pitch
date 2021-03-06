---
title       : Smoking cost calculator
subtitle    : A shiny app for calculating smoking costs
author      : Tuomo Sillanpaa
job         : Student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Description of the Application

<br>
<h4> - The Smoking Cost Calculator -app is a simple </h4>
<h4> way to measure the costs of one's smoking over </h4>
<h4> a perioid of time. </h4>
<br>
<h4> - Such information might then serve to motivate </h4>
<h4> the user to reduce or altogether quit his/her smoking. </h4>

--- .class #id 

## Motivation behind the Application

<br>
<h4> - The app was designed as a coursework for the </h4>
<h4> course "Developing Data Products". </h4>
<br>
<h4> - The goal was to create a simple shiny app </h4>
<h4> that gives the user useful information based </h4>
<h4> on his/her input. </h4>

---

## Functionality of the Application

<br>
<h4> - The user can input values for his/her </h4>
<h4> amount of years and months of smoking, </h4>
<h4> the average amount of packs smoked each month, </h4>
<h4> and the average price of each pack in euros. </h4>
<br>
<h4> - After the user presses the "Submit"-button, </h4>
<h4> the app calculates the total cost based on these values. </h4>

---

## Example values and result

<br>
<h4> - For example, if the user inputs the following values: </h4>
<h5> Years smoked: 2 </h5>
<h5> Months smoked: 4 </h5>
<h5> Packs per month on average: 9 </h5>
<h5> Price of pack on average in euros: 4.5 </h5>
<br>
<h4> The calculation and the result will be as follows: </h4>

```r
((12 * 2) + 4) * 9 * 4.5
```

```
## [1] 1134
```


