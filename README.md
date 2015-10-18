# JuliaSetPkg

This is an example package for CME257 HW4

The package contains a function `juliaSet()` to generate the Julia set given any rational function.

### Example

```
x=collect(linspace(-1,1,200))
y=collect(linspace(-1,1,200))
R = z -> (z^2 + -0.4+0.6*im )
A=juliaSet(R,x,y)
spy(A)
```

