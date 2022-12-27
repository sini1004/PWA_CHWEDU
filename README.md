## 💻 학원 앱(PWA) 💻

### 📄 프로젝트 소개 📄
퍼블리셔로 재직 중 유지보수하던 사이트 '청운학원=> http://www.chwedu.co.kr/' 는 시간표게시판 페이지 이용률이 가장 높다.<br>
학생들이 시간표 안내를 확인하기 위해 사이에 접속하는 부분이 아쉬웠고, 디자인 부분에서도 부족함을 느껴<br>
리뉴얼과 기능 추가를 통해 좀 더 사용성 있는 사이트로 이용되기 바라는 마음으로 제작하게 되었다.<br>

기존 사이트는 pc와 mobile이 따로 제작되어있어 이 부분을 핸드폰을 많이 사용하는 시대에 맞게 아이콘을 홈 화면에 추가할 수 있고, <br>
설치가 따로 필요없으며, 오프라인상태에서도 사용할 수 있는 PWA로 제작하였다.<br>

'CHWEDU(청운학원)'에서는 출석체크에 많이 사용하는 QR코드 인식시스템을 사용할 수 있으며, 2024년 수능 디데이 날짜를 확인할 수 있고,<br>
앱 접속시 또는 새로고침 시 마다 랜덤하게 수능영단어를 노출시켜 앱 접속 시 영단어 공부까지 할 수 있도록 하였다.<br>
또한 학생들이 하루하루 목표를 설정할 수 있는 TODO 페이지를 구현하였고, 
문제 풀이 시 타이머를 통해 한 문제 또는 한 페이지에 대한 시간을 체크할 수 있는 스톱워치 페이지를 구현하였다. <br>

### 💡 기술 스택 💡
> html5

> css3

> jquery

> javascript
  - Math.random() 메서드를 이용하여 등록된 단어 갯수 내에서 무작위로 단어를 보여줌. 
  - getDate() 메소드로 현재 날짜에 해당하는 숫자를 반환하여 수능 디데이를 보여줌.
