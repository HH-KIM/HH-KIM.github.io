#데이터분석 입문_머신러닝

## 지도학습

- 입력데이터(x)와 타겟값(y)을 알고있는 데이터를 학습하여, 이들의 관계를 모델링하는 학습방법

- 새로운 데이터에 대한 타겟값을 예측하는데에 사용

ex) 개와 고양이를 분류하는 것을 가르쳐봅시다.

- 개, 고양이를 분류하는 모델 생성과정과 예측과정

새로운 x를 모델( f(x) 에 넣으면 타겟값 y 로 나온다. 타겟값은 hat y ^y 로 불린다.

지도학습은 Y의 형태에 따라 두 가지로 나눈다.
1. 분류
2. 회귀

### 분류 ( classification)
- 타겟변수가 이산형 변수인 경우 ( 특정한 값만 가진다 )

### 회귀 (Regression)
- 타겟변수 Y가 연속형 변수인 경우 ( 연속범위 내에서 임의의 값들로 표현)
ex) 주가 예측, 소매점의 수요예측

## 비지도 학습
