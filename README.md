## [미션1] 테이블 설계하기
### 도서관 책 대출 관리 시스템입니다.
N:M의 관계를 가지는 책과 고객으로 테이블을 생성했습니다.

---
#### 구현할 기능
- **Books**
  - 책 등록
  - 책 삭제 (기록 없을 때, 있으면 상태 변경)
  - 책 수정 (상태, 소개글)
  - 책 전체 조회
  - 책 개별 조회
  - 책 검색
  - 연체된 책 조회

- **Customers**
  - 고객 등록
  - 고객 삭제 (기록 없을 때)
  - 고객 수정 (다 연체 고객 상태 변경)
  - 고객 전체 조회
  - 고객 개별 조회
  - 고객 검색
  - 연체된 고객 조회

- 대출/반납을 구현...? 바코드...?
- 회원 가입 구현...?

---
#### miniBook ERD
![image](https://github.com/user-attachments/assets/d77e987a-a360-498b-a88b-1d68ed271a80)

---
#### [미션3] REST API 설계하기
- **Books**
  - 책 등록 - POST/books
  - 책 삭제 - DELETE/books/1
  - 책 수정 - PUT/books/1
  - 책 전체 조회 - GET/books
  - 책 개별 조회 - GET/books/1
  - 책 검색 - GET/books/serch?...
  - 연체된 책 조회 - GET/books/lateDate

- **Customers**
  - 고객 등록 - POST/customers
  - 고객 삭제 - DELETE/customers/1
  - 고객 수정 - PUT/customers/1
  - 고객 전체 조회 - GET/customers
  - 고객 개별 조회 - GET/customers/1
  - 고객 검색 - GET/customers/serch?...
  - 연체된 고객 조회 - GET/customers/lateDate


