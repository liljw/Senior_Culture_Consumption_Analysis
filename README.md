# 서울특별시 내 시니어들의 특성에 따른 문화생활 참여 예측 및 소비 분석

## 개요

해당 프로젝트는 **문화 빅데이터 경진대회**에 참가한 프로젝트이다.  
4인 구성의 빅데이터 분석 프로젝트이며, 총 3주의 시간이 주어졌으며,  
데이터 분석 툴은 **R**과 **Python**을 사용하였다.  

본 프로젝트는 전공 프로젝트로도 동시에 활용하였으며,  
총 5개 팀의 참가 가운데 **최우수상**을 수상하였다.

---

## 목차

1. 프로젝트 후기
2. 주제 선정 배경
3. 활용 데이터 셋
4. 전처리
5. EDA (탐색적 데이터 분석)
    - 기초 통계 분석
    - ANOVA 분산분석
    - 선형 회귀 분석
    - 군집화
        - K-Prototype
6. 머신러닝
    - 모델링 전처리 (타겟 범주화)
    - 다중회귀
        - 릿지, 라쏘
    - 로지스틱 회귀
    - LightGBM
    - 랜덤포레스트 
    - 결과 및 최종 모델 선정
    - 피쳐 중요도 파악
7. 소비분석
    - 통계 분석 
    - 문화 참여 분석과 연계 분석
8. 인사이트 도출
9. 한계점

---

## 프로젝트 후기

본 프로젝트를 통해 다양한 머신러닝 모델링을 다뤄보아   
**주제에 적합한 모델을 선택할 수 있는 범용성**이 넓어질 수 있었다.  

특히 기초 통계 분석과 회귀분석에서 그치지 않고,   
ANOVA 분산분석까지 범위를 넓혀 데이터를 한 층 더 깊게 분석해 보았고,  

거기서 그치지 않고 머신러닝 비지도 학습인 클러스터링 기법을 이용하여   
군집 별 특성을 파악하는 것까지 시도하여 **데이터에 대한 이해도**를 100%에 가까이 끌어올렸다.   

또한 K-Prototype이라는 새로운 클러스터링 알고리즘을 도입 및 적용해보았으며,  
머신러닝에서도 여러가지 회귀 및 분류 알고리즘을 사용하여 모델 간 비교를 통해  
가장 완성도 있는 모델을 사용하려 하였다.  

무엇보다 위의 머신러닝 모델을 이용한 예측 결과 및 피쳐 중요도를 사용하여  
이를 **소비 분석과 연계하여 소득층 간의 문화 분야별 소비 금액의 차이를 분석**해 내어  
그에 따른 정책적, 사업적 방안을 제시하는 **인사이트 도출**의 과정까지 경험해보았다.  

이번 경진대회 참가를 통해 데이터 분석가로서 한층 더 단단해진 경험을 한 것 같다. 

---

## 주제 선정 배경

<img width="1680" alt="planning" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/79d41896-c365-4cbc-b47e-8b79619194cd">

---

## 활용 데이터 셋

<img width="1680" alt="dataset" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/578103ae-d9fe-43f7-97cb-ec3e92452a48">

---

## 전처리

<img width="1680" alt="preprocessing" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/d17e07bd-b32c-4f5f-bc00-533d45d7e873">

---

## EDA (탐색적 데이터 분석)

### 기초 통계 분석

<img width="1680" alt="wordcloud" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/649e3e6f-bffc-4b32-9ce7-db33290b67cb">

### 분산분석

<img width="1680" alt="anova" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/d8723c79-3f68-4cc4-81e3-cff99c1ef34d">

### 선형 회귀 분석

<img width="1680" alt="regression" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/cf5c4287-2413-41c4-8841-dbfcb55bff57">

### 군집화

<img width="1680" alt="clustering1" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/e7b89e18-07af-4b40-9523-4b6fe4088bf8">

<img width="1680" alt="clustering2" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/1c009120-0054-449d-8904-924fce6e6d4b">

<img width="1680" alt="clustering3" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/912104dd-3175-4783-869c-34177db4a8ff">

---

## 머신러닝

### 모델링 전처리 (타겟 범주화)

<img width="1680" alt="binning" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/d305fbd6-cf4c-4683-a720-7cd7e9bd9c29">

### 다중회귀

<img width="1680" alt="multi_regression" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/f7661640-b0bd-4256-84a2-e8cacb760b12">

### 로지스틱 회귀

<img width="1680" alt="logistic_regression" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/b9e7a32c-46ad-457b-a082-ad68926d34f0">

### LightGBM

<img width="1680" alt="LightGBM" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/7d7aa84c-3040-44b6-b0a5-f89979b64a61">

### 랜덤 포레스트

<img width="1680" alt="random_forest" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/0a6e29ea-29d0-428e-b2f9-a8d8082236a2">

### 결과 및 최종 모델 선정

<img width="1680" alt="model_result" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/735f4ec6-90ef-4195-a683-0ee711bd8cce">

### 피쳐 중요도

<img width="1680" alt="feature_importance" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/2418ddc0-6a48-49bd-acc7-dd8a2750776d">

---

## 소비분석

### 통계분석

<img width="1680" alt="consumption_analysis1" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/b395adb0-ec19-4c1d-8eea-2f24ea61d8a5">

<img width="1680" alt="consumption_analysis2" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/5060aa96-ea29-4fa8-a0f0-a3746e28c34f">


### 연계 분석

<img width="1680" alt="consumption_analysis3" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/538d35a8-8024-4e8f-8cab-9c8ef52404de">

<img width="1680" alt="consumption_analysis4" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/92e132d9-85fb-4b2e-aee9-d3b21b40bc88">

<img width="1680" alt="consumption_analysis5" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/01ddfb39-5aa7-4ff3-8153-f12acd9dda7d">

---

## 인사이트 도출

### 결론
<img width="1680" alt="insight" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/562d0da2-b246-4ca0-a92c-78526146d984">


### 한계점
<img width="1680" alt="limitation" src="https://github.com/liljw/Juvenile_Crime_Regression/assets/129480514/3f50637b-7867-4d22-b275-8185c5b2b835">
