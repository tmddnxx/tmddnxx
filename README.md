# 👋 안녕하세요, 이승우입니다

<div align="center">

**"Systems that move money must never go wrong."**

결제 · 정산 · 토큰 거래 — 돈이 흐르는 시스템의 **정합성과 신뢰성**을 책임지는 백엔드 엔지니어입니다.

멱등성, 보상 트랜잭션(Saga), 복구 설계로 분산 환경의 데이터 정합성 문제를 풀어왔고,  
기획부터 개발, 운영, 장애 대응까지 Product 전체에 참여하며 비즈니스 가치를 만드는 일에 보람을 느낍니다.

</div>

---

## 🔍 What I Do

- 💳 **결제 시스템 신뢰성 설계** — PG 빌링키(정기/후불) 연동에서 응답 유실·타임아웃 시
  거래조회 기반 복구 로직과 멱등성·보상 트랜잭션(Saga)으로 이중과금/결제 누락을 구조적으로 차단

- ⛓️ **블록체인 STO 백엔드** — Hyperledger Fabric 기반 프라이빗 블록체인 네트워크를 구축·연동하고,
  토큰 발급·분배를 담당하는 백엔드 서버 개발

- 🔗 **분산 데이터 정합성** — 외부 시스템을 Source of Truth로 삼은 멱등(idempotent) 동기화 엔진으로
  대량 데이터를 reconcile, 오취소·중복 처리 사고를 원천 방지

- 🔄 **무중단 레거시 마이그레이션** — 운영 중인 Express 서비스를 NestJS로 단계적 이관,
  E2E 스냅샷 회귀검증으로 29+ 엔드포인트를 다운타임·회귀 없이 전환

- 🚀 **Spring Boot 기반 B2C 서비스 런칭** — RabbitMQ, ECS 도입으로 병렬성과 응답속도 개선,
  장애 발생 시 원인 분석 → 복구 → 재발 방지까지 주도

- 🧩 **멀티벤더 하드웨어 추상화 라이브러리** — 벤더마다 제각각인 IoT 장비 프로토콜을
  어댑터 패턴으로 단일 인터페이스화, npm 패키지로 SemVer 배포(v0.1 → v1.0.0)

---

## 🛠️ Tech Stack

### Languages

<p>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="Java" src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
</p>

### Frameworks & Libraries

<p>
  <img alt="NestJS" src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" />
  <img alt="Spring Boot" src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img alt="Express" src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img alt="TypeORM" src="https://img.shields.io/badge/TypeORM-FE0803?style=for-the-badge&logo=typeorm&logoColor=white" />
  <img alt="JPA" src="https://img.shields.io/badge/JPA-0C4B33?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img alt="MyBatis" src="https://img.shields.io/badge/MyBatis-000000?style=for-the-badge" />
</p>

### Blockchain

<p>
  <img alt="Hyperledger Fabric" src="https://img.shields.io/badge/Hyperledger_Fabric-2F3134?style=for-the-badge" />
</p>

### Databases & Storage

<p>
  <img alt="MariaDB" src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white" />
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
</p>

### Messaging & Realtime

<p>
  <img alt="RabbitMQ" src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" />
  <img alt="AWS SQS" src="https://img.shields.io/badge/AWS_SQS-FF4F8B?style=for-the-badge" />
  <img alt="MQTT" src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white" />
  <img alt="Socket.io" src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white" />
  <img alt="Redis Pub/Sub" src="https://img.shields.io/badge/Redis_PubSub-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
</p>

### Cloud & Infrastructure

<p>
  <img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge" />
  <img alt="AWS ECS" src="https://img.shields.io/badge/AWS_ECS-FF9900?style=for-the-badge" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img alt="AWS CloudWatch" src="https://img.shields.io/badge/CloudWatch-FF4F8B?style=for-the-badge" />
</p>

### DevOps & Quality

<p>
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img alt="AWS CodeDeploy" src="https://img.shields.io/badge/AWS_CodeDeploy-527FFF?style=for-the-badge" />
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img alt="Swagger" src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" />
</p>

---

## 📫 Contact

- 이메일: lsw8762@gmail.com

---

_즐거운 개발 생활 되세요!_
