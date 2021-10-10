<center><h1>Calculus</h1></center>

<div style="border-bottom: none;"><center><h3>Content</h3></center></div>

[TOC]

<div style="page-break-after: always;"></div>

# Chapter 1 Functions

## 1.1 Common Functions

**Function**

Some types of functions: linear, parabolas, ...

The domain of a function $ f $ is the set of all valid input values. The range consists of the set of all output values that can be reached using those domain values.



**Rational Function**

basic form: $ y = {1 \over x} $

vertical asymptote at $ x = 0 $

horizontal asymptote at $ y = 0 $

<img src="./img/C1/1-1/1.png" style="zoom:80%;" />



**Root Function**

basic form: $ y = \sqrt[n]{x} $

$ n $ even: undefined when the root is negative

$ n $ odd: $ x \in \mathbb{R} $

<img src="./img/C1/1-1/1.png" style="zoom:80%;" />

<img src="./img/C1/1-1/1.png" style="zoom:80%;" />



**Higher-degree of Polynomial Function**

basic form: $ y = x^n $

domain: $ x \in \mathbb{R} $

$ n $ even: both ends of the function tend to $ +\infin $ or both tend to $ -\infin $

$ n $ odd: one end tends to $ +\infin $ while the other tends to $ -\infin $

<img src="./img/C1/1-1/1.png" style="zoom:80%;" />

<img src="./img/C1/1-1/1.png" style="zoom:80%;" />

 <div style="page-break-after: always;"></div>

## 1.2 Angles, Degrees, and Radians

**Angle**

An angle is created by two rays that intersect at a common endpoint. We use Greek letter $ \theta $ to denote angles.

![](./img/C1/1-2/1.png)

An angle that opens counterclockwise from the x-axis is positive.

An angle that opens clockwise from the x-axis is negative.



**Degree / Radian**

Angles can be measured in 2 ways:

1. A degree is a measure of the angle formed by $ 1 \over 360 $ of one complete rotation of a circle.
2. A radian is a measure of the angle formed by the arc of a circle whose length is equal to the circle’s radius.

$$
\theta = {s \over r} = {arclength \over radius}
$$

How are radians and degrees related?

<img src="./img/C1/1-2/2.png" style="zoom:67%;" />
$$
180\degree = \pi \ radians \\
1\degree = {\pi \over 180} \ radians \\
1 \ radian = {180 \over \pi}\degree
$$
This relationship provides us with a way to easily convert between the two measures.

---

【Example】Convert from degrees to radians.

(a) $ 30\degree =  $

(b) $ 220\degree =  $



【Example】Convert from radians to degrees.

(a) $ {\pi \over 4} =  $

(b) $ {5\pi \over 6} = $ 

---

Given any angle $ \theta $, what are these equivalent angles?
$$
\theta + 2k\pi \ (k \in \mathbb{Z})
$$

 <div style="page-break-after: always;"></div>

 ## 1.3 Trigonometric Functions

**Trigonometric Functions**

Let O be the origin and $ P(x, y) $ be a point on the unit circle so that the radius $ OP $ forms an angle of $ \theta $ radians with respect to the positive x-axis.

<img src="./img/C1/1-3/1.png" style="zoom: 67%;" />
$$
x = cos(\theta) \\
y = sin(\theta)
$$
Here are the three most common trigonometric functions and their reciprocals.

| $ sin(\theta) = y $      | <img src="./img/C1/1-3/2.png" style="zoom:80%;" /> |
| ------------------------ | :------------------------------------------------: |
| domain                   |                                                    |
| range                    |                                                    |
| $ sin(\theta) = 0 $ when |                                                    |



| $ cos(\theta) = x $      | <img src="./img/C1/1-3/2.png" style="zoom:80%;" /> |
| ------------------------ | :------------------------------------------------: |
| domain                   |                                                    |
| range                    |                                                    |
| $ cos(\theta) = 0 $ when |                                                    |



| $ tan(\theta) = {y \over x} $ | <img src="./img/C1/1-3/2.png" style="zoom:80%;" /> |
| ----------------------------- | :------------------------------------------------: |
| domain                        |                                                    |
| range                         |                                                    |
| $ tan(\theta) = 0 $ when      |                                                    |



| $ csc(\theta) = {1 \over y} $ | <img src="./img/C1/1-3/2.png" style="zoom:80%;" /> |
| ----------------------------- | :------------------------------------------------: |
| domain                        |                                                    |
| range                         |                                                    |
| $ csc(\theta) = 0 $ when      |                                                    |



| $ sec(\theta) = {1 \over x} $ | <img src="./img/C1/1-3/2.png" style="zoom:80%;" /> |
| ----------------------------- | :------------------------------------------------: |
| domain                        |                                                    |
| range                         |                                                    |
| $ sec(\theta) = 0 $ when      |                                                    |



| $ cot(\theta) = {1x \over y} $ | <img src="./img/C1/1-3/2.png" style="zoom:80%;" /> |
| ------------------------------ | :------------------------------------------------: |
| domain                         |                                                    |
| range                          |                                                    |
| $ cot(\theta) = 0 $ when       |                                                    |



**Special Triangles**

![](./img/C1/1-3/3.png)

【Example】Evaluate each of the following.

(a) $ sin({\pi \over 4}) = $

(b) $ cos({\pi \over 4}) = $

(c) $ csc({\pi \over 4}) = $



【Example】Find all values of $ \theta $ satisfying the following.

(a) $ tan(\theta) = {1 \over \sqrt{3}} $



(b) $ sec(\theta) = \sqrt{2} $



(c) $ cot(\theta) = \sqrt{3} $





**Trigonometric Identities**
$$
sin^2(\theta) + cos^2(\theta) = 1 \\
sin(-\theta) = -sin(\theta) \\
cos(-\theta) = -cos(\theta) \\
tan(\theta) = {sin(\theta) \over cos(\theta)} \\
cot(\theta) = {cos(\theta) \over sin(\theta)} \\
tan^2(\theta) + 1 = sec^2(\theta) \\
cot^2(\theta) + 1 = csc^2(\theta) \\
sin(\theta) = cos(\theta - {\pi \over 2}) \\
sin(a \pm b) = sin(a)cos(b) \pm cos(a)sin(b) \\
cos(a \pm b) = cos(a)cos(b) \mp sin(a)sin(b) \\
sin(2\theta) = 2sin(\theta)cos(\theta) \\
cos(2\theta) = cos^2(\theta) - sin^2(\theta) \\
sin^2(\theta) = {1 - cos(2\theta) \over 2} \\
cos^2(\theta) = {1 + cos(2\theta) \over 2}
$$
Reminder: $ trig^n(x) $ is a notation often used to indicate $ (trig(x))^n $.

 <div style="page-break-after: always;"></div>

