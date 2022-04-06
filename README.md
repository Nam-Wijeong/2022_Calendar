# 🗓2022년 Calendar 만들기
## table 태그를 익히기 위한 달력 만들기 실습입니다.

### 📍설명
- table의 컨테이너 요소인 제목(caption)과 행(tr), 열(col) 그리고 셀(td)과 셀의 제목(th) 역할을 하는 여러 요소들을 사용하여 2022년 12개월 달력을 제작했습니다.
- 일요일은 각 행(tr)의 셀 제목(th)과 셀 내용(td)의 첫번째에 위치해 있으며, th:nth-child(1), td:nth-child(1) 를 사용하여 빨간색으로 지정했습니다.
- 생일과 크리스마스에는 class 를 지정하여 hover 이벤트를 지정했습니다.(transform : scale, transition)
- hover 이벤트가 지정된 항목은 a 태그를 사용하여 관련 페이지로(새창) 이동하도록 했습니다.

### 📍사용한 기술
- HTML
- CSS
