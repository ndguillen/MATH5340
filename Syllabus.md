# Syllabus
# Scientific Computation. MATH 5340 (Fall 2023)

## Instructor: Nestor Guillen (nestor@txtstate.edu)

## Course overview

Welcome to Scientific Computation!. In this course you will be given a modern introduction to the field of scientific computing. In short, scientific computing is the area of mathematics concerned with the analysis and creation of algorithms for the problems of continuum mathematics -- such as the solution of a differential equation, the determination of an equilibrium probability distribution for a stochastic process, the design of surfaces which optimize their shape according to some geometrical or mechanical criterium, and more. By its very nature this is a field that combines tools and ideas from advanced mathematics (real analysis, multivariable calculus, calculus of variations, differential equations) with computer programming (in our course's specific case, the Python programming language). This means that in this course you will be dealing with pure mathematical questions as well as with practical coding assignments. Both will involve creative problem solving and applying the theories and methods learned in lectures and in the material. 

From a more official perspective, *The Texas State Course Catalog* entry for MATH 5340 is as follows

> MATH 5340
> : This course will involve the analysis of algorithms from science and mathematics, and the implementation of these algorithms using a computer algebra system. Symbolic numerical and graphical techniques will be studied. Applications will be drawn from science, engineering, and mathematics. A knowledge of differential equations is expected.

**Lectures time and location**. Class meets Tuesdays and Thursdays from 3:30 to 4:50 pm in Derrick 331.

**Office Hours**. Tuesdays 2:00-3:00 pm, or by appointment (request via email at least one day in advance). 

**Forums**. Apart from lectures and office hours, an important point of interaction for the class will be **the Canvas Discussions page**. If you have a question related to a particular problem set, or a question about a method discussed in a lecture, this should be the first place to share that question. Sometimes I will provide answers to forum questions, or use a question to explain a broader point or a method. Experience with public forums like [Stack Exchange](https://en.wikipedia.org/wiki/Stack_Exchange) and [MathOverflow](https://en.wikipedia.org/wiki/MathOverflow) suggests this can be a great learning tool in their own right.

**Emails**. I will get back to any email within 72 hours. Preferably, questions about the content of the class should be posted on the course forum, with email used for individual concerns or questions -- but this is not a strict rule. **Please make sure to start the subject line of your emails with 'MATH5340', so that I can reply promptly.**

**Prerequisites**. An practical and theoretical understanding of multivariable calculus, differential equations, and linear algebra is a must for the course. Basic programming skills, as well as familiarity with Python and mathematical topics like real analysis or topology are helpful additions but not strictly necessary for the course.

**Course materials**. 
You will need access to a computer that can run Python as well as Jupyter Notebooks -- more information on this will be given in class. 

We will not be following one book -- a lot of the course material will be provided in the form of Jupyter Notebooks and slides in PDF format. That being said, the course will refer to or follow with some frequency each of the following textbooks:

J. Solomon's [Numerical Algorithms](https://people.csail.mit.edu/jsolomon/#book) by Solomon.

The 2023 edition of the [SciPy Lectures](https://lectures.scientific-python.org/_downloads/ScientificPythonLectures-simple.pdf). 

L.C. Evans' [Partial Differential Equations](https://bookstore.ams.org/gsm-19-r/)

T. Hastie, R. Tibshirani, and J. Friedman's [Elements of Statistical Learning](https://hastie.su.domains/publications.html)

A. Ern and J. Guermond's [Theory and Practice of Finite Elements](https://books.google.com/books/about/Theory_and_Practice_of_Finite_Elements.html?id=CCjm79FbJbcC)



## Course evaluation

**Overview** For this course's evaluation I will attempt to follow [Patrick Winston's grading philosophy](https://web.mit.edu/fnl/volume/204/winston.html), and the course evaluation will consist of the following

* 4 quizzes (each quiz takes place in class and lasts 1 hour)

* 1 Final (consisting of 5 parts)

* 5 Problem Sets

Each quiz, problem set, and each part of the final will receive a numerical grade in the form of an integer between $0$ and $5$. These numbers are combined to form a *score* according to the following rule

$$s = \frac{\text{3*(Problem Set Average)} + \max\{\text{Quiz 1},\text{Final Part 1}\}+\ldots+\max\{\text{Quiz 4},\text{Final Part 4}\}+\text{(Final Part 5)}}{8}$$

The final exam will have five topics, the first four corresponding to the quizes done throughout the semester -- you only need to excel in either the quiz or the corresponding part of the final to get the full grade (this is the function of the $\max$ in the formula for $s$). The last and fifth part of the final will be a topic not covered in the quiz so it stands on its own. Note the factor of $3$ in front of the Problem Set Average -- this means the Problem Set Average amounts for 3/8 of the final score. 

**Quizzes**: The four quizzes will be on each of the first four topics of the class, and they will take place on the following weeks at the time of Lecture:

1. Function spaces (end of week 4)
2. ODE (end of week 7)
3. Graphs, Laplacians, and Markov Chains (end of week 11)
4. Gradient descent and stochastic optimization (end of week 13)

**Problem Sets**: The problem sets will have flexible deadlines (to be announced throughout the semester). If a student does not submit a problem set they will get an automatic grade of $0$ for that problem set.

**Submission guidelines**: Your submitted problem sets must be submitted in PDF format plus a .ipynb file. Files should be named as: YourLastName\_ProbSetN.pdf and YourLastName\_ProblemSetN.ipynb, here N is the corresponding number for the problem set.

**Important dates**: As mentioned earlier, problem sets will be due on Fridays at 11:59 pm. 

  * First two problem sets due by Friday, September 29th at 11:59 pm

  * Quizzes: Thursday lecture on weeks 4, 7, 11, and 13.

  * Final: Week of December 4th.

**Final Course Grade**:  Your final course grade is computed fromm the score $s$ according to the following table

$$\begin{array}{|c|c|}\hline \text{Letter grade} & \text{Score range} \\ \hline \text{A} & 4.4 \leq s\leq 5 \\ \text{B} & 3.4\leq s <4.4 \\  \text{C} & 2.4\leq s <3.4 \\ \text{D or F} & s<2.4 \\ \hline \end{array}$$



## Parts of the course)

* Introduction / motivation
* Part 1: Function spaces (their representation, discretization, and approximation)
* Part 2: Ordinary differential equations
* Part 3: Graphs, Laplacians, and Markov Chains
* Part 4: Gradient descent and stochastic gradient descent
* Part 5: Basics of finite elements

