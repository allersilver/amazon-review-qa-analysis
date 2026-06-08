# Amazon Review QA Analysis
## AI 학습 데이터 품질 관리 프로젝트

## 프로젝트 개요
Amazon 상품 리뷰 데이터를 단순 EDA가 아닌  
AI 학습 데이터 품질 관리 관점에서 분석한 프로젝트

수집된 데이터가 AI 학습에 바로 사용 가능한지 검증하고,  
품질 기준을 직접 설계하여 저품질 데이터를 탐지했다.

## 사용 기술
- Python (Pandas, Numpy, Matplotlib, Seaborn)
- SQL (SQLite, DBeaver)
- Jupyter Notebook

## 노트북 구성
| 번호 | 파일명 | 내용 |
|------|--------|------|
| 01 | data_cleaning | 데이터 전처리 및 QA 오류 탐지 |
| 02 | synthetic_data | 유저/이벤트 합성 데이터 생성 |
| 03 | price_analysis | 가격·할인율·평점 관계 분석 |
| 04 | review_quality | 리뷰 텍스트 품질 분류 |
| 05 | sql_analysis | SQL 기반 데이터 품질 분석 |
| 06 | insight_action | 핵심 인사이트 및 서비스 액션 |

## 핵심 결과
- 전체 1,212건 중 **442건(36.5%)** AI 학습 부적합 저품질 데이터 탐지
- **HomeImprovement(50%)**, OfficeProducts(45.2%) 저품질 비율 높음
- 저품질 유형 3가지 분류 (저품질_길이 / 저품질_URL / 저품질_복합)
- 실제 구매 로그 부재 → **Synthetic User 9,050명 · 이벤트 로그 직접 생성**

## 데이터 출처
Kaggle - Amazon Sales Dataset
