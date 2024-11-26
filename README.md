# ECR_Project


<h3>프로젝트 명 <br> 
    : ECR (Ecape Room) </h3>

<h3>프로젝트 주제</h3>
    : 

<h3>프로젝트 소개</h3>
<ul>
  <li>방탈출 테마 예약 및 관리를 위한 포털 사이트 구축</li>
  <li>사용자 편의를 최우선으로 고려한 방탈출 통합 포털 플랫폼 구현</li>
  <li>방탈출 정보를 한 화면에서 확인할 수 있는 통합 정보 시스템 구현</li>
  <li>오픈소스 및 API를 활용해 직관적이고 접근성 높은 웹 서비스 구성</li>
  <li>한눈에 확인하고 쉽게 예약할 수 있는 직관적인 통합 예약 시스템 제공</li>
</ul>









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
<li>Fullpage.js 인스턴스가 적절히 해제되지 않으면 메모리 누수가 발생하거나 예상치 못한 스크롤 동작이 발생</li>
<br><br>

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Camera%20with%20Flash.png" alt="Camera with Flash" width="25" height="25" /><b> 반응형 이슈</b>
<br>
<li>카드 크기와 레이아웃이 작은 화면에서 겹치거나 UI가 깨지는 문제가 발생</li>
<br><br>

</ul>











<h2>테마리스트</h2>
<img src="https://github.com/user-attachments/assets/bf493f1a-bc63-4cf3-8483-c24829b84d0c"  width="800px" height="500px">

<ul>
 <h3> 📍 기능구현(사용자/관리자)</h3>
<br>
<b> 👨‍🦱사용자 </b>
<br>
  
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
<li>필터 및 검색 조건에 맞는 데이터가 없을 경우 공백 화면이 표시가 안남</li>

---------------

  <b> 🧓 관리자 </b>
  <br>
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
  <br>: 테마 이름, 카페 이름, 가격, 소요시간, 테마 설명, 주소, 인원수, 난이도, 장르, 이미지</li>
  <li>카카오 지도 API를 통한 주소 검색 및 좌표 변환 후 저장</li>
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
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Camera%20with%20Flash.png" alt="Camera with Flash" width="25" height="25" /><b>권한 문제</b>
<br>
<li>관리자가 아닌 사용자가 URL을 통해 등록/수정 페이지에 접근</li>

<hr>
<h3><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Light%20Bulb.png" alt="Light Bulb" width="25" height="25" /> 공통 개발 이슈</h3>
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Camera%20with%20Flash.png" alt="Camera with Flash" width="25" height="25" /><b> 카카오 지도 API 의존성 </b>
<br>
<li>카카오 지도 API 호출이 실패하거나 로드되지 않을 경우 주소 검색 및 좌표 변환 기능이 동작하지 않았음</li>
<br>
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Camera%20with%20Flash.png" alt="Camera with Flash" width="25" height="25" /><b> 평점 계산 오류 </b>
<br>
<li>/api/tema/{temaNo}/avgRating API 호출 시 평점이 표시되지 않음</li>
<br><br>
</ul>









<ul>
 <h3> 📍 기능구현(사용자/관리자)</h3>
<br>

<b> 👨‍🦱사용자 </b>
<br>
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
  <br>
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
</ul>
