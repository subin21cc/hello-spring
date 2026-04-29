# 🌱 스프링 입문 - 코드로 배우는 스프링 부트, 웹 MVC, DB 접근 기술

> 인프런 김영한님의 [스프링 입문 강의](https://www.inflearn.com/course/%EC%8A%A4%ED%94%84%EB%A7%81-%EC%9E%85%EB%AC%B8-%EC%8A%A4%ED%94%84%EB%A7%81%EB%B6%80%ED%8A%B8?cid=325630) 학습 정리 레포지토리입니다.

---

## 📚 강의 정보

| 항목 | 내용 |
|------|------|
| 강의명 | 스프링 입문 - 코드로 배우는 스프링 부트, 웹 MVC, DB 접근 기술 |
| 강사 | 김영한 (전 우아한형제들 기술이사) |
| 플랫폼 | 인프런 |
| 난이도 | 입문 |
| 총 강의 수 | 28강 (5시간 21분) |
| 수강료 | 무료 |

---

## 🛠 기술 스택

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring MVC](https://img.shields.io/badge/Spring_MVC-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![H2 Database](https://img.shields.io/badge/H2_Database-0000bb?style=for-the-badge&logo=databricks&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-007396?style=for-the-badge&logo=java&logoColor=white)

---

## 📋 커리큘럼

### Section 1. 강의 소개
- 강의 소개
- 강의 자료

### Section 2. 프로젝트 환경설정
- 프로젝트 생성
- 라이브러리 살펴보기
- View 환경설정
- 빌드하고 실행하기

### Section 3. 스프링 웹 개발 기초
- 정적 컨텐츠
- MVC와 템플릿 엔진
- API

### Section 4. 회원 관리 예제 - 백엔드 개발
- 비즈니스 요구사항 정리
- 회원 도메인과 리포지토리 만들기
- 회원 리포지토리 테스트 케이스 작성
- 회원 서비스 개발
- 회원 서비스 테스트

### Section 5. 스프링 빈과 의존관계
- 컴포넌트 스캔과 자동 의존관계 설정
- 자바 코드로 직접 스프링 빈 등록하기

### Section 6. 회원 관리 예제 - 웹 MVC 개발
- 회원 웹 기능 - 홈 화면 추가
- 회원 웹 기능 - 등록
- 회원 웹 기능 - 조회

### Section 7. 스프링 DB 접근 기술
- H2 데이터베이스 설치
- 순수 JDBC
- 스프링 통합 테스트
- 스프링 JdbcTemplate
- JPA
- 스프링 데이터 JPA

### Section 8. AOP
- AOP가 필요한 상황
- AOP 적용

### Section 9. 다음으로
- 다음으로

---

## 📁 프로젝트 구조

```
src
├── main
│   ├── java
│   │   └── hello.hellospring
│   │       ├── HelloSpringApplication.java
│   │       ├── controller       # 웹 MVC 컨트롤러
│   │       ├── service          # 비즈니스 로직
│   │       ├── repository       # DB 접근 계층
│   │       ├── domain           # 도메인 객체
│   │       └── aop              # AOP 관련
│   └── resources
│       ├── static               # 정적 파일
│       ├── templates            # Thymeleaf 템플릿
│       └── application.properties
└── test
    └── java
        └── hello.hellospring    # 테스트 코드
```

---

## 🗂 학습 내용 정리

### ✅ 스프링 웹 개발 방식 3가지

| 방식 | 설명 |
|------|------|
| 정적 컨텐츠 | 파일을 그대로 웹 브라우저에 전달 |
| MVC와 템플릿 엔진 | 서버에서 HTML을 동적으로 렌더링 |
| API | JSON 형태로 데이터를 전달 |

### ✅ 스프링 빈 등록 방법

- **컴포넌트 스캔** : `@Component`, `@Controller`, `@Service`, `@Repository` 어노테이션 활용
- **자바 코드로 직접 등록** : `@Configuration` + `@Bean` 활용

### ✅ DB 접근 기술 발전 흐름

```
순수 JDBC → JdbcTemplate → JPA → 스프링 데이터 JPA
```

### ✅ AOP (Aspect Oriented Programming)

공통 관심사(cross-cutting concern)를 핵심 비즈니스 로직으로부터 분리하여 모듈화

---

## 💡 핵심 개념

- **IoC (Inversion of Control)** : 제어의 역전, 스프링 컨테이너가 객체 생명주기 관리
- **DI (Dependency Injection)** : 의존관계 주입, 외부에서 의존 객체를 주입
- **OCP (Open/Closed Principle)** : 기능 확장 시 기존 코드 변경 없이 새 코드 추가

---

## 🔗 관련 링크

- 📌 [강의 링크](https://www.inflearn.com/course/%EC%8A%A4%ED%94%84%EB%A7%81-%EC%9E%85%EB%AC%B8-%EC%8A%A4%ED%94%84%EB%A7%81%EB%B6%80%ED%8A%B8?cid=325630)
- 📌 [김영한 스프링 완전 정복 로드맵](https://www.inflearn.com/roadmaps/373)

