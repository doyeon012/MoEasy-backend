# MoEasy Backend

모임을 더 쉽게 도와주는 웹 서비스의 백엔드입니다.

## 기술 스택

| 분류 | 기술 |
|:---|:---|
| Framework | NestJS |
| Language | TypeScript |
| Database | (프로젝트 내 설정에 따름) |
| Infra | Docker |

## 주요 기능

- 모임(Meeting) 생성 및 관리
- 활동(Activity) 관리
- 회원(Member) 관리 및 인증
- 카테고리 / 지역 기반 모임 탐색
- 알림(Notification) 기능
- Discord 연동

## 실행 방법

```bash
npm install
npm run start:dev
```

Docker:
```bash
docker-compose up -d
```
