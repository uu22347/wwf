# WWF 북극곰 보호 캠페인 랜딩페이지
* 모바일 ~ 데스크탑까지 반응형 설계작업
*26/03/03 `index.html` 1행 완성(반응형)
*26/03/04 `index.html` 2행 완성(모바일 기준)
## POINT
### 2행 퀴즈 영역 input 디자인
* `<input type="radio">`
* `<input type="checkbox">`
* `<option><select>`
* 위 선택, 목록 태그는 CSS디자인 불가능
### radio, checkbox 디자인 방법
1. radio, checkbox와 형제관계 태그 준비 (ex) label,span 등
2. 1번 형제태그에  background-image로 radio, checkbox를 대신할 이미지 적용
3. `input:checked + 배경이미지가 들어간 형제태그 {}` 선택자 준비
4. 위 3번 선택자에 선택됐을 때 변경될 배경이미지 재연결
5. 1번 태그 선택자에 `display:none` 적용으로 기존 input 숨기기
### option, select 디자인 방법
* select 대신 div 태그 사용해서 디자인하기(호랑가시나무 객실선택 참고)
* option 대신 button 또는 a 태그 사용해서 디자인하기