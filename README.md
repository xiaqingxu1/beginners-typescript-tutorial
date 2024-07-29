# Example Markdown File with LaTeX

## Introduction

This document includes some examples of LaTeX used in Markdown.

## Inline LaTeX

You can include inline LaTeX by wrapping your LaTeX code with single dollar signs `$`. For example, the quadratic formula is written as $ax^2 + bx + c = 0$.

## Display LaTeX

For larger equations that you want to display on their own line, you can wrap your LaTeX code with double dollar signs `$$`. Here’s an example:

$$
\frac{d}{dx} \left( \int_{a}^{x} f(t) \, dt \right) = f(x)
$$

## More Examples

### Pythagorean Theorem

The Pythagorean theorem is a fundamental relation in Euclidean geometry among the three sides of a right triangle. It can be expressed as:

$$
a^2 + b^2 = c^2
$$

### Euler's Identity

Euler's identity is a famous equation in mathematics that shows a deep relationship between the most fundamental numbers in mathematics:

$$
e^{i\pi} + 1 = 0
$$

### Matrix

You can also include matrices in your LaTeX. For example, here’s a 2x2 matrix:

$$
\begin{pmatrix}
a & b \\
c & d
\end{pmatrix}
$$

## Conclusion

LaTeX is a powerful tool for including mathematical notation in your Markdown documents. It allows you to clearly and concisely present complex mathematical ideas.
<a href="https://totaltypescript.com"><img src="./og-image.png" /></a>

## Quickstart 07/18/2024

Clone this repo or [open in Gitpod](https://gitpod.io/#https://github.com/total-typescript/beginners-typescript).

```sh
# Installs all dependencies
npm install

# Starts the first exercise
npm run exercise 01

# Runs linting and tests on the solution
npm run solution 01
```

## Video Walkthrough

I walked through the first few exercises on [VSCode's live stream](https://www.youtube.com/watch?v=p6dO9u0M7MQ)! The plan for these exercises is to develop them into a full workshop, and then bundle them into the full video course - [Total TypeScript](https://totaltypescript.com).

## How to take the course

You'll notice that the course is split into exercises. Each exercise is split into a `*.problem.ts` and a `*.solution.ts`.

To take an exercise:

1. Go into `*.problem.ts`
2. Run `npm run exercise 01`, where `01` is the number of the exercise you're on.

The `exercise` script will run TypeScript typechecks and a test suite on the exercise.

This course encourages **active, exploratory learning**. In the video, I'll explain a problem, and **you'll be asked to try to find a solution**. To attempt a solution, you'll need to:

1. Check out [TypeScript's docs](https://www.typescriptlang.org/docs/handbook/intro.html)
2. Try to find something that looks relevant.
3. Give it a go to see if it solves the problem.

You'll know if you've succeeded because the tests will pass.

**If you succeed**, or **if you get stuck**, unpause the video and check out the `*.solution.ts`. You can see if your solution is better or worse than mine!

You can run `npm run solution 01` to run the tests and typechecking on the solution.

## Acknowledgements

Say thanks to Matt on [Twitter](https://twitter.com/mattpocockuk) or by joining his [Discord](https://discord.gg/8S5ujhfTB3). Consider signing up to his [Total TypeScript course](https://totaltypescript.com).

## Reference

### `npm run exercise 01`

Alias: `npm run e 01`

Run the corresponding `*.problem.ts` file.

### `npm run solution 01`

Alias: `npm run s 01`

Run the corresponding `*.solution.ts` file. If there are multiple, it runs only the first one.
