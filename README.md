# Numerical Method Solver

A web-based numerical methods solver for engineering students with step-by-step calculation tables and exportable results.

This project is built with plain HTML, CSS, and JavaScript, so it runs directly in the browser without backend, framework, or installation.

## Features

- Bisection method
- False position method
- Newton-Raphson method
- Composite trapezoidal rule
- Euler method for ordinary differential equations
- Runge-Kutta 4th order method
- Iteration table
- Approximate error tracking
- CSV export
- Responsive dark-blue UI
- GitHub Pages ready

## Supported Expression Syntax

Use JavaScript-style math syntax:

```txt
x^3 - x - 2
sin(x)
cos(x)
exp(-x) - x
sqrt(x)
```

For ODE methods, use expressions involving `x` and `y`:

```txt
x + y
x - y
sin(x) + y
```

## Project Structure

```txt
numerical-method-solver/
│
├── index.html
├── README.md
├── LICENSE
└── .gitignore
```

## How to Run Locally

Clone this repository:

```bash
git clone https://github.com/yourusername/numerical-method-solver.git
cd numerical-method-solver
```

Open the app:

```bash
start index.html
```

For macOS:

```bash
open index.html
```

For Linux:

```bash
xdg-open index.html
```

You can also simply double-click `index.html`.

## Deployment with GitHub Pages

1. Push this project to GitHub.
2. Open your repository.
3. Go to **Settings**.
4. Open **Pages**.
5. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Save.
7. Your solver will be available as a public website.

## Disclaimer

This solver is intended for educational purposes and preliminary numerical computation practice.  
Always verify results manually or with trusted numerical tools for formal academic or professional use.

## Future Improvements

- Add graph visualization
- Add secant method
- Add Gauss-Seidel method
- Add Simpson 1/3 rule
- Add Lagrange interpolation
- Add equation input validation
- Add downloadable PDF report
- Add unit tests for numerical algorithms

## Author

Muhammad Reyvan Andrian  
Petroleum Engineering Student  
Institut Teknologi Bandung

## License

This project is licensed under the MIT License.
