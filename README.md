# FDFDViz.jl

![](img/coupler_fields.png)

FDFDViz.jl is the companion package to [FDFD.jl](https://github.com/ianwilliamson/FDFD.jl) that provides functions for visualizing fields and other results. Originally these functions were part of FDFD.jl but I decided to detach them to remove FDFD.jl's dependency on PyPlot. This tends to be problematic on HPC environments.

FDFD.jl is a 2D finite difference frequency domain (FDFD) code written completely in Julia for solving Maxwell's equations. It also supports performing the linear solve steps with the Pardiso and MUMPS packages. For more information please see the [FDFD.jl Github page](https://github.com/ianwilliamson/FDFD.jl).
