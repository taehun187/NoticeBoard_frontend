## 📂 프로젝트 구조

### **Frontend**
React 기반의 사용자 인터페이스(UI)입니다.
- **사용된 주요 라이브러리**:
  - Axios: API 호출 및 데이터 통신.
  - React Router: 라우팅 처리.
  - CKEditor: 게시글 작성 시 WYSIWYG 에디터 제공.
  
- **폴더 구조**:
  ```
  frontend/
  ├── public/
  ├── src/
      ├── components/    # UI 컴포넌트
      ├── pages/         # 주요 페이지 (게시글 리스트, 작성 등)
      ├── utils/         # Axios 설정 및 유틸리티 함수
      └── App.js         # 메인 엔트리 포인트
  ```


How to start?
=

### `npm install`

node package manager(npm)을 통해서 node.js에서 사용하는 모듈들을설치합니다.\
현재 프로젝트의 package.json 파일을 참고하여 의존성 모듈을  일괄적으로 설치합니다.

### `npm install -save react-scripts`

> 'react-scripts' is not an internal or external command, an executable program, or a batch file <br>
> 'react-scripts'은(는) 내부 또는 외부 명령, 실행할 수 있는 프로그램, 또는 배치 파일이 아닙니다

'react-scripts' 오류가 발생할 때 실행하는 명령어입니다.\
또한 package.json 파일을 살펴보고 react-scripts 명령어가 실행하는 버전을 확인해주세요.


### `npm start`

앱을 개발 모드로 실행합니다.\
[http://localhost:3000](http://localhost:3000)을 열어 브라우저에서 볼 수 있습니다.\
코드를 변경하면 페이지가 다시 로드되며, 콘솔에서 오류를 확인할 수도 있습니다.
