# Kaggle Titanic <파이썬으로 시작하는 캐글>

## '1. train_set_profiling.ipynb'
- pandas profiling을 활용한 데이터 개요 확인
- matplotlib와 seaborn을 활용한 특성과 목적 변수와의 관계 확인
- 파생변수 생성

## '2. modeling.ipynb'
- 결측값 처리 (평균값, 최빈값, 평균과 표준편차를 이용한 랜덤 값)
- 파생 변수
- 사용하지 않을 특성 제거
- 모델링 (로지스틱 회귀, 랜덤포레스트, Light GBM)
- Light GBM 파라미터 튜닝 (Optuna)
- Light GBM 교차검증
- 교차검증 폴드마다의 예측값 평균으로 최종 예측값 생성

## 3. 이미지, 텍스트, groupby 폴더
- 책에 나와있는 이미지 분석, 텍스트 분석, groupby를 이용한 테이블 핸들링을 각각 정리해놓은 폴더
- image.ipynb
  - torchvision 데이터를 이용한 실습
- Text.ipynb
  - 문장을 벡터로 변환 -> bag of words, TF-IDF, Word2vec
- table_handling.ipynb
  - 그룹화 및 join을 이용한 서로 다른 데이터 프레임 병합
