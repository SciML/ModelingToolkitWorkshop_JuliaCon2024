# ModelingToolkitWorkshop_JuliaCon2024

These are the workshop materials for the ModelingToolkit workshop at JuliaCon 2024, entitled:

Hierarchical Component-Based Modeling with ModelingToolkit.jl

- [Slides](https://docs.google.com/presentation/d/1DjyJHAoVr7Naw6RTUhN6s1lDW4DcmxIptMt7k8UnTng)

## Pluto Notebooks

To open the Pluto notebooks, first install Pluto locally via:

```julia
using Pkg
Pkg.install("Pluto")
```

and then run the following command to get Pluto running:

```julia
import Pluto; Pluto.run()
```

Then to open the Pluto notebooks, simply paste the following URLs into Pluto:

- [Symbolic-Numeric Modeling with ModelingToolkit](https://github.com/SciML/ModelingToolkitWorkshop_JuliaCon2024/blob/main/SymbolicNumericMTK.jl)
- [Acausal Modeling with ModelingToolkit via the RC Circuit](https://github.com/SciML/ModelingToolkitWorkshop_JuliaCon2024/blob/main/Acausal_RC_Circuit.jl)
- [Understanding Difficult Differential-Algebraic Equations: DAE Index Reduction and Dummy Derivatives](https://github.com/SciML/ModelingToolkitWorkshop_JuliaCon2024/blob/main/DAE_StructuralSimplify.jl)
- [Initialization of Differential-Algebraic Equations](https://github.com/SciML/ModelingToolkitWorkshop_JuliaCon2024/blob/main/DAE_Initialize.jl)