## 코로나 세계 현황판 만들기

최종 프로젝트 폴더입니다

## 자바스크립트 프로젝트에 타입스크립트 적용하기

0. JSDoc로 타입스크립트처럼 JS 변경하기
   - 코드가 많고 코드를 잘 모르는 경우 TS 적용의 대안이 될 수 있다.
1. 타입스크립트의 기본 환경 구성
   - [x] NPM 초기화
   ```
   npm init
   ```
   - [x] 타입스크립트 라이브러리 설치
   ```
   npm i typescript
   ```
   - [x] 타입스크립트 설정 파일 생성 및 기본 값 추가
         `tsconfig.json`
   - [x] 자바스크립트 파일을 타입스크립트로 확장자 변경하기
         `js -> ts`
   - [x] tsc 명령어로 타입스크립트 컴파일 하기
2. 명시적인 `any` 선언하기
   - `tsconfig.json`파일에 `noImplicitAny` 값을 `true`로 추가

## 참고 자료

- [존스 홉킨스 코로나 현황](https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6)
- [Postman API](https://documenter.getpostman.com/view/10808728/SzS8rjbc?version=latest#27454960-ea1c-4b91-a0b6-0468bb4e6712)
- [Type Vue without Typescript](https://blog.usejournal.com/type-vue-without-typescript-b2b49210f0b)
