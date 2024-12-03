<h1>📃 공포 방탈출 사용자를 위한 프로젝트<br> </h1>

<h3>1. 제작 기간 <br></h3>
2024.09.02 ~ 2024.09.27


<h3>2. 프로젝트 멤버</h3>

|Name|Position|explanation|
|------|---|---|
|현민환(팀장)|Back||
|박혜연|Back, Front|메인페이지, 테마리스트, 공지사항, UI|
|유병수|Back, Front||
|김광훈|Back||
|김승욱|Back||

<h3> 
3. 프로젝트 소개<br></h3>
<b>: 공포 방탈출 예약과 정보를 효율적으로 관리할 수 있는 통합 서비스</b> <br>
 <br>
<ul>
  <li>방탈출 테마 예약 및 관리를 위한 포털 사이트 구축</li>
  <li>사용자 편의를 최우선으로 고려한 방탈출 통합 포털 플랫폼 구현</li>
  <li>방탈출 정보를 한 화면에서 확인할 수 있는 통합 정보 시스템 구현</li>
  <li>오픈소스 및 API를 활용해 직관적이고 접근성 높은 웹 서비스 구성</li>
  <li>한눈에 확인하고 쉽게 예약할 수 있는 직관적인 통합 예약 시스템 제공</li>
</ul>


<h3> 4. 사용 언어 </h3>
<div>
<img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" alt="Oracle DB">
</div>
<div>
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot">
  <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white" alt="Spring Security">
  <img src="https://img.shields.io/badge/JPA-59666C?style=for-the-badge&logo=jpa&logoColor=white" alt="JPA">
  <img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white" alt="Thymeleaf">
</div>
<div>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS">
</div>
<div>
  <img src="https://img.shields.io/badge/SQL%20Developer-4479A1?style=for-the-badge&logo=oracle&logoColor=white" alt="SQL Developer">
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"> 
</div>


<br><br>

<h2>메인페이지</h2>
  <img src="https://github.com/user-attachments/assets/06a4c399-3a5b-4a43-a844-5b9949aecb0b" width="800px" height="500px">
<ul>
  <br>
  <h3> 📍 기능구현</h3>
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Backhand%20Index%20Pointing%20Right%20Light%20Skin%20Tone.png" alt="Backhand Index Pointing Right Light Skin Tone" width="25" height="25" /> <b>Fullpage.js를 이용한 페이지 섹션화 구현</b>
    <br><br>
  <li>Fullpage.js를 초기화하여 스크롤 기반의 섹션 전환을 구현</li>
  <li>각 섹션은 메인이미지, 테마 카드, 주의사항 등으로 구성</li>

<br><br>
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Backhand%20Index%20Pointing%20Right%20Light%20Skin%20Tone.png" alt="Backhand Index Pointing Right Light Skin Tone" width="25" height="25" /> <b>테마 정보 API 호출 및 정렬</b>
    <br>
  <li>/api/topmenu 경로에서 데이터를 가져와 평점 순으로 정렬한 후 상위 5개의 테마를 렌더링하도록 구현</li>
  <li>React useState와 useEffect를 사용하여 상태 관리 및 API 통신 처리</li>

<br><br>
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Backhand%20Index%20Pointing%20Right%20Light%20Skin%20Tone.png" alt="Backhand Index Pointing Right Light Skin Tone" width="25" height="25" /> <b>스타일링 (CSS)</b>
    <br>
  <li>테마 카드, 주의사항 섹션, 아이콘 등을 포함하여 다크 테마 기반으로 CSS 설계</li>
  <li>GIF 이미지를 배경으로 사용하여 동적인 비주얼 효과 추가</li>
  <li>그라데이션 텍스트와 박스 그림자 효과 적용</li>

<br><br>
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Backhand%20Index%20Pointing%20Right%20Light%20Skin%20Tone.png" alt="Backhand Index Pointing Right Light Skin Tone" width="25" height="25" /> <b>호버 애니메이션 및 반응형 디자인</b>
    <br>
  <li>테마 카드에 마우스 호버 시 확대와 그림자 효과를 통해 사용자 경험 강화</li>
  <li>flexbox를 사용하여 카드와 아이콘의 배치를 반응형으로 설계</li>

