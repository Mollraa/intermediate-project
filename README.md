# intermediate-project<br>
<p>포트폴리오 바로가기 링크</><br>
https://www.daeguoracle.com/homeGallery/hpGalleryDetail?tableNm=hp_pofol&boardType=&crsId=0&instId=0&menuCtgr=&bbsId=190#
<h2>여성, 남성 의류 쇼핑몰 입니다.</h2><br>
프로젝트 핵심 기술(설계 주안점)<br>
VCM형식의 CRUD기능응용 및 API 활용<br>
구현도구 - jquery, mybatis, apache tomcat, oracle DB, eclipse, bootstrap, maven, java
<hr><br>
<h3>구현기능</h3>
<h4>메인 페이지</h4>
상단 메뉴에서 로고, BEST, SALE, TOP, BOTTOM, OUTER, BOARD, 로그인 및 회원가입, 장바구니를 볼 수 있다.<br>
로고는 클릭 시 메인 페이지로, 각각의 메뉴는 해당 페이지로 이동할 수 있다.<br>
OUR PRODUCT에서는 쇼핑몰에서 판매하는 모든 상품을 확인할 수 있으며, 대분류를 클릭할 시 필터링이 가능하다.<br>
REVIEWS에서는 가장 조회수가 많은 3개의 리뷰가 노출된다.<br>
하단 메뉴에서 로고, MAIN, BLOG, BEST, SALE, MYPAGE, Q&A, NOTICE, REVIEW, 각 SNS 사이트 아이콘, 쿠폰 입력창을 볼 수 있다.<br>
MYPAGE는 로그인 여부를 판단하여 로그인이 되어있다면 마이페이지로 이동하고, 아니라면 회원가입 페이지로 유도하는 창을 띄운다.<br>
쿠폰 입력창에서는 특정 쿠폰 번호를 입력할 경우, 포인트 획득이 가능하다.<br>
<br>
<h4>회원가입</h4>
회원가입 시 아이디(ajax를 이용하여 DB에서 확인)와 비밀번호의 중복여부를 체크한다.<br>
모든 필수 항목을 양식에 맞게 입력한 후 이용약관에 동의하면 회원가입이 완료된다.<br>
<br>
<h4>로그인</h4>
입력된 정보의 값을 받아 DB에서 확인 후 성공시 세션에 정보를 담아둔다.<br>
<br>
<h4>My Page</h4>
로그인이 되어있을 경우에만 상단 메뉴에 My Page를 표시한다.<br>
My Page 하단 메뉴는 구매내역, 정보조회, 회원탈퇴로 구성되어 있다.<br>
정보조회에서는 자신의 상세한 정보를 조회할 수 있으며, 이를 수정할 수 있다.<br>
구매내역에서는 구매한 상품에 대한 정보를 조회할 수 있으며, 배송상태가 '배송완료'일 경우 상품수령 버튼이 활성화되며 구매 확정이 가능해진다.<br>

<h4>정보조회, 구매내역</h4> - 리스트로 볼 수 있다.<br>

