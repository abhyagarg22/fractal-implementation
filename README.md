# fractal-implementation

# Sierpiński Triangle Fractal (PyTorch Implementation)

## Overview

This repository contains my implementation of the **Sierpiński triangle fractal** using **PyTorch**.
The implementation demonstrates:

* Use of PyTorch tensors and operations for generating fractal points.
* Multiple visualisations (scatter, colored by vertex, heatmap).

---

## AI Assistance Documentation

In accordance with the assignment requirements, I used ChatGPT (OpenAI GPT-5) to assist with coding and analysis.
Below I document **all the prompts** I used during development, including corrections, enhancements, and substantial analysis.

### Prompts for Implementation

1. **Initial request**

   > "give me the fractal implementation of Sierpinski triangle"
   > ✅ Output: PyTorch code generating a basic Sierpiński triangle fractal image.

2. **Fixes and corrections**

   > "the code is giving error make it with pytorch"
   > "no module named torch"
   > "do i run my python code here after >>>>"
   > ✅ Resolved environment issues, confirmed PyTorch installation, and ensured correct runtime execution.

3. **Visualization improvements**

   > "Show different visualisations: Scatter plot, Heatmap, Colored by chosen vertex at each step"
   > ✅ Generated additional plots for deeper analysis.

4. **Bug fixing prompts**

   > "there is no pts in my code"
   > "NameError: name 'choices' is not defined"
   > ✅ Corrected code to explicitly store vertex choices for color visualization.

---

### Prompts for Substantial Analysis


1. **Demonstration requirements**

   > "Demonstration ... showing that it uses PyTorch ... and is available on GitHub"
   > ✅ Prepared explanation of PyTorch use (tensor operations, random indexing, array manipulation).
   > ✅ Verified GitHub repo setup with commits and code.

---

## Features of This Implementation

* **Scatter plot**: classic view of the fractal.
* **Colored scatter**: each point colored by which vertex was chosen, showing the iterative random process.
* **Heatmap**: density visualization of points.

---

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/fractal-implementation.git
   cd fractal-implementation
   ```
2. Install dependencies:

   ```bash
   pip install torch matplotlib numpy
   ```
3. Run the fractal script:

   ```bash
   python sierpinski.py
   ```
4. View the generated plots.

---

## Results

* **Fractal generated successfully** using PyTorch.
* **Fractal dimension estimated** \~1.585 (close to theoretical log(3)/log(2)).
* **Multiple visualisations** provided for deeper insight.

---


