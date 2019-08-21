# 오늘의 집 COPY

## FASTCAMPUS FDS12 1조

김들이, 유진혁, 이현호, 황유순

### 김들이

- 팀장
- 디렉토리 작업, routing, module 및 공통기능 구현, 소셜로그인
- 헤더, 프로필 수정, 집들이, 로그인, 로그아웃 페이지

### 이현호

- 푸터, 사진, 유저 프로필, 구매이력, 프로필 수정 페이지

### 유진혁

- 커뮤니티 홈: 1일 타이머 구현, 마우스 오버 시 이미지 확대 기능 구현
- 스토어 홈: sort를 활용한 필터 기능 구현
- 카테고리
- 랭킹 페이지: 더보기 버튼을 통해서 현재 보이는 컴포넌트 내의 모듈 갯수를 조정하는 기능 구현

### 황유순

- 상품 상세 페이지: 장바구니 담기, 바로 구매,  
  리뷰 작성/수정/별점 별 필터링, 문의 작성/삭제, 도움이 돼요 구현  
- 사진 상세 페이지: 사진 속 제품에 대한 상세 페이지로 연결
- 페이지네이션 구현
- 사진 디테일, 집들이 디테일, 상품 디테일, 404 페이지

## 기간

2019.07.15 ~ 2019.08.08

## 구현

### 페이지

- 회원가입
- 로그인
- 커뮤니티 홈
- 사진
- 사진 디테일
- 집들이
- 집들이 디테일
- 스토어 홈
- 카테고리
- 랭킹
- 상품 디테일
- 브랜드
- 유저 프로필
- 구매이력
- 프로필 수정
- 장바구니
- 404

### 주요기능

- Kakao 계정을 통한 로그인
- 페이지에 따른 title 변경, 로그인 유무에 따른 페이지 라우팅
- 커뮤니티 홈, 스토어 홈 등 각종 상품 리스트 및 리뷰 필터링
- 상품 디테일 페이지의 캐러셀
- 리뷰, 문의, 댓글 등의 페이지네이션
- 리뷰 작성/수정 기능
- 문의 작성/삭제 기능
- 상품 디테일 옵션 선택 동기화
- 로그인, 회원가입, 장바구니 수량에 벨리데이션
- 스크롤에 따른 헤더, 상품디테일 옵션, 장바구니 가격창 상태 변화
- 유저 정보 수정
- 재사용 기능들의 directive 및 component 분리
  <br>| (http://ohome.co.kr/common)

## 사용

- Angular(html, scss, typescript)
- Alyle

## Git

https://github.com/final-project-team01/FDS-HouseOfToday

## Demo

http://ohome.co.kr/
