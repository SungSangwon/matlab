# Built-in functions

> ### fminbnd (일변수함수)
> ### fminsearch (다변수함수)

* ### fminbnd

        -A built-in function, fminbnd, finds the minimum of a
        function of one valuable within a fixed interval.
        >>[xmin, fval] = fminbnd(f, x1, x2)
        --> 최솟값이 x1,x2 사이에 있다는 가정.

* ### fminbnd 결과창

![default](https://user-images.githubusercontent.com/44973398/48908476-adf3f780-eead-11e8-9777-e41410dc2e83.PNG)

        fminbnd 가 golden-section search 와 parabolic interpolation을 포함하고 있다는 것을 확인할 수 있다.
* ### fminsearch
    
        -A built-in function, fminsearch, finds the minimum of
        a scalar function of several variables, starting at an
        initial estimate. this is generally referred to asunconstrained
        nonlinear optimization.
        >>[xmin, fval] = fminsearch(f,x0)
        --> x0 근방에서 최솟값이 있을거라고 가정한것이다.
