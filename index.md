## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/sagisk/Matrix-Computations/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

### Support or Contact

If you want to make a contribution, have a suggestion or noticed some error contact me via [mail](mailto:tone.menu@mail.ru).

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

# 1.0 Introduction

#### Exercise 1.0.P1
$x^TAx = \sum_{i}x_{i}\sum_{j}A_{ij}x_{j} = \sum_{i}\sum_{j}A_{ij}x_i^2$ is a quadratic function of $x$ hence, it is continuous. Assuming that the set $S = \{x \in R^n : x^Tx = 1\}$ is compact (closed and bounded) we can apply the Weierstrass’s theorem to get that the function $x^TAx$ attains its maximum at some point in $S$. Then following the text derivations we have that $Ax = \lambda x$ where $\lambda$ is an eigenvalue of $A$. Hence, any real symmetric matrix have at least one real eigenvalue.

ToDo: Show that $S$ is a compact set.

#### Exercise 1.0.P2
The problem is: maximize $x^TAx$ subject to $x^Tx = 1$. Let's take the eigenvalue decomposition of $A$. Let $v_1,...v_n$ be the orthonormal eigenvectors of $A$. Note that the set of eigenvectors creates a basis for $R^n$ hence $x = \sum_{i = 1}^{n} a_iv_i$ and $x^TAx = \sum_{i=1}^{n}\lambda_i a_i^2$ (by noting that $Av_i = \lambda_iv_i$. Now the problem becomes: maximize $\sum_{i=1}^{n}\lambda_i a_i^2$ subject to $\sum_{i = 1}^{n} a_i^2 = 1$. Since the weights $a_i^2$ add up to one the greatest value will be achieved if we set up $a_i = 1$ for $i$ corresponding to the greatest eigenvalue $\lambda_i$ and $a_{j \not= i} = 0$. Hence, the solution of the problem is is the largest real eigenvalue of $A$.


- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Matrix Computations
