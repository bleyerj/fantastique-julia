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

- [Julia High Performance](https://juliahighperformance.com/)

### Jupyter notebooks

- [JuliaBoxTutorials by Jane Herriman](https://github.com/xorJane/JuliaBoxTutorials)

## Libraries

### Julia

- [StaticArrays](https://github.com/JuliaArrays/StaticArrays.jl):
  Statically sized arrays for Julia
- [CxxWrap](https://youtu.be/u7IaXwKSUU0):
  Creation of Julia packages relying on C++ libraries (equivalent to `Boost.Python` or `pybind11` for Python)

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

### Python

### Maple

- [tens3d and tenssurf](http://jean.garrigues.perso.centrale-marseille.fr/tens3d.html):
Maple and Mathematica packages for tensor calculation (including variant-covariant, Christoffel coefficients, differential operators…)

### LaTeX

- [juliaplots](https://github.com/sisl/juliaplots.sty):
  This package makes it easy to integrate Julia code and plots into LaTeX documents

<!-- Local Variables: -->
<!-- fill-column: 80 -->
<!-- End: -->
