# Mathcracked

BSc-level mathematics, every step justified.

A web app that solves BSc-level math problems and shows each step with the reason behind it. Works on mobile and desktop.

**Live demo:** https://mathcracked.netlify.app

## Features
- Step-by-step solutions: Given, Goal, numbered steps with reasons, final answer
- Example bank with search/filter
- Copy solution and print-friendly view
- Demo button for a quick walkthrough

## Modules and example inputs
| Module | Example inputs that work |
|---|---|
| Calculus | Differentiate y = (3x + 1)^2, product/quotient prompts, Integrate x e^x dx, partial fractions, lim x->0 (1 - cos x)/x^2, implicit differentiation |
| Linear algebra | det [[1,2],[3,4]], inverse, Gaussian elimination, eigenvalue, matrix multiply prompts |
| Differential equations | dy/dx = y, integrating factor, y'' - 3y' + 2y = 0 style |
| Series | Geometric series wording |
| Probability | Bayes-style wording |
| Algebra extras | Expand (x - 2)^2, linear and quadratic equations, mean |
| Proofs | Induction, sqrt(2) is irrational, even product, (a+b)^2, odds |

## How it works and its limits
Matches exact example prompts, plus keyword routing to the matching worked solution. It is not a general-purpose solver: inputs outside the supported patterns above may not be handled.

## Run locally
No build step. Open `index.html` in a browser, or:

    python3 -m http.server 8000

## Deploy
Static site. On Netlify: build command empty, publish directory `.`

## Demo login
None. No login required.

## AI tool disclosure
Built with assistance from Claude (Anthropic) and Grok (xAI) for code generation and debugging. Design direction, testing, and final decisions by the author.

## License
MIT, see LICENSE.
