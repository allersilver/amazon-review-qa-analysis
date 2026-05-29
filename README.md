# Amazon 리뷰 데이터 품질 분석

## 프로젝트 개요
Amazon 상품 리뷰 데이터를 단순 EDA가 아닌  
AI 학습 데이터 품질 관리 관점에서 분석한 프로젝트

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

## 핵심 분석 결과
- 전체 리뷰의 36.5%가 AI 학습에 부적합한 저품질 데이터
- 할인율 81~100% 구간 평균 평점 3.93으로 가장 낮음
- 재구매율 15.9% → 재구매 유도 전략 필요
- HomeImprovement(50%), OfficeProducts(45.2%) 저품질 비율 높음

## 데이터 출처
Kaggle - Amazon Sales Dataset
