# 1. Research Question and Hypotheses
In this first assignment, you will **formulate and answer a research question** using the academic method.  
Your report should document your experiment — for instance, as a **Jupyter Notebook**.

### Overall Research Question
Which software characteristic has the largest impact on energy consumption compared to CPU-intensive workloads?

### More Precise Research Question
Does **[chosen characteristic]** lead to higher energy consumption than CPU-bound workloads when controlling for execution time?

When working, it is important to define the **independent**, **dependent**, and **controlled** variables.  
Both questions above are intentionally general and do not yet define the independent variable.

Your first task is to make the question **precise enough to be testable**, for example:

> Programs dominated by [characteristic] consume less energy than CPU-heavy programs because [expected reason, e.g., more idle CPU cycles, I/O wait, etc.].

### Requirement 1.1
In your report, state your:
- **Research Question**
- **Precise null hypothesis** and **alternative hypothesis**

*A short motivation for why you chose your independent variable is appreciated but not required.*

### Requirement 1.2
In your report, describe your:
- **Independent variable**
- **Dependent variable**
- **Controlled variables**

---

# 2. Methodology

In this assignment, the methodology is partly fixed since you must use **RAPL** on the provided laptops.  
However, the number of executions and how you control variables are up to you.

Your method description should be **detailed enough** that another person could reproduce your experiment, including your code.

### Requirement 2.1
In your report, describe the:
- **Control** and **experimental setup**

After collecting your results, analyze them statistically and state whether you have sufficient evidence to **reject the null hypothesis**.

### Requirement 2.2
In your report, provide and briefly describe:
- The **collected data**
- The **statistical analysis and results**

---

# 3. Interpretation and Discussion

After completing your statistical analysis, **interpret and discuss your results**.  
Go beyond stating whether you can reject the null hypothesis and reflect on **why** your results appear as they do.

As part of your discussion, consider what **RAPL (Running Average Power Limit)** actually measures and whether it can be expected to capture the energy effects of your chosen software characteristic.

Think about:
- Which parts of the system are measured  
- How measurements are obtained  
- How this might influence your interpretation of the results  

You may consult:

> Khan et al. (2018) – *RAPL in Action: Experiences in Using RAPL for Power Measurements.*  
> ACM Transactions on Modeling and Performance Evaluation of Computing Systems (TOMPECS), 3(2), 9:1–9:22.  
> [https://doi.org/10.1145/3177754](https://doi.org/10.1145/3177754)

### Requirement 3.1
In your report, include a brief discussion interpreting your results in relation to:
- Your **experimental observations**
- Whether and how **RAPL** would be expected to measure the energy effects of your chosen characteristic

---

# 4. Validation

### Internal Validity
Internal validity refers to how accurately your experiment measures what it intends to measure.  
In other words, it assesses whether the observed effects between variables truly result from manipulation of the independent variable(s), rather than from **confounding factors**.

To ensure high internal validity, you must minimize the influence of confounding variables — that is, variables other than the independent variable that may affect the dependent variable and lead to inaccurate conclusions.

For inspiration on identifying potential confounders, see:  
Luis Cruz’s blog on energy experiments:  
[https://luiscruz.github.io/2021/10/10/scientific-guide.html](https://luiscruz.github.io/2021/10/10/scientific-guide.html)

### Requirement 4.1
In your report, briefly describe the **internal validity** of your experiment, i.e., identify possible **confounding variables**.

---

### External Validity
External validity refers to how **generalizable** your results are — that is, whether your findings apply to other settings, populations, or technological environments beyond your experiment.

Consider relevant dimensions of external validity, such as:
- Real-world IT systems  
- Diverse IT environments  
- Different user behaviors  
- Software applications  
- Scaled-up infrastructure  
- Technological advancements  

Include only the aspects you find most relevant.

### Requirement 4.2
In your report, briefly describe the **external validity** of your experiment.

---

# 5. Reflections

To support research and improve the course, please include some reflections based on your work with energy efficiency:

- Did you have any “aha” moments or surprises?  
- What was the most cumbersome aspect of conducting the experiment?  
- Can you identify any learnings that may influence your future software design or coding practices?  
- Did you use any particular tactics or approaches?  
- Any other interesting observations?

### Requirement 5.1
In your report, include your **reflections**.
