# Build Tool

## 1. Module Bundler

![image](https://user-images.githubusercontent.com/100753621/163428174-ec16eec8-e300-4c30-aef7-cb14f79211ad.png)  
_이미지 출처 : https://joshua1988.github.io/webpack-guide/webpack/what-is-webpack.html#%EC%9B%B9%ED%8C%A9%EC%97%90%EC%84%9C%EC%9D%98-%EB%AA%A8%EB%93%88_  

<br />

### 1-1) Module Bundler 란?

- 웹 애플리케이션을 구성하는 자원(HTML, CSS, JavaScript, Image 등)을 모두 각각의 모듈로 보고 이를 조합해서 하나의 결과물을 만드는 도구

<br />

### 1-2) Module Bundling 이란?

- 웹 애플리케이션을 구성하는 몇 십, 몇 백개의 자원들을 하나의 파일로 병합 및 압축해주는 동작

<br />

### 1-3) 대표적인 Module Bundler

![image](https://user-images.githubusercontent.com/100753621/163428330-ccb5b3e3-4c23-4576-86de-8898606af289.png)  
_이미지 출처 : https://www.peterkimzz.com/extremely-faster-esbuild-than-webpack/_

- [parcel](https://parceljs.org/)
- [rollup](https://rollupjs.org/guide/en/)
- [webpack](https://webpack.js.org/)
- [esbuild](https://esbuild.github.io/)

<br />
<br />

## 2. Linter and Formatter

### 2-1) Linter 란?

- 소스 코드를 분석하여 프로그램 오류, 버그, 스타일 오류, 의심스러운 구조체에 표시를 달아놓기 이ㅜ한 도구
- 코딩 컨벤션과 에러를 체크해주는 프로그램
- [ESLint](https://eslint.org/)
  - 자바스크립트 코드에서 발견된 문제 패턴을 식별하기 위한 정적 코드 분석 도구
  - 자바스크립트 코드가 EcmaScript 재단에서 명시한 Specification에 부합하는지 검사해주는 도구
  - 코드 품질과 코딩 스타일 문제를 모두 다룸
  - _정적 분석 : 프로그램을 실행시키지 않고 코드 분석 수행_

<br />

### 2-2) Formatter 란?

- 개발자가 작성한 코드를 정해진 스타일을 따르도록 변환해주는 도구
- [Prettier](https://prettier.io/)
  - 파일을 저장할때마다, 코드를 사용자가 원하는 형식으로 모양을 예쁘게 만들어주는 Node.js 패키지
  - VSCode 확장 기능, npm 기능을 이용하여 설치 가능

<br />
<br />

## 3. 그 외 궁금한 것들

|                | create-react-app |     vite     |
| :------------- | :--------------: | :----------: |
| module bundler |   webpack 사용   | esbuild 사용 |

|       |          정의          |
| :---- | :--------------------: |
| build |      모듈 번들링       |
| start | 모듈 번들링 + 서버실행 |
