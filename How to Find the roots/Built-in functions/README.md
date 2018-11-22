# Built-in functions

> ### fminbnd (일변수함수)
> ### fminsearch (다변수함수)

* ### fminbnd
    -A built-in function, fminbnd, finds the minimum of a
    function of one valuable within a fixed interval.
    >>[xmin, fval] = fminbnd(f, x1, x2)
    --> 최솟값이 x1,x2 사이에 있다는 가정.
    
* ### fminsearch
    -A built-in function, fminsearch, finds the minimum of
    a scalar function of several variables, starting at an
    initial estimate. this is generally referred to asunconstrained
    nonlinear optimization.
    >>[xmin, fval] = fminsearch(f,x0)
    --> x0 근방에서 최솟값이 있을거라고 가정한것이다.
