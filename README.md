# 🛍️ DaMall 쇼핑몰 구축 프로젝트

SEED-PARK 팀에서 진행한 **DaMall 종합 쇼핑몰 구축 프로젝트**의 README입니다.

---

## 🌟 프로젝트 개요 (Project Overview)

본 프로젝트는 국내 종합 쇼핑몰 **DaMall** 구축을 목표로 진행되었습니다.

### 📌 주요 특징

* 의류, 전자기기 등 다양한 상품 제공
* 고객 서비스 중심의 **인터넷 기반 종합 쇼핑 플랫폼**
* 회원 서비스, 쇼핑 관리, 게시판, 관리 기능 등 핵심 기능 포함

### 📌 기업 요청 기능

* 회원 및 쇼핑 관련 기능 제공
* 플랫폼 데이터의 저장 및 관리 기능
* 문의 게시판 구축
* 쇼핑몰 운영을 위한 관리자 기능 제공

---

## 💻 개발 환경 및 기술 스택 (Development Environment & Tech Stack)

### ⚙️ 시스템 환경

| 구분  | 사양         |
| --- | ---------- |
| HDD | 256GB      |
| CPU | 2.90GHz    |
| RAM | 6.0GB DDR3 |

### 🛠️ 개발 도구

* **IDE:** Eclipse IDE 2021-09 (4.21.0)
* **Database:** Oracle Database 12c
* **Web Server:** Apache Tomcat v9.0

### 🚀 기술 스택

* **Frontend:** HTML, CSS, JavaScript (유효성 검사 포함)
* **Backend:** JSP, Java
* **DB 연결:** JDBC (Java Database Connectivity)

---

## ✨ 주요 기능 구현 (Main Features)

### 👤 회원 및 관리 기능

* 로그인 / 회원 가입
* 회원 탈퇴
* 관리자용 회원 목록 조회

### 🛒 쇼핑 기능

* 상품 등록, 저장(관리자)
* 상품 목록 보기, 검색
* 장바구니 담기 / 조회
* 주문하기, 주문 저장, 주문 내역 확인

### 💬 문의 게시판 기능

* 글 목록 보기, 작성, 상세 보기, 수정, 삭제
* 파일 다운로드 지원
* JSP 기반 **MVC(Model-View-Controller)** 구조로 구현

---

## 🗓️ 개발 일정 (Development Schedule)

| 단계              | 일정                 | 담당자      |
| --------------- | ------------------ | -------- |
| 요구사항 분석 / 환경 구축 | 2022.10.17 ~ 10.20 | 정하영, 조정희 |
| UI/UX 디자인       | 2022.10.24 ~ 10.27 | 문혜민      |
| 프론트엔드 개발        | 2022.10.24 ~ 11.03 | 정하영, 조정희 |
| 백엔드 개발          | 2022.10.31 ~ 11.10 | 정찬영, 방휘원 |
| DB 설계 및 개발      | 2022.11.07 ~ 11.18 | 김우혁      |
| API 연동          | 2022.11.07 ~ 11.10 | 김우혁      |
| QA 및 테스트        | 2022.11.14 ~ 11.18 | 정찬영      |
| 배포 및 유지보수       | 2022.11.14 ~ 11.18 | 방휘원      |

---

## ⚠️ 어려웠던 점 & 보완할 점 (Challenges & Improvements)

### 🤔 어려웠던 점

* **Oracle 한글 깨짐 문제** 발생 → DB/클라이언트 캐릭터셋 일치로 해결
* **Spring 설치 오류**로 스프링 게시판 구축 불가 → JSP MVC로 대체
* 다양한 오류 해결에 많은 시간 소요

### 💡 향후 개선 사항

* URL 구조 개선
* Spring 기반 MVC 게시판으로 확장 개발
* 개인정보 마스킹 등 보안 강화
* 가이드 정비 및 디버깅 효율 향상

---

## 🔗 소스 코드 (Repository)

[https://github.com/toto6343/SEED-PARK](https://github.com/toto6343/SEED-PARK)

---

## 👥 팀 소개 (Team Introduction)

**SEED-PARK**은 "성장 잠재력이 높은 팀원들이 함께 아이디어를 발전시키며 성장하는 팀"이라는 의미를 담고 있습니다.

---
## 🖼️ Screenshots

### 메인 페이지
## 🖼️ Screenshots

### 메인 페이지
![메인 페이지](https://github.com/user-attachments/assets/9057ce63-bcc6-467d-ba39-7a5a58f5c0c3)

### 관리자 상품 등록 페이지
![관리자 상품 등록](https://github.com/user-attachments/assets/383c162c-32b0-43b3-a064-df43e34a5b79)

### 사용자 상품 목록 페이지
![사용자 상품 목록](https://github.com/user-attachments/assets/3f6d7e26-5720-4f7e-94fb-08ec2eae8aeb)



