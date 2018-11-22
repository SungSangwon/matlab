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

함수명 | 의미 | 자세한설명 링크
---|:---:|---:
`Plot(X,Y)` | plot(X,Y)는 X의 대응값에 대한 Y 데이터의 2차원 선 플롯을 생성합니다. | https://kr.mathworks.com/help/matlab/ref/plot.html
`legned` | 좌표축에 범례 추가 | https://kr.mathworks.com/help/matlab/ref/legend.html?searchHighlight=legend&s_tid=doc_srchtitle
`hold` | 새 플롯 추가 시 현재 플롯 유지 | https://kr.mathworks.com/help/matlab/ref/hold.html?searchHighlight=hold%20on&s_tid=doc_srchtitle
`xlable` | x축에 레이블 지정 | https://kr.mathworks.com/help/matlab/ref/xlabel.html


X와 Y가 모두 벡터이면 이 둘은 길이가 같아야 합니다. plot 함수는 X에 대한 Y의 플롯을 그립니다.
X와 Y가 모두 행렬이면 이 둘은 크기가 같아야 합니다. plot 함수는 X의 열에 대한 Y의 열을 플로팅합니다.

X와 Y 중 하나가 벡터이고 다른 하나가 행렬인 경우, 이 행렬의 차원 중 하나는 벡터 길이와 같아야 합니다. 행렬 행 개수가 벡터 길이와 같은 경우 plot 함수는 벡터에 대한 각 행렬 열을 플로팅합니다. 행렬 열 개수가 벡터 길이와 같은 경우 이 함수는 벡터에 대한 각 행렬 행을 플로팅합니다. 행렬이 정사각 행렬인 경우 이 함수는 벡터에 대한 각 열을 플로팅합니다.

X와 Y 중 하나가 스칼라이고 다른 하나가 스칼라 또는 벡터인 경우 plot 함수는 이산 점을 플로팅합니다. 그러나 점을 표시하려면 마커 기호를 지정해야 합니다(예: plot(X,Y,'o')).
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

![odesimp](https://user-images.githubusercontent.com/44973398/48885131-7dd73500-ee6a-11e8-9ec4-9b3700192d61.PNG)
