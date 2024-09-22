# 😊안녕하세요!<br>  화면 프로젝트로 대학교 커뮤니티를 만들어보았습니다!
## 🔧 Stack

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

## 🖥️ Main Image
![20240922_224736_1](https://github.com/user-attachments/assets/d95fc031-c194-4cf9-ba91-8cd22198993f)

## 👨‍💻 Role & Contribution
- 이번 화면  프로젝트에서 조장을 맡았습니다.
- 발표에서 PPT 제작을 맡았습니다.
- 제작 페이지<br>1. 메인 페이지 제작 : 카카오 지도 API 구현, 이미지 자동 슬라이드 구현<br>2. 상세 페이지 (시간표, 학점계산기, 쪽지함) 제작 : 테이블 태그를 이용한 시간표 등록 방식 구현

## 👨‍👩‍👧‍👦 Develop
- 개발기간<br>
2024.08.19 - 2024.08.26

- 팀원<br>
차민주, 박건희, 엄기빈, 최수경

## 📖 Description  
3주 동안 배운 HTML, CSS, JS를 활용하여 화면 프로젝트를 진행하였습니다. 
저희 팀은 프로젝트의 주제로 '대학교 커뮤니티'를 정했고 '에브리타임'을 참고하여 만들어보았습니다. 기본적으로 로그인, 게시판을 구현하였고 주제와 맞는 상세 페이지로 강의평가, 시간표 등등  특색있는 페이지도 제작하였습니다. 
1. 로그인 관련 페이지에서 정규표현식을 이용한 유효성 검사 구현
2. 대학교명, 학과, 강의 정보가 담긴 JSON 데이터를 가져와 페이지에서 응용
3. 커뮤니티에서 가장 큰 비중을 차지하는 게시판을 로컬 스토리지를 이용해 구현
4. 주제에 맞는 사이트로 강의평가, 시간표 제작 페이지 등 

## ⭐ Main Feature
### 회원 가입, 내 정보 확인
- 정규표현식을 이용한 검증 과정을 넣었습니다.
- 회원가입이 승인되면 로컬 스토리지에 작성한 정보가 저장됩니다. 
- 회원 가입을 통해 로컬 스토리지에 저장된 정보를 가져와 내 정보 보기 페이지에서 출력 되도록 구현 했습니다.
  
### 로그인, 계정 찾기 페이지
![20240922_224736_7](https://github.com/user-attachments/assets/ce2c08f2-d350-46ac-a70c-9ba35b5ddc28)
- 회원 가입 페이지를 통해 로컬 스토리지에 가입된 사용자의 정보를 저장, 저장된 정보에서 아이디와 패스워드가 일치하는지 <br>
 확인하여 로그인 승인/거부할 수 있습니다. 
- 계정 찾기 페이지에서도 사용자가 입력한 정보가 로컬 스토리지에 저장된 email value에 있는지 확인합니다. <br>
있다면 입력한 email에 같이 저장된 아이디를 제공하고, 없다면 안내 메시지를 출력합니다.

### 공지사항, 자유게시판
![20240922_224736_2](https://github.com/user-attachments/assets/3810b9c7-4140-4998-8981-8b56a214d3f6)
- 게시판의 CRUD (Create Read Update Delete) 구현했습니다.
- 게시글 작성 시 권한 확인 후 작성을 허용/금지 할 수 있습니다. 자유 게시판의 경우 로그인 여부를 확인해 로그아웃 상태라면 작성이 불가합니다. <br>
더 나아가 공지사항 - 게시판은 관리자 권한을 가진 사용자만 작성할 수 있습니다.
- 게시글 작성 시 제목과 내용중 하나라도 공백일 경우 오류 메시지와 함께 로컬 스토리지에 저장되지 않습니다. 

### 강의 평가, 시험 후기
![20240922_224736_4](https://github.com/user-attachments/assets/f4c9b7e8-04e8-4f73-b0c1-b070e74d5795)
- JSON 데이터를 활용하여 검색 기능을 구현했습니다. (대학교 강의명 데이터)
- 검색 후 강의를 선택해 강의 평가를 작성할 수 있습니다. 
- 클릭으로 별점, 평가 항목을 선택할 수 있습니다. 
- 사용자가 입력한 텍스트와 클릭한 정보를 로컬스토리지에 저장하고 강의 평가 목록에서 출력할 수 있습니다.

### 시간표, 학점 계산기
![20240922_224736_3](https://github.com/user-attachments/assets/52445463-a11e-4756-b724-9e6581758dc5)
![20240922_224736_5](https://github.com/user-attachments/assets/2209ecc8-6b8a-4737-b397-f3b000122790)
![20240922_224736_6](https://github.com/user-attachments/assets/ff951b9f-548b-439c-8f22-e9d9b093b34d)
- 시간표 : 사용자가 입력한 정보를 저장해 시간표 테이블에 블록으로 채웁니다. <br>
강의 시간을 선택하면 선택한 시간을 바탕으로 블록의 높이와 표현될 위치를 선정해 출력합니다. 중복 또는 잘못된 시간을 입력하면 저장되지 않습니다. 
- 학점 계산기 : 사용자가 입력한 정보(학점, 성적)를 바탕으로 각 학기의 평균 학점을 계산해 꺾은선 그래프에 표현합니다. <br>
중간 박스를 이용해 학기별로 사용자가 입력한 과목명, 점수, 전공여부 등을 확인할 수 있습니다. 
- 쪽지함 : 기본틀에서 사용자가 선택한 쪽지를 자세히 볼 수 있습니다. 모달창을 구현하여 쪽지를 보내는 것 처럼 표현해보았습니다.

### 메인페이지
![20240922_224736_1](https://github.com/user-attachments/assets/d95fc031-c194-4cf9-ba91-8cd22198993f)
- 로그인/ 비로그인/ 관리자권한 로그인의 세 가지 상태를 나누어 그에 맞는 화면을 출력합니다.
- 메인화면에 들어갈 사진이 자동으로 슬라이드되도록 구현했습니다.
- 각각의 상세 페이지의 미리보기 버전을 만들어 구성했습니다.


## 📂 Project Structure
📦prontProject<br>
 ┣ 📂css<br>
 ┃ ┣ 📜detail.css<br>
 ┃ ┣ 📜fboard.css<br>
 ┃ ┣ 📜idPw.css<br>
 ┃ ┣ 📜join.css<br>
 ┃ ┣ 📜login.css<br>
 ┃ ┣ 📜modify.css<br>
 ┃ ┣ 📜myinfo.css<br>
 ┃ ┣ 📜nboard.css<br>
 ┃ ┣ 📜reset.css<br>
 ┃ ┣ 📜style.css<br>
 ┃ ┣ 📜write.css<br>
 ┃ ┗ 📜강의평가.css<br>
 ┣ 📂font<br>
 ┃ ┗ 📜NotoSansKR-VariableFont_wght.ttf<br>
 ┣ 📂html<br>
 ┃ ┣ 📜free_board.html<br>
 ┃ ┣ 📜free_detail.html<br>
 ┃ ┣ 📜free_detail_sample.html<br>
 ┃ ┣ 📜free_modify.html<br>
 ┃ ┣ 📜free_write.html<br>
 ┃ ┣ 📜idPw.html<br>
 ┃ ┣ 📜join.html<br>
 ┃ ┣ 📜login.html<br>
 ┃ ┣ 📜main.html<br>
 ┃ ┣ 📜myinfo.html<br>
 ┃ ┣ 📜notice_board.html<br>
 ┃ ┣ 📜notice_detail.html<br>
 ┃ ┣ 📜notice_detail_sample.html<br>
 ┃ ┣ 📜notice_modify.html<br>
 ┃ ┣ 📜notice_write.html<br>
 ┃ ┣ 📜강의시험목록.html<br>
 ┃ ┣ 📜강의시험입력.html<br>
 ┃ ┣ 📜강의평가개요.html<br>
 ┃ ┣ 📜강의평가메인.html<br>
 ┃ ┣ 📜강의평가목록.html<br>
 ┃ ┣ 📜강의평가입력.html<br>
 ┃ ┣ 📜메인.html<br>
 ┃ ┣ 📜시간표.html<br>
 ┃ ┣ 📜쪽지.html<br>
 ┃ ┗ 📜학점계산기.html<br>
 ┣ 📂img<br>
 ┣ 📂js<br>
 ┃ ┣ 📜free_board.js<br>
 ┃ ┣ 📜free_detail.js<br>
 ┃ ┣ 📜free_modify.js<br>
 ┃ ┣ 📜free_write.js<br>
 ┃ ┣ 📜idPw.js<br>
 ┃ ┣ 📜join.js<br>
 ┃ ┣ 📜login.js<br>
 ┃ ┣ 📜myinfo.js<br>
 ┃ ┣ 📜notice_board.js<br>
 ┃ ┣ 📜notice_detail.js<br>
 ┃ ┣ 📜notice_modify.js<br>
 ┃ ┣ 📜notice_write.js<br>
 ┃ ┗ 📜style.js<br>
 ┗ 📂json<br>
 ┃ ┗ 📜전국대학공개강의서비스정보_KOCW_표준데이터.json<br>
   
## ❤️ Thank you!
그동안 수업을 들으며 받았던 퍼즐 조각들을 모아서 하나의 그림을 완성한 것 같아 뿌듯합니다. 추가하고 싶은 기능, 더 깔끔하게 수정하고 싶은 코드들이 눈에 아른거리네요. 첫 팀 프로젝트 결과인 만큼 더 소중한 것 같습니다. 
조장이라는 역할이 처음에는 부담되었지만, 프로젝트의 방향성과 정해진 기간안에 완성하는 것에 집중하며 도전해보았습니다. 좋은 경험이 되었던 것 같습니다.

처음 계획할 때는 시간표와 학점 계산기 페이지에 로컬 스토리지를 이용해 저장된 데이터를 다루고 싶었습니다. 하지만 코드에서 변수를 선언할 때 값이 초기화 되는 문제를 해결하지 못해 기능을 빼게 되었습니다. 좀 더 고민했다면 해결할 수 있었겠지만 하루에 한 페이지는 꼭 완성해야 기간을 맞출 수 있을 것 같아 포기했던게 많이 아쉽습니다. 이 부분을 다시 확인하고 고치고 싶네요.

## 📌 Link  
더 자세한 설명은 제 개인 블로그에서 이어집니다. <br>
https://blog.naver.com/momonocha
