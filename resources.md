# 참고 자료

## 공식
- [Supabase Docs](https://supabase.com/docs) — 가장 정확한 1차 자료
  - Database / Tables
  - Auth
  - Row Level Security
  - Storage
  - Edge Functions
  - AI & Vectors (pgvector)
- Supabase 공식 유튜브 채널 — 기능별 짧은 영상
- [PostgreSQL 공식 문서](https://www.postgresql.org/docs/)

## 영상
- Net Ninja — Supabase Crash Course (영어, 약 1시간, CRUD + RLS 입문)
- 유튜브 한국어 검색어: `수파베이스 강의`, `supabase 입문`, `supabase 바이브코딩`

## 유료 강의 (필요할 때)
- 인프런 — [풀스택 입문] Firebase보다 10배 좋은 Supabase
- 인프런 — Supabase Next 시작하기 (Supabase OAuth, Next.js 14)

## 책
- 「아는 만큼 보이는 백엔드 개발」 — 1장(웹 구조), 2.3(데이터베이스), 4장(DBMS), 5장(API) 위주로 개념 보강
- *Building Production-Grade Web Applications with Supabase* (Packt, 2024) — DB 설계·보안·스토리지 심화

## 키워드 사전
| 키워드 | 한 줄 정리 |
|---|---|
| BaaS | 백엔드를 서비스로 빌려 쓰는 것 |
| PostgreSQL | Supabase가 쓰는 관계형 DB |
| PK / FK | 행을 구분하는 고유값 / 다른 테이블 행을 가리키는 값 |
| ERD | 테이블 관계도 |
| 정규화 | 중복 없이 테이블을 나누는 설계 원칙 |
| RLS | 행 단위 접근 권한 규칙 |
| anon key / service_role key | 공개용 키 / 모든 권한을 가진 서버 전용 키 (절대 노출 금지) |
| Edge Function | Supabase에서 돌리는 서버리스 함수 |
| pgvector | PostgreSQL에서 벡터 검색을 하게 해주는 확장 |
