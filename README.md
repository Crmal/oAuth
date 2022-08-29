# oAuth study

oAuth 연습용 개인 레포입니다

## How to start development server

```shell
yarn start:dev
```

## Commit conventions

- feat : 기능 추가
- refactor : 리팩토링, 기능은 그대로 두고 코드를 수정
- fix : 버그 수정
- style : 코드에 지장 안 가는 스타일적 코드 수정
- setting : eslint 변경, 라이브러리 설치 등
- docs : 주석 추가삭제, readme 변경 등

## .env

```
DB_NAME=                          // MySQL DB 이름
DB_PASSWORD=                      // MySQL Password
```

## Pre-installation

DB 선행 설치가 필요합니다

```
MySQL
```

[Docker Compose](https://docs.docker.com/compose/)를 이용하여 쉽게 실행할 수 있습니다.

실행 전 .env파일이 설정되어 있어야 합니다.

```shell
docker-compose up -d
```
