# My select shop

물품을 네이버 API로 검색하여 폴더에 넣고 모아볼 수 있는 웹사이트입니다.

폴더를 여러 개 만들어 물품 별로 관리할 수 있습니다.

[프로젝트 사이트 바로가기](http://43.203.251.13/) > 현재 DB 사용 불가능. 프리티어에서도 RDS와 EC2를 외부에서 연결하려면 비용이 발생.

# 결과

### 로그인 화면

![login](/assets/login.png)

### 탐색하기 > 네이버 API를 이용한 검색 기능

상품 옆에 있는 다운로드 아이콘을 통해 원하는 상품을 등록할 수 있다.

![result_01](/assets/result_01.png)

### 모아보기

등록한 상품만 모아보기에서 한번에 볼 수 있다.

![result_02](/assets/result_02.png)

## 폴더 추가

폴더를 만들어 모아놓은 물건들을 다시 한번 분류할 수 있다.

![result_03](/assets/result_03.png)

### 폴더 보기 > 사고 싶은 물건

![result_04](/assets/result_04.png)

### 폴더 보기 > 라면 장바구니

![result_05](/assets/result_05.png)

# 기간

24.07.29 - 24.07.31 (3일)

# 구성원

개인 프로젝트

# 주요 기술 스택

Spring Boot, JPA, MYSQL, Thymeleaf, AWS EC2, AWS RDS

# 프로젝트 목적

- 검색한 물품 중 원하는 물품을 최저가와 물품 별로 보기 위해서 

- Spring Boot 프레임워크 및 최신 기술 스택에 익숙해지기 위한 토이 프로젝트

# 주요 기능

- 폴더를 통한 물품 별 관리
- 네이버 API를 사용한 검색 기능
- 죄저가 설정 시 해당 물품을 가장 싼 가격으로 구매 가능
- Scheduler를 이용하여 매일 새벽 1시에 상품 정보 최신화

# 앞으로

- 네이버 로그인 API를 이용한 로그인
- 단위 테스트 작성
