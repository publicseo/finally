# Finally

<p>파이널 프로젝트에서는 학사관리시스템을 만들어보았습니다.</p>
<p>제가 맡은 부분은 교직원관리 페이지로 학생 관리, 교수 관리, 자유게시판을 중점적으로 만들었습니다</p>
<br/>
<br/>
<br/>
<h3>처음에는 저희가 짠 erd 구성입니다. </h3>
<div>
  <img src="https://user-images.githubusercontent.com/54519603/75852062-799c1480-5e2e-11ea-8169-4525aefd5cd6.PNG">
</div>
<br/>
<br/>
<p>위에 erd 중에 제가 사용했던 테이블입니다.</p>
<div>
  <img src="https://user-images.githubusercontent.com/54519603/75855345-66d90e00-5e35-11ea-926f-c9a01792cb3c.PNG">
</div>
<br/>
<br/>
<p>여기는 제가 controller에서 사용한 service들을 간추려 보았습니다. <br/>
  라이브러리를 사용한것은 주소, 이메일 보내기, 엑셀포이정도가 있습니다.</p>
<div>
  <img src="https://user-images.githubusercontent.com/54519603/75855686-25952e00-5e36-11ea-9f13-48a7c3338371.jpg">
</div>
<div>
  <img src="https://user-images.githubusercontent.com/54519603/75855690-275ef180-5e36-11ea-89f4-0856dd180297.jpg">
</div>
<br/>
<br/>
<p>학생 게시판은 Jquery + ajax  를 이용하여 게시판을 만들어 보았습니다.<br/>
등록에서는 엑셀을 통하여 학생목록을 전체 추가할수 있으며 학생사진을 단체로 올릴수 있습니다.<br/>
학생 이메일로 학생 아이디와 비밀번호가 보내지게 만들어봤습니다. 물론 엑셀로 전체 올렸을때에도 보내집니다 </p>
<h3>학생 등록</h3>
<div>
  <img src="https://user-images.githubusercontent.com/54519603/75856134-0cd94800-5e37-11ea-9a88-227bbd7227fa.PNG">
</div>
<h3>학생 정보 </h3> 
<div>
  <img src="https://user-images.githubusercontent.com/54519603/75856139-0ea30b80-5e37-11ea-86ad-95aa345063bc.PNG">
</div>
<h3>학생 정보 변경</h3>
<div>
  <img src="https://user-images.githubusercontent.com/54519603/75856136-0e0a7500-5e37-11ea-8493-f00d9b734114.PNG">
</div>
<br/>
<br/>
<p>교수 게시판은 vue + ajax 를 이용하여 게시판을 만들어보았습니다<br/>
교수 등록은 학생등록과 마찬가지로 교수이메일로 교수 아이디, 비밀번호가<br/>
  보내지게 만들었습니다 </p>
<h3>교수 등록</h3>
<div>
  <img src="https://user-images.githubusercontent.com/54519603/75856128-0ba81b00-5e37-11ea-8b7f-81d594aa467c.PNG">
</div>
<h3>교수 정보 </h3>
<div>
  <img src="https://user-images.githubusercontent.com/54519603/75856130-0c40b180-5e37-11ea-8210-51db552ce49f.PNG">
</div>
<h3>교수 정보 업데이트</h3>
<div>
  <img src="https://user-images.githubusercontent.com/54519603/75856126-0a76ee00-5e37-11ea-8e07-087b6572d924.PNG">
</div>
<br/>
<br/>

<p>강의 신청은 교수가 강의 개설을 보내오면 그에 대한 자료를 조회하고 수락/ 거부를 누를수 있게 해놓았습니다.<br/>
<h3>강의 신청 목록</h3>
<div>
  <img src="https://user-images.githubusercontent.com/54519603/75856124-0945c100-5e37-11ea-9f5f-13d35d6c8559.PNG">
</div>
<br/>
<br/>
<p>자유게시판에서는 학생, 교수, 교직원 전체가 사용할수 있게 만들어져있으며 <br/> 
   교직원은 전체게시글에 접근과 삭제를 할수 있으며 교수, 교직원은 글쓰기, 자기글 업데이트/삭제가 가능합니다 <br/>
   글은 모두 익명으로 올릴수 있고 댓글을 달고 할수 있습니다.
 </p>

<h3>자유게시판</h3>
<div>
  <img src="https://user-images.githubusercontent.com/54519603/75856131-0cd94800-5e37-11ea-8eff-9dc716fbf84c.PNG">
</div>
