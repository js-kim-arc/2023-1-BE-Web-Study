# 2023-1-BE-Web-Study
2023 1학기 기초 백엔드 스터디 커리큘럼 과제입니다
1. mvc 패턴이란??
우선, mvc란 model, view, Controller의 약자입니다. 하나의 프로젝트를 구성할 때 그 구성요소를 세가지의 역할로 구분한 패턴입니다.
<img src="https://mblogthumb-phinf.pstatic.net/MjAxNzAzMjVfMjIg/MDAxNDkwNDM4ODMzNjI2.nzDNB5K0LuyP4joE2C4rIbL5Ue2F3at7wiI6ZpuTJN0g.WZ6V-WHZygLYW2WSdzcs7uAiAWgAJe3_H0XdkYKkutkg.PNG.jhc9639/1262.png?type=w800">
위의 그림처럼 사용자가 컨트롤러를 조작하면 컨트롤러는 모델을 통해서 데이터를 가져오고 그 정보를 바탕으로 시각적인 표현을 담당하는 View를 제어해서 사용자에게 전달하는 구조이다. 

2. api와 서버 
간단하게 api 란 application programming interface로  
api 서버는 이 api를 제공해주는 서버를 API라고 한다. 


3. restful이란??
rest-> 클라이언트 - 서버 통신 방식 
restapi-> rest가 적용된 api
restful-> restapi가 제공하는 시스템이 restful이다 
representational
state
transfer
-> 어떠한 상태를 주고 받는 
http : 주고받는 프로토콜(규약)
http를 이용해서 구성 -url(주소)/하위 리소스 지정/
하위 리소스에 대해 
C  -> POST
R  -> GET
U  -> PUT
D  -> DELETE  http프로토콜을 가지고 자원을 핸들링 하는 것 


->api를 open을 해서 CRUD롤 맵핑을 해서 오픈을 해주면
  그게 바로 RESTFUL 방식이 된다. 

도서 대출/반납   -> 도서 대출 C (책이 대출되었다는 정보)  
             조회 R(대출을 정보를 읽어온다)    < -  도서관
                 U(대출을 연장하거나 그러한 업데이느)    
                 D(그냥 정보 삭제 해버리기)
도서에 대해 CRUD를 한다.
