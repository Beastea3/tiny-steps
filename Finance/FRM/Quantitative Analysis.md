# Quantitative Analysis

## Fundamentals of Probability

### 2 + 1 Events

***Independent Events*** are the events that do not affect each other. In other words, the likelihood of an event happen will not affected by given that the other event happened. If two events are independent, must obey the following formula:

$$P(AB) = P(A)P(B)$$

***Conditional Independent Events*** infer that these events are independent from each other in some condition, If two events are independent, they must obey the formula below:

$$P(AB | C) = P(A|C) * P(B|C)$$

***Mutually Exclusive Events***, if two events are mutually exclusive, it means:

$$P(AB) = 0$$

### 3 Probabilities

***Unconditional Probability*** is the probability which does not rely on any other event else;

$$P(A)$$

***Conditional Probability*** is the probability which given another event has happened;

$$P(B|A)$$

The probability above is a conditional probability which infers the probability of event A given that event B has happened;

***Joint Probability*** is measures the likelihood of two events occurring together and at the same point of time.

$$P(AB)$$

The probability above infers the likelihood of event A and B happen at the same time, and we have the formula to calculate this if event A and event B are **independent events**:

$$P(AB) = P(A)P(B)$$

### Two Formulas

***Total Probability Formula***

$$P(A) = P(A|A_1)P(A_1)+P(A|A_2)P(A_2)+...+P(A|A_n)P(A_n)$$

***Bayes rule***

$$P(B|A) = \dfrac{P(A|B)}{P(A)}P(B)$$

In this formula, the information adjustment factor is:

$$\dfrac{P(A|B)}{P(A)}$$

$P(B|A)$ is posterior probability and $P(A)$ is prior probability;

## Random Variables and Basic Statistics

### 2 Classes of Random Variables

**Discrete random variable**, the set of values is finite and the set must be countable.

* Probability Mass Function;
* CDF(Cumulative distribution function): $F_x(x) = P(X\leq x)$

**Continuous random variable** produces values from an un countable set.
* $P(X=x) = 0$ even though x can occur;

### Multivariate random variables

This extends single random variable to include measures of dependence between two or more random variables. This can be either discrete or continuous;

### Marginal distributions

It shows a single side distribution based on only one variable;

* Presented by $f_Y(y)$;

### Conditional distributions

Show the probability when a variable given;

$f_{Y|X}(y|x=2)$ is a conditional distribution;

### Independence

The components of a bivariante random variable are independent if $f_{X,Y}(x,y)=f_X(x)\times f_Y(y)$;

## Moments

### Expectations

### Variance

### Skewness

### Kurtosis

### The BLUE mean estimator