1. node 프로젝트(application, library) 만들기
    1) 프로젝트 생성: 디렉토리 만들기
        ```
        $ mkdir ex 01
        ```
    2) 프로젝트 이동
        ```
        $ cd ex01
        ```
    3) 프로젝트 초기화: 프로젝트 매니페스트 파일(package.json) 생성
        ```
        $ npm init -y
        ```

2. 패키지
    1) 완전한 어플리케이션(babel, webpack, nodemon, Lint, ...)
    2) 프로젝트에서 사용하는 라이브러리 모듈(react, react-dom, ...)

3. 의존성
    1) 개발하는 프로젝트에서 설치하는 패키지 
    2) 일반 의존성: 개발하고 있는 프로젝트가 런타임 중 사용하는 패키지
    3) 개발 의존성: 개발할 때 필요한 도움이 되는 패키지로 빌드와 배포에는 포함되지 않음

4. 패키지 설치
    1) 전역 설치
    2) 지역 설치

=== 실습: 설치 ===
```
$ npm i ejs             [지역, 일반]
$ npm i -D nodemon      [지역, 개발]
$ npm i -D -g gulp      [전역, 개발]
```

=== 실습: 삭제 ===
```
$ npm un ejs            [지역]
$ npm un nodemon        [지역]
$ npm un -g gulp        [전역]
```

5. Modules