## 1.4 Exponential Functions

**Exponential Functions**

Exponential functions are of the form $ y = a^x $, where $ a $ is a positive number and $ x $ is any real number. You might see these sorts of functions when studying population growth, economic growth, global temperature, monetary value, etc.

<img src="./img/C1/1-4/1.png" style="zoom:80%;" />

<img src="./img/C1/1-4/1.png" style="zoom:80%;" />

- Domain:

- Range:

- The graph $ y = a^x $ always passes through $ (0, 1) $ and $ (1, a) $.

- If $ a > 1$ then the graph of $ y = a^x $ is increasing.
- If $ 0 < a < 1 $ then the graph of  $ y = a^x $ is decreasing.
- $ y = 0 $ is always a horizontal asymptote of $ y = a^x $.



**Exponent Rules**
$$
a^{-x} = {1 \over a^x} \\
{1 \over a^{-x}} = a^x \\
(ab)^x = a^xb^x \\
({a \over b})^x = {a^x \over b^x} \\
a^{kx} = (a^k)^x = (a^x)^k \\
a^ma^n = a^{m+n} \\
{a^m \over a^n} = a^{m-n} \\
a^{1/n} = \sqrt[n]{a} \\
a^{m/n} = \sqrt[n]{a^m} = (\sqrt[n]{a})^m
$$


**The Base e**

A very special exponential function is $ y = e^x $, where $ e $ is just a content with a non-terminating decimal like $ \pi $.
$$
e = 2.718281845...
$$
What is so special about an exponential function with base $ e $?

At any point on the graph, the height of the exponential function is equal to the slope of the tangent line to the graph at that point.

<img src="./img/C1/1-4/2.png" style="zoom:50%;" />

 <div style="page-break-after: always;"></div>

## 1.5 Logarithmic Functions

**Logarithmic Functions**

Logarithms are the inverse of exponential functions. Let $ a > 0$, then we define a logarithm (log) as follows:

if
$$
y = log_a(x)
$$
then
$$
a^y = x
$$
If no base $ a $ is shown, a base of 10 is assumed.

For example:
$$
log(x) = log_{10}(x)
$$
---

【Example】Evaluate each of the following.

(a) $ log_{2}8 = $

(b) $ log(100) =  $

(c) $ log_{5}{1 \over 25} = $

(d) $ log_{8}1 = $

---

Since any positive number to the power of 0 is equal to 1, we have the property that $ log_a(1) $, no matter what the base $ a $ is.

<img src="./img/C1/1-5/1.png" style="zoom:80%;" />

<img src="./img/C1/1-5/1.png" style="zoom:80%;" />

- Domain:
- Range:
- $ y = log_a(x) $ always passes through $ (a, 1) $ and $ (1, 0) $.
- If $ a > 1 $ then the graph of $ y = log_a(x) $ is increasing.
- If $ 0 < a < 1 $ then the graph of $ y = log_a(x) $ is decreasing.
- $ x = 0 $ is always a vertical asymptote of $ y = log_a(x) $.



**Logarithm Rules**
$$
log_a(a^x) = x \\
a^{log_a(x)} = x \\
log_a(xy) = log_a(x) + log_a(y) \\
log_a({x \over y}) = log_a(x) - log_a(y) \\
log_a(x^n) = nlog_a(x)
$$


**Change of Base Formula**

We can switch between any two bases easily by using the formula:
$$
log_a(x) = {log_b(x) \over log_b(a)}
$$
---

【Example】Proof
$$
\begin{aligned}

&\because y = log_a(x) \lrarr a^y = x \\

&\begin{aligned} \\
log_b(x) &= log_b(a^y) \\
        &= ylog_b(a) \\
        &= log_a(x) \cdot log_b(a) \\
\end{aligned} \\ \\

&\therefore {log_b(x) \over log_b(a)} = log_a(x)

\end{aligned}
$$



【Example】Convert $ log_4(x) $ into a logarithm with each of the following bases.

(a) base 3





(b) base 22







**The Natural Logarithm**

A special logarithm is the natural logarithm, which is the logarithm with a base of $ e $. Rather than write $ log_e(x) $, we typically write $ ln(x) $.

The natural logarithm has the exact same properties as any other logarithmic function.

In particular,
$$
ln(e^x) = x \\
e^{ln(x)} = x
$$
---

【Example】Solve each of the following for $ x $.

(a) $ 2^x = 2^{1-x} $











(b) $ 3^{{1 \over 2} + 10} = 27 $











(c) $ 2^x = 10 $











(d) $ log(x) - 1 = log(x - 1) $













(e) $ log_2(x) + log_2(x^2) = 6 $













(f) $ log_2(x^4) + log_2(x^2) = 6 $















 <div style="page-break-after: always;"></div>

# Chapter 2 Inequalities

## 2.1 Piecewise Functions

**Piecewise Functions**

Piecewise functions typically feature one or more points at which the function changes from one form to another. To graph a piecewise function, simply graph each piece and then restrict it to its designated domain. Pay special attention when plotting the breaking point (closed circle includes the point, open circle excludes the point).

---

【Example】Graph the piecewise function given by
$$
y = \begin{cases}
1 & x \le 0 \\
4^x & x > 0
\end{cases}
$$
<img src="./img/C2/2-1/1.png" style="zoom:80%;" />



【Example】Graph the piecewise function given by
$$
y = \begin{cases}
{1 \over 2}x + 3 & x < -2 \\
0 & -2 \le x \le 2 \\
x^2 - 1 & x > 2
\end{cases}
$$
<img src="./img/C2/2-1/1.png" style="zoom:80%;" />

 <div style="page-break-after: always;"></div>

## 2.2 Absolute Value Functions

**Absolute Value Functions**

A very special and common piecewise function is the absolute value function.

basic form: $ y = |x| = \begin{cases} x & x \ge 0 \\ -x & x < 0 \end{cases} $

domain:

range:

<img src="./img/C2/2-2/1.png" style="zoom:80%;" />
$$
|ab| = |a| \cdot |b| \\
|{a \over b}| = {|a| \over |b|} \\
if\ |a| \le b,\ then\ -b \le a \le b \\
if\ |a| \ge b,\ then\ a \ge b \ or \ a \le -b \\
(Triangle \ Inequality)\ |a + b| \le |a| + |b|
$$

 <div style="page-break-after: always;"></div>

## 2.3 Inequalities Notation

**Inequalities Notation**

When solving equation we may get a single answer, or a number of answers that satisfy the equation.

Consider $ 3x - 5 = 1 $, only one value satisfies this equation.

But if we consider $ x^2 - 1 = 3 $, more than one value satisfies this equation.

Inequalities notation like $ 1 \le x < 3 $, where the symbols $ \le $ and $ \ge $ indicate inclusion of an endpoint, and $ < $ and $ > $ indicate exclusion of an endpoint.

