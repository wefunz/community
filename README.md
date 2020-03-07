##峰峰社区

##资料
[Spring文档](https://spring.io/guides)  
[Spring web文档](https://spring.io/guides/g/serving-web-content)  
[es社区](https://elasticsearch.cn/explore)  
[github OAuth](https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/)  
[GitHub oAuth说明文档](https://developer.github.com/apps/building-github-apps/identifying-and-authorizing-users-for-github-apps/)  
[spring](https://docs.spring.io/spring-boot/docs/)

##工具
[flyway](https://flywaydb.org/)

##脚本
```sql
create table USER
(
	ID INT auto_increment,
	ACCOUNT_ID VARCHAR(100),
	NAME VARCHAR(50),
	TOKEN CHARACTER(36),
	GMT_CREATE BIGINT,
	GMT_MODIFIED BIGINT,
	constraint USER_1_PK
		primary key (ID)
);


```

```bash
mvn flyway:migrate
```