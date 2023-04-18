# 제2회 ETRI 휴먼이해 인공지능 논문경진대회
---

- 개발 환경 : Python


- 데이터 : ETRI 라이프로그 데이터셋 (2020-2018) (링크 : https://nanum.etri.re.kr/share/schung1/ETRILifelogDataset2020?lang=ko_KR)


- 필요한 라이브러리 : **pandas, numpy, datetime, time, sys, os, sklearn, random, math, warnings, matplotlib, re, xgboost, fancyimpute, shap**


- 데이터 전처리(총합) 순서
> 1. 2020년 데이터 전처리 : **2020 lifelog 데이터 전처리.ipynb** -> **2020 survey_sleep data merge.ipynb** -> **2020 lifelog, sleep, info 데이터 병합.ipynb**
> 2. 2018-2019년 데이터 전처리 : **2018-2019_lifelog 데이터 전처리.ipynb** -> **2018_2019_survey_sleep data merge.ipynb** -> **2018-2019_lifelog, sleep, info 데이터 병합.ipynb**
> 3. 2020년 데이터와 2018-2019년 데이터 전처리 : **2018,2019,2020 데이터 병합.ipynb**
  
- 머신러닝 적용
> - uni(유저맞추기).ipynb : 라이프로그 데이터로 해당 유저가 누군지 맞추는 실험
> - uni_코드 보완.ipynb : 단일연도 모델 실험
> - 과적합 검증(LR)_코드 보완.ipynb, 과적합 검증(RF)_코드 보완.ipynb : 2018년 데이터만 학습에 사용한 뒤 2018-2020모델로 테스트해서 과적합 검증한 실험
> - 데이터통합(2018, 2019, 2020 각각 적용)_코드 보완.ipynb : 통합 모델 실험 