A second notation is interval notation, for example, $ x \in [1, 3) $, where a square (or closed) bracket indicates inclusion of an endpoint, and a round (or open) bracket indicates exclusion of an endpoint.

The infinity symbol $ \infin $ is always accompanied by round brackets.

---

【Example】Write each of the following in interval notation.

(a) $ 2 \le x \le 7 $





(b) $ x < 9 $





(c) $ -3 > x > 0 $







【Example】Write each of the following using inequalities.

(a) $ x \in [3, 6) $





(b) $  x \in (-2, 4) $





(c) $ x \in (-\infin, -1] $





---

It is possible to have ranges of values that are disjoint. We use the union symbol $ \bigcup $ to include all of the values in any of the disjoint ranges. For example, $ [-1, 4) \bigcup [7, 10) $ meas $ -1 \le x < 4 $ or $ 7 \le x < 10 $.

---

【Example】Express each of the following in interval notation.

(a) $ -3 \le x < {1 \over 2} $ or $ 4 < x < 7 $





(b) $ 1 \le x < 5 $ or $ 3 \le x < 7 $





(c) $ x \in [-2, 6) \bigcup (0, 5) $





---

Intersection symbol $ \bigcap $ allows only the values that are common between intervals. For example, $ [-1, 6) \bigcap (2, 7) $ means $ (2, 6) $.

---

【Example】Express each of the following in interval notation.

(a) $ -2 < x \le 6 $ and $ 0 < x < 7 $





(b) $ x \in [0, 5] \bigcap [3, 5] $





(c) $ -4 < x < 0 $ and $ 3 < x < 7 $







**Solving Inequalities**

When solving inequalities, there are a few rules that we must follow:

1. When it comes to addition, subtraction, multiplication, and division, what you do to one side of the inequality, you must do to the other.
2. If you multiply or divide by a negative quantity, you must flip the inequality.
3. If both sides are positive or both sides are negative, then you can take the reciprocal of both sides, but you must flip the inequality.

---

【Example】Find all values of x that satisfy the following.

(a) $ -6x + 7 \ge 8x $









(b) $ -{5 \over 2} < 4 - 2x \le 1 $









(c) $ 5x^3 + 27 > -13 $









(d) $ 3x^2 + 2 < -4 $









(e) $ \sqrt{x-1} > 4 $









(f) $ log_2(3x) \le -3 $










<div style="page-break-after: always;"></div>

## 2.4 The Case Method

**The Case Method**

Consider the following example: $ {x - 3 \over x - 1} < 10 $

You might be tempted to cross multiply, but be careful! The quantity $ x - 1$ is not always positive. If we multiply by $ x - 1$, the inequality needs to flip for some values of $ x $. How might we deal with this?

1. Separate into 2 cases

    |                          Case 1                          |                          Case 2                          |
    | :------------------------------------------------------: | :------------------------------------------------------: |
    | $$ \begin{aligned} x - 1 &> 0 \\ x &> 1 \end{aligned} $$ | $$ \begin{aligned} x - 1 &< 0 \\ x &< 1 \end{aligned} $$ |

2. Solve the original problem under each assumption

    |                            Case 1                            |                            Case 2                            |
    | :----------------------------------------------------------: | :----------------------------------------------------------: |
    | $$ \begin{aligned} {x-3 \over x-1} &< 10 \\ x - 3 &< 10(x-1) \\ -9x &< -7 \\ x &> {7 \over 9} \end{aligned} $$ | $$ \begin{aligned} {x-3 \over x-1} &< 10 \\ x - 3 &> 10(x-1) \\ -9x &> -7 \\ x &< {7 \over 9} \end{aligned} $$ |

3. Find all common points between assumption and solution

    |                            Case 1                            |                            Case 2                            |
    | :----------------------------------------------------------: | :----------------------------------------------------------: |
    | $$ \begin{aligned} x > 1 \ and \ x > {7 \over 9} \\ x \in (1, \infin) \end{aligned} $$ | $$ \begin{aligned} x < 1 \ and \ x < {7 \over 9} \\ x \in (-\infin, {7 \over 9}) \end{aligned} $$ |

4. Consolidate the 2 cases by taking the union
    $$
    x \in (1, \infin) \bigcup (-\infin, {7 \over 9})
    $$

---

【Example】Find all values of x such that $ {7x - 2 \over 1 - 2x}  \ge 4 $.

1. Separate into 2 cases

    |   Case 1    |   Case 2    |
    | :---------: | :---------: |
    | $$ \\ \\ $$ | $$ \\ \\ $$ |

2. Solve the original problem under each assumption

    |      Case 1       |      Case 2       |
    | :---------------: | :---------------: |
    | $$ \\ \\ \\ \\ $$ | $$ \\ \\ \\ \\ $$ |

3. Find all common points between assumption and solution

    |   Case 1    | Case 2 |
    | :---------: | :----: |
    | $$ \\ \\ $$ |        |

4. Consolidate the 2 cases by taking the union



<div style="page-break-after: always;"></div>

## 2.5 The Number line Method

**The Number Line Method**

Another method for solving inequalities uses the following basic logic:
$$
\begin{aligned}
(+)(+) = + && {(+) \over (+)} = + \\
(-)(-) = + && {(-) \over (-)} = + \\
(+)(-) = - && {(+) \over (-)} = - \\
(-)(+) = - && {(-) \over (+)} = -
\end{aligned}
$$
By manipulating expressions into factors that are multiplied and/or divided on one side of the inequality (with a zero appearing on the other side), we can simply consider the combinations of positive and negative factors to draw conclusions.

---

【Example】Find all values of x that satisfy $ 3x^2 - 13x > -10 $.













【Example】Find all values of x that satisfy $ x - 2 \ge {4 \over x+1} $.













<div style="page-break-after: always;"></div>

# Chapter 3 Limits and Continuity

## 3.1 Basic Limits

**Basic Limits**

Suppose we have a function $ y = f(x) $. The limit of $ f(x) $ as $ x $ approaches the number $ a $, denoted $ \lim\limits_{x \rarr a}f(x) $.

For example, suppose we wanted to determine $ \lim\limits_{x \rarr 3}x^2 $.

| $ x $ approaches 3 from the left | $ x $ approaches 3 from the right |
| :------------------------------: | :-------------------------------: |
|        $ f(2.9) = 8.41 $         |         $ f(3.1) = 9.61 $         |
|       $ f(2.99) = 8.9401 $       |       $ f(3.01) = 9.0601 $        |
|     $ f(2.999) = 8.994001 $      |      $ f(3.001) = 9.006001 $      |

No matter which way we approach from, as $ x $ gets close 3, we can see that $ x^2 $ gets very close to 9.

---

