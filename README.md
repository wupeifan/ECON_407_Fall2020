# ECON407, Fall 2020
Course material and schedules for ECON407 in 2020 fall

## Syllabus
Check [Syllabus](syllabus.md) for more details.

[Final Project](FinalProject.md). Due date: **December 22nd**, the last day of exams.

## Jupyter Hubs
You can either use [UBC Syzygy Jupyter Hub](http://ubc.syzygy.ca) or Google Colab for a free Jupyter hub.

## Lectures
1. **September 8th**: Imagine Day at UBC. Class cancelled.
2. **September 10th**: Logistics, [Syllabus](syllabus.md), [Math Review](Notes/Math_Review.pdf)
3. **September 15th**:
    - Finish [Math Review](Notes/Math_Review.pdf): Leftover proof; Example of constrained optimization; Probability part
    - Introduction to Python
        - [Setting up Environment](https://python-programming.quantecon.org/getting_started.html): Local installation, or [UBC Jupyter Hub](http://ubc.syzygy.ca)
        - [Jupyter Notebook Basics](https://python-programming.quantecon.org/getting_started.html#Notebook-Basics): Code block / Markdown block, running codes, function help, etc
        - Try running codes as in [An Introductory Example](https://python-programming.quantecon.org/python_by_example.html). Make yourself familiar with Jupyter notebook
    - [Python Basics](Notebooks/Basics.ipynb)
        - In addition, go over [Writing Good Code](https://python-programming.quantecon.org/writing_good_code.html) by yourselves

4. **September 17th**:
    - [Collections and Numpy vector/matrix operations](Notebooks/CollectionAndNumpy.ipynb)
        - Please go over [Numpy](https://python-programming.quantecon.org/numpy.html) by yourselves
    - [Control Flow](Notebooks/ControlFlow.ipynb), [Functions](Notebooks/Functions.ipynb)
        - For those who don't have programming experience before, please go over [Python Essentials](https://python-programming.quantecon.org/python_essentials.html) for reference and details.

5. **September 22nd**:
    - Briefly cover [Numpy vector/matrix](Notebooks/CollectionAndNumpy.ipynb)
        - Please go over the Jupyter notebook carefully. We won't go over all of them in detail.
    - [Finite Markov Chains](https://python.quantecon.org/finite_markov.html). Some Python code examples [here](Notebooks/MarkovChainExample.ipynb)

6. **September 24th**:
    - Finish [Finite Markov Chains](https://python.quantecon.org/finite_markov.html): properties of Markov chain, distribution simulation, etc.
        - Python code examples [here](Notebooks/MarkovChainExample.ipynb)

7. **September 29th**:
    - Introduction to [Dynamic Programming](https://en.wikipedia.org/wiki/Dynamic_programming):
        - [Maximum Path Sum](https://projecteuler.net/problem=18)
    - The definitions of value function and policy functions
    - Handle questions and discussions for [Problem Set 1](ProblemSets/PS1.pdf)

8. **October 1st**:
    - Dynamic Programming continued: [Shortest Paths](https://python.quantecon.org/short_path.html) on a directed acyclic graph
    - An example in Economics: [McCall Model](https://python.quantecon.org/mccall_model.html)

9. **October 6th**:
    - [Problem Set 1](ProblemSets/PS1.pdf) Review
    - Lab session for Basic Python coding for the rest of the class
        - Check [Programming Examples](Notebooks/ProgrammingExamples.ipynb) for details

10. **October 8th**:
    - More formal introduction to [Discrete Dynamic Programming](Notes/Dynamic_Programming.pdf)
    - [McCall Model](https://python.quantecon.org/mccall_model.html) continued

11. **October 13th**:
    - Code to solve [Discrete Dynamic Programming](Notes/Dynamic_Programming.pdf) problems with [McCall Model](https://python.quantecon.org/mccall_model.html)
        - Code example used in class is [here](Notebooks/McCall.ipynb)
        - Note: We will differ a bit from the QuantEcon lectures, therefore going through the webpages might not be sufficient.
    - Practice formulating Bellman equations and coding to solve them
        - An example similar to [An Extension of McCall Model](https://python.quantecon.org/mccall_model_with_separation.html)

12. **October 15th**:
    - Two more examples for [variations of McCall Model](Notebooks/McCallVariations.ipynb)
        - Formulate the Bellman equations
        - Code to solve the model
        - If you are interested, you can check the following lectures [here](https://python.quantecon.org/index_search.html) (you don't have to)

13. **October 20th**:
    - [Problem Set 2](ProblemSets/Solutions/PS2_sol.ipynb) Review
    - Stochastic Growth / Real Business Cycle Models
        - [Motivation](Notebooks/RBC_motivation.ipynb)
        - Check [RBC Notes](Notes/RBC.pdf)

14. **October 22nd**:
    - RBC model continued

15. **October 27th**:
    - [Problem Set 3](ProblemSets/Solutions/PS3_sol.ipynb) Review
    - [Solve the model](Notebooks/RBC_solve.ipynb)
    - The simplest General Equilibrium: adding labor into RBC
        - [Motivation](Notebooks/RBC_motivation.ipynb)
        - Check [RBC Notes](Notes/RBC.pdf)

16. **October 29th**:
    - [Risk Aversion](Notes/Risk_Aversion.pdf)
        - We will further talk about it when covering simple asset pricing applications
    - Policy function analysis
        - Check the updates of [Solve the model](Notebooks/RBC_solve.ipynb)
    - Shortcomings of RBC
        - Check a [comment](References/Summers_comment.pdf) from Larry Summers
        - Parameters? Shocks? Market Clear? Monetary Policy?

17. **November 3rd**:
    - [Discretize an AR(1) process](Notes/Tauchen.pdf)
    - [Lucas Asset Pricing Model](Notes/Lucas_Tree.pdf)
        - Check [this lecture](https://python-advanced.quantecon.org/lucas_model.html) for further reading

18. **November 5th**:
    - [Lucas Asset Pricing Model](Notes/Lucas_Tree.pdf) continued
    - CAPM and CCAPM
    - [Asset Pricing in Finite State Space](https://python.quantecon.org/markov_asset.html)

19. **November 10th**:
    - [Example of CCAPM](Notebooks/CCAPM.ipynb) asset pricing
    - Incomplete Markets on the household side: [Income fluctuation](https://python.quantecon.org/ifp.html) and Aiyagari model

20. **November 12th**:
    - [Problem Set 4](ProblemSets/Solutions/PS4_sol.ipynb) Review
    - Incomplete Markets on the household side: [Income fluctuation](https://python.quantecon.org/ifp.html) and Aiyagari model, continued
        - [Permanent Income Hypothesis](Notes/PIH.pdf)

21. **November 17th**:
    - [Natural borrowing limit](Notes/Natural_Debt_Limit.pdf)
    - Solving the [Income fluctuation](https://python.quantecon.org/ifp.html) Problem
        - Comparative statics and further discussions
    - Inequality and redistribution implications

22. **November 19th**:
    - Incomplete Markets on the firm side: The firm investment problem
        - [Notes](Notes/Firm_Dynamics.pdf)
    - Tobin's q, and the value of the firm

23. **November 24th**
    - Average Q vs Marginal Q
    - Hayashi (1982), convex adjustment cost
    - The value premium
        - check updated [Notes](Notes/Firm_Dynamics.pdf)

24. **November 26th**
    - Entry, Exit, and Firm Dynamics
        - [Model with Entry and Exit](Notes/Entry_Exit_Firm.pdf)
        - Empirical motivations

25. **December 1st**
    - Modeling COVID in macroeconomics
        - Check [this paper](References/Epidemics.pdf) and their [slides](References/ERTslides.pdf)

26. **December 3rd**
    - Optimal government policy: [Ramsey problem](Notes/Ramsey.pdf)

## Assignments

1. [Problem Set 1](ProblemSets/PS1.pdf) due on **September 30th**
2. [Problem Set 2](ProblemSets/PS2.ipynb) due on **October 14th**
3. [Problem Set 3](ProblemSets/PS3.ipynb) due on **October 25th**
4. [Problem Set 4](ProblemSets/PS4.ipynb) due on **November 9th**
5. [Problem Set 5](ProblemSets/PS5.ipynb) due on **December 6th**
