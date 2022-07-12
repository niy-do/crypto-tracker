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
  https://flatuicolors.com

### 샘플 프로젝트 생성 시 사용한 API 목록 및 사이트

1. 코인관련 API 정보 사이트  
   https://api.coinpaprika.com/
2. 코인 이미지 Link 사이트  
   https://coinicons-api.vercel.app/

## 강의와 다르게 변경된 사항

1. React-Router-Dom 버전 (6.3.0 사용)

- Router 5버전과 6버전 간 차이 점 확인 사이트

  - https://blog.woolta.com/categories/1/posts/211
  - https://velog.io/@peacesong/react-router-v6
  - https://unho94.tistory.com/55

- Link 사용 시 state 전달하는 방식이 바뀜.  
  \* 6버전 미만 : `<Link to={{pathname:uri, state:{propName:value}}} ></Link>`  
  \* 6버전 이상 : `<Link to=uri state={{propName:value}} ></Link>`

- URL match에 사용하는 hook 바뀜.  
  \* v5 : useRouteMatch() => 매치되면 Object 반환, 아닌 경우 null 반환  
  \* v6 : useMatch() => true/false