【Example】Find  $ \lim\limits_{x \rarr 0}f(x) $ where
$$
f(x) = \begin{cases}
	cos(x) & x \ne 0 \\
	-1 & x = 0
\end{cases}
$$
<img src="./img/C3/3-1/1.png" style="zoom: 67%;" />

$ \lim\limits_{x \rarr 0}f(x) = $

$ f(0) = $



**Law of Limits**
$$
\lim\limits_{x \rarr a}(f+g)(x) = \lim\limits_{x \rarr a}f(x) + \lim\limits_{x \rarr a}g(x) \\
\lim\limits_{x \rarr a}(f-g)(x) = \lim\limits_{x \rarr a}f(x) - \lim\limits_{x \rarr a}g(x) \\
\lim\limits_{x \rarr a}(fg)(x) = \lim\limits_{x \rarr a}f(x) \cdot \lim\limits_{x \rarr a}g(x) \\
\lim\limits_{x \rarr a}({f \over g})(x) = {\lim\limits_{x \rarr a}f(x) \over \lim\limits_{x \rarr a}g(x)}\\
$$
---

【Example】Evaluate $ \lim\limits_{x \rarr 0}xsin({1 \over x}) $.











**One-sided Limits**

$ x $ can approach the value a in two ways:

- left-hand limit: $ \lim\limits_{x \rarr a^-}f(x) $
- right-hand limit: $ \lim\limits_{x \rarr a^+}f(x) $

We can tighten our definition of the limit of a function $ f(x) $ as $ x $ approaches $ a $. If the left-hand and right-hand limits of $ f(x) $ are both equal to a number $ L $, then we say that $ \lim\limits_{x \rarr a}f(x) $ exists and is equal to $ L $.

---

【Example】Consider the piecewise function given by
$$
f(x) = \begin{cases}
	x & x < 1 \\
	-1 & x = 1 \\
	\sqrt{x-1} & x > 1
\end{cases}
$$
(a) $ \lim\limits_{x \rarr 1^-}f(x) = $

(b) $ \lim\limits_{x \rarr 1^+}f(x) = $

(c) $ f(1) = $

(d) Does $ \lim\limits_{x \rarr 1}f(x) $ exist?

<div style="page-break-after: always;"></div>

## 3.2 Continuity

**Continuity**

It seems like sometimes we can evaluate a limit by just plugging in, but sometimes we can’t!

---

【Example】Evaluate $ \lim\limits_{x \rarr 1}(ln(\sqrt{x}) + {1 \over x}) $.











---

A function is continuous at a point a if each of the following conditions hold:

1. $ \lim\limits_{x \rarr a}f(x) $ exists
2. $ f(a) $ exists
3. $ \lim\limits_{x \rarr a}f(x) = f(a) $



**Discontinuity**

Kinds of discontinuities:

|                     essential                      |                     removable                      |                        jump                        |
| :------------------------------------------------: | :------------------------------------------------: | :------------------------------------------------: |
| <img src="./img/C3/3-2/1.png" style="zoom:67%;" /> | <img src="./img/C3/3-2/1.png" style="zoom:67%;" /> | <img src="./img/C3/3-2/1.png" style="zoom:67%;" /> |

So far, we know that evaluating $ \lim\limits_{x \rarr a}f(x) $ is easy if $ f(x) $ is continuous at $ a $. But what if it isn’t? The limit may still exist.

---

【Example】Evaluate the following limits.

(a) $ \lim\limits_{x \rarr 3^+}{1 \over 3-x} = $

(b) $ \lim\limits_{x \rarr 3^-}{1 \over 3-x} = $

(c) $ \lim\limits_{x \rarr 0^+}ln(x) = $

(d) $ \lim\limits_{x \rarr -{\pi \over 2}^+}sec(x) = $

---

A function doesn’t have to go to $ \pm \infin $ at a discontinuity though. Consider, for instance, evaluating $ \lim\limits_{x \rarr 3}{x^2-x-6 \over x-3} $. Plugging in $ x = 3 $ gives us "$ 0 / 0 $", which is known as an indeterminate form.

A good first step is to factor where possible. Once we cancel the factor $ x - 3 $ on top and bottom, this function is just the function $ f(x) = x + 2 $, but with a hole at $ x = 3 $. The hole is there because we cannot ignore that the original form of the function had issues at $ x = 3 $.

---

【Example】Evaluate the following limits.

(a) $ \lim\limits_{x \rarr 3}{x^2-x-6 \over x-3} $







<img src="./img/C3/3-2/1.png" style="zoom: 67%;" />



(b) $ \lim\limits_{x \rarr -1}{x^3 - 11x^2 + 8x + 20 \over x + 1} $









(c) $ \lim\limits_{x \rarr 4}{\sqrt{x+5} - 3 \over x-4} $











(d) $ \lim\limits_{x \rarr 2}{{1 \over x-4} + {1 \over 2} \over x-2} $













<div style="page-break-after: always;"></div>

## 3.3 The Fundamental Sine Limit

**The Fundamental Sine Limit**

Consider the following limit:
$$
\lim\limits_{x \rarr 0}{sin(x) \over x}
$$
We can quickly see that this is a "$ 0 / 0 $" limit, and therefore is indeterminate. We can’t factor anything or otherwise simplify the expression to get rid of the issue.

<img src="./img/C3/3-3/1.png" style="zoom:80%;" />

It is pretty clear from the graph that
$$
\lim\limits_{x \rarr 0}{sin(x) \over x} = \lim\limits_{x \rarr 0}{x \over sin(x)} = 1
$$
---

【Example】Evaluate the following limits.

(a) $ \lim\limits_{t \rarr 0}{5sin(t) \over 2t} $









(b) $ \lim\limits_{\theta \rarr 0}{\theta \over sin(4\theta)} $











(c) $ \lim\limits_{x \rarr -1}{sin^2(x+1) \over (x+1)^2} $









(d) $ \lim\limits_{x \rarr 0}{sin(3x) \over sin(2x)} $









(e) $ \lim\limits_{\theta \rarr 0}{100\theta \over tan(3\theta)} $













(f) $ \lim\limits_{h \rarr 0}{cos(h)-1 \over h} $









<div style="page-break-after: always;"></div>

## 3.4 Limits Approaching $ \pm \infin $

**Limits Approaching $ \pm \infin $**

Sometimes, we will be interested in determining what happens as $ x $ gets really big, either in the positive or negative direction.

---

【Example】Evaluate the following limits.

(a) $ \lim\limits_{x \rarr \infin}{1 \over x} = $

(b) $ \lim\limits_{x \rarr -\infin}{1 \over x} = $

(c) $ \lim\limits_{x \rarr -\infin}{401 \over x^203} = $

(d) $ \lim\limits_{x \rarr -\infin}{-238 \over 23x^{1/4}} = $

