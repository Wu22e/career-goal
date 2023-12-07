# KYS 작성 (Known Your Self)

## Key Strength 작성
- JAVA
- SPRING (BOOT)
- REDIS
- MARIA DB
- JPA
- AWS
- NODE JS
- GOLANG
- Recruitment Tech


## Read.me 작성
- Task force 팀에 합류하여 개발자 채용 플랫폼 서비스의 개발/배포/운영을 경험하였습니다.
- 2년 간 제품의 처음 부터 개발, 출시, 운영을 모두 경험하였고 누적 1억원 금액의 B2B 매출을 달성하였습니다.
- Java 기반, Spring Boot, JPA 를 활용하여 기업 관리자 및 코딩 테스트 서비스를 개발하였습니다. 
- 레거시 채점 서버를 javascript 기반 nodejs 를 활용하여 스케일링에 유연한 서버리스 아키텍처를 구축하였습니다.
- 채점 서버의 작업을 병렬로 효과적으로 처리하기 위해 Golang 언어로 마이그레이션 하여 서버 자원을 최대한으로 활용하도록 전환하였습니다.


## Goal 작성
- 응시자 동시 10만명에 대한 트래픽을 안정적으로 운영할 수 있는 아키텍처로 개발 및 운영
- 순간적인 트래픽 급증에 대응하는 다양한 전략에 대한 이해와 구현 능력 갖추기
- 상황에 맞는 해결책을 제시할 수 있는 개발자 (어떤 기술을 사용해서 어떻게 해결할 것인지와 같은 정답이 없는 상황에서 오버 엔지니어링 하지 않고 적절한 해결책을 제시하는 것. 또는 엔지니어링으로 풀지 않아도 되는 방법을 생각하고 제안하는 것.)


# GAP 분석

## 필요 역량

- Java 개발 역량
- Spring Boot 역량
- JPA 역량
- Golang 개발 역량
- 대용량 트랜잭션 처리 역량
  - DB Transaction
  - Bulk Transaction
  - 비동기 처리
  - Spring Batch 역량

- 시스템 아키텍처 역량
  - AWS 클라우드 서비스 역량
  - 리눅스 역량
  - 분산 시스템 
    - Database Sharding
    - Server Cluster Mode(Consistent Hashing)
  - Circuit Break 도입 (https://spring.io/guides/gs/cloud-circuit-breaker/ or Resilience4)

- 적절한 캐싱을 활용한 응답 시간 단축
  - Redis 
  - Cloud Front
  - Akamai

- 서비스 테스트 역량
  - TDD / ATDD 
  - 부하 테스트 (k6, locust)

- 도메인 이해 역량

  - Domain 모델 작성 능력
  - 서비스 전반의 이해 가능한 Flow 작성 
  - 문서화 능력

- 협업 소통 능력
  - 자신의 주장을 정확히 전달할 수 있는 능력
  - 소통을 통해 합의점을 찾아낼 수 있는 능력
  - 경험 및 데이터 기반으로 논리적인 해결책을 제시할 수 있는 능력
  - 도메인을 완벽히 이해하고 도메인에 적절한 여러 방안을 제시할 수 있는 능력


## 나의 상태
- Java 개발 역량 [O]
- Spring Boot 역량 [O]
- JPA 역량 [O]
- Golang 개발 역량 [△]
- 대용량 트랜잭션 처리 역량
  - DB Transaction [O]
  - Bulk Transaction [△]
  - 비동기 처리 [O]
  - Spring Batch 역량 [△]
- 시스템 아키텍처 역량 (Devops)
  - AWS 클라우드 서비스 역량 [△]
  - 리눅스 역량 [△]
  - 분산 시스템 [△]
    - Database Sharing [X]
    - Server Cluster Mode(Consistent Hashing) [X]

  - Circuit Break 도입 (https://spring.io/guides/gs/cloud-circuit-breaker/ or Resilience4) [X]
  
- 적절한 캐싱을 활용한 응답 시간 단축
  - Redis [O]
  - Cloud Front [△]
  - Akamai [△]
  
- 서비스 테스트 역량
  - TDD / ATDD [O]
  - 부하 테스트 (k6, locust) [O]

- 도메인 이해 역량
  - Domain 모델 작성 능력 [O]
  - 서비스 전반의 이해 가능한 Flow 작성 [O] 
  - 문서화 능력 [O]

- 협업 소통 능력
  - 자신의 주장을 정확히 전달할 수 있는 능력 [O]
  - 소통을 통해 합의점을 찾아낼 수 있는 능력 [△]
  - 경험 및 데이터 기반으로 논리적인 해결책을 제시할 수 있는 능력 [X]
  - 도메인을 완벽히 이해하고 도메인에 적절한 여러 방안을 제시할 수 있는 능력 [△]
  
  
## Gap 분석
- 자바 최적화, 비동기 기술에 대한 부족함이 있음. ex) Future, Syncronized, webflux, r2dbc
- Spring Boot 를 다시 한번 정리해서 부족한 부분을 매꿀 필요가 있음. ex) Spring Bean Cycle
- JPA Lock 처리에 대한 이해가 필요함.
- 최근 Golang 을 특정 서비스에 적용하고 있는데, 숙련도가 부족함.
- Bulk Transaction 처리에 대한 이해 필요
- 리눅스를 이용한 서비스 모니터링 역량 필요
- 시스템 아키텍쳐 역량을 높이기 위한 분산 시스템 기술에 대한 역량 필요. (db sharding, cluster mode)
- 프론트 엔드에 작동 원리에 대한 지식 부족 & 클라우드 프론트 (CDN)의 동작 및 적용 방법 이해 필요
- 다른 사람과 소통하며 합의점을 찾아내는 과정에 대한 연습이 필요. (PM 이 일하는 방법, 구글 엔지니어는 이렇게 일한다 등등 책 읽기)
- 다양한 서비스에 대한 경험 및 데이터기반 서비스 운영 경험이 적음.

## TO-DO List
- 자바 심화 내용 학습 (Future, Syncronized, webflux, r2dbc)
- Spring Boot 필수 개념들 재정리
- JPA Lock 원리 및 처리 방법 정리
- Golang 동시성 처리 방법 학습
- Bulk Transaction 을 사내의 비효율적인 부분에 적용하기
- 급증하는 트래픽의 우회 방법 적용해보기 (Circuit Break)
- 서비스에 직접 APM을 달아서 리눅스 기반 서비스 모니터링해보기
- 서비스에서 CDN을 활용할 수 있는 곳을 찾아서 적용해보기 (akamai, cloud front)
  - 프론트 엔드 동작원리 이해 & 클라우드 프론트 사용 사례 학습 및 사이드 프로젝트에 적용해보기

- 매일 하루를 회고하며 그날 있었던 다른 사람과의 소통에서 나의 부족한 점을 찾아내고 어떻게 하면 좋았을지 생각하기
- 사이드 프로젝트를 실제로 런칭해서 새로운 도메인에 대한 경험 및 운영해보기 





