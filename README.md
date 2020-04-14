# 시냅스 방법론 3.0
> 시냅스 방법론 3.0 의 공정 및 주요 산출물, 샘플코드를 공유한다.



# SW Moderization 공정도




# 네이티브 공정도

![공정도](https://github.com/cnaps/main/blob/master/img/%EA%B3%B5%EC%A0%95%EB%8F%84.png)  

# 프렉티스 별 주요활동 & 산출물 
|Practice | Step | Output |
||||

# 주요 ASSET
## 0.아키텍처 
- 아키텍처 구성도
  - 외부 아키텍처
    - 배포 구성도 
    - 쿠버네티스 기반 
  - 내부 아키텍처 
    - 헥사고널 & 클린아키텍처 

## 1.설계
- 마이크로서비스도출
  - 컨텍스트맵
    - DDD 전략적설계 개념
    - 이벤트스토밍가이드
    
- 마이크로서비스설계 
  - 내부구조정의 
    - 헥사고널 아키텍처 적용 패키지구조
    - 단순 CRUD구조와 도메인모델구조 선택가이드
  - API설계서
    - API 설계 개념  
  - 도메인모델
    - DDD 전술적설계 개념
  - 데이터모델 
## 2.개발
- 내부영역개발
  - 도메인 구현
  - 레파지토리 구현
  - 서비스 구현
  - 도메인이벤트 구현
- 외부영역개발
  - 컨트롤러 구현
- EDA구현
  - 도메인이벤트 어댑터 구현
    - 카프카 설치
- CQRS구현
    
## 3.통합 및 배포
- 도커라이징
  - DockerFile
- 컨테이너라이징
  - 쿠버네티스 아키텍처의 이해
  - 실습
- 배포파이프라인구축
  - 애저
  - AWS

## 컨텐츠 및 교육교재
  - [MSA개념 및 주요패턴](https://engineering-skcc.github.io/tags/microservice/)
    - [마이크로서비스 개념](https://engineering-skcc.github.io/categories/#microservice-%EA%B0%9C%EB%85%90)
    - [마이크로서비스 Outer 아키텍처](https://engineering-skcc.github.io/categories/#microservice-outer-achitecture)
    - [마이크로서비스 Inner 아키텍처](https://engineering-skcc.github.io/categories/#microservice-inner-achitecture)
    - 교육교재 
  - 마이크로서비스 모델링
    - 도메인주도설계
      - 전략적설계
      - 전술적설계
    - API설계
    - 이벤트스토밍
    - 교육교재
   