---

For problems like $ \lim\limits_{x \rarr \infin}{2x^2 + 3x + 1 \over x^2 - 10x + 100} $, a good first step is to divide the top and the bottom by the highest power of $ x $ appearing in the denominator.

---

【Example】Evaluate the following limits.

(a) $ \lim\limits_{x \rarr \infin}{2x^2 + 3x + 1 \over x^2 - 10x + 100} $













(b) $ \lim\limits_{x \rarr -\infin}{3 - 2x^3 \over 1 + x + x^2} $













(c) $ \lim\limits_{x \rarr \infin}{\sqrt{x^2 - x + 1}} $





















(d) $ \lim\limits_{t \rarr \infin}{\sqrt{3t^2 + 2t + 5} + t} $





<div style="page-break-after: always;"></div>

# Chapter 4 Derivatives

## 4.1 The First Principles

**The First Principles**

The equation of a line $ y = mx + b $ where $ b $ is the y-intercept and $ m $ is the slope of the line. Calculating the slope is easy using any two points on the line $ (x_1, y_1) $ and $ (x_2, y_2) $.

$$
m
= {\Delta y \over \Delta x}
= {{y_2 - y_1} \over {x_2 - x_1}}
= {f(x_2) - f(x_1) \over x_2 - x_1}
= {f(x + h) - f(x) \over h}
$$
<img src="./img/C4/4-1/1.png" style="zoom: 67%;" />

What if we made the point even closer to $ (x, f(x)) $?

<img src="./img/C4/4-1/2.png" style="zoom: 67%;" />

As $ h $ gets smaller and smaller, the point $ (x+h, f(x+h)) $ approaches the point $ (x, f(x)) $. As this occurs, the slope of the secant line approaches the slope of the tangent line. We can write this action mathematically as:
$$
\lim\limits_{h \rarr 0}{f(x+h) - f(x) \over h}
$$
If this limit exists as a finite number, the this value is equal to the slope of the tangent line. This is the instantaneous rate of $ f(x) $ at the point $ (x, f(x)) $. This very special limit is also called the derivative of $ f(x) $ at $ (x, f(x)) $.

If $ y = f(x) $, then we can denote the derivative in a few different ways:
$$
\begin{aligned}
{dy \over dx} && y' && f'(x)
\end{aligned}
$$
When $ f(x) $ has a derivative at $ (a, f(a)) $, we say that $ f(x) $ is differentiable at the value $ x = a $. This means that
$$
\lim\limits_{h \rarr 0^-}{f(x+h) - f(x) \over h} = \lim\limits_{h \rarr 0^+}{f(x+h) - f(x) \over h}
$$
---

【Example】From The First Principles, find the derivatives.

(a) $ f(x) = x^2 $

















(b) $ f(x) = \sqrt{x+2} $



















【Example】From The First Principles, find the derivative of $ f(x) = {1 \over x} $ at $ x = 5 $.



















<div style="page-break-after: always;"></div>

## 4.2 Differentiability and Continuity

**Differentiability and Continuity**

A non-differentiable function has one of the following properties:

|                       Corner                       |                    Sudden Turn                     |                     Asymptote                      |      Left-hand Limit $ \ne $ Right-hand Limit      |
| :------------------------------------------------: | :------------------------------------------------: | :------------------------------------------------: | :------------------------------------------------: |
| <img src="./img/C4/4-2/1.png" style="zoom:60%;" /> | <img src="./img/C4/4-2/2.png" style="zoom:50%;" /> | <img src="./img/C4/4-2/3.png" style="zoom:53%;" /> | <img src="./img/C4/4-2/4.png" style="zoom:50%;" /> |

In all of these cases, the limit of the slopes does not exist at a point. Functions are not differentiable at such points.

Differentiability implies continuity, but the reverse is not true. Consider the function $ y = |x| $ as a counterexample. This function is continuous for all values of $ x $, but it is not differentiable at $ x = 0 $, because there is a corner there. The limit of the slopes does not exist at $ x = 0$.

---

【Example】Discuss the continuity and differentiability.

<img src="./img/C4/4-2/5.png" style="zoom:67%;" />

(a) $ x = 2 $:

(b) $ x = 1 $:

(c) $ x = -3 $:

<div style="page-break-after: always;"></div>

## 4.3 Derivative Rules

**Derivative Rules**

The First Principles definition of the limit can become a cumbersome task when functions get complicated. Luckily, there are rules for finding derivatives more quickly depending on their form. All of these rules are derived from The First Principles.

1. Power Rule

    Let $ f(x) = x^n $, then $ f'(x) = nx^{n-1} $.

    ---

    【Example】Find the derivative of $ f(x) = x^7 $.

    

    

2. Derivative of a Constant

    Let $ f(x) = k $, then $ f'(x) = 0 $. Graphically, since a constant function is a horizontal line, so its slope must be zero.

    ---

    【Example】Find the derivative of $ f(x) = 672 $.

    

    

3. Derivatives of Logarithmic Functions

    $ {d \over dx}log_a{x} = {1 \over xln(a)} $, where $ a > 0 $ and $ a \ne 1 $

    $ {d \over dx}ln(x) = {d \over dx}log_e(x) = {1 \over xln(e)} = {1 \over x} $

    ---

    【Example】Find the derivative of $ f(x) = log_4(x) $.

    

    

4. Derivatives of Exponential Functions

    $ {d \over dx}a^x = a^xln(a) $, where $ a > 0 $ and $ a \ne 1 $

    $ {d \over dx}e^x = e^xln(e) = e^x $

    ---

    【Example】Find the derivative of $ f(x) = 5^x $.

    

    

5. Derivatives of Trigonometric Functions
    $$
    \begin{aligned}
    {d \over dx}sin(x) &= cos(x) \\
    {d \over dx}csc(x) &= -csc(x)cot(x) \\
    {d \over dx}cos(x) &= -sin(x) \\
    {d \over dx}sec(x) &= sec(x)tan(x) \\
    {d \over dx}tan(x) &= sec^2(x) \\
    {d \over dx}cot(x) &= -csc^2(x)
    \end{aligned}
    $$
    Memory tool: if the trigonometric function starts with `c`, then its derivative has a minus sign.

---

What about combining these basic derivative rules for functions? That is, how do we find the derivatives of the addition, subtraction, multiplication, division, or take the constant of functions? For all of the following rules, we assume that f and g are differentiable on their domains.

1. Multiplication by a Constant

    $ (kf(x))' = kf'(x) $

    ---

    【Example】Find the derivative of $ f(x) = 5ln(x) $.

    

    

2. Sum / Difference

    $ (f \pm g)'(x) = f'(x) \pm g'(x) $

    ---

    【Example】Find the derivative of $ f(x) = ln(x) + 4x^3 - 6csc(x) $.

    

    

    

