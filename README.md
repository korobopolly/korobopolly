# Korobopolly

> 백엔드를 중심으로, 프런트와 자동화·도구 만들기를 두루 즐기는 개발자입니다.

귀찮은 일을 코드로 줄이고, 학습한 내용을 글과 템플릿으로 정리하는 데 관심이 많습니다.
Java / Spring Boot · React · Python · Shell 을 주로 쓰며, AI 도구(Claude Code)를 적극 활용해 작업 흐름을 다듬는 것을 좋아합니다.

- Blog : <https://korobopolly.github.io>
- 주력 스택 : Java 17 · Spring Boot · React · PostgreSQL · Python
- 관심 분야 : 백엔드 아키텍처 · 자동화 · 개발 생산성 · AI 도구

---

## Tech Stack

**Backend**  Java · Spring Boot · Spring JDBC · Flyway · HikariCP
**Frontend** React 19 · Vite · React Router
**Database** PostgreSQL
**Tooling**  Python · Bash · GitHub Actions · Docker · PyInstaller · Hugo
**AI / Workflow** Claude Code · OMC(oh-my-claudecode) 플러그인

---

## Projects

실험·학습·실무 자동화를 목적으로 만든 프로젝트들입니다.

### 풀스택 / 백엔드

| 프로젝트 | 설명 | Stack |
| --- | --- | --- |
| **[SpringTemplate_BE](https://github.com/korobopolly/SpringTemplate_BE)** | 게시판 도메인 기반 백엔드 학습/재사용 템플릿. 순수 JDBC(`NamedParameterJdbcTemplate`) + Flyway 마이그레이션 + Testcontainers 통합 테스트 조합. | Spring Boot 4 · Java 17 · PostgreSQL · Flyway |
| **[SpringTemplate_FE](https://github.com/korobopolly/SpringTemplate_FE)** | `SpringTemplate_BE` 와 짝을 이루는 게시판 SPA. `/api` 를 백엔드로 프록시해 CRUD 화면 제공. | React 19 · Vite 8 · React Router 7 |

### 자동화 / 생산성 도구

| 프로젝트 | 설명 | Stack |
| --- | --- | --- |
| **[Git2Sheet](https://github.com/korobopolly/Git2Sheet)** | GitLab(또는 로컬 git) 커밋 이력을 수집해 주간업무보고서 엑셀을 만들고 이메일로 발송. GitHub Actions로 매주 금요일 자동 실행. | Python · GitHub Actions · openpyxl · SMTP |
| **[fclean (file_remover)](https://github.com/korobopolly/fclean)** | 날짜·크기·패턴·중복 기준으로 파일을 정리하는 CLI. 드라이런·휴지통 이동·시스템 파일 보호 같은 안전장치 우선 설계. WSL 9P 자동 감지로 멀티스레드 스캔 성능 보호. | Python · Click · xxhash · YAML |
| **[FilterKey](https://github.com/korobopolly/filterKey)** | Windows 필터키(접근성 기능) — Accept Delay / Repeat delay / Repeat rate — 를 GUI 로 조작하고 프리셋 저장. ctypes 로 Win32 API 직접 호출. | Python · Tkinter · Win32 API · PyInstaller |
| **[HashCompute](https://github.com/korobopolly/HashCompute)** | 5천만 건 규모 파일 정합성 검사를 메모리(HashMap) 대신 디스크 기반 sort merge-join 으로 처리하기 위한 셸 스크립트 + 통합 설계. | Bash · `sort` / `join` · md5sum/sha256sum |

### 데스크톱 / 비전

| 프로젝트 | 설명 | Stack |
| --- | --- | --- |
| **[Chess Vision (chess_helper)](https://github.com/korobopolly/chess_helper)** | 화면의 체스 보드를 캡처·인식해 FEN 으로 변환하고 Stockfish 로 최선의 수를 추천하는 도구. 핫키 기반 분석 모드 지원. | Python · OpenCV · mss · Stockfish |

### 콘텐츠

| 프로젝트 | 설명 | Stack |
| --- | --- | --- |
| **[korobopolly.github.io](https://github.com/korobopolly/korobopolly.github.io)** ([live](https://korobopolly.github.io)) | Hugo 기반 기술 블로그. Java · Spring Boot · React · Claude Code · OMC 플러그인 · 네트워크 · 보안 · DB · Git · Docker 등 실전 시리즈를 연재 중. `main` 푸시 시 GitHub Actions 로 자동 배포. | Hugo · GitHub Pages · GitHub Actions |

---

## What I'm into

- **자동화 우선** — 매주 반복되는 업무 보고서 같은 일은 가능한 한 git 이력에서 자동 생성하도록 만듭니다.
- **안전장치 있는 CLI** — 파괴적인 작업(파일 정리 등)에는 드라이런·휴지통 이동 같은 안전장치를 기본값으로 둡니다.
- **풀스택 템플릿** — 새 프로젝트 시작 비용을 줄이려고 BE/FE 짝으로 동작하는 학습용 템플릿을 정리해 둡니다.
- **AI 도구 활용** — Claude Code 와 OMC 플러그인 워크플로우를 실전 작업에 녹여서, 그 경험을 블로그로 공유합니다.

---

## Contact

- Blog : <https://korobopolly.github.io>
- Email : ofitsolution.management@gmail.com
