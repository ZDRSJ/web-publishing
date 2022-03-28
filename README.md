# 🎀 web-publishing & design

## ⚙️ Stack & Tool used
    - html & css & javascript
    - visual studio code, procreate

📂 Directory Structure
---

🗂 homefront

ㄴ 🗂 contact

ㄴ 🗂 css

    ㄴ 🗳 styles.css

ㄴ 🗂 image

ㄴ 🗳 contact.html

ㄴ 🗳 dashboard.html

ㄴ 🗳 feedback.html

ㄴ 🗳 index.html

ㄴ 🗳 map.html

ㄴ 🗳 predict.html

ㄴ 🗳 result.html


## 📍 세부 설명
### 1. main page
  1. 메뉴 바에 맞게 각각 html 제작 후 `<a>`태그로 링크(총 5개의 메뉴바)
  2. 아래는 프로젝트 목적에 맞게 아파트 전경 이미지를 `img` 태그로 삽입 및 `width` 속성을 퍼센트 단위인 90%로 지정하여, 이미지의 너비를 화면의 크기에 맞게 반응하도록 제작
### 2. map page
  1. 팀원이 python을 이용하여 구현한 map을 html로 변환한 파일 첨부
  2. 마우스 스크롤을 위해 양옆에 map에  `style="margin-left:15px; margin-right:15px;”` css를 적용하였으나, 왼쪽만 적용됨(오른쪽 안됨 - 보완사항)
### 3. dashboard page
### 4. predict page
  1. `js`를 이용하여 `<select>` 콤보 박스 선택에 따라 다음 `<select>` 콤보 박스 영향 부여(구 선택 → 동 선택)
  2. `<form>` 태그, `<input type=”sumbit">` 를 사용하여, 사용자 입력값 전체를 서버로 제출(django에서 사용할 수 있도록 `id` 부여)
  3. `<select>` 콤보박스 크기 동일하게 수정 및 화살표 이미지 추가
### 5. contact page
  1. [구글](https://fonts.google.com/), [눈누](https://noonnu.cc/) 등 사이트를 활용하여 저작권에 침해받지 않는 폰트 추가
  2. 팀원 및 디자이너 소개 : 개인 프로필 사진 포토샵 작업 & 메뉴바와 마찬가지로 팀원별 page를 개별 html로 제작 & 각 인원 클릭 시 해당하는 사람은 안 보이게 처리
  3. sns, 연락처, 메일 등 연결
      1. `mailto`, `tel` 등의 속성을 사용하여 `<a>`태그 활용 & 사이즈 동일하게 직접 아이콘 png 파일 제작
      2. 연결된 페이지 클릭 시, `target="_blank”` 를 사용하여 새로운 창이 열리도록 설정
  4. `@media screen and (max-width: 855px)` 를 활용하여 반응형 웹페이지 제작 : 855px을 기준으로 사진 및 폰트 크기 수정
  5. 웹사이트 타이틀 이름에 맞게 수정 : `<title>`
### 6. feedback page
  1. 프로젝트 개요 및 소개 포토샵 작업하여 이미지로 추가
  2. [Disqus](https://disqus.com/)를 사용하여 댓글 기능 구현
### 7. result page : 머신러닝 예측 결과 보여주는 페이지
  1. 예측값과 사용자가 설정한 값 시각화 되도록 {}로 표시하여 백엔드로 넘김
### 8. 공통
  1. 페비콘 적용 : `rel="shortcut icon”` 속성 활용
### 9. 느낀 점 & 보완
  1. css 파일을 page 별로 나누어 적용해 보지 못하고 하나의 파일에서 모든 css 코드를 작성 보완 필요
  2. 조금 더 옵셔널 한 기능을 구현해 보지 못한 아쉬움(로그인, bgm, 댓글 및 별점 / 자바스크립트)
