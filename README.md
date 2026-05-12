# OnlineJudge Front End
[![vue](https://img.shields.io/badge/vue-2.5.13-blue.svg?style=flat-square)](https://github.com/vuejs/vue)
[![vuex](https://img.shields.io/badge/vuex-3.0.1-blue.svg?style=flat-square)](https://vuex.vuejs.org/)
[![echarts](https://img.shields.io/badge/echarts-3.8.3-blue.svg?style=flat-square)](https://github.com/ecomfe/echarts)
[![iview](https://img.shields.io/badge/iview-2.8.0-blue.svg?style=flat-square)](https://github.com/iview/iview)
[![element-ui](https://img.shields.io/badge/element-2.0.9-blue.svg?style=flat-square)](https://github.com/ElemeFE/element)
[![Build Status](https://travis-ci.org/QingdaoU/OnlineJudgeFE.svg?branch=master)](https://travis-ci.org/QingdaoU/OnlineJudgeFE)

>### OnlineJudge를 위해 제작된 다중 페이지 앱입니다. [데모 보기](https://qduoj.com)

## 주요 기능

+ 번들 크기가 최적화된 Webpack3 다중 페이지
+ 사용하기 쉬운 simditor 및 깔끔한 codemirror 에디터
+ 뛰어난 차트 및 데이터 시각화 (echarts)
+ 사용자 친화적인 인터페이스 및 조작
+ 꽤 아름답습니다 :)

## 시작하기

먼저 Node.js v8.12.0 버전을 설치해 주세요.

### Linux

```bash
npm install
# we use webpack DllReference to decrease the build time,
# this command only needs execute once unless you upgrade the package in build/webpack.dll.conf.js
export NODE_ENV=development 
npm run build:dll

# the dev-server will set proxy table to your backend
export TARGET=http://Your-backend

# serve with hot reload at localhost:8080
npm run dev
```
### Windows

```bash
npm install
# we use webpack DllReference to decrease the build time,
# this command only needs execute once unless you upgrade the package in build/webpack.dll.conf.js
set NODE_ENV=development 
npm run build:dll

# the dev-server will set proxy table to your backend
set TARGET=http://Your-backend

# serve with hot reload at localhost:8080
npm run dev
```

## 스크린샷

[여기서 확인하세요.](https://github.com/QingdaoU/OnlineJudge)

## 지원하는 브라우저

최신 모던 브라우저 및 Internet Explorer 10 이상.

## 라이선스

[MIT](http://opensource.org/licenses/MIT)