<h4>상품 페이지</h4>
메인 메뉴를 통하여 상품의 대분류(TOP, BOTTOM, OUTER) 혹은 이벤트(BEST, SALE) 별로 상품의 목록을 확인할 수 있으며,<br>
이는 목록 옆의 Categories에서도 동일한 기능이 동작한다.<br>
목록에서 상품의 이미지를 클릭하면 상품의 상세정보 페이지로 넘어가게 되며, 해당 상품의 상세 정보 및 추천 상품의 목록을 볼 수 있다.<br>
로그인이 되어있고 해당 상품의 재고가 남아있는 경우, 해당 상품의 사이즈 및 개수를 지정하여 ADD TO CART 버튼을 클릭하면 장바구니에 담을 수 있다.<br>
<br>
<h4>장바구니</h4>
장바구니 상품 개수 변경<br>
상품 개수를 마우스로 클릭하거나 키보드로 직접 입력하여 변경이 가능하고, 금액의 변동을 총 금액에서 확인할 수 있다.<br>
<br>
<h4>장바구니 비우기</h4>
각 상품의 오른쪽 끝 삭제 버튼으로 장바구니에서 개별 상품을 제거 할 수 있으며, 장바구니 상단의 전체 삭제 버튼으로 장바구니를 비울 수 있다.<br>
<br>
<h4>장바구니 상품 주문</h4>
장바구니 오른쪽 하단 전체 상품 주문 버튼을 클릭하면 장바구니에 있는 모든 상품의 금액이 합산되고,<br>
체크 박스 선택 후 선택 상품 주문 버튼을 클릭하면 선택된 상품의 금액만 합산되어 상품 가격에 표시된다.<br>
상품 가격이 5만원 이상일 때는 무료배송, 5만원 미만일 때는 배송비가 적용되어 최종 결제 금액에 반영된다.<br>
<br>
<h4>포인트 사용</h4>
포인트 탭에서 회원이 보유한 포인트를 확인할 수 있으며, 보유한 포인트 내에서 사용할 포인트를 입력하면 최종 결제 금액에서 입력한 포인트 만큼 금액이 차감된다.
<br>
<h4>게시판 페이지</h4>
게시글을 작성하면 업로드한 파일을 기준으로 사진이 출력되며, 게시글을 클릭하면 조회수가 카운트된다.<br>



<h4>공지</h4>
이용자의 Author 값을 확인하여 관리자만 글의 등록, 수정 및 삭제가 가능하다.<br>
<br>
<h4>리뷰</h4>
이용자의 ID 값을 확인하여 본인의 글만 수정 및 삭제가 가능하다.<br>
<br>
<h4>Q&A</h4>
이용자의 ID 값을 확인하여 본인의 글만 조회, 작성, 수정 및 삭제가 가능하다. 글 제목을 질문 종류에 맞게 선택할 수 있다.<br>
<br>
<h4>댓글</h4>
리뷰 및 Q&A 게시판에서만 작성할 수 있으며, 본인의 댓글만 삭제할 수 있다.<br>
비회원은 공지 및 리뷰 게시판의 조회만 할 수 있고, 관리자는 모든 글을 조회할 수 있고 모든 댓글을 삭제할 수 있다.<br>
관리자가 댓글을 작성할 경우, 작성자명이 파란색으로 표시된다.<br>
<br>
<h4>관리자 페이지</h4>
공통적으로 페이징, 통합 키워드 검색, 해당 칼럼기준 오름/내림차순 정렬이 가능하다.<br>

<h4>메인</h4>
월매출 / 연매출 / 목표 매출 달성률 / 공지사항 갯수를 보여주고 공지등록으로 이동할 수 있다.<br>
<br>
<h4>고객관리</h4>
등록된 모든고객을 고객 목록에서 확인할 수 있으며, 목록 상단의 고객 ID 검색을 통하여 특정 고객을 검색 할 수 있다.<br>
목록에서 고객을 클릭하면 회원의 상세 정보 페이지로 이동하며 해당 고객의 상세 정보를 확인 할 수 있다.<br>
<br>
<h4>상품관리</h4>
등록된 모든 상품을 상품 목록에서 확인할 수 있으며, 목록 위 상품 추가 버튼을 클릭하면 상품 등록 페이지로 이동하며 상품을 등록 할 수 있다.<br>
목록에서 상품을 클릭하면 상품의 상세 정보 페이지로 이동하며 이 곳에서 해당 상품 정보의 수정 및 삭제를 할 수 있다.<br>
<br>
<h4>배송관리</h4>
고객 및 상품 통계 검색을 통해 입력한 고객 및 상품 기준의 판매 내역과 배송 상태를 조회할 수 있다.<br>
판매 번호를 기준으로 상세 정보를 열람하고 삭제할 수 있으며, 배송상태 열에서 배송상태를 변경할 수 있다.<br>
<br>
<h4>통계</h4>
쇼핑몰의 판매 내역을 목록 형태로 확인할 수 있고,<br>
고객 및 상품 통계 검색으로 각 기준의 판매 내역을  볼 수 있으며 총액 버튼으로 현재 해당 테이블의 총액을 볼 수 있다.<br>
<h4>통계 차트</h4>
월매출 및 연매출을 차트로 나타내며, 판매 상품의 각 비율을 도넛형 그래프로 볼 수 있다.
