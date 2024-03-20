## Repository for AI4ML class
* Chung-Ang University Class「AI를 위한 머신러닝
* 2023 - 2

### Folders
* **week** : Exercise notebooks for corresponding weeks
* **project** : Dacon Competition (대구 교통사고 피해 예측 AI 경진대회)

### Project 요약
- **Model**
  - 시군구, 사고일시 관련 파생변수 생성
  - 단일 모델 성능 비교를 통해 4개의 모델 선정 (XGBoost, LightGBM, Catboost, Linear Regression)
  - Optuna 튜닝 후, Voting Ensemble을 통해 최종 성능 달성
- **Result** : RMSLE = 0.42832

### Ref
* https://github.com/stefmolin/Hands-On-Data-Analysis-with-Pandas-2nd-edition
* https://github.com/ageron/handson-ml2
