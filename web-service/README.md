# Web-Service
## FrontEnd
### Framework
- React, Vue.js 등
- 비교적 쉽게 개발 가능한 React 활용
  - React : web framework (javascript library)
  - facebook에서 개발 (2013년 5월 오픈소스화)
  - features
    - 단방향 dataflow
    - component 기반 구조 (재사용성)
    - Virtual Dom (document object model)
    - props and state
    - JSX (마크업 언어 확장된 javascript 문법)
- npm; node pakage manager
  - *** dependency issue가 너무 많다 (오래된 소스일 수록)
  - yarn을 통해서 문제해결
  - ```
    $ npm install -g yarn
    $ yarn install
    $ yarn start
    ```
  - PORT 설정
  - ```
    $ PORT=% yarn start
    ```
### 테스트 오픈 소스
- 유명한 material-ui 활용
  - https://github.com/creativetimofficial/material-dashboard-react
  - 주로 dashboard 개발이 대부분이라고 생각
- 테스트 url
  - http://211.109.168.54:9213/admin/dashboard
### 개발 일지
- 2021.6.30 : react example code test
- 2021.7.1 : react dashboard ui 탐색
- 2021.7.2 : npm dependency issue
- 2021.7.3 : yarn을 활용한 웹서비스 동작
- 2021.7.5 : 코드 구조 분석
- 2021.7.6 : 간단한 테스트 (text 변경, 이미지 변경, layout 변경 등)


---
## BackEnd
### Framework
- Python에서는 대표적으로 Flask, Django
- 프로토 타입 개발용으로는 Flask가 좋다 (코딩의 효율성)

- example



---
## Docker-compose
- Frontend, Backend 각각의 Docker image로 부터 하나의 웹 서비스 실행
