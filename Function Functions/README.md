# Function Functions 와 Anonymus functions를 이용하여 문제풀이 및 Euler's method 구현!

### Function Functions란?

-Function Functions are functions that operate on other functions which are passed to it as input arguements.
The input argument may be the handle of an anonymous function, the name of a built-in function. or the name of a M-file function.


### Anonymous functions란?

-Anonymous functions are simple one-line functions created within the command window without the need for an M-file
 

### Euler method란?

-The Euler method is a first-order method, which means that the local error (error per step) is proportional to the square of the step size, and the global error (error at a given time) is proportional to the step size. The Euler method often serves as the basis to construct more complex methods.

출처 : wikipedia

* * *
+ ## Function Functions 에 쓰인 기본적인 matlab 함수들

함수명 | 의미 |자세한설명 링크 |
---|:---:|---:
`Plot(X,Y)` | plot(X,Y)는 X의 대응값에 대한 Y 데이터의 2차원 선 플롯을 생성합니다. | https://kr.mathworks.com/help/matlab/ref/plot.html
`legned` | 좌표축에 범례 추가 | https://kr.mathworks.com/help/matlab/ref/legend.html?searchHighlight=legend&s_tid=doc_srchtitle
`hold` | 새 플롯 추가 시 현재 플롯 유지 | https://kr.mathworks.com/help/matlab/ref/hold.html?searchHighlight=hold%20on&s_tid=doc_srchtitle
`xlable` | x축에 레이블 지정 | https://kr.mathworks.com/help/matlab/ref/xlabel.html
`varargin` | 가변 길이 입력 인수 목록 | https://kr.mathworks.com/help/matlab/ref/varargin.html

* * *
+ ### 결과화면

+ 모든 Problem들은 교재 'applied numerical methods with matlab for engineers and scientists 3rd edition' 의 Problem 문제입니다.


+ Prob.2_5  결과


![prob2_5](https://user-images.githubusercontent.com/44973398/48885079-53857780-ee6a-11e8-8946-1fcc8f4994c0.png)

+ Prob.2_13 결과


![prob2_13](https://user-images.githubusercontent.com/44973398/48885089-5a13ef00-ee6a-11e8-818f-aba84528d11c.png)

+ Prob.2_19 결과


![prob2_19](https://user-images.githubusercontent.com/44973398/48885095-5f713980-ee6a-11e8-9418-889541648263.png)

+ odesimp(Eulermethod)를 FunctionFucntions로 구현한 결과

<img src="https://user-images.githubusercontent.com/44973398/48885680-83ce1580-ee6c-11e8-8a23-bff6b6d5f6ec.jpg" width="60%">

![prob_3_12](https://user-images.githubusercontent.com/44973398/48887802-f989af80-ee73-11e8-896d-66787a3f0a7b.PNG)

