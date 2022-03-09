## JSP로 간단한 게시판 만들기

## Skill Version
JSP, mysql 8.0.28

## Database

```mysql
mysql> create table user (
    -> userID varchar(20),
    -> userPassword varchar(20),
    -> userName varchar(20),
    -> userGender varchar(20),
    -> userEmail varchar(50),
    -> PRIMARY KEY (userID)
    -> );
```

Use Case
```$xslt
$ insert into user values('gildong', '123456', '홍길동', '남자', 'gildong@naver.com');
$ commit
```

## Result 
[](/img/login.png)
[](/img/login_success.png)