--------------------------------------------------------------

<h3><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bell.png" alt="Bell" width="25" height="25" /> 개발 이슈</h3>

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Camera%20with%20Flash.png" alt="Camera with Flash" width="25" height="25" /><b> Fullpage.js 관련 문제</b>
<br>
<li>Fullpage.js 인스턴스가 적절히 해제되지 않으면 메모리 누수가 발생 & 예상치 못한 스크롤 동작이 발생</li>
    🔎 페이지 전환 시 인스턴스를 명확히 해제하는 로직을 추가하여 안정성을 강화
<br><br>

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Camera%20with%20Flash.png" alt="Camera with Flash" width="25" height="25" /><b> 반응형 이슈</b>
<br>
<li>카드 크기와 레이아웃이 작은 화면에서 겹치거나 UI가 깨지는 문제가 발생</li>
    🔎 반응형 디자인을 적용 & CSS 미디어 쿼리를 활용하여 다양한 화면 크기에서도 UI가 안정적으로 표시되도록 수정
<br><br>

</ul>











<h2>테마리스트</h2>
<img src="https://github.com/user-attachments/assets/bf493f1a-bc63-4cf3-8483-c24829b84d0c"  width="800px" height="500px">

<ul>
 <h3> 📍 기능구현(사용자/관리자)</h3>
<br>
<b> 👨‍🦱 사용자 </b>
<br><br>
  
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Backhand%20Index%20Pointing%20Right%20Light%20Skin%20Tone.png" alt="Backhand Index Pointing Right Light Skin Tone" width="25" height="25" /> <b>테마 목록 조회 (temaList.js) & 테마 상세 정보 보기 (detail.js) </b>
    <br><br>
  <li>/api/menu API 호출로 전체 테마를 가져와 필터링 및 검색 기능 제공</li>
  <li>필터 조건: 장르, 지역, 난이도, 인원수</li>
  <li>테마 클릭 시 조회수를 증가시키고 상세 페이지로 이동</li>
  ❌ 로그인 하지 않은 사용자는 예약 불가능
  <br>
<h3><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bell.png" alt="Bell" width="25" height="25" /> 개발 이슈</h3>
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Camera%20with%20Flash.png" alt="Camera with Flash" width="25" height="25" /><b>검색 결과 없음</b>
<br>
<li>필터 및 검색 조건에 맞는 데이터가 없을 경우 공백 화면이 표시되지 않는 문제</li>
    🔎 조건에 맞는 데이터가 없을 때 안내 메시지나 대체 화면이 나타나도록 로직을 추가

---------------

  <b> 🧓 관리자 </b>
  <br><br>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Backhand%20Index%20Pointing%20Right%20Light%20Skin%20Tone.png" alt="Backhand Index Pointing Right Light Skin Tone" width="25" height="25" /> <b>테마 관리 페이지 (temaManagement.js)</b>
    <br>
  <li>/api/menu API 호출로 관리자가 테마 목록을 조회</li>
  <li>테마 삭제 기능 구현(/api/delete/{temaNo})</li>
  <li>삭제 후 목록 재조회 기능</li>
  <br><br>

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Backhand%20Index%20Pointing%20Right%20Light%20Skin%20Tone.png" alt="Backhand Index Pointing Right Light Skin Tone" width="25" height="25" /> <b>테마 수정 기능 (ModifyTema.js)</b>
    <br>
  <li>/api/menu/{temaNo}로 기존 테마 데이터 로드</li>
  <li>카카오 지도 API를 통한 주소 검색 및 좌표 변환</li>
  <li>수정된 데이터를 /api/tema에 PUT 방식으로 전송</li>
  <br><br>

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Backhand%20Index%20Pointing%20Right%20Light%20Skin%20Tone.png" alt="Backhand Index Pointing Right Light Skin Tone" width="25" height="25" /> <b>테마 등록 기능 (insertTema.js)</b>
    <br>
  <li>/api/tema API를 사용해 새로운 테마 등록 가능
  <br>: 테마 이름, 카페 이름, 가격, 소요시간, 테마 설명, 주소, 인원수, 난이도, 장르, 이미지업로드(jpg, png)</li>
  <li>네이버 지도 API를 통한 주소 검색 및 좌표 변환 후 저장</li>
  <li>수정된 데이터를 /api/tema에 PUT 방식으로 전송</li>
  <br><br>


