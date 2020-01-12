# Java Spring Boot Study
* * *

# 어떻게 만들 것인가?
> 시스템 아키텍쳐 설계
  - 제약 조건 : 홈페이지 , 웹 기술 ,HTML ,CSS
  - 모바일 어플리케이션
  - Front-end
  - Back-end ( 여기에 집중 )
  
> 멀티 티어 아키텍쳐 
  - 주로 3티어 아키텍쳐 사용
  ``` 
      Presentation
      Business
      Data Source 
  ```
   - Business
   ```
     Layerd 아키텍쳐
   
     UI
     Application 
     Domain
     Infrastructure
   ```
   각각의 layer 는 자신의 레이어의 바로 위 아래의 레이어와 통신할 수 있고 의존되어있다.
   UI 레이어가 도메인레이어와 인프라스트럭쳐 레이어에 접근을 할 수 없다.
   
   - 복잡한 프로그램의 경우 각 각의 레이어가 분리되어 있어야 개발과 유지보수가 쉬워짐
