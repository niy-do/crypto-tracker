# 프로젝트 개요

Nomad Coder의 강의 React마스터 클래스 강의 실습 프로젝트

## 프로젝트 설치 모듈

1. styled-components  
   `npm i styled-components`  
   `npm i --save-dev @types/styled-components`
2. React Router Dom  
   `npm i react-router-dom`  
   `npm i --save-dev @types/react-router-dom`
   - React-Router-Dom v6 부터 Switch를 지원하지 않게됨.
     (강의 상은 버전 5.3.0 기준임.)
     https://velog.io/@kcdoggo/Switch-is-not-exported-from-react-router-dom-%EC%97%90%EB%9F%AC

### #Style 설정

- styled-components의 createGlobalStyle를 활용하여 전역 css 적용 처리.
- npm 모듈 github의 css를 사용하여 초기화 처리
  https://www.npmjs.com/package/styled-reset

- 폰트 검색 및 삽입 코드 사이트
  https://fonts.google.com

- 색상코드 팔레트 사이트
  https://flatuicolors.com/