<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Backhand%20Index%20Pointing%20Right%20Light%20Skin%20Tone.png" alt="Backhand Index Pointing Right Light Skin Tone" width="25" height="25" /> <b>테마 상세 페이지 구현 (detail.js)</b>
    <br>
  <li>테마의 세부 정보(이미지, 내용, 가격, 장르, 난이도, 인원수) 표시</li>
  <li>예약 기능: 로그인 상태 확인 후 예약 페이지로 이동</li>
  <li>삭제 후 목록 재조회 기능</li>
  <br><br>

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Backhand%20Index%20Pointing%20Right%20Light%20Skin%20Tone.png" alt="Backhand Index Pointing Right Light Skin Tone" width="25" height="25" /> <b>평균 평점 표시 (avgRating.js)</b>
    <br>
  <li>/api/tema/{temaNo}/avgRating API 호출로 평점 데이터 가져오기</li>
  <li>React StarRatings를 사용해 별점으로 표시</li>
 <br>
 
<h3><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bell.png" alt="Bell" width="25" height="25" /> 개발 이슈</h3>
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Camera%20with%20Flash.png" alt="Camera with Flash" width="25" height="25" /> <b>권한 문제</b>
<br>
<li>관리자가 아닌 사용자가 URL을 통해 등록/수정 페이지에 접근</li>
    🔎 로그인 타입으로 권한 설정
<br><br>
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Camera%20with%20Flash.png" alt="Camera with Flash" width="25" height="25" /><b> 이미지 업로드 </b>
<br>
<li>내부 경로로 저장할 때 발생했던 새로고침 오류</li>
    🔎 외부 경로를 활용하도록 변경하였으며, 이를 통해 자동 새로고침이 정상적으로 동작하도록 개선


<hr>
<h3><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Light%20Bulb.png" alt="Light Bulb" width="25" height="25" /> 공통 개발 이슈</h3>
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Camera%20with%20Flash.png" alt="Camera with Flash" width="25" height="25" /><b> 평점 계산 오류 </b>
<br>
<li>/api/tema/{temaNo}/avgRating API 호출 시 평점이 표시되지 않음</li>
   🔎 평점 계산 로직을 점검
<br><br>
</ul>









<ul>
 <h3> 📍 기능구현(사용자/관리자)</h3>
<br>

<b> 👨‍🦱 사용자 </b>
<br><br>
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Backhand%20Index%20Pointing%20Right%20Light%20Skin%20Tone.png" alt="Backhand Index Pointing Right Light Skin Tone" width="25" height="25" /> <b>공지사항 목록 확인 (Anc_Board.js)</b>
  <li>/board/list/{page}/5 API를 호출하여 페이징된 공지사항 목록을 가져옴</li>
  <li>공지사항 제목, 작성자, 작성일, 조회수 등을 사용자에게 표시</li>
  <li>공지사항 클릭 시 상세 보기 페이지로 이동 가능</li>
  <br><br>

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Backhand%20Index%20Pointing%20Right%20Light%20Skin%20Tone.png" alt="Backhand Index Pointing Right Light Skin Tone" width="25" height="25" /> <b>공지사항 상세 보기 (Anc_DetailForm.js)</b>
  <li>/board/form/{boardNo} API를 통해 특정 공지사항의 세부 정보를 표시</li>
  <li>제목, 작성자, 작성일, 수정일, 내용을 읽기 전용으로 제공</li>
  <br><br>

  <b> 🧓 관리자 </b>
  <br><br>
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Backhand%20Index%20Pointing%20Right%20Light%20Skin%20Tone.png" alt="Backhand Index Pointing Right Light Skin Tone" width="25" height="25" /> <b>공지사항 작성(Anc_List.js) & 수정(Anc_EditForm.js) & 삭제 (Anc_EditForm.js)</b>
  <li>/board/write2 API 호출로 제목과 내용을 입력받아 공지사항 작성 가능</li>
  <li>/board/form/{boardNo} API를 통해 수정할 공지사항 데이터 불러오기</li>
  <li>/board/delete/{boardNo} API 호출로 공지사항 삭제 기능 구현</li>
  
