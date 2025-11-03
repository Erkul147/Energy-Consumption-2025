# 1. Research Question and Hypotheses

## Overall Research Question
Which software characteristic has the largest impact on energy consumption compared to CPU-intensive workloads?

## More Precise Research Question
Does [chosen characteristic] lead to higher energy consumption than CPU-bound workloads when controlling for execution time?

Your first task is to make the question precise enough to be testable, for example:

> Programs dominated by [characteristic] consume less energy than CPU-heavy programs because [expected reason, e.g., more idle CPU cycles, I/O wait, etc.].

### Requirement 1.1
In your report, state your **Research Question**, together with a precise **null hypothesis** and **alternative hypothesis**.

A short motivation for why you chose your independent variable is appreciated but not required.

### Requirement 1.2
In your report, describe your **independent**, **dependent**, and **controlled variables**.


# 2. Methodology

In this assignment, the methodology is partly fixed since you must use the external power supply on the provided laptops.  
However, the number of executions and how you control variables are up to you.  
Your method description should be detailed enough that another person could reproduce your experiment, including your code.

### Requirement 2.1
In your report, describe the **control and experimental setup**.

After collecting your results, analyze them statistically and state whether you have sufficient evidence to reject the null hypothesis.

### Requirement 2.2
In your report, provide and briefly describe:
- The **collected data**, and  
- The **statistical analysis and results**


# 3. Interpretation and Discussion

After completing your statistical analysis, interpret and discuss your results.  
Go beyond stating whether you can reject the null hypothesis and reflect on why your results appear as they do.

As part of your discussion, consider what the external power supply actually measures and whether it can be expected to capture the energy effects of your chosen software characteristic.  
Think about which parts of the system are measured, how measurements are obtained, and how this might influence your interpretation of the results.

### Requirement 3.1
In your report, include a brief discussion interpreting your results in relation to:
- Your **experimental observations**, and  
- Whether and how the **external power supply** would be expected to measure the energy effects of your chosen characteristic.


# 4. Validation

Internal validity refers to how accurately your experiment measures what it intends to measure.  
In other words, it assesses whether the observed effects between variables truly result from manipulation of the independent variable(s), rather than from confounding factors.

To ensure high internal validity, you must minimize the influence of confounding variables — that is, variables other than the independent variable that may affect the dependent variable and lead to inaccurate conclusions.

For inspiration on identifying potential confounders, see:  
[Luis Cruz’s blog on energy experiments](https://luiscruz.github.io/2021/10/10/scientific-guide.html)

### Requirement 4.1
In your report, briefly describe the **internal validity** of your experiment, i.e., identify possible **confounding variables**.
