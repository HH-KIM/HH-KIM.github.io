# 기초 통계

## 도수 분포표

- 도수 분포표
  * 수집된 자료를 쉽게 이해할 수 있도록 일목요연하게 정리된 표로,
    특정 항목 또는 특정 범위에 속하는 빈도수를 나타내는 표

- 막대 그래프
  * 비연속형 변수 (명목척도 및 서열척도)에 사용되는 그래프로, 각 항목에 속하는 빈도수를 나타내는 그래프
  
- 히스토그램
  * 연속형 변수 ( 등간척도 및 서역척도 )에 사용되는 그래프로, 일정 범위에 속하는 빈도수를 나타낸 그래프

- 선그래프
  *히스토그램의 끝 부분을 선으로 연결한 그래프
  
<hr/>  

## 공분산과 상관계수

- 공분산
  + 두 변수가 함께 각자의 평균으로부터 멀어지는 정도
  + 한 변수가 자신의 평균으로부터 멀어질 때 다른 변수가 자신의 평균으로부터 멀어지는 정도를 의미

- 상관계수
  + 두 변수 간의 관계로, 하나의 변수가 변화함에 따라 다른 변수가 변화하는 정도를 의미
  + -1 과 1사이의 범위를 가짐
  
## 가설과 신뢰수준/유의확률 
  
- 영가설 / 연구가설
    + 영가설 : 실제 분석이 이루어지는 가설
    + 연구가설 : 분석을 통해서 알아보고자 하는 내용으로 이루어진 가설
    
 - 유의 확률
 - 신뢰수준
  + 실제로는 영가설이 참(채택)이고 통계분석을 통해서도 영가설을 참(채택)으로 판단할 가능성
  + 신뢰수준이 높아질수록 연구가설이 실제현상을 반영할 가능성이 높아진다.
    
    
 ## 양측 검증과 단측 검증
 
 - 양측 검증
  + 방향성을 고려하지 않은 채로 연구가설을 설정할 때 사용하는 검증 방법 
  + 신뢰수준이 95% 일 때 양측의 2.5%의 영가설이 분석

 - 양측 검증의 예시 
  + A,B집단간의 평균간에 차이가 있을 것이다.
  + A변수가 B 변수에 미치는 영향의 크기는  '0'이 아니다.
 - 단측검증
  + 방향성을 고려하여 연구가설을 설정할 때 사용하는 검증 방법
  + 플러스 혹은 마이너스 한 방향을 잡고 5% 영가설에 포함
  
## t 분석

 - t 분석 방법이란
 독립변수가 비연속형 변수이고, 종속변수가 연속형 변수일 때 사용하는 분석방법으로, 독립변수의 집단이 2개 이하일 때 사용하는 분석 방법
 
 * t-분석의 종류
 * 일표본 t-분석
 * 독립표본 t-분석 : 두개의 모집단에서 각각의 표본을 추출할 때 사용되는 분석으로 두 집단의 표본들의 평균이 서로 같은지 다른지를 검증  
 * 대응표본 t-분석 : 하나의 모집단에서 표본을 추출하지만, 같은 표본에게 두 번의 측정이 이루어질 때 사용 
   - ex) 사전 수치와 사후 수치는 다르다 (양측 검증 )
   - ex) 사전 수치보다 사후 수치가 더 크다 ( 단측 검증 )

## 분산 분석( ANOVA )

- 독립변수가 비연속형 변수이고, 종속변수가 연속형 변수일 떄 사용하는 분석방법으로, 독립변수의 집단이 3개 이상일 떄 사용하는 분석방법
- F-분포를 사용하여 분석

분산분석 대표적인 영가설은 집단들의 평균은 모두 같다
분산분석의 연구가설은 집단들의 평균은 서로 다르다. 

- 분산분석의 원리
 + 집단 간 분산과 집단 내 분산을 통해 분석
- 사후분석 : 어떠한 집단들 간에 평균 차이가 발생하는지 알아보기 위한 분석 방법 

## 회귀 분석

- 독립변수와 종속변수가 모두 연속형 변수( 등간척도나 비율척도 ) 일 때 사용하는 방법
- 회귀분석에서는 여러개의 독립변수를 포함하는 것이 가능하다.

### 설명량 ( R**2 )

- 독립 변수들에 의해서 설명되어지는 종속변수의 분산
- R**2가 증가할수록 회귀식에서 설명되어지지 못하는 오차는 감소

## 로지스틱 회귀분석

- 독립변수가 연속형 변수이지만, 종속변수가 비연속형 변수( 특히, 이분형 변수 : 어떠한 상태가 0과1 만 존재할 때)
- Odd Ratio = p / 1-p
- 로지스틱 회귀식
  * ln ( p / 1-p ) = b0 + b1*x
  
- 로지스틱 회귀분석의 원리
 + b1 > 0:x 가 증가할 수록 특정 사건이 발생하지 않을 확률보다 발생활 확률이 높다는 의미
 + b1 < 0:x 가 증가할 수록 특정 사건이 발생할 확률보다 발생하지 않을 확률이 높다는 의미
  
### 모형 적합도
 - 모형이 적절하게 만들어졌는지를 보여주는 지표

## 조절효과와 매개효과

### 조절효과
- 독립 변수가 종속변수에 미치는 영향이 조절변수에 의해서 달라지는 지를 알아보는 분석방법
### 매개효과
- 독립변수와 종속변수 간의 직접적인 인과관계 이외에도 매개변수를 통한 간접적인 인과관계가 존재하는 지를 알아보는 분석방법


## 구조 방정식 모형
- 매개효과에 특화된 보형
- 변수들 간의 관계를 밝히는 구조모형과 각 변수와 이를 측정하는 문항들 간의 관계를 밝히는 측정모형을 함께 고려한느 분석방법

## 다수준 분석
- 단일수준 분석 :모든 변수가 하나의 수준으로 이루어진 경우
  + 회귀분석만으로 분석 가능
- 독립변수와 종속변수의 수준이 다른경우 : 집단 -> 개인 | 개인 -> 집단
