# Supabase_study

> Supabase 기초부터 RLS·Storage·pgvector까지, 개념 정리와 SQL 실습을 쌓아가는 개인 학습 저장소

![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Status](https://img.shields.io/badge/status-studying-yellow)

특정 프로젝트와 별개로, 개념 정리 + SQL 실습 + 작은 예제를 꾸준히 쌓아갑니다.

## 목표
- PostgreSQL 기반 테이블 설계와 SQL을 손에 익힌다
- Supabase의 핵심 기능(Database, Auth, RLS, Storage, API, Edge Functions)을 직접 써본다
- 최종적으로 Next.js + Supabase로 작은 풀스택 앱을 하나 완성한다
- 여유가 되면 pgvector로 RAG까지 확장한다

## 학습 로드맵

| 단계 | 폴더 | 주제 | 상태 |
|---|---|---|---|
| 0 | `00_setup` | 계정·프로젝트 생성, 대시보드 둘러보기 | ⬜ |
| 1 | `01_database-basics` | 테이블·컬럼·타입·PK/FK | ⬜ |
| 2 | `02_table-design` | ERD, 1:N / N:M 관계, 정규화 | ⬜ |
| 3 | `03_sql-crud` | SELECT / INSERT / UPDATE / DELETE / JOIN / GROUP BY | ⬜ |
| 4 | `04_auth` | 회원가입·로그인, `auth.users` | ⬜ |
| 5 | `05_rls` | Row Level Security, policy 작성 | ⬜ |
| 6 | `06_storage` | 파일 업로드, 버킷, 용량·형식 제한 | ⬜ |
| 7 | `07_client-api` | supabase-js로 CRUD, 자동 생성 REST API | ⬜ |
| 8 | `08_edge-functions` | 서버리스 함수, 트리거·웹훅 | ⬜ |
| 9 | `09_pgvector-rag` | 임베딩 저장, 벡터 검색, RAG | ⬜ |
| 10 | `10_mini-project` | Next.js + Supabase 미니 앱 | ⬜ |

상태: ⬜ 시작 전 · 🟨 진행 중 · ✅ 완료

## 폴더 구조
```
Supabase_study/
├── README.md
├── resources.md          # 참고 자료 모음
├── logs/                 # 날짜별 공부 기록 (TIL)
│   └── _template.md
├── 00_setup/
├── 01_database-basics/
├── 02_table-design/
├── 03_sql-crud/
├── 04_auth/
├── 05_rls/
├── 06_storage/
├── 07_client-api/
├── 08_edge-functions/
├── 09_pgvector-rag/
└── 10_mini-project/
```

각 폴더에는 `notes.md`(개념 정리)와, 필요하면 `*.sql` 실습 파일을 둡니다.

## 공부 방식
1. 단계 폴더의 `notes.md`에 있는 체크리스트를 따라간다
2. 실습한 SQL은 그대로 `.sql` 파일로 남긴다
3. 그날 배운 것은 `logs/YYYY-MM-DD.md`에 짧게 기록한다
4. 단계가 끝나면 README 표의 상태를 ✅로 바꾸고 커밋한다

## 커밋 규칙
- `docs: 01 테이블 타입 정리`
- `feat: 03 JOIN 실습 쿼리 추가`
- `log: 2026-10-11 TIL`
