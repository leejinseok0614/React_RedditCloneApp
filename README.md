# Reddit Clone App

Reddit 스타일 커뮤니티 서비스를 구현하기 위한 full-stack 학습 프로젝트입니다.  
현재 repository는 Express/TypeScript 기반 API 서버와 PostgreSQL 개발 환경을 중심으로 구성되어 있습니다.

## 주요 기능

- 사용자 인증 API 구조
- 게시글, 댓글, 커뮤니티, 투표 domain entity 설계
- TypeORM 기반 데이터 모델링
- PostgreSQL Docker 개발 환경
- Express route 기반 API 구성

## 기술 스택

- Node.js
- TypeScript
- Express
- TypeORM
- PostgreSQL
- Docker Compose

## 프로젝트 구조

```text
server/
  src/
    entities/     # User, Post, Comment, Vote, Sub
    routes/       # auth route
    utils/        # common helpers
    data-source.ts
    server.ts

docker-compose.yaml
```

## 실행

```bash
docker compose up -d

cd server
npm install
npm run dev
```

## 학습 포인트

- TypeScript 기반 Express 서버 구성
- TypeORM entity 관계 설계
- PostgreSQL을 Docker로 띄우는 개발 환경 구성
- 커뮤니티 서비스에서 필요한 domain 모델링 연습
