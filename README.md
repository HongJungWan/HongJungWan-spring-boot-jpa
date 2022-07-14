# 🚩 JPA 활용 1, 2, 스프링 데이터 JPA

<br>

## 🔍 학습 목표

<br/>

1편 : 회원, 상품, 주문 도메인이 있는 간단한 웹 애플리케이션을 설계하고 개발

<br/>

2편 : 조회용 API의 성능 최적화, 실무에서 꼭 필요한 JPA의 조회 쿼리 튜닝과 관련된 부분 학습

<br>

스프링 데이터 JPA : 실무에서 실제 사용하는 기능 위주로 학습

<br><br>

## 💡 기록

<br>


| 분류                | 링크                                                                                                                                                                                                                                     |
|-------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| JPA Part 1</span> | [Entity 매핑](https://velog.io/@daydream/Spring-JPA-Entity-%EB%A7%A4%ED%95%91) <br/>                                                                                                                                                     | 
| JPA Part 1</span> | [Entity 연관 관계 매핑](https://velog.io/@daydream/Spring-JPA-Entity-%EC%97%B0%EA%B4%80-%EA%B4%80%EA%B3%84-%EB%A7%A4%ED%95%91) <br/>                                                                                                         |
| JPA Part 1</span> | [영속성 컨텍스트, 1차 캐시, 쓰기 지연](https://velog.io/@daydream/Spring-JPA-%EC%98%81%EC%86%8D%EC%84%B1-%EC%BB%A8%ED%85%8D%EC%8A%A4%ED%8A%B8-1%EC%B0%A8-%EC%BA%90%EC%8B%9C-%EC%93%B0%EA%B8%B0-%EC%A7%80%EC%97%B0) <br/>                             |
| JPA Part 1</span> | [연관관계 편의 메서드](https://velog.io/@daydream/Spring-JPA-%EC%97%B0%EA%B4%80%EA%B4%80%EA%B3%84-%ED%8E%B8%EC%9D%98-%EB%A9%94%EC%84%9C%EB%93%9C) <br/>                                                                                         |
| JPA Part 1</span> | [@Transactional(readOnly = true)](https://velog.io/@daydream/Spring-TransactionalreadOnly-true) <br/>                                                                                                                                  |
| JPA Part 1</span> | [Entity 설계 시 주의점](https://velog.io/@daydream/Spring-JPA-Entity-%EC%84%A4%EA%B3%84%EC%8B%9C-%EC%A3%BC%EC%9D%98%EC%A0%90) <br/>                                                                                                          |
| JPA Part 1</span> | [변경 감지와 병합(merge)](https://velog.io/@daydream/Spring-JPA-%EB%B3%80%EA%B2%BD-%EA%B0%90%EC%A7%80%EC%99%80-%EB%B3%91%ED%95%A9merge) <br/>                                                                                                 |
|||
| JPA Part 2</span> | [API 개발 기본 (등록, 수정, 조회)](https://velog.io/@daydream/Spring-API-%EA%B0%9C%EB%B0%9C-%EA%B8%B0%EB%B3%B8-%EB%93%B1%EB%A1%9D-%EC%88%98%EC%A0%95-%EC%A1%B0%ED%9A%8C) <br/>                                                                   |
| JPA Part 2</span> | [API 개발 고급 - 지연 로딩과 조회 성능 최적화](https://velog.io/@daydream/Spring-JPA-API-%EA%B0%9C%EB%B0%9C-%EA%B3%A0%EA%B8%89-%EC%A7%80%EC%97%B0-%EB%A1%9C%EB%94%A9%EA%B3%BC-%EC%A1%B0%ED%9A%8C-%EC%84%B1%EB%8A%A5-%EC%B5%9C%EC%A0%81%ED%99%94) <br/> |
| JPA Part 2</span> | [API 개발 고급 - 컬렉션 조회 최적화, ❶](https://velog.io/@daydream/Spring-JPA-API-%EA%B0%9C%EB%B0%9C-%EA%B3%A0%EA%B8%89-%EC%BB%AC%EB%A0%89%EC%85%98-%EC%A1%B0%ED%9A%8C-%EC%B5%9C%EC%A0%81%ED%99%94) <br/>                                          |
| JPA Part 2</span> | [API 개발 고급 - 페이징과 한계 돌파](https://velog.io/@daydream/JPA-API-%EA%B0%9C%EB%B0%9C-%EA%B3%A0%EA%B8%89-%ED%8E%98%EC%9D%B4%EC%A7%95%EA%B3%BC-%ED%95%9C%EA%B3%84-%EB%8F%8C%ED%8C%8C) <br/>                                                    |
| JPA Part 2</span> | [API 개발 고급 - 컬렉션 조회 최적화 ❷](https://velog.io/@daydream/JPA-API-%EA%B0%9C%EB%B0%9C-%EA%B3%A0%EA%B8%89-%EC%BB%AC%EB%A0%89%EC%85%98-%EC%A1%B0%ED%9A%8C-%EC%B5%9C%EC%A0%81%ED%99%94) <br/>                                                  |
| JPA Part 2</span> | [API 개발 고급 정리](https://velog.io/@daydream/JPA-API-%EA%B0%9C%EB%B0%9C-%EA%B3%A0%EA%B8%89-%EC%A0%95%EB%A6%AC) <br/>                                                                                                                      |
| JPA Part 2</span> | [OSIV와 성능 최적화](https://velog.io/@daydream/JPA-OSIV%EC%99%80-%EC%84%B1%EB%8A%A5-%EC%B5%9C%EC%A0%81%ED%99%94) <br/>                                                                                                                      |
|||
| Spring Data JPA   | [공통 인터페이스 기능](https://velog.io/@daydream/JPA-Spring-Data-JPA-%EA%B3%B5%ED%86%B5-%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4-%EA%B8%B0%EB%8A%A5) <br/>                                                                                |                                                                                                                                                                                                                                   |                                                                                                                                                                                                                                   |                                                                                                                                                                                                                                     |
| Spring Data JPA   | [Query method 기능 ①](https://velog.io/@daydream/JPA-Spring-Data-JPA-Query-method-%EA%B8%B0%EB%8A%A5)                                                                                                                                    |
| Spring Data JPA   | [Query method 기능 ②](https://velog.io/@daydream/JPA-Spring-Data-JPA-Query-method-%EA%B8%B0%EB%8A%A5-xazhu97j)                                                                                                                           |
| Spring Data JPA   | [순수 JPA 👉 Spring Data JPA 페이징, 정렬](https://velog.io/@daydream/JPA-Spring-Data-JPA-%EC%88%9C%EC%88%98-JPA-Spring-Data-JPA-%ED%8E%98%EC%9D%B4%EC%A7%95-%EC%A0%95%EB%A0%AC)                                                                                                                                                                                                                                   |
| Spring Data JPA   ||
| Spring Data JPA   ||

<br><br>

## 🔍 강의 목차

### 1편

🔹  도메인 분석 설계 <br/>
🔹  애플리케이션 구현 준비 <br/>
🔹  회원 도메인 개발 <br/>
🔹  상품 도메인 개발 <br/>
🔹  주문 도메인 개발 <br/>
🔹  웹 계층 개발 <br/>

<br/>

### 2편

🔹  API 개발 기본 <br/>
🔹  API 개발 고급 - 준비 <br/>
🔹  API 개발 고급 - 지연 로딩과 조회 성능 최적화 <br/>
🔹  API 개발 고급 - 컬렉션 조회 최적화 <br/>
🔹  API 개발 고급 - 실무 필수 최적화 <br/>

<br>

### 스프링 데이터 JPA

🔹 공통 인터페이스 기능 <br/>
🔹 쿼리 메소드 기능 <br/>
🔹 확장 기능 <br/>
🔹 스프링 데이터 JPA 분석 <br/>
🔹 Specifications, Query By Example, Projections, 네이티브 쿼리 <br/>

<br><br>

## 🔍 개발 환경

🔹 Java 11 <br>
🔹 Gradle 7.3.1 <br>
🔹 Spring Boot 2.4.1 <br>

<br><br>

## 정보

👉홍정완👈

[cs 블로그](https://velog.io/@daydream) -
hjw43ok@hs.ac.kr
