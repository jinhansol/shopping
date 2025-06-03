<h2>🛒 스프링 부트 쇼핑몰 프로젝트 with JPA</h2></br>
"이 저장소는 『스프링 부트 쇼핑몰 프로젝트 with JPA』(변구훈 저) 책을 따라가며 학습한 결과물입니다."

<hr>
<h2>📚 프로젝트 소개</h2>
<li>Spring Boot, Spring Data JPA, Spring Security 등 주요 백엔드 기술을 활용하여 쇼핑몰 서비스를 구현한 학습용 프로젝트입니다.</li>
<li>실습과 실전 경험을 쌓기 위해 책의 예제와 실습을 직접 구현하고, 필요한 부분은 커스터마이징하였습니다.</li>
<li>주요 기능: 회원가입/로그인, 상품 등록·관리, 장바구니, 주문, 권한별 서비스 등</li>

<hr>
<h2>🛠️ 사용 기술 (Tech Stack)</h2>

| Java | Spring Boot | Spring Data JPA | Spring Security | Thymeleaf | MySQL |
|------|-------------|-----------------|-----------------|-----------|-------|

- **백엔드**: Java, Spring Boot, Spring Data JPA, Spring Security, Hibernate  
- **프론트엔드**: HTML, CSS, JavaScript, Thymeleaf  
- **데이터베이스**: MySQL

<hr>
<h2> 📝 주요 기능 </h2>

### 회원
- 회원가입, 로그인/로그아웃
- 역할별 권한(관리자, 일반회원)

### 상품
- 상품 등록/수정/삭제 (관리자)
- 상품 목록/상세 조회
- 조건별 검색/필터링

### 주문
- 상품 주문, 주문 내역 조회, 주문 취소

### 장바구니
- 상품 추가/수정/삭제, 장바구니 상품 주문

### 보안
- Spring Security 기반 인증/인가

<hr>
<h2>💾 데이터베이스 테이블</h2>

- `member`: 회원 정보
- `item`: 상품 정보
- `item_img`: 상품 이미지
- `order`: 주문 정보
- `order_item`: 주문별 상품 정보
- `cart`: 장바구니 정보
- `cart_item`: 장바구니별 상품 정보

<hr>
<h2>📑 참고 도서 </h2>
『스프링 부트 쇼핑몰 프로젝트 with JPA』, 변구훈 저, 로드북
