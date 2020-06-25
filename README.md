# Learning How to Learn: Powerful mental tools to help you master tough subjects

This Gitbook contains my notes on the course [Learning How to Learn: Powerful mental tools to help you master tough subjects](https://www.coursera.org/learn/learning-how-to-learn).

A tutorial I wrote on how to host this gitbook on github pages is written [here](https://medium.com/@richdayandnight/simple-tutorial-on-hosting-your-gitbook-documentation-on-github-pages-bonus-with-gitbook-editor-f27f60d5d408?postPublishedType=initial).

## How to locally serve this repository

1. Open your terminal and run
    - `git clone https://github.com/richdayandnight/tutorial-gitbook-learning-how-to-learn.git`
2. Install dependencies (this is assuming that you already have npm and yarn installed)
    - `npm install -g gitbook-cli`
    - `yarn add gulp gulp-gh-pages gulp-load-plugins --save-dev`
    - `gitbook install`
3. On the root folder of this repository (`cd tutorial-gitbook-learning-how-to-learn`) run
    - `gitbook serve`
4. To deploy changes to github, run
    - `gulp publish`

## What a gitbook can contain

### Some code

```python
# This program adds two numbers

num1 = 1.5
num2 = 6.3

# Add two numbers
sum = num1 + num2

# Display the sum
print('The sum of {0} and {1} is {2}'.format(num1, num2, sum))
```

## Some formula

$$
\int_{-\infty}^\infty g(x) dx
$$

Block math with (tag):

$$
\tag{a.1} x+y^{2x}
$$

Block math with tag:
$$
\tag{a.2} x+y^{2x}
$$
