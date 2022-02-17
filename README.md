# DataDrivenLinearModels.jl

**ATTENTION : Development of this package has just started! If you feel like contributing, please get in touch for further discussion. This also the first proper Julia package I am developing. Any tips and pieces of advice are welcome :)**

DataDrivenLinearModels.jl is a package for identifying low-rank linear models from data. Several models regularly used in Engineering Sciences are implemented, e.g.

- [Proper Orthogonal Decomposition](https://en.wikipedia.org/wiki/Proper_orthogonal_decomposition), (POD)
- Linear Stochastic Estimation (LSE),
- [Dynamic Mode Decomposition](https://en.wikipedia.org/wiki/Dynamic_mode_decomposition) (DMD).

As they rely on similar mathematics, classical algorithms for input-output linear system identification are also provided such as the [EigenRealization Algorithm](https://en.wikipedia.org/wiki/Eigensystem_realization_algorithm) (ERA). This package is being developed as a companion for the paper *Unifying framework for data-driven linear modeling* currently being written by [Steve Brunton](https://github.com/eigensteve) and myself.
