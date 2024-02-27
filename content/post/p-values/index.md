+++
author = "Johnny Lowe"
title = "P-Values"
date = "2024-02-26"
description = "An introduction to p-values."
tags = [
  "p-values",
  "statistics"
]
categories = [
]
series = [""]
aliases = [""]
+++

P-values are values between 0 and 1 that tell us the strength of evidence against the null hypothesis. A lower p-value suggests stronger evidence against the null hypothesis, indicating that the observed data is less likely to be due to random chance alone. We establish a significance level, denoted by $\alpha$, as the threshold for rejecting the null hypothesis, typically set at $\alpha$ = 0.05.

We interpret the p-value by checking whether or not it is **less than or equal to**  or **greater than** the level of signifiance we selected. If the p-value $<=$ $\alpha$, then we reject the null hypothesis and determine that the observed data is unlikely to have occured simply by chance; however, if the p-value $> \alpha$, then we fail to reject the null hypothesis and determine the observed data could have occured due to random chance. 
