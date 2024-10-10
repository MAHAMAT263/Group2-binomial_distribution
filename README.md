# Group2-Binomial_Distribution

This project explores the binomial distribution, a fundamental concept in probability theory used to model discrete random variables with two possible outcomes, typically "success" and "failure." It's characterized by two key parameters:

- **Number of trials (n):** Represents the total number of independent experiments or observations conducted.
- **Probability of success (p):** Represents the likelihood of a successful outcome in a single trial.

This project delves into the application of the binomial distribution through various resources:

# 1. Slides:

Here is the [link](https://www.canva.com/design/DAGTLelAXTw/9pR0bzBMW2qpNYp47uXtaA/edit?utm_content=DAGTLelAXTw&utm_campaign=designshare&utm_medium=link2&utm_source=sharebuttonl)

The included slides provide a comprehensive visual explanation of the binomial distribution, encompassing:

- **Diagram:** A clear visual representation of the probability distribution's shape, highlighting the variation of probability across different numbers of successes.
- **Plot:** An X-Y plot that showcases the relationship between the number of successes (k) and the corresponding probability values.
- **Relevant Formula:** The formula used to calculate the probability of obtaining a specific number of successes (k) in n independent trials, given the probability of success (p) in each trial.
- **Example:** A detailed explanation of how to apply the binomial formula to solve a practical problem, like the one presented in this project.

# 2. Python Code Example (NumPy):

The project provides a Python code snippet implemented using the NumPy library. Here is the [link
](https://colab.research.google.com/drive/1V-bMDt-Sm0ZiV7KzDa7SjzlrLhgm1hfS?usp=sharing)
This code demonstrates:

- **Calculation:** The script calculates the probability mass function (PMF) for each possible number of successes (k) using NumPy's built-in mathematical functions and factorial calculations.
- **Visualization:** The code generates an X-Y plot using Matplotlib, effectively visualizing the distribution based on the calculated PMF values. This plot depicts a bar chart with overlaid data points for better visualization.

# 3. Example Question and Solution:

Refer to the link in No. 2 For The Example Question, Solution & Diagram.
The project also presents a real-world scenario where the binomial distribution can be applied:

**Scenario:** A factory produces batteries, with 3% of them being defective. If 100 batteries are produced, what is the probability that exactly 4 batteries are defective?

The provided Python code addresses this question by:

- **Setting Parameters:** Defining the number of trials (n = 100) and the probability of success (p = 0.03).
- **Calculating PMF:** Utilizing a list comprehension to calculate the PMF for all possible values of k (number of successes).
- **Visualization:** Generating a bar chart using Matplotlib to visualize the PMF, providing an intuitive understanding of the probabilities associated with different numbers of defective batteries.

# 4. Video Demo:
- A video presentation (maximum 7 minutes) by the group is also included, Here is the link.

