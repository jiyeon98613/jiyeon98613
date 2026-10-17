# 김지연

건강보험 청구 업무에서 출발해 데이터 구조와 자동화를 만들고 있습니다.  
2인 프로젝트에서 DB·백엔드·정기 수집 배치 운영을 주로 담당하고 있습니다.

[포트폴리오](https://jiyeon98613.github.io/) · [소개와 담당 범위](https://jiyeon98613.github.io/about/)

## 대표 작업

### 건강보험 청구 시스템

중복 문서, 잘못된 추출값, 새 처방으로 대체된 자료를 구분하고 과거 청구의 근거를 보존하도록 설계했습니다. 환자별 월 관리와 기간별 청구, 업무·계산 근거와 첨부 문서의 역할을 나눴습니다.

[문서 상태·청구 모델·OCR 개선 과정](https://jiyeon98613.github.io/projects/nhis-billing/)

### 관리자 콘솔

환자·수면·처방·기기 이력을 확인하는 협업 제품입니다. 저는 데이터 모델과 조회·변경 계약, DB 역할·권한, 백엔드·배치를 주로 담당했습니다. 포트폴리오에는 실제 UI를 가상 데이터로 실행한 화면을 담았습니다.

[실제 화면과 DB·백엔드 기여](https://jiyeon98613.github.io/projects/admin-console/)

### 교육용 데이터베이스 설계

공개 데이터의 식별 기준과 관계를 정리해 PostgreSQL 테이블 15개를 설계하고, DDL 생성과 카탈로그 조회로 스키마를 확인했습니다. 실제 데이터 적재와 성능 검증은 별도 범위입니다.

[ERD·설계 근거·생성 검증](https://jiyeon98613.github.io/projects/education-db/#erd)

## 주로 다루는 기술

| 영역 | 사용 경험 |
| --- | --- |
| 데이터베이스 | PostgreSQL, SQL, 관계형 모델링·제약조건, Alembic |
| 백엔드·자동화 | Python, FastAPI, SQLAlchemy, Playwright |
| 운영 | Linux, systemd 서비스·타이머, 실행 결과 확인과 재처리 절차 |
| 접근 통제·협업 | DB 역할·제한 함수, Cloudflare Access, Git·Forgejo·Woodpecker |

SQL·Python 구현에 AI 코딩 도구를 활용합니다. 제가 정리한 업무 조건과 결정, 실제 확인한 결과와 담당 범위를 중심으로 설명합니다.

SQLD 취득 · 2026.06  
한국어 / 영어로 학업·업무 의사소통
