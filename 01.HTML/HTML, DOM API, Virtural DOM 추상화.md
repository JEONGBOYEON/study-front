## HTML

## DOM API
- 정적인 웹페이지를 동적으로 변경하기 위한 방법
- 메모리 상에 존재하는 DOM 을 변경하는 것
- 결국은 브라우저에서 다룰 HTML 문서를 파싱하여 "문서의 구성요소들을 **객체로 구조화**하여 나타낸 것"입니다.

## Virtual DOM
- DOM을 추상화한 가상의 객체

### 어떤 문제를 해결하기 위한 기술인가?
- DOM을 반복적으로 직접 조작하면 그 만큼 브라우저가 **렌더링을 자주**하게 되고, 그 만큼 PC 자원을 많이 소모하게되는 문제를 해결하기 위한 기술
- DOM 조작에 의한 렌더링이 비효율적인 문제
- SPA(Single Page Application)특징으로 DOM 복잡도 증가에 따른 최적화 및 유지 보수가 더 어려워지는 문제

## 추상화

https://jeong-pro.tistory.com/210
