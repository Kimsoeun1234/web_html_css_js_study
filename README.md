<h1>반응형 웹디자인 & 웹퍼블리셔 양성과정 버전기록</h1>
<p>EX) 날짜 - 제목 - 요약</p>
<h2>230213 시작 - HTML</h2>
<p>h1~h6, p, br, inline, block</p>
<p>h1~h3은 검색키워드로 활용가능하다. h4~h6 꼭 필요한 경우만 이용하거나 권장안함</p>
<p>block과 inline태그는 의미에 맞게 외부/내부 구조로 구성해서 사용해야 한다.(의미 중첩되지 않도록)</p>
<hr>
<h2>230214 - HTML - 문서태그+내비게이션 개념</h2>
<p>피그마 기본 툴, 단축키 </p>
<p>내비게이션 개념 - GNB ( global navigation bar) LNB(local navigation bar) SNB(side navigation bar) fnb(footer navigation bar) </p>
<p><em>em</em>, <strong>strong</strong>, <blockquote>blockquote</blockquote>, q, <address>address</address>, <code>code</code>, <hr>hr</hr>, <del>del</del>, <s>s</s>, <sub>sub</sub>, <sup>sup</sup> </p>
<blockquote> cite="https://webty.tistory.com/85"</blockquote>
<hr>
<h2>23.02.15 - HTML - 문단태그</h2>
<u1>
 <li>ul,ol,li 순서있는 목록 없는 목록 구분 확실히 해야함.</li>
 <li>li의 <em>형제태그</em>는 li만 올 수 있으니 나머지 태그는 그 자식, 자손태그에 삽입해야 한다</li>
</u1>
<dl>
 <dt><em>dl,dt,dd</em>제목과 내용 구조로 된 목록에 정의형 목록 태그를 사용합니다.</dt>
  <dd>
   <ul>
    <li>정의형 목록은 dl, dt, dd 3가지 태그로 이루어져 있습니다.</li>
    <li>dl은 정의형 제목과 내용을 묶는 그룹입니다.</li>
    <li>dt는 dl안 자식으로 배치되며 제목을 의미합니다.</li>
    <li>dt는 dd 기준 항상 먼저 시작합니다.</li>
    <li>dd는 dl안 자식으로 배치되며 dt의 다음 형제 요소로 배치되거나 기존 dd의 형제로도 배치될 수 있습니다.</li>
    <li>정의형 목록의 내용을 의미합니다.</li>
   </ul>
  <dt>
</dl>
<hr>
<div class="study">
 <h2>23.02.16 - HTML - 시맨틱태그, 그룹태그</h2>
 <dl>
   <dt>그룹 div</dt>
   <dd>2개 이상의 인라인 or 블록 요소를 묶어주는 그룹 태그</dd>
   <dd> class를 이용해 이름을 지정해 둘 것 div class="title" </dd>
 </dl>
 </div>
<hr>
<h2>23.02.17 이미지, 비디오, 링크 넣는 방법</h2>
<dl>
 <dt>비디오 작성하는 방법</dt>
 <dd>[video] src="동영상경로"[/video]</dd>
 <dt>비디오를 작성하는 방법2</dt>
 <dd> <video>
 <source src="동영상경로" type="동영상타입1">
    	<source src="동영상경로" type="동영상타입2">
  </video> </dd>
  <hr>
  <h2>0220</h2>
  표제작
  <hr>
  <h2>23.02.21-HTML-form</h2>
  <form action="#" method="get">
  <fieldset>
  <legend>form 퀴즈</legend>
  <span>다음 중 label for와 연관된 input 속성은?</span><br>
  <label><input type="radio" name="quiz" value="id">1.id</label><br>
  <label><input type="radio" name="quiz" value="class">2.class</label><br>
  <label><input type="radio" name="quiz" value="name">3.name</label><br>
   <span>다음 중 form 정보 컨트롤 요소 들을 용도에 맞게 그룹으로 묶을 경우 사용하는 태그는? </span><br>
   <lable><input type="radio" name="quiz" value=Fieldset>1.Fieldset</label>
   <lable><input type="radio" name="quiz" value=Fieldset>2.legend</label>
   <lable><input type="radio" name="quiz" value=Fieldset>3.label</label>
  </fieldset>
 </form>
 <hr>
 <h2>23.02.23-css-form</h2>
<dl>
 <dt>css reset</dt>
  <dd>
   <ul>
    <li>reset.css를 제작하여 링크를 html title밑에 넣고 외부스타일시트 각주표시해주기<br>link href="./styles/reset.css" rel="stylesheet" type="text/css"</li>
    <li>선택자 작성연습<br>1. HTML태그 꾸미는 대상 확인<br>2. 위 태그가 가족관계에 속해있는지 확인 (가족관계 중 body, html은 생략가능)</li>
   </ul>
  <dt>
</dl>
 <hr>
 <h2>23.02.24-css-스타일</h2>
<dl>
 <dt>css 스타일 변화</dt>
  <dd>
   <ul>
    <li></li>
    <li></li>
   </ul>
  <dt>
</dl>
<hr>
<h2>23.02.28-css-수열선택자</h2>
