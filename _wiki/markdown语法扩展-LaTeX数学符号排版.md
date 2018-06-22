---
title: markdown 语法扩展-LaTeX数学符号排版
layout: wiki
mathjax: true
---
1. ==指数==和==下标==(左上、左下、右上、右下、正上、正下)
```latex
$$a_1\qquad x^2\qquad e^{-\alpha t}\qquad e^{x^2}\neq{e^x}^2$$
$$\sideset{^1_2}{^3_4}\bigotimes$$
$$\mathop{abc}\limits_1$$
```
$$a_1\qquad x^2\qquad e^{-\alpha t}\qquad e^{x^2}\neq{e^x}^2$$
$$\sideset{^1_2}{^3_4}\bigotimes$$
$$\mathop{abc}\limits_1$$
2. ==平方根==和==n 次方根==（自动调整形式、仅符号形式）
```latex
$$\sqrt{x}\qquad\sqrt{x^2+\sqrt y} \qquad\sqrt[3]2\qquad\surd[x^2+y^2]$$
```
$$\sqrt{x}\qquad\sqrt{x^2+\sqrt y} \qquad\sqrt[3]2\qquad\surd[x^2+y^2]$$
3. ==水平线==（上方、下方）
```latex
$$\overline{m+n}\qquad \underline{m+n}$$
```
$$\overline{m+n}\qquad \underline{m+n}$$
4. ==括号==（大小调整、隐藏形式）
```latex
$$f(x,y,z) = 3y^2z \left( 3+\frac{7x+5}{1+y^2} \right)$$
$$\left.{\rm d}u \over {\rm d}x \right|_{x=0}$$
```
$$f(x,y,z) = 3y^2z\left ( 3+\frac{7x+5}{1+y^2} \right)$$
$$ \left.{\rm d}u \over {\rm d}x \right|_{x=0}$$
5. ==水平大括号==
```latex
$$\underbrace{a+b+\dots+z}_{26} \qquad \overbrace{0+1+\dots+9}^{10}$$
```
$$\underbrace{a+b+\dots+z}_{26}\qquad \overbrace{0+1+\dots+9}^{10}$$
6. ==公式大括号==
```latex
$$f(x)=\left\{\begin{aligned}x &=& \cos(t) \\y &=& \sin(t) \\z &=& \frac xy\end{aligned}\right.$$
$$F^{HLLC}=\left\{\begin{array}{rcl}F_L&&{0<S_L}\\F^*_L&&{S_L \leq 0 < S_M}\\F^*_R&&{S_M\leq0<S_R}\\F_R&&S_R\leq0 \end{array}\right.$$
$$f(x)=\begin{cases}0&{x=0}\\1&{x\neq0}\end{cases}$$
```
$$f(x)=\left\{\begin{aligned}x &=& \cos(t) \\y &=& \sin(t) \\z &=& \frac xy\end{aligned}\right.$$
$$F^{HLLC}=\left\{\begin{array}{rcl}F_L&&{0<S_L}\\F^*_L&&{S_L \leq 0 < S_M}\\F^*_R&&{S_M\leq0<S_R}\\F_R&&S_R\leq0 \end{array}\right.$$
$$f(x)=\begin{cases}0&{x=0}\\1&{x\neq0}\end{cases}$$

7. ==向量==
```latex
$$\vec a\quad \overrightarrow {AB}$$
```
$$\vec a\qquad \overrightarrow {AB}$$
8. ==分数==
```latex
$$1\frac{1}{2}hours\qquad \frac{x^2}{k+1} \qquad x^{\frac{2}{k+1}} \qquad x^{1/2}$$
$$1 \over 2$$
```
$$1\frac12hours\qquad \frac{x^2}{k+1} \qquad x^{\frac{2}{k+1}} \qquad x^{1/2}$$
$$1 \over 2$$
9. ==省略号==（与底线对齐、与中线对齐）
```latex
$$f(x_1,x_x,\ldots,x_n) = x_1^2 + x_2^2 + \cdots + x_n^2 $$
```
$$f(x_1,x_x,\ldots,x_n) = x_1^2 + x_2^2 + \cdots + x_n^2 $$ 
10. ==积分运算符==和==求和运算符==和==乘积运算符==
```latex
$$\sum_{x=1}^{n}\qquad \sum\limits_{i=1}^n \qquad \int_0^{\frac\pi2} \qquad \prod\limits_\epsilon$$
```
$$\sum_{x=1}^{n}\qquad \sum\limits_{i=1}^n \qquad \int_0^{\frac\pi2} \qquad \prod\limits_\epsilon$$
11. ==极限==
```latex
$$\lim\limits_{n\rightarrow+\infty}\frac 1{n(n+1)}$$
```
$$\lim\limits_{n\rightarrow+\infty}\frac 1{n(n+1)}$$
12. ==多行数学公式==
```latex
$$\begin{eqnarray}\cos 2\theta & = & \cos^2 \theta - \sin^2 \theta \\& = & 2 \cos^2 \theta- 1.\end{eqnarray}$$
```
$$\begin{eqnarray}\cos2\theta&=&\cos^2\theta-\sin^2\theta\\& = & 2 \cos^2\theta-1.\end{eqnarray}$$
13. ==矩阵==
```latex
$$\left( \begin{array}{}a&b&c\\d&e&f\\g&h&i \end{array} \right)$$
$$\chi(\lambda)=\left|\begin{array}{ccc}\lambda-a&-b&-c\\-d&\lambda-e&-f\\-g&-h&\lambda-i \end{array}\right|$$
```
$$\left( \begin{array}{}a&b&c\\d&e&f\\g&h&i \end{array} \right)$$
$$ \chi(\lambda) = \left| \begin{array}{ccc} \lambda - a & -b & -c \\ -d & \lambda - e & -f \\ -g & -h & \lambda - i \end{array} \right|$$

详见[一份不太简短的$\LaTeX2_{\varepsilon}$介绍](/blog/lshort-cn.pdf)