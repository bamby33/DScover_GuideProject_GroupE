# DScover Guide Project - Group E

**성균관대학교 DScover 26기 1학기 가이드 프로젝트** E조 저장소입니다.

- 기간: 2025.03.09 ~ 2025.03.20

## 프로젝트 구조

```
├── EDA/                        # 탐색적 데이터 분석
│   ├── EDA_시온.ipynb
│   ├── EDA_이유준.ipynb
│   └── EDA_채현.ipynb
│
├── PreProcessing/              # 데이터 전처리
│   ├── 전처리_시온.ipynb
│   ├── 전처리_유준.ipynb
│   └── 전처리_예린.ipynb
│
├── FeatureEngineering/         # 피처 엔지니어링
│   ├── 피처엔지니어링_시온.ipynb
│   └── 피처엔지니어링_유준.ipynb
│
├── Modeling/                   # 모델 학습 및 평가
│   ├── 모델링_시온.ipynb
│   ├── 모델링_예린.ipynb
│   ├── 모델링2_예린.ipynb
│   ├── 앙상블_모델링_유준.ipynb
│   └── 앙상블_모델링_v1_유준.ipynb
│
├── csvData/                    # 데이터 파일
│   ├── sample_submission.csv
│   ├── train_step3_cleaned.csv
│   ├── train_target_only_cleaned.csv
│   ├── ensemble_lgbm_xgb_submission.csv
│   └── ensemble_lgb_xgb_cat_submission.csv
│
├── test/                       # 테스트 데이터 (TEST_00 ~ TEST_24)
│   └── meta/                   # 메타 데이터 (산지공판장, 전국도매)
│
└── catboost_info/              # CatBoost 학습 로그
```

## 사용 모델

- **LightGBM (LGBM)**
- **XGBoost**
- **CatBoost**
- **앙상블** (LightGBM + XGBoost + CatBoost)

## 진행 단계

1. **EDA** - 데이터 분포, 결측치, 이상치 분석
2. **PreProcessing** - 데이터 정제 및 전처리
3. **Feature Engineering** - 피처 생성 및 선택
4. **Modeling** - 모델 학습, 하이퍼파라미터 튜닝, 앙상블
