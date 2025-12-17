# ☕ Hacking Review Cafe

**Hacking Review Cafe** 는 보안 공부·CTF·웹해킹 실습을 좋아하는 사람들이  
함께 모여 코드 리뷰하고, 공격·방어 과정을 정리해서 공유하는 스터디 카페입니다.

> “공부하자 윤종아”

## 🎯 목표

- **웹/시스템/네트워크 보안 전반 실력 향상**
- CTF 문제 풀이 & Write-up 공유 문화 만들기
- 실제 서비스 수준의 **보안 실습용 프로젝트** 운영
- 코드 리뷰와 리팩터링을 통한 **클린 코드/안전한 코드** 연습

## 📂 주요 리포지토리

- **FE** – Hacking Review Cafe 프론트엔드
  - Tech: React, TypeScript, Vite, Tailwind CSS
  - Features: 로그인/회원가입, 데일리 공부 게시판, CTF Write-up 게시판, 댓글·대댓글, 좋아요
- **BE** – PHP 기반 API 서버 (예정)
  - Tech: PHP, MySQL, Docker
  - Features: 인증, 게시판 CRUD, 권한 체크, 로깅
- **ctf-writeups** – CTF Write-up 모음
  - 대회별/문제별로 폴더 나눠서 정리
- **lab-env** – 해킹·방어 실습용 환경
  - Docker로 구성된 Web/DB/Logging/Monitoring 환경

## 🧰 기술 스택

### Frontend

- React + TypeScript + Vite
- React Router
- Tailwind CSS
- ESLint / Prettier (정적분석툴;코드 버그 / JS 코드의 스타일;[줄 바꿈, 띄어쓰기, 따옴표, 공백]을 중점적으로 수정해줌]

### Backend (계획/또는 진행 중인 것)

- PHP (Laravel / Slim / Pure PHP 등 택 1)
- REST API / JWT 또는 세션 기반 인증
- MySQL / MariaDB
- Docker, docker-compose

### Dev & Collaboration

- GitHub Issues / Projects
- GitHub Actions (CI, Lint, Test)
- Conventional Commits (권장)  
- Code Review 필수
