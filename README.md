# Carousel
슬라이더 만들기

# ui
* Container
  * ArrowButton
    * RiArrowDropLeftLine
  * CarouselList
    * CarouselListItem
      * img
  * ArrowButton
    * RiArrowDropRightLine

* Nav
  * NavItem
    * NavButton

# 로직
1. activeIndex로 현재 화면에 표시해야 하는 img번호 관리.

2. 오른쪽 버튼 클릭시 (activeIndex+1)%슬라이더 갯수. %슬라이더 갯수를 해주는 이유는 맨마지막일때 만약 8개의 갯수가 있을때 (7+1)%8 을 하면 나머지가 0이라 맨 앞으로 간다.

3. 왼쪽 버튼 클릭시 (activeIndex-1+슬라이더 갯수)%슬라이더 갯수. 슬라이더가 맨앞일때 (0-1+8)%8 을 하면 맨 마지막으로 간다.

4. 3초 마다 슬라이더 이동 구현.

5. 마우스가 슬라이더 위에 있을때 3초마다 이동 정지.

6. nav버튼으로 원하는 슬라이더 이동.

# 알게된점
## flex
https://velog.io/@toyo8/flex-%EB%9E%80
## Transform
https://velog.io/@toyo8/Transform%EC%9D%B4%EB%9E%80
## 디자인 패턴
https://velog.io/@toyo8/%ED%95%A9%EC%84%B1-%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8%EB%A1%9C-%EC%9E%AC%EC%82%AC%EC%9A%A9%EC%84%B1-%EA%B7%B9%EB%8C%80%ED%99%94%ED%95%98%EA%B8%B0
