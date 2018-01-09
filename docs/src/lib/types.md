# Types

This section describes systems types implemented in `Systems.jl`. 

```@contents
Pages = ["types.md"]
Depth = 3
```

```@meta
CurrentModule = Systems
DocTestSetup = quote
    using Systems
end
```

## Abstract Systems

```@docs
AbstractSystem
AbstractContinuousSystem
AbstractDiscreteSystem
```

## Continuous Systems

```@docs
LinearContinuousSystem
LinearControlContinuousSystem
ConstrainedLinearContinuousSystem
ConstrainedLinearControlContinuousSystem
LinearAlgebraicContinuousSystem
ConstrainedLinearAlgebraicContinuousSystem
```

## Discrete Systems

```@docs
LinearDiscreteSystem
LinearControlDiscreteSystem
ConstrainedLinearDiscreteSystem
ConstrainedLinearControlDiscreteSystem
LinearAlgebraicDiscreteSystem
ConstrainedLinearAlgebraicDiscreteSystem
```

## Initial Value Problems

```@docs
InitialValueProblem
IVP
```