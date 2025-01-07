# persistence.xml(또는 appication.yml 설정)

---

## JPA 표준 속성
- javax.persistence.jdbc.driver : JDBC 드라이버
- javax.persistence.jdbc.user : DB 접속 아이디
- javax.persistence.jdbc.password : DB 접속 비밀번호
- javax.persistence.jdbc.url : DB 접속 Url

## 하이버네이트 속성
- hibernate.dialect : DB 방언(Dialect) 설정
  - H2 : org.hibernate.dialect.H2Dialect
  - 오라클 10g: org.hibernate.dialect.Oracle10gDialect
  - MySQL : org.hibernate.dialect.MySQL8Dialect (8)
- hibernate.show.sql : 하이버네이트가 실행한 SQL을 출력
- hibernate.format_sql : 출력한 SQL을 보기 쉽게 정렬