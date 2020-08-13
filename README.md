# Spring_CRUDexample

<h3>Steps</h3>
<p>
2020/08/12 수업
1. spring legacy 생성(spring mvn project로)

2. DB 접속 - table 생성
create table emp100 (
  id int not null auto_increment, 
  name varchar(30), 
  salary float default 0, 
  designation varchar(4000),
  regdate datetime default current_timestamp,
  primary key(id) 
 )

3. 라이브러리 추가(pom.xml)
mysql connector mvn(8.0.16)
spring jdbc(5.2.5)
-내꺼랑 개발환경이 같은지, 버전을 항상 확인해야 할 것!
spring으로 되어 있는거는 반드시 버전 맞춰줄 것! ${org.springframework-version}
변수화 해놓은거 갖다 쓰기
https://spring.io/projects/spring-framework#learn
Spring 버전 확인하는 사이트
(파일 업로드 라이브러리 추가하고 싶다면 cos.jar)


-그리고 run해서 defualt 페이지 잘 나오는지 확인해보기

4. bean을 만든다
구글검색해서 디렉터리 구조 참고할수도
 변수 적고, getters setters 받아오기

5.Dao를 만든다
Data access object, CRUD 기능 여기다가 만들거야
DB 접속을 우선해야 해(우리는 그 접속 부분은 xml으로 해서 할 것, 그래서 spring jdbc를 썼어)
 

6. root-context.xml
jdbcTemplate setting

7. Dao
import

http://localhost:8087/mypage/
잘 되는지 확인해보기

8. Controller
Create / List(View) / Update /Delete



<form:form method="POST" action="/SpringMVCCRUDSimple/editsave"> 



com.camp.mypage


</p>
