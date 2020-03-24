# retulix

![리투릭스 ppt](https://user-images.githubusercontent.com/58322576/77391195-7798f600-6ddb-11ea-99e9-2d56f11ad538.PNG)


<h2>1. 개발목적 및 프로젝트 개요</h2>

이 프로젝트의 목표는 소비자와 공급자간의 드라마, 영화에 대한 양방향성 리뷰 플랫폼을 만드는 것입니다. 
소비자와 공급자를 따로 구분하지 않고, 조회수에 대한 수익창출 구조를 통해 컨텐츠 생산을 유도하고, 다양한 리뷰를 바탕으로 드라마,
 영화에 대한 소비의 접근 용이성을 높였습니다.
 
<h3>1) 제작 환경</h4>
Oracle Database 11g Express Edition  11.2.0.2.0<br>
Oracle JDK 1.8.0_231<br>
Eclipse 2019-09 IDE<br>
Visual Studio Code<br>
SqlDeveloper<br>

 <h3>2) 사용 언어 및 기타 기술</h4>
jQuery, Servlet, jsp, JSTL, javascript<br>
Java, Ajax, Spring, MyBatis

<h2>2. 프로젝트 소개</h2>

<h3> 1) 데이터베이스 설계</h4>
 
![retulix_exerd](https://user-images.githubusercontent.com/58322576/77390001-0277f180-6dd8-11ea-89de-396bea54232a.PNG)

<h3> 2) 프로젝트 시연
 
 <h4> @회원가입 페이지<h4> 
  -형식에 맞지 않거나 중복 값 입력 시 알림창이 뜨며 가입이 되지 않습니다.<br>
  -비밀번호가 일치하지 않을 시 알림창과 함께 비밀번호가 초기화 됩니다.
 
![회원가입](https://user-images.githubusercontent.com/58322576/77389278-191d4900-6dd6-11ea-8872-56e2aa8d2c7d.PNG)
 
 <h4> @메인 페이지 - 트레일러<h4> 
  -화면 클릭시 재생이 되며, 영상 보러가기 클릭 시 해당 리뷰 페이지로 이동합니다.
 
![메인트레일러](https://user-images.githubusercontent.com/58322576/77389289-2803fb80-6dd6-11ea-8315-0d4259a0352b.PNG)
![메인트레일러 재생](https://user-images.githubusercontent.com/58322576/77389314-3520ea80-6dd6-11ea-8613-3f30cc17c2ac.PNG)
 
 <h4> @메인 페이지 - 슬라이더<h4> 
  -슬라이더 형태로 양옆으로 움직이며, 화면 크기에 따라 사진 개수와 검색창의 길이가 반응합니다.
 
![메인 슬라이더 ](https://user-images.githubusercontent.com/58322576/77453776-09841b80-6e3b-11ea-96ff-79392e17ba40.PNG)
![반응형 합친거](https://user-images.githubusercontent.com/58322576/77453822-186ace00-6e3b-11ea-8309-b1e9b392c233.png)

 <h4> @메인 페이지 - 정렬<h4> 
  -원하는 항목으로 정렬이 가능합니다. 가능한 항목에는 영화, 드라마, 좋아요순, 조회수순이 있습니다.
 
![정렬하기1](https://user-images.githubusercontent.com/58322576/77453884-2fa9bb80-6e3b-11ea-97db-8d9396404fd1.PNG)
 
  <h4> @메인 페이지 - 예외 처리<h4> 
  -회원의 찜한 영상 또는 최근에 본 영상의 기록이 없으면, 해당 슬라이더와 사이드 바의 항목이 다른 것으로 대체 됩니다.
 
![히스토리 합친거](https://user-images.githubusercontent.com/58322576/77454127-7697b100-6e3b-11ea-95bb-6da75c9abbbf.PNG)

  <h4> @메인 페이지 - 구독 리스트<h4> 
  -구독리스트는 7개 이상인 경우 더 보기를 클릭하면 스크롤바와 함께 모든 리스트가 표시 됩니다.
 
![구독리스트 합친거](https://user-images.githubusercontent.com/58322576/77454159-831c0980-6e3b-11ea-8f5c-7103f532c4d3.PNG)

 <h4> @메인 페이지 - 검색<h4>
 -검색 결과가 없을 시 결과 없음을 표시합니다.
 
 
![검색 합친거](https://user-images.githubusercontent.com/58322576/77454276-a777e600-6e3b-11ea-9974-6e94f39f7872.png)


