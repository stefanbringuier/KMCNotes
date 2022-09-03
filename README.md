## Presentation: Kinetic Monte Carlo Review Notes 
The review notes focus on background and use cases of kinetic Monte Carlo methods with a focus on materials simulation.

The presentation can be viewed on [here]() and PDF report-style version can be accessed [here](). This presentation uses  the [quarto](quarto.org) package to build a [revealjs](revealjs.com) presentation. 

## Cite


## Setup to render presentation

The document preparation is carried out in [VSCode](code.visualstudio.com) using the [quarto](quarto.org) extension. The executed code blocks in this
presentation are done in [python](python.org) or [Julia](julialang.org).

1. Install [Quarto](https://quarto.org/docs/get-started/)
2. Install Julia
    1. Add [IJulia](https://julialang.github.io/IJulia.jl/stable/) and [Revise](https://timholy.github.io/Revise.jl/stable/)
        ```julia
        julia> using Pkg
        julia> Pkg.add("IJulia")
        julia> Pkg.add("Revise")
        ```
    2. *(Optional)* Create julia startup files for  [IJulia](https://julialang.github.io/IJulia.jl/stable/) and [Revise](https://timholy.github.io/Revise.jl/stable/)
    3. Clone repo and Instantiate package environment:
        ```julia
        julia> using Pkg
        julia> Pkg.activate()
        julia> Pkg.instantiate()
        ```
3. Add the quarto extension:
    ```shell
    quarto install extension quarto-ext/fontawesome
    ```
3. Render document/project :
    ```shell
    quarto render .
    ```

Peforming these steps will produce a [revealjs](revealjs.com) in the [output](output) folder along with a report style pdf. 

        