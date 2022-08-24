# kurly_hack_festa2022

![image](https://user-images.githubusercontent.com/86671456/186306402-23d2a2df-ebd8-4ddc-bda1-e75b649a3b87.png)


<br>
## Tech

![image](https://user-images.githubusercontent.com/86671456/186363278-d400b6df-91dd-45f3-9435-aceb7e043c98.png)


## Abstract

| 분석명 |목적|결과|
|:-----:|----------|-----|
|마켓컬리의 추천시스템 성능 및 검색엔진 개선| 4가지의 성능 개선을 위한 아이디어 제공 및 구현|본선 진출|

|  소스 데이터 |     데이터 입수 난이도    |      분석방법     |데이터 출처|
|:------------------:| -----|:---------------:|-----------|
|CSV,Json|중 |EDA, Visualization, Regression   |Kaggle, crawled Kurly data |
|  분석 적용 난이도  |     분석적용 난이도 사유    |      분석주기     | 분석결과 검증 Owner|
|상| 유사한 BM모델을 갖고 있는 회사와 컬리의 데이터를 적용시키기 위한 논리 구축|Daily  | Kulry Team  |



<br>

###  Project 

---
**진행: 애자일 방법론**

|  프로젝트 순서 |     Point    | 세부 내용 |  
|:------------------:| -----|------|
|문제 정의|해결할 점, 찾아내야할 점 |마켓컬리의 고객들을 위한 개인화 추천 알고리즘 구축 및 검색엔진 조정|
|데이터 수집|공개 데이터, 자체 수집, 제공된 데이터 |Kaggle Instacart, crawled Kurly data|   
|데이터 전처리|문제에 따라서 처리해야할 방향 설정 |User와 상품의 데이터를 바탕으로 추천 시스템 알고리즘 적용|
|Feature Engineering|모델 선정 혹은 평가 지표에 큰 영향|유사 상품을 많이 사는 user 혹은 제품을 많이 사는 user를 바탕으로 user-based의 추천 시스템 구축|
|연관 데이터 추가|추가 수집 |Intersection data, user data, item data를 집산하기 위해서 수집 |
|알고리즘 선택| 기본적, 현대적|Word2Vec, Efficinet, Customer Segmentation by PCA, 연관 규칙을 바탕 유사 상품 추천 |   
|모델 학습|모델을 통해서 얻고 싶은 것 |기존 데이터의 양이 적어서 캐글 Instacart 데이터를 추가하여 물품 유통 파악 및 user의 구매 건수 파악|
|모델 평가|확률 | NDCG 정확도를 3%향상|
|모델 성능 향상|성능 지표, 하이퍼파라미터, 데이터 리터러시 재수정 |하이퍼파라미터 조정 및 추가, 3%의 NDCG향상  |
|모델 배포|Amazon Personalize| 추천 시스템 성능 평가 및 조절, 웹 사이트 데모 배포
<br>

### Basic information

**공식기간: 2022.07.25 ~ 2022.08.29**

|  상세 기간 |     Point    | 세부 내용 |  
|:------------------:| -----|------|
|7.25 ~ 8.15|참가 신청 및 과제 계획서 접수 |컬리 고객들에게 적합한 상품을 추천할 수 있는 아이디어 제안|
|8.17|본선 진출팀 발표 |본선 진출|   
|8.19|본선 진출팀 대상 온라인 LIVE 개최 설명회 |과제 및 향후 프로세스 상세 안내, AWS교육|
|8.19 ~ 8.24|본선 진출팀 과제 개발 기간|Amazon Personalize 인프라 환경 기반 개발|
|8.29|결선 진출팀 발표 |AWS 개발 만료  |
|8.31| 결선 PT 및 최종 우승팀 발표|시상식|   