3. Product Rule

    $ (fg)'(x) = f'(x)g(x) + f(x)g'(x) $

    ---

    【Example】Find the derivative of $ f(x) = ln(x)cos(x) $.

    

    

    

4. Quotient Rule

    $ ({f \over g})'(x) = {f'g - fg' \over g^2} $, where $ g(x) \ne 0 $

    ---

    【Example】Find the derivative of $ f(x) = {5^x \over x^2} $.

    

    

    

    【Example】Use the Quotient Rule to prove that $ {d \over dx}cot(x) = -csc^2(x) $.

    

    

    

    

    

    

5. Chain Rule

    $ (f(g(x)))' = f'(g(x)) \cdot g'(x) $

    ---

    【Example】Find the derivative of the following functions.

    (a) $ f(x) = cos(x^3) $

    

    (b) $ f(x) = (x^2 + 3x + 2)^5 $

    

    (c) $ f(x) = ln(4x^2) $

    

    (d) $ f(x) = e^{sec(x)} $

    

    (e) $ f(x) = sin^3(x^2 + {1 \over x}) $
    

<div style="page-break-after: always;"></div>

## 4.4 Higher Order Derivatives

**Higher Order Derivatives**

What happens if we take the derivative of a derivative (the second derivative)? What if we do this many times?

Second derivative notations:
$$
\begin{aligned}
{d^2y \over dx^2} && y'' && f''(x)
\end{aligned}
$$
Third derivative notations:
$$
\begin{aligned}
{d^3y \over dx^3} && y''' && f'''(x)
\end{aligned}
$$
Higher order derivative notations:
$$
\begin{aligned}
{d^ny \over dx^n} && y^{(n)} && f^{(n)}(x)
\end{aligned}
$$
---

【Example】Let $ f(x) = 2x^4 $, find $ f'(x) $, $ f''(x) $, $ f'''(x) $, $ f^{(4)}(x) $, $ f^{(5)}(x) $.











<div style="page-break-after: always;"></div>

## 4.5 Implicit Derivatives

**Implicit Differentiation**

|               $ x^3 + xy + y^2 = 1 $                |             $ sin(xy) + ln(x + y) = 0 $             |
| :-------------------------------------------------: | :-------------------------------------------------: |
| <img src="./img/C4/4-5/1.png" style="zoom: 67%;" /> | <img src="./img/C4/4-5/2.png" style="zoom: 67%;" /> |

For relations like these, there is no way to isolate for either $ x $ or $ y $. Either variable is implicitly defined in the equation in both of the above cases.

---

【Example】If $ x^3 + xy + y^2 = 1 $, find $ dy \over dx $ at the point $ (x, y) = (1, 0) $.

















【Example】If $ sin(tx^3) + ln(t^2 + x) = 0 $, find $ dx \over dt $.













【Example】Show that if $ e^{2xy} +e^x + e^y = y $ that $ {dx \over dy} = {1 \over {dy \over dx}} $.



























【Example】If $ x^3 + x = y $, find $ d^2y \over dx^2 $.



















【Example】A 10m ladder leans against a perpendicular wall.

(a) The top of the ladder slides down the wall at 0.5m/s. How fast is the foot of the ladder moving at the moment the top of the ladder touches the wall 8m above the ground?





























(b) Consider the angle that the ladder makes with the ground. How fast is this angle changing at that exact moment?











<div style="page-break-after: always;"></div>

## 4.6 Logarithmic Differentiation

**Logarithmic Differentiation**

Logarithmic differentiation allows us to take the derivatives of more complicated expressions. The derivative rules give us a way to quickly differentiate expression like $x^5$, $e^{4x}$, $ 2^x $. But what about $x^x$?

---

【Example】Use a table of values to sketch the function $ f(x) = x^x $.

<img src="./img/C4/4-6/1.png" style="zoom:80%;" />

<img src="./img/C4/4-6/1.png" style="zoom:80%;" />

| $ x < 0 $ | $ f(x) $ | $ x > 0 $ | $ f(x) $ |
| :-------: | :------: | :-------: | :------: |
|           |          |           |          |
|           |          |           |          |
|           |          |           |          |
|           |          |           |          |

$ x^x $ is indeterminate when $ x = 0 $. Because the domain of $ x^x $ is extremely complicated when $ x < 0 $, this function is often only considered for $ x > 0 $.

So, how do we determine the derivative of this function? With logarithmic differentiation, we take the ln() of both side. Then we use log rules to simplify what we get before we finish by differentiating implicitly.

---

【Example】If $ y = x^x $, find $ dy \over dx $.















【Example】If $ y = (cos(\pi x))^{2x} $, find $  dy \over dx $.









---

It would be tedious to differentiate expression like $ y = {(x-2)^2(3x+1)^3\sqrt{x^2+2} \over (x-1)(x+10)^{10}} $ using product and quotient rules, and put pus at a high risk for making mistakes. We can use logarithms to simplify problems. It is technically an important step that we take the absolute value of both sides first that we aren’t considering the $ ln() $ of a negative number.

---

【Example】If $ y = {(x-2)^2(3x+1)^3\sqrt{x^2+2} \over (x-1)(x+10)^{10}} $, find $ dy \over dx $.









<div style="page-break-after: always;"></div>

## 4.7 Differential Approximation

**Differential Approximation**

Differential approximation allows us to calculate estimates if numbers that would be impossible to find by hand. For example, we know what $ sin(\pi) $ is, but what about $ sin(3) $?

The idea is simple. Given a function $ f(x) $ and a difficult-to-evaluate value of $ x = a $, we want to follow this process to estimate $  f(a) $:

1. Find a nearby value $ a^* $ at which $ f $ is easy to calculate.
2. Find the tangent line there, called $ L(x) $, with slope $ f'(a^*) $.
3. Estimate $ f(a) $ by using the height $ L(a) $ instead.

<img src="./img/C4/4-7/1.png" style="zoom:67%;" />

【Example】Estimate $ sin(3) $ using differential approximation.

1. Let $ f(x) = sin(x) $, and the nearby value $ a^* = \pi $.

    Then $ f'(x) = cos(x) $, so $ f'(a^*) = cos(\pi) = -1 $.

2. Now, find the equation of the tangent line to $ f $ at the nearby value $ \pi $.

    $$
    \begin{aligned}
    L(x) &= mx + b \\
    	&= (-1)x + b \\
    0 &= -\pi + b \\
    b &= \pi \\
    \therefore L(x) &= -x + \pi
    \end{aligned}
    $$

3. Calculate the estimate of $ f(a) = f(3) $ using $ L(a) = L(3) $ instead.
    $$
    L(3) = -3 + \pi \approx 0.14159265
    $$

4. True value of $ sin(3) = 0.14112 $.



