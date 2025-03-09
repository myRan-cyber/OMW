# OMW
  记录大二下各次最优化方法作业、心得以及知识总结
## LaTex main.tex 基本模板

## LaTex基础语法

## LaTex数学环境

1. 常用宏包

```
\usepackage{amsmath}   % 基础数学环境
\usepackage{amssymb}   % 数学符号
\usepackage{bm}        % 粗体数学符号（如 \bm{A}）
\usepackage{mathtools} % 增强数学功能（如 cases* 环境）
```
2. 数学环境

行内公式用 \( ... \) 或 $ ... $。

行间公式用 \[ ... \] 或 equation 环境。

3. 对齐
多行公式用 align 环境：

```
\begin{align}
f(x) &= x^2 + 3x + 2 \\
     &= (x+1)(x+2)
\end{align}
```


## LaTex与线性代数相关语法摘要

1. 向量与矩阵
向量(粗体或箭头):

```
\mathbf{v} = \begin{pmatrix} v_1 \\ v_2 \\ v_3 \end{pmatrix}, %粗体
\quad \vec{u} = \begin{bmatrix} u_1 \\ u_2 \end{bmatrix}      %箭头
```

矩阵(各种括号):

```
A = \begin{pmatrix}  %小括号
1 & 2 \\
3 & 4
\end{pmatrix}, \quad
B = \begin{bmatrix}  %中括号
a & b \\
c & d
\end{bmatrix}, \quad
C = \begin{vmatrix}  %绝对值
x & y \\
z & w
\end{vmatrix}
```

2. 行列式与迹

```
\det(A) = \begin{vmatrix} a & b \\ c & d \end{vmatrix},  %行列式
\quad \tr(B) = \sum_{i=1}^n b_{ii}                       %迹
```

3. 方程组

```
\begin{cases}
x + 2y = 5 \\
3x - y = 1
\end{cases}
```

4. 转置

```
A^\top
```

5. 逆矩阵

``` 
A^{-1}
```

6. 内积

```
\mathbf{u} \cdot \mathbf{v}
```

## LaTex与微积分相关语法摘要

## first homework

主要涉及线性代数和微积分的基础知识
