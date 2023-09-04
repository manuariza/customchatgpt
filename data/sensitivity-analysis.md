---
title: "Sensitivity analysis"
category: "Operations"
date: "2021-04-07 12:00:00 +09:00"
desc: "‘Sensitivity analysis’ is a tool for mapping out the range of potential outcomes around a decision, and is especially useful when there is uncertainty around key variables"
thumbnail: "./images/sensitivity-analysis/thumbnail.jpg"
alt: "‘Sensitivity analysis’ is a tool for mapping out the range of potential outcomes around a decision, and is especially useful when there is uncertainty around key variables. ."
---

'Sensitivity analysis' is a tool for mapping out the range of potential outcomes surrounding a decision, and it is especially useful when key variables are uncertain. Due to the possibility of multiple variables interacting with one another, sensitivity analysis is typically aided by computer software. <br>

## When to use it

● To gain a better understanding of how a proposed plan might turn out if certain model inputs are known. <br>
● To identify flaws in the proposed plan before it is implemented.<br>
● To comprehend the factors that have the greatest influence on outcomes.<br>

## Origins
During the computer revolution, sensitivity analysis emerged. Before computers, making quantitative estimates based on multiple inputs was a time-consuming process. As processing speeds increased, it became much easier to make small changes to calculation inputs to see what the result would be. <br><br>
The introduction of computer-based spreadsheets transformed sensitivity analysis. Visicalc, introduced in 1979, was the first spreadsheet, eventually being surpassed by Lotus 1-2-3 in the 1980s and Microsoft Excel in the 1990s. Of course, the beauty of spreadsheets is that changing one cell changes the entire set of calculations. <br><br>
Over the years, many other types of sensitivity analysis have emerged. If you can't use a spreadsheet because the inputs interact in highly complex ways, you can perform 'Monte Carlo simulations' to identify a range of possible outcomes. <br>

## What it is
Sensitivity analysis is a useful tool when faced with a complex decision and want to know what impact a change in one input variable will have on the results. A simple form of sensitivity analysis could isolate the impact of a change in sales levels on a company's net earnings. A more sophisticated approach might consider how price changes from two competitors interact to affect your sales levels. Sensitivity analysis can also be quite complicated. Consider a life insurance company that wants to know how to price its new term life insurance product, which is aimed at smokers aged 60 and up. An analytical team could examine the life tables that show the rate of deaths for this population over a given time period, then create a Monte Carlo simulation in Excel to test the product in question. A Monte Carlo simulation generates different models of results – possibly thousands of times in a row – to determine the range of possible outcomes for a scenario. In this case, the goal may be to determine how best to price the policies in order to earn a small underwriting profit.<br>

## How to use it
There are numerous approaches to sensitivity analysis that can be used. Here is a typical set of steps you could take:
● Select the key parameters (the input variables): Choose a reasonable range for each one, such as maximum and minimum values or an 80% confidence interval around the likely mean. Consider other scenarios that could affect the outcomes.<br>
● Conduct the sensitivity analysis by varying each parameter individually: This allows you to identify specific parameters to which the key decision variables are relatively unresponsive. They can then be excluded from further investigation.<br>
● For the remaining parameters, consider how correlated they are with one another: Then, based on that analysis, develop a model that allows you to change various variables. Select variables that are not highly correlated with each other through trial and error (for example, net income and EBIT may show a higher degree of correlation than net income and sales).<br>
● Summarise the results: Choose and rank the variables that have the greatest influence on the results. Report them in tables or use a chart to visually represent the results.<br>
● Identify a ‘best-bet’ strategy: A thorough examination of the results should reveal a 'best-bet' strategy as well as several alternatives. A strategy may be chosen because it produces the best results, it serves another purpose (for example, the launch of a new product supports another product line), or it is ready to implement right away. <br><br>

### Top practical tip
<div style="background:transparent;
            border-radius: 25px; 
            font-size: 20px; 
            padding: 10px; 
            border: 5px solid lightgray; 
            margin: 10px;">A thorough sensitivity analysis takes time and effort. While it may be tempting to try to skip some of the steps, perhaps because you have a gut feeling about what the answer will be, this should be avoided. The compound effects of certain variables on others can be surprising at times, and it takes careful analysis to uncover these interactions.<br></div>

### Top pitfall
<div style="background:transparent;
            border-radius: 25px; 
            font-size: 20px; 
            padding: 10px; 
            border: 5px solid lightgray; 
            margin: 10px;">
The most common mistake in performing sensitivity analysis is assuming that input variables move relatively independently of one another when, in fact, they are highly correlated. Consider the 2008 financial crisis. At its core, the crisis occurred because toxic assets known as "collateralized debt obligations" were far more risky than banks and credit rating agencies had previously believed. Because of poor sensitivity analysis, these risks were underplayed – everyone assumed that only a small percentage of home-owners would default on their mortgages, when in fact all home-owners were vulnerable to the same risk of rising interest rates. Many homeowners defaulted around the same time, precipitating the financial crisis. <br></div>

## Further reading
Saltelli, A., Chan, K. and Scott, E.M. (eds.) (2000) Sensitivity Analysis. New York: John Wiley & Sons.<br><br>
Silver, N. (2012) The Signal and the Noise: Why so many predictions fail, but some don’t. London: Penguin.<br><br>