<h3><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bell.png" alt="Bell" width="25" height="25" /> 개발 이슈</h3>
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Camera%20with%20Flash.png" alt="Camera with Flash" width="25" height="25" /><b>권한 문제</b>
<li>테마쪽과 비슷하게, 관리자가 아닌 사용자가 URL 직접 접근을 통해 Anc_List나 Anc_EditForm에 접근할 가능성이 있었음</li>

-----------------------------------------------------

<h3><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Light%20Bulb.png" alt="Light Bulb" width="25" height="25" /> 공통 개발 이슈</h3>
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Camera%20with%20Flash.png" alt="Camera with Flash" width="25" height="25" /><b> 입력값 검증</b>
<br>
<li>공지사항 제목 및 내용의 길이 제한, 입력값 검증이 추가되지 않아 비정상적인 데이터가 저장될 가능성</li>
<br><br>





<h2> <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Beating%20Heart.png" alt="Beating Heart" width="25" height="25" />ECR만의 장점은? </h2>

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Heart%20Hands%20Medium-Light%20Skin%20Tone.png" alt="Heart Hands Medium-Light Skin Tone" width="25" height="25" /> <b>편의성</b>
 <br>
다른 사이트들은 각각 따로 확인해야하는 번거로움이 존재한다면, ECR 웹사이트는 장르, 난이도, 인원수, 가격, 평점, 위치를 한눈에 볼 수 있습니다.

<br>

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Heart%20Hands%20Medium-Light%20Skin%20Tone.png" alt="Heart Hands Medium-Light Skin Tone" width="25" height="25" /> <b>제약성</b>
 <br>
다른 사이트들은 자신들의 체인점만 제공되어 전체를 한눈에 보기 어려운 반면, ECR 웹사이트는 다양한 공포 방탈출게임을 한곳에서 볼 수 있다는 장점이 있습니다.

<br>

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Heart%20Hands%20Medium-Light%20Skin%20Tone.png" alt="Heart Hands Medium-Light Skin Tone" width="25" height="25" /> <b>접근성</b>
 <br>
모든 공포 테마를 직관적으로 구성해 직관적으로 구성해 쉽게 파악할 수있습니다.


<br>
<br>
<h2> <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Collision.png" alt="Collision" width="25" height="25" /> ECR만의 단점은? </h2>
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Rightwards%20Pushing%20Hand%20Light%20Skin%20Tone.png" alt="Rightwards Pushing Hand Light Skin Tone" width="25" height="25" /> <b>타겟 사용자층의 제한</b>

<li>스릴러와 호러를 중심으로 한 한정적인 테마로 구성되어 있어, 공포를 선호하는 사용자들에게 최적화된 플랫폼</li>
<li>공포를 기피하는 사용자들에게는 전혀 접근되지 않음</li>
<br>
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Rightwards%20Pushing%20Hand%20Light%20Skin%20Tone.png" alt="Rightwards Pushing Hand Light Skin Tone" width="25" height="25" /> <b>테마의 다양성 부족</b>
<li>스릴러와 호러에만 초점을 맞추다 보니, 다른 장르(예: 코미디, 미스터리, 판타지)를 원하는 사용자들이 흥미를 느끼지 못할 가능성이 큼</li>

<br>
<br>
<h2> <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Construction.png" alt="Construction" width="25" height="25" /> 보완할 점 </h2>
<li>회원가입 시 SMS 인증 기능 추가</li>
<ul><li>사용자 계정의 안전성을 확보하기 위해 SMS 인증 API를 활용한 기능 도입 필요</li></ul>
<br>
<li>결제 시스템 강화</li>
<ul><li>예약 시 결제 처리를 위해 결제 API를 추가적으로 연동해야 함</li></ul>
<br>
<li>실적 조회 기능 구현</li>
<ul><li>테마별 이용 횟수, 월별 결제 금액, 취소 신청 횟수 등의 통계를 확인할 수 있는 기능 필요</li></ul>
<br>
<li>리뷰 등록 기능 추가</li>
<ul><li>사용자가 예약을 완료한 후 리뷰를 등록할 수 있는 기능 구현 필요</li></ul>
</ul>
