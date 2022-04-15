# Package Manager(패키지 관리자)

## 1. 라이브러리 ≥ 패키지 ≥ 모듈

**라이브러리 ≥ 패키지 ≥ 모듈**

|            | 정의                               |
| :--------- | :--------------------------------- |
| 라이브러리 | 패키지와 모듈의 집합               |
| 패키지     | 관련 있는 모듈의 집합              |
| 모듈       | 변수, 함수, 클래스를 모아놓은 팡리 |

<br/>
<br/>

## 2. Package Manager

### 2-1) Package Manager란?

- 프로젝트가 의존하고 있는 패키지를 효과적으로 설치, 갱신, 삭제할 수 있도록 도와주는 관리 도구

<br/>

### 2-2) JavaScript Package Manager란?

- Node.js 실행 환경에서 돌아가며, package.json 이라는 파일에 프로젝트가 의존하고 있는 패키지 목록을 명시
- package는 프로젝트의 node_modules 디렉토리에 저장됨.
- npm, yarn

<br/>

### 2-3) npm(node package manager) vs yarn(yet another resource negotiator)

- 차이점

  |      | npm                                              | yarn                                                |
  | :--- | :----------------------------------------------- | :-------------------------------------------------- |
  | 속도 | 패키지를 한번에 하나씩 순차적으로 설치           | 여러 패키지를 동시에 가져오고 설치하도록 최적화     |
  | 보안 | 자동으로 패키지에 포함된 다른 패키지 코드를 실행 | yarn.lock 또는 package.json 파일에 있는 파일만 설치 |

- 명령어

  | 명령어             | npm                                 | yarn                          |
  | :----------------- | :---------------------------------- | :---------------------------- |
  | dependencies 설치  | npm install                         | yarn                          |
  | 패키지 설치        | npm install [패키지명]              | yarn add [패키지명]           |
  | dev 패키지 설치    | npm install --save-dev [패키지명]   | yarn add --dev [패키지명]     |
  | 글로벌 패키지 설치 | npm install --global [패키지명]     | yarn global add [패키지명]    |
  | 패키지 제거        | npm uninstall [패키지명]            | yarn remove [패키지명]        |
  | dev 패키지 제거    | npm uninstall --save-dev [패키지명] | yarn remove [패키지명]        |
  | 글로벌 패키지 제거 | npm uninstall --global [패키지명]   | yarn global remove [패키지명] |
  | 업데이트           | npm update                          | yarn upgrade                  |
  | 패키지 업데이트    | npm update [패키지명]               | yarn upgrade [패키지명]       |
