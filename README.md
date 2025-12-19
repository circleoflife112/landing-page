# landing-page

랜딩페이지 반응형 구현

## 느낀점 (수확)

## 구현 포인트

display : flex 를 적극 활용해 반응형 페이지에 용이함

## 구현 과정

### 모바일 화면 구성

### 미디어 쿼리 (media query) - 3단계 화면 구성

자연스러운 반응형을 위해 3단계로 구성
`@media` 자체에 `:root` 속성 (ex 컨테이너 요소의 공통 `padding`값) 을 지정 - 일관성 있는 레이아웃 완성
화면 크기에 따른 `font-size` 변화나 `flex-direction` 위주의 작업

## 에러 해결

1. 모바일 화면 fixed nav : position: absolute , top: 100% > position: fixed 로 수정
2. section container 배경 문제 : 자체에 1280px 을 부여할 경우 background color까지 1280px 에 맞춰지는 현상
