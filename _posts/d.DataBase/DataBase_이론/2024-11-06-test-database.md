---
title: DataBase 기본 개념
description: DataBase 의 기본 개념과 기능, 특징, 종류 에 대해서 알아봅시다.
date: 2024-11-24 01:02:00 +0900
categories: [DataBase, DataBase 이론]
tags: [DataBase, MySQL, MongoDB, Redis, SQL, DBMS]
---
<img width="660" height="300" src="https://github.com/user-attachments/assets/8859d369-7c20-4d44-8872-2ccff76744e4">

## DataBase 의 정의

**Database 는 여러 사람이 공유하여 사용할 목적으로 체계화해 통합, 관리하는 데이터의 집합입니다. 데이터를 체계적으로 저장하고 관리하는 시스템으로 사용자나 애플리케이션이 데이터를 쉽게 입력, 검색, 수정, 삭제할 수 있도록 도와주고 데이터 무결성을 유지하며 동시성을 지원하여 여러 사용자나 다양한 애플리케이션에서 데이터를 효율적으로 활용할 수 있도록 설계되었습니다.**

<br>
<br>

## DataBase 의 특징

- 실시간 접근성 (Real Time Accessibility)

- 지속적인 변화 (Continuous Evolution)
  
- 동시 공유 (Concurrent Sharing)
  
- 내용에 대한 참조 (Content Referencing)

<br>

### 실시간 접근성 (Real Time Accessibility)

Database 는 사용자가 데이터를 즉시 접근하고 사용할 수 있어야 합니다.    

예를 들어 온라인 뱅킹 시스템에서 잔액을 조회하는 경우, 전자상거래에서 상품 재고 상태를 실시간으로 확인하는 경우가 있습니다.

<br>

### 지속적인 변화 (Continuous Evolution)

Database 는 데이터의 삽입(Insert), 삭제(Delete), 갱신(Update) 으로 시간에 따라 지속적으로 변화합니다. 데이터를 효율적으로 갱신하면서 일관성을 유지해야 합니다.

예를 들어 사용자의 배송 상태가 "준비 중" 에서 "배송 중" 으로 변경되는 경우, SNS 게시물의 "좋아요" 개수 업데이트 등이 있습니다.

<br>

### 동시 공유 (Concurrent Sharing)

Database 는 여러 사용자가 동일한 데이터를 동시에 접근하고 수정할 수 있어야 합니다. 동시성 제어 메커니즘을 통해 충돌을 방지하고 데이터의 무결성을 유지합니다.

예를 들어 협업 도구에서 여러 사용자가 동시에 문서를 편집하는 경우, 대규모 온라인 쇼핑몰에서 다수의 고객이 같은 상품을 조회하는 경우가 있습니다.

<br>

### 내용에 대한 참조 (Content Referencing)

Database 는 저장된 데이터를 고유하게 식별하고 참조할 수 있도록 설계해야 합니다.

예를 들어 제품 ID 로 특정 상품 정보를 조회, 학생 ID 로 특정 학생의 성적을 확인 하는 경우가 있습니다.

<br>











<br>

***

### ⚠️ 참고자료
- [WIKI - Database](https://ko.wikipedia.org/wiki/%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B2%A0%EC%9D%B4%EC%8A%A4)
- [Hierarchical DBMS](https://sqlversity.wordpress.com/2013/02/21/hierarchical-dbms/)
- [Blog - SQL과 NOSQL의 차이](https://gyoogle.dev/blog/computer-science/data-base/SQL%20&%20NOSQL.html)