---

【Example】Estimate $ \sqrt{65} $ using differential approximation.



























<div style="page-break-after: always;"></div>

# Chapter 5 Antiderivatives

## 5.1 The Indefinite Integral

**The Indefinite Integral**

How do we undo a derivative? If we were given the derivative of a function $ f'(x) $, how could we find the original function $ f(x) $? The answer is called the antiderivative of $ f(x) $, which we will denote by the associated capital letter $ F(x) $.

Another way to think about this question is: "What function do I have to take the derivative of in order to get the answer?" The antiderivative of $ f(x) = 2x $ is $ x^2 $.

But what about $ F(x) = x^2 + 1 $? This works too! In fact, since when we take the derivative of a constant, we get zero. We could have chosen any constant. As a result, we report our antiderivative in its most general form $ x^2 + C $. The constant $ C $ is an important part of the antiderivative.

Notationally, we denote the operation of take the antiderivative (known as integration) as:
$$
\int 2x \ dx = x^2 + C
$$
This is also called the indefinite integral of the function $ f(x) $, or sometimes just the integral of $ f(x) $, where $ f(x) $ is called the integrand.

That was a pretty simple example, so how do we find antiderivatives of more complicated expressions? In much the same way as we did with derivatives, we can generate a set of rules for finding antiderivatives, derived simply by thinking of our familiar derivative rules in reverse.



**Basic Antiderivative Rules**

The power rule for derivatives multiplies by the power and then subtracts one from the power. Reversing these operations means that we add one to the power and divide by the new power.

1. Reverse Power Rule
    $$
    \int x^n \ dx = {x^{n+1} \over n+1} + C,\ where\ n \ne -1
    $$
    ---

    【Example】Find the anitiderivatives.
    
    (a)
    $$
    \int x^6 \ dx
    $$
    
    
    
    
    
    (b)
    $$
    \int \sqrt[4]{t} \ dt
    $$
    
    
    
    

    
    
    
    
    (c)
    $$
    \int {1 \over x^{5/3}} \ dx
    $$
    
    
    
    
    
    
    
2. Antiderivative of Zero
    $$
    \int 0 \ dx = C
    $$
    
    
3. Antiderivative of a Constant
    $$
    \int k \ dx = kx + C,\ where\ k\ is\ any\ constant
    $$
    ---
    
    【Example】Find the anitiderivatives.
    $$
    & \int \pi \ dx \\
    $$
    
    
    
    
    
4. Multiplicative Constants
    $$
    \int kf(x) \ dx = k \int f(x) \ dx
    $$
    ---

    【Example】Find the anitiderivatives.

    (a)
    $$
    \int 4x^7 \ dx
    $$

    

    

    

    (b)
    $$
    \int {\pi \over \sqrt{t}} \ dt
    $$

    

    

    

5. Sum / Difference
    $$
    \int (f(x) \pm g(x)) \ dx = \int f(x) \ dx \pm \int g(x) \ dx
    $$
    ---

    【Example】Find the anitiderivatives.

    (a)
    $$
    \int (3x^2 + 5) \ dx
    $$

    

    

    


    (b)
    $$
    \int ({1 \over x^3} - {2 \over x^2}) \ dx
    $$

    

    

    

6. Trigonometric Functions
    $$
    \begin{aligned}
    \int sin(x) \ dx &= -cos(x) + C \\
    \int cos(x) \ dx &= sin(x) + C \\
    \int csc^2(x) \ dx &= -cot(x) + C \\
    \int sec^2(x) \ dx &= tan(x) + C \\
    \int sec(x)tan(x) \ dx &= sec(x) + C \\
    \int csc(x)cot(x) \ dx &= -csc(x) + C
    \end{aligned}
    $$
    

7. Exponential / Logarithmic
    $$
    \begin{aligned}
    \int a^xln(a) \ dx &= a^x + C \\
    \int e^xln(e) \ dx &= e^x + C \\
    \int {1 \over xln(a)} \ dx &= log_a|x| + C \\
    \int {1 \over x} \ dx &= ln|x| + C
    \end{aligned}
    $$
    ---

    【Example】Find the anitiderivatives.

    (a)
    $$
    \int 4^xln(4) + 5e^x - {6 \over x} \ dx
    $$

    

    


    (b)
    $$
    \int 3^z \ dz
    $$

    

---

Sometimes we need to manipulate the integral a little bit before we can apply the rules.

---

【Example】Find the anitiderivatives.

(a)
$$
\int {2s^3 - 5s^4 \over 3s^2} \ ds
$$










(b)
$$
\int ({1 \over x} + {1 \over x^2})(3 + 2x^2) \ dx
$$








<div style="page-break-after: always;"></div>

## 5.2 Chain Rule in Reverse

**Chain Rule in Reverse**

The derivative of $ f(u(x)) $ is $ f'(u(x))u'(x) $, so
$$
\int f'(u(x))u'(x) \ dx = f(u(x)) + C
$$
Notice that in the integration, the $ u'(x) $ piece disappears, being absorbed back into $ f(x) $. The steps for finding the antiderivative of composition functions are as follows:

1. Identify the core layer $ u(x) $.
2. Identify the derivative of the core layer $ u'(x) $.
3. Identify the outer layer $ f' $, and integrate $ f' $ leaving $ u(x) $inside.

---

【Example】Find the anitiderivatives.

(a)
$$
\int (6x^2 + 1)sin(2x^3 + x) \ dx
$$














(b)
$$
\int sec^2(4t) \ dt
$$
















(c)
$$
\int 4x^3(3x^4 - 1)^{14} \ dx
$$


















(d)
$$
\int {e^{1 \over x} \over 4x^2} \ dx
$$


















【Example】Integrate in one step.
$$
\int e^{-2t} + sin(3t) + cos({1 \over 4}t) \ dt
$$




<div style="page-break-after: always;"></div>

## 5.3 The Method of Substitution

**The Method of Substitution**

The idea behind the method of substitution is to change a difficult integral in terms of one variable into an easier integral in terms of some other variable using a substitution.
$$
\int f'(u(x)) \ {du \over dx} = \int f'(u) \ du
$$
---

【Example】The method of substitution.
$$
\int (6x + 4)(3x^2 + 4x)^5 \ dx
$$
Step 1: identify the core layer $ u(x) = 3x^2 +4x $.

Step 2: find the derivative of the core $ {du \over dx} = 6x + 4 $.

Step 3: transform from an integral in $ x $ to an integral in the new variable $ u $ using the change of variable theorem.
$$
\begin{aligned}
& \int (6x + 4)(3x^2 + 4x)^5 \ dx \\
&= \int {du \over dx}u^5 \ dx \\
&= \int u^5 \ du \\
&= {u^6 \over 6} + C
\end{aligned}
$$
Step 4: convert back to the original variable by substituting $ u(x) $ back in.
$$
\begin{aligned}
& {u^6 \over 6} + C \\
&= {(3x^2 + 4x)^6 \over 6} + C
\end{aligned}
$$

