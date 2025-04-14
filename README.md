1. 타이타닉 생존자 예측 (Titanic - Binary Classification)
 데이터셋: Titanic Dataset (Kaggle)
설명: 탑승객 정보(나이, 성별, 객실 등)를 바탕으로 생존 여부를 예측하는 고전적인 이진 분
류 문제
분석 과정
데이터 전처리
결측치 처리 (나이, 객실 정보)
원-핫 인코딩 (성별, 승선항구)
특성 선택 및 생성
가족 크기 변수 생성 (형제+부모)
객실 등급을 범주형 변수로 변환
모델 학습 및 비교
기본 모델: 로지스틱 회귀, Decision Tree
개선 모델: Random Forest, XGBoost
딥러닝: 간단한 MLP 모델 (TensorFlow/Keras 활용)
모델 평가
정확도(Accuracy), 정밀도-재현율(F1 Score), ROC-AUC
2. 손글씨 숫자 분류 (MNIST - Multi-class Classification)
 데이터셋: MNIST Handwritten Digits
설명: 0~9까지의 손글씨 숫자 이미지를 보고, 올바른 숫자를 분류하는 문제
분석 과정
데이터 탐색 및 전처리
픽셀 값을 0~1 사이로 정규화
28x28 이미지를 벡터 형태로 변환
모델 학습 및 비교
기본 모델: KNN, Decision Tree
고급 모델: SVM, Random Forest, XGBoost
딥러닝: CNN(Convolutional Neural Network)
성능 비교
정확도(Accuracy)
Confusion Matrix 및 Class별 Precision/Recall
3. 주택 가격 예측 (Boston Housing - Regression)
 데이터셋: Boston Housing Dataset
설명: 지역별 범죄율, 방 개수, 교통 접근성 등을 이용해 주택 가격을 예측하는 회귀 문제
분석 과정
데이터 전처리
결측치 처리
이상치 탐지 및 제거
특성 정규화 (Min-Max Scaling)
모델 학습 및 비교
기본 모델: 다중 선형 회귀(Linear Regression)
고급 모델: Random Forest, XGBoost, LightGBM
딥러닝: 간단한 Fully Connected Neural Network (MLP)
모델 평가
MSE(Mean Squared Error), R² Score
4. 고객 이탈 예측 (Telco Customer Churn - Binary Classification)
 데이터셋: Telco Customer Churn (Kaggle)
설명: 인터넷 및 전화 서비스를 사용하는 고객들이 이탈(Churn)할지 여부를 예측하는 문제
분석 과정
데이터 전처리
결측치 처리
범주형 변수 인코딩 (예: 계약 유형, 결제 방식)
스케일링 (월별 요금, 총 지출금액)
모델 학습 및 비교
기본 모델: 로지스틱 회귀
고급 모델: Random Forest, XGBoost, LightGBM
딥러닝: 간단한 DNN (Deep Neural Network)
모델 평가
정밀도(Precision), 재현율(Recall), F1 Score, ROC-AUC
5. 영화 추천 시스템 (MovieLens - Recommendation)
 데이터셋: MovieLens 100k
설명: 사용자 영화 평가(1~5점)를 기반으로 추천 시스템을 만드는 문제
분석 과정
데이터 전처리
사용자-영화 간 행렬(Matrix) 생성
데이터 sparsity 해결 (행렬 보간)
추천 알고리즘 비교
기본 모델: 협업 필터링 (User-Based, Item-Based)
행렬 분해: SVD, ALS(Alternating Least Squares)
딥러닝: Autoencoder 기반 추천 시스템
모델 평가
RMSE(Root Mean Squared Error)
사용자 만족도 (Top-N Precision, Recall)
6. 신용카드 사기 탐지 (Credit Card Fraud - Anomaly Detection)
 데이터셋: European Credit Card Transactions (Kaggle)
설명: 신용카드 거래 데이터를 분석하여 정상 거래와 사기 거래를 분류하는 문제 (불균형 데
이터)
분석 과정
데이터 전처리
불균형 데이터 처리 (SMOTE, 언더샘플링)
거래 금액 정규화
모델 학습 및 비교
기본 모델: 로지스틱 회귀, Decision Tree
고급 모델: Random Forest, XGBoost, Isolation Forest
딥러닝: Autoencoder 기반 이상탐지
모델 평가
AUC-ROC, Precision-Recall Curve
7. 당뇨병 예측 (Pima Indians Diabetes - Binary Classification)
 데이터셋: Pima Indians Diabetes Dataset (Kaggle)
설명: 당뇨병 발생 여부(0 또는 1)를 BMI, 혈압, 나이 등 건강 관련 지표를 기반으로 예측하
는 이진 분류 문제
 분석 과정
1⃣ 데이터 탐색 및 전처리
EDA(탐색적 데이터 분석)
변수 간 상관관계 분석 (히트맵, 박스플롯 활용)
분포 확인 (연속형 변수: BMI, 혈압 등 / 이산형 변수: 나이, 당뇨 여부)
결측치 처리
Glucose, BloodPressure, SkinThickness 등의 결측값을 중앙값(median)으로 대체
데이터 정규화 (Feature Scaling)
Min-Max Scaling 또는 Standard Scaling 적용
2⃣ 모델 학습 및 비교
기본 모델
Logistic Regression
Decision Tree
고급 모델
Random Forest
XGBoost
LightGBM
딥러닝
간단한 DNN (MLP)
Dropout 및 Batch Normalization 적용
3⃣ 성능 평가 및 비교
평가 지표
Accuracy (정확도)
Precision, Recall, F1-score (의료 데이터에서는 Recall이 중요!)
ROC-AUC (이진 분류 모델 평가)
불균형 데이터 처리
SMOTE (Synthetic Minority Over-sampling Technique)
가중치  조정 (Class Weight 조정)

보내주신 pdf 파일 요구사항대로 ipynb 파일을 만들었습니다. 6번의 데이터는 용량이 커서 업로드가 되지 않습니다. 나머지는  다 업로드 했습니다.
