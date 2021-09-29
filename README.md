# fantastique-julia

A list of resources about the Julia language

## References

### Websites

- [Julia documentation](https://docs.julialang.org/)
- [Modern Numerical Computing](http://courses.csail.mit.edu/18.337/2018/) (MIT 18.337/6.338)
- [Multidimensional algorithms and iteration](https://julialang.org/blog/2016/02/iteration/)
- [Type-dispatch-design ≠ object-oriented programming language](http://www.stochasticlifestyle.com/type-dispatch-design-post-object-oriented-programming-julia/)

### Videos

- [Intro to Julia tutorial (version 1.0) by Jane Herriman](https://youtu.be/8h8rQyEpiZA)
- [Developing Julia Packages](https://youtu.be/QVmU29rCjaA)
- [Automatic Differentiation with Julia](https://youtu.be/vAp6nUMrKYg)
- [The Unreasonable Effectiveness of Multiple Dispatch](https://www.youtube.com/watch?v=kc9HwsxE1OY)

### Books

#### Julia High Performance

[Link to publisher](https://juliahighperformance.com/)

> The Julia programming language has brought an innovative new approach to
> scientific computing, promising a combination of performance and productivity
> that is not usually available in the current set of languages that is commonly
> used. In solving the two- language problem, it has seen tremendous growth both
> in academia and industry. It has been used in domains from robotics,
> astronomy, and physics, to insurance and trading. It has particular relevance
> in the area of machine learning, with increasing use for the emerging field of
> differentiable computing.

> Most new developers are attracted to the language due to its promise of high
> performance. This book shows you how and why that is possible. We talk about
> the design choices of the language's creators that allow such a
> high-performance compiler to be built. We also show you the steps that you, as
> an application developer, can take to ensure the highest possible performance
> for your code. We also tell you the ways in which your code can work with the
> compiler and runtime to fully utilize your hardware to the greatest extent
> possible.

> This book is for the beginner and intermediate Julia developer who wants to
> fully leverage Julia's promise of performance with productivity. We assume you
> are proficient with one or more programming languages and have some
> familiarity with Julia's syntax. We do not expect you to be expert Julia
> programmers yet but assume that you have written small Julia programs, or that
> you have taken an introductory course on the language.

#### Hands-On Design Patterns and Best Practices with Julia

[Link to publisher](https://www.packtpub.com/product/hands-on-design-patterns-and-best-practices-with-julia/9781838648817)

> Design patterns are fundamental techniques for developing reusable and
> maintainable code. They provide a set of proven solutions that allow
> developers to solve problems in software development quickly. This book will
> demonstrate how to leverage design patterns with real-world applications.

> Starting with an overview of design patterns and best practices in application
> design, you'll learn about some of the most fundamental Julia features such as
> modules, data types, functions/interfaces, and metaprogramming. You'll then
> get to grips with the modern Julia design patterns for building large-scale
> applications with a focus on performance, reusability, robustness, and
> maintainability. The book also covers anti-patterns and how to avoid common
> mistakes and pitfalls in development. You'll see how traditional
> object-oriented patterns can be implemented differently and more effectively
> in Julia. Finally, you'll explore various use cases and examples, such as how
> expert Julia developers use design patterns in their open source packages.

> By the end of this Julia programming book, you'll have learned methods to
> improve software design, extensibility, and reusability, and be able to use
> design patterns efficiently to overcome common challenges in software
> development.

### Jupyter notebooks

- [JuliaBoxTutorials by Jane Herriman](https://github.com/xorJane/JuliaBoxTutorials)

## Libraries

#### General purpose

- [StaticArrays](https://github.com/JuliaArrays/StaticArrays.jl):
  Statically sized arrays for Julia
- [CxxWrap](https://youtu.be/u7IaXwKSUU0): Creation of Julia packages relying on
  C++ libraries (equivalent to `Boost.Python` or `pybind11` for Python)

#### Documentation

- [Documenter](https://github.com/JuliaDocs/Documenter.jl.git): A documentation generator for Julia.
- [DocStrings](https://github.com/miguelraz/DoctorDocstrings.jl.git): Diagnose the missing docstrings in your package. Copy paste from your REPL the smart inputs straight into your docstrings.

#### Plotting

- [Plots](http://docs.juliaplots.org/latest/) – powerful convenience for
  visualization in Julia.
- [Makie](http://makie.juliaplots.org/stable/) is a high-performance,
  extendable, and multi-platform plotting ecosystem for the Julia programming
  language.
- [PGFPlotsX](https://kristofferc.github.io/PGFPlotsX.jl/stable/) is a Julia
  package for creating publication quality figures using the LaTeX library
  PGFPlots as the backend. See also [this
  video](https://www.youtube.com/watch?v=XHJ-u7PgBs8).

#### Finite elements

- [JuAFEM.jl](https://kristofferc.github.io/JuAFEM.jl/latest/) is a finite
  element toolbox that provides functionalities to implement finite element
  analysis in Julia.
- [Gridap.jl](https://gridap.github.io/Gridap.jl/stable/) provides a set of
  tools for the grid-based approximation of partial differential equations
  (PDEs) written in the Julia programming language. The main motivation behind
  the development of this library is to provide an easy-to-use framework for the
  development of complex PDE solvers in a dynamically typed style without
  sacrificing the performance of statically typed languages. The library
  currently supports linear and nonlinear PDE systems for scalar and vector
  fields, single and multi-field problems, conforming and nonconforming finite
  element discretizations, on structured and unstructured meshes of simplices
  and hexahedra.

#### Others

- [BifurcationKit.jl](https://github.com/rveltz/BifurcationKit.jl) aims at
  performing **automatic bifurcation analysis** of large dimensional equations
  F(u, λ)=0 where λ∈ℝ by taking advantage of iterative methods, sparse
  formulation and specific hardwares (e.g. GPU).
  
 - [JuMP.jl](https://jump.dev/) offers a modelling language for mathematical optimization.
   It interacts with various convex optimization solvers for solving linear programming (LP),
   second-order cone programming (SOCP), semi-definite programming (SDP), etc.

### Sources of inspiration

#### Python

#### Maple

- [tens3d and tenssurf](http://jean.garrigues.perso.centrale-marseille.fr/tens3d.html):
  Maple and Mathematica packages for tensor calculation (including
  variant-covariant, Christoffel coefficients, differential operators…)

#### LaTeX

- [juliaplots](https://github.com/sisl/juliaplots.sty):
  This package makes it easy to integrate Julia code and plots into LaTeX documents

<!-- Local Variables: -->
<!-- fill-column: 80 -->
<!-- End: -->
