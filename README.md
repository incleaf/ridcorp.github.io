# RIDI Corporation

www.ridicorp.com 도메인으로 접속할 수 있는 리디 주식회사의 홈페이지입니다.

[Jekyll](https://jekyllrb.com/)을 이용한 정적 블로그 생성 툴을 이용하여 관리하고 있으며, GitHub 연동과 관련한 자세한 문서는 [이곳](https://help.github.com/articles/using-jekyll-with-pages/)을 참고하세요.

## How to Build


### 1. 스타일시트 빌드하기

```shell
$ npm install # 빌드에 필요한 모듈들을 설치합니다.
$ npm run watch # less를 수정하면 자동으로 CSS로 빌드되도록 합니다.
```

### 2. Jekyll 설치하기

간단한 명령어로 설치할 수 있습니다. 상세한 내용은 [Jekyll 웹사이트](https://jekyllrb.com/)를 참고하세요.

```
$ (sudo) gem install bundler
$ bundle install
```

### 3. 로컬에서 확인하기

Bundler를 사용하여 웹사이트를 테스트할 수 있습니다.
```
$ bundle exec jekyll serve
```
