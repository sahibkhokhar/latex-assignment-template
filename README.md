# LaTeX Assignment Template

A simple LaTeX template that I use for my homework assignments in my Computer Science Undergraduate courses.

Modified from [this template](https://github.com/jdavis/latex-homework-template).
Delete this `README.md` if using as a GitHub template.

Will be updated with more commands as needed.

## Files
- [`header.sty`](https://github.com/sahibkhokhar/latex-assignment-template/blob/main/header.sty): Custom LaTeX package defining document settings, headers, and commands.
- [`assignment.tex`](https://github.com/sahibkhokhar/latex-assignment-template/blob/main/assignment.tex): Example LaTeX document using the `header.sty` package.
- [`assignment.pdf`](https://github.com/sahibkhokhar/latex-assignment-template/blob/main/assignment.pdf): Output of the `assignment.tex` file.

## Setup
1. Place `header.sty` in the same directory as your `.tex` file.
2. Include `\usepackage{header}` in your LaTeX document preamble.
3. Customize the homework details (e.g., title, due date, class) in your `.tex` file.

## GitHub Template Setup
1. Top right of this repo, click on `Use this template`
2. Then click on `Create a new repository`.
3. Fill in your repository name and set your options.
4. Customize in your own repo!

## Custom Commands in `header.sty`

### Document Header Commands
These commands define the homework details displayed in the title and header/footer of the document:
- `\hmwkTitle`: Sets the assignment title.
- `\hmwkDueDate`: Sets the due date.
- `\hmwkClass`: Sets the class name.
- `\hmwkClassInstructor`: Sets the instructor's name.
- `\hmwkAuthorName`: Sets the author's name.

### Problem Environment
- `\begin{homeworkProblem}[#]` ... `\end{homeworkProblem}`: Creates a numbered problem section. Optional argument `[#]` sets the problem number manually (e.g., `\begin{homeworkProblem}[3]` starts at Problem 3).

### Mathematical Commands
- `\alg{name}`: Formats algorithm names in small, bold, sans-serif text (e.g., `\alg{Quicksort}`).
- `\deriv{expression}`: Typesets the derivative of an expression (e.g., `\deriv{x^2}` → \(\frac{d}{dx}(x^2)\)).
- `\pderiv{var}{expression}`: Typesets the partial derivative with respect to a variable (e.g., `\pderiv{x}{x^2 + y^2}` → \(\frac{\partial}{\partial x}(x^2 + y^2)\)).
- `\dx`: Inserts a differential \(dx\) symbol (e.g., `\int x^2 \dx` → \(\int x^2 dx\)).
- `\solution`: Creates a bold "Solution" section header.
- `\E`: Typesets the expectation symbol (e.g., `\E[X]` → \(\mathrm{E}[X]\)).
- `\Var`: Typesets the variance symbol (e.g., `\Var[X]` → \(\mathrm{Var}[X]\)).
- `\Cov`: Typesets the covariance symbol (e.g., `\Cov[X,Y]` → \(\mathrm{Cov}[X,Y]\)).
- `\Bias`: Typesets the bias symbol (e.g., `\Bias[\theta]` → \(\mathrm{Bias}[\theta]\)).

### Inline Code
- `\inlinecode{text}`: Formats text as inline code using a typewriter font (e.g., `\inlinecode{print(x)}` → `print(x)`).

## Example Usage

An example [`assignment.tex`](https://github.com/sahibkhokhar/latex-assignment-template/blob/main/assignment.tex) file is provided using all the commands given along with its output file in [`assignment.pdf`](https://github.com/sahibkhokhar/latex-assignment-template/blob/main/assignment.pdf).

## Packages Needed
- `fancyhdr`
- `extramarks`
- `amsmath`
- `amsthm`
- `amsfonts`
- `amssymb`
- `tikz`
- `algorithm`
- `algpseudocode`
- `enumitem`
