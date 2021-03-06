![Microbiome.jl logo](logo.png)

## For analysis of microbiome and microbial community data

**Latest Release:**

[![Latest Release](https://img.shields.io/github/release/BioJulia/Microbiome.jl.svg)](https://github.com/BioJulia/Microbiome.jl/releases/latest)
[![Docs stable](https://img.shields.io/badge/docs-stable-blue.svg)](https://biojulia.net/Microbiome.jl/stable/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/BioJulia/Microbiome.jl/blob/master/LICENSE)
![BioJulia maintainer: kescobo](https://img.shields.io/badge/BioJulia%20Maintainer-kescobo-blue.svg)

**Development Status**

[![Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
[![CI](https://github.com/BioJulia/Microbiome.jl/workflows/CI/badge.svg)](https://github.com/BioJulia/Microbiome.jl/actions?query=workflow%3ACI)
[![codecov](https://codecov.io/gh/BioJulia/Microbiome.jl/branch/main/graph/badge.svg)](https://codecov.io/gh/BioJulia/Microbiome.jl)

[![Docs dev](https://img.shields.io/badge/docs-latest-blue.svg)](https://biojulia.net/Microbiome.jl/latest/)

## Description

Microbiome.jl is a package for manipulating and analyzing
microbiome and microbial community data.
Many functions have been added to external packages
and are imported here.

## Installation

Install Microbiome from the Julia REPL:

Install Microbiome from the Julia REPL:

```julia
julia> using Pkg

julia> pkg"registry add https://github.com/BioJulia/BioJuliaRegistry.git" # note: this only needs to be done once

julia> pkg"add Microbiome"
```

If you are interested in the cutting edge of the development, please check out
the master branch to try new features before release.

```julia
julia> pkg"add Microbiome#master"
```

## Companion Packages

You might also be interested in some functionality provided by
[BiobakeryUtils.jl](https://github.com/BioJulia/BiobakeryUtils).

Microbiome.jl uses [EcoBase](https://github.com/EcoJulia/EcoBase.jl) under the hood
for many of its types and methods.
