## 사용자가 직접 특정구간에서 근을찾는 함수를 정의한 것.

### 사용한 함수들

### * LIST
> * Inceremental Search
> * Bisection
> * Golden-Section

### * Incremental Search
    -The incremental search method tests the value of the function
    at evenly spaced intervals and finds brackets by identifying function
    sign changes between neighboring points.


![incremental](https://user-images.githubusercontent.com/44973398/48905932-353d6d00-eea6-11e8-8231-63917b283b77.PNG)
![incremental](https://user-images.githubusercontent.com/44973398/48905933-353d6d00-eea6-11e8-96e9-fd1bd090f500.PNG)

    -Incremental 결과 Figure 과 command창 

### * Bisection
    -The bisection method is a variation of
    the incremental search method in which the interval is
    always divided in half.
 변수명 | 의미 |
 ---|:---:
`func` |  name of function
`xl, xu` | lower and upper guesses
`es` | desired relative error (default = 0.0001%)
`maxit` | maximum allowable iterations (default = 50) 
`pl,p2,...` | additional parameters used by func
`root` | real root
`fx` | function value at root
`ea` | approximate relative error (%)
`iter` | number of iterations
    
    
    example)
    root(2)를 찾는 command창
    >> f=@(x) x.^2-2;
    >> bisect(f,1,2,0.5*10^-10) 