---

【Example】Calculate using the method of substitution.

(a)
$$
\int sin(x)e^{5cos(x)} \ dx
$$






















(b)
$$
\int {x \over (5x + 7)^3} \ dx
$$


























(c)
$$
\int xsec(3x^2)tan(3x^2) \ dx
$$
















(d)
$$
\int {-{1 \over t^2} + 1 \over \sqrt{{1 \over t} + t}} \ dt
$$


















(e)
$$
\int (1 + 900x)^{1/15000} \ dx
$$
















(f)
$$
\int sin(\theta)(cos^3\theta - cos^5\theta) \ d\theta
$$








(g)
$$
\int {7x \over 4x^2 + 9} \ dx
$$






















(h)
$$
\int (2x + 5) \cdot \sqrt[3]{3x + 1} \ dx
$$
















<div style="page-break-after: always;"></div>

## 5.4 Definite Integrals

**Riemann Sum**

Suppose we wanted to find the area underneath the graph of a straight line that lies above the x-axis, between $ x = a $ and $  x = b $. Since we have formulas for finding the area of basic shapes, we can easily figure this out.

![](./img/C5/5-4/1.png)

But what about finding the area underneath the graph of a general curve $ y = f(x) $ and above the x-axis between $  x = a $ and $ x = b $?

Bernhard Riemann’s idea was to carve up the desired area into rectangle and user their area to estimate the true area. He called this the Riemann Sum and it goes as follows:

1. Create a partition $ P $, dividing up the interval $ [a, b] $ into n subintervals $ I_1, I_2, \dots, I_n $.
2. Choose an x-value (called it $ x_k $) in each subinterval $ I_k $.
3. For each $ x_k $ we choose, draw a rectangle with height $ f(x_k) $ and a width spanning $ I_k $ ($ \Delta x_k $).

<img src="./img/C5/5-4/2.png" style="zoom: 67%;" />

The area of rectangle k is:
$$
f(x_k) \cdot \Delta x_k
$$
The total area of all the rectangles is:
$$
f(x_1) \cdot \Delta x_1 + f(x_2) \cdot \Delta x_2 + \dots + f(x_n) \cdot \Delta x_n = \sum_{k=1}^{n} f(x_k) \cdot \Delta x_k
$$
---

【Example】Use the Riemann Sum to estimate the area below $ y = sin({1 \over 2}x) $ and above the x-axis, between $ x = 0 $ and $ x = 2\pi $. Use a partition of 4 subintervals.

<img src="./img/C5/5-4/3.png" style="zoom: 50%;" />











---

So, what happens as make the rectangles skinnier?

<img src="./img/C5/5-4/4.png" style="zoom:67%;" />

As the width of the rectangles decreases, the accuracy of the estimate increases. So, what happens if we let the width of all the rectangles in the partition approach 0?

Notationally:
$$
\lim\limits_{n \rarr \infin, \ ||p|| \rarr 0} \sum_{k=1}^{n} f(x_k) \cdot \Delta x_k \\
$$
We should get the exact area, that is, our estimate is no longer just an estimate.

Notationally, instead of limit, we write it as:
$$
\int_{x = a}^{b} f(x) \ dx
$$


**Definite Integral**

For all of the following, suppose that $ k $, $ a $, $ b $, and $ c $ are constants with $ a < b < c $, and that $ f $ and $ g $ are integrable functions on the domain of integration.

| Formula                                                      |                        Graph                        |
| :----------------------------------------------------------- | :-------------------------------------------------: |
| $$ \begin{aligned} & \int_a^b k \ dx \\ &= (b - a)k \end{aligned} $$ | <img src="./img/C5/5-4/5.png" style="zoom:50%;" />  |
| $$ \begin{aligned} & \int_a^a f(x) \ dx \\ &= 0 \end{aligned} $$ | <img src="./img/C5/5-4/6.png" style="zoom:50%;" />  |
| $$ \begin{aligned} & \int_b^a f(x) \ dx \\ &= -\int_a^b f(x) \ dx \end{aligned} $$ | <img src="./img/C5/5-4/7.png" style="zoom:50%;" />  |
| $$ \begin{aligned} & \int_a^c f(x) \ dx \\ &= \int_a^b f(x) \ dx + \int_b^c f(x) \ dx \end{aligned} $$ | <img src="./img/C5/5-4/8.png" style="zoom:50%;" />  |
| $$ \begin{aligned} & \int_a^b kf(x) \ dx \\ &= k \int_a^b f(x) \ dx \end{aligned} $$ | <img src="./img/C5/5-4/9.png" style="zoom:50%;" />  |
| $$ \begin{aligned} & \int_a^b (f(x) \pm g(x))  \ dx \\ &= \int_a^b f(x) \ dx \pm \int_a^b g(x) \ dx \end{aligned} $$ | <img src="./img/C5/5-4/10.png" style="zoom:50%;" /> |

【Example】Evaluate.

(a)
$$
\int_1^2 {1 \over t} \ dt
$$










(b)
$$
\int_{-2}^1 x^3 \ dx
$$












(c)
$$
\int_1^5 s(s^2 + 1) \ ds
$$














(d)
$$
\int_{\sqrt{ln(2)}}^{\sqrt{ln(4)}} xe^{x^2} \ dx
$$
























(e)
$$
\int_x^{x^2} sin(t) \ dt
$$










(f)
$$
\int_5^{13} (x + 1)\sqrt{2x - 1} \ dx
$$






































<div style="page-break-after: always;"></div>

## 5.5 Area Under a Curve

**Area Under a Curve**

【Example】Find the area below the curve $ f(x) = sin(x) $ and above the x-axis between $ x = {\pi \over 2} $ and $ x = \pi $.

<img src="./img/C5/5-5/1.png" style="zoom:80%;" />











---

What if we have a more interesting situation where many curves are involved? For instance, how do we find the area between two curves $ f $ and $ g $?

![](./img/C5/5-5/2.png)

【Example】Calculate the area bounded by $ y = 2x + 1 $ and $ y = x^2 - 2x - 3 $.

<img src="./img/C5/5-5/3.png" style="zoom: 67%;" />





























【Example】Calculate the area bounded by $ y = -x $ and $ y = -x^2 + 2 $ between $ x = 0 $ and $ x = 2 $.

<img src="./img/C5/5-5/4.png" style="zoom: 50%;" />



















【Example】Find the area bounded by $ y^2 = x + 4 $ and $ y = {1 \over 2}x + {1 \over 2} $.

<img src="./img/C5/5-5/5.png" style="zoom: 67%;" />
