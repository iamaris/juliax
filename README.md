# juliax
julia cheatsheet


### Setup
1) Download [here](https://julialang.org/downloads/)
2) Add link
``` bash
sudo ln -s /Applications/Julia-0.6.app/Contents/Resources/julia/bin/julia /usr/local/bin/julia
```
3) Run julia and install packages
``` bash
julia
Pkg.add("IJulia")
Pkg.add(“JuMP)
Pkg.add("Clp")
Pkg.add("Ipopt")
Pkg.add("PyPlot")
```
