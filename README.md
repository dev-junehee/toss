# 토스(toss) 메인 홈페이지 클론 코딩
## 실제 사이트와 배포한 과제물
[토스 홈페이지](https://toss.im/)<br />
[과제물 실제 배포 페이지](https://funny-vacherin-5977e2.netlify.app/)<br />
## 사용한 기술 스택
HTML : `<header>` , `<section>` , `<footer>` 등<br />
CSS : flex, position, hover 등<br />
JS : scroll animation, 이미지 floating 효과<br />
## 작업 내용
- 상단 헤더 내 메인 메뉴 hover 효과
- 마우스 아래로 스크롤 시, 상단 헤더 border-bottom 생성
- 메인 페이지 배경 이미지 상단 gradient 효과
- 메인 페이지 하단 버튼 floating 효과 및 특정 위치 연결
- 각 섹션별 스크롤 애니메이션 구현 (delay 사용하여 시간차 효과)
- 대부분의 링크는 실제 페이지로 연결되도록 함<br />

## 아쉬운 점
- 메인 페이지 하단 버튼 클릭 시, 이동하는 위치가 뷰포트(모니터?) 크기에 따라 변경되는 점
- 메인 페이지 내 어플리케이션 버튼 정렬이 틀어진 점
- 스크롤 위치에 따라 이미지 opacity 값을 조절하지 못한 점
- BEM 방법론 사용하지 못한 점
- 토스 전용 폰트를 사용하지 못한 점