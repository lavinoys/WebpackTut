# WebpackTut
웹팩을 해봅시다.


# npm 설정파일 생성
npm init -y
# webpack 기본 틀 구성
npm i -D webpack webpack-cli
# dir 폴더 생성
mkdir src
# 이동
cd src
# npm빌드
npm run build
# html loader 웹팩 플러그인 설치 -D는 디펜던시 포함 설치
npm i -D html-webpack-plugin html-loader
# 웹팩 테스트 서버 플러그인 설치
npm i -D webpack-dev-server
# 웹팩 테스트 서버 구동
npm run start:dev
# 바벨 설치
npm i -D @babel/core babel-loader @babel/preset-env
# 이미지 파일 읽을 수 있는 플러그인 설치
npm i -D file-loader
# scss, style, css을 읽을 수 있는 플러그인 설치
npm i -D node-sass style-loader css-loader sass-loader mini-css-extract-plugin