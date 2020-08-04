# JavaErrorRepositorys
자바 에러 저장용..

----------------------------------------------------  
### 1. 클래스에 Implicit super constructor Object() is undefined for default constructor. Must define an explicit constructor 에러  
- 프로젝트 우클릭 -> Build Path -> Configure BuildPath -> JRE 경로 수정  
### 2. JSP 아무 이유 없이 에러 뜰 때 (선언부에)
- Project 우클릭 -> Properties -> Java Build Path -> Tomcat 버전 확인
### 3. XML 부등호 The content of elements must consist of well-formed character data or markup. 에러  
- XML파일 에서는 <부등호를 TAG로 인식하기 때문에 에러 발생, Query안에 사용되고 있는 부등호가 문자열이라는 것을 의미하게 ```<![CDATA[내용]]>``` 으로 감싸준다.  

