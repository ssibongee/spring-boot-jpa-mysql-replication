스프링 부트와 JPA를 활용한 프로젝트에서 MySQL 데이터베이스 서버 이중화를 연습하기 위한 프로젝트.

* MySQL 데이터베이스 서버 이중화 적용
* 애플리케이션에 여러개의 `DataSource`를 정의하는 방법
* `@Transactional` 어노테이션의 타입에 따라서 `Master` 또는 `Slave` 서버로 자동으로 라우팅하도록 설정
* 여러개의 `DataSource`를 사용하지만 애플리케이션의 입장에서는 하나의 추상화된 `DataSource`에 접근할 수 있도록 구성
