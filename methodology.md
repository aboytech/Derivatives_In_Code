# Mini-Task: Derivatives in Code

## What you're building
A single, clean Jupyter Notebook with two sections. No new repo needed — add it to your existing Financial Return Analyzer repo as a new notebook called `derivatives_in_code.ipynb`.

## Section 1 — Visualizing a Function and Its Derivative
**What to deliver:** A side-by-side plot of f(x) = x³ - 2x and its derivative f'(x) = 3x² - 2.

**Steps to work through:**

1. Think about what range of x values makes this function interesting to look at — where does it change behavior?
2. Generate that x range using numpy
3. Compute both f(x) and f'(x) — by hand first, then in code
4. Plot them side by side in the same figure with two subplots
5. On the derivative plot, identify and mark where f'(x) = 0 — what does that point mean geometrically on the original function?

## Section 2 — Rate of Change of Log Returns
**What to deliver:** A plot of your AAPL log returns alongside the output of numpy.gradient() applied to them.

**Steps to work through:**

1. Pull your AAPL log returns from Project 1 — reuse that code
2. Apply `numpy.gradient()` to the returns series
3. Before plotting, ask yourself: what does numpy.gradient actually compute here? What question is it answering about the returns?
4. Plot both series — returns and their gradient — in two vertically stacked subplots, sharing the x-axis (dates)
5. Write 3–4 sentences in Markdown interpreting what the gradient plot is telling you that the returns plot alone wasn't