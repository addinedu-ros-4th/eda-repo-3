# 패션 트렌드 분석 EDA Project

## Exploratory Data Analysis Project - (Fashion Trend Data Analysis)


![Screenshot from 2024-03-06 16-05-12](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/b96088ff-ee1d-4819-be2b-bdf59cefb798)

---

## 1. 프로젝트 소개

### 1.1 프로젝트 목표

```
- Kaggle data from Musinsa using Selenium and BeautifulSoup
- Analyze the Fashion Trends of Musinsa users
- Visualize Interesting Information

```

### 1.2 프로젝트 멤버

```
팀명: 유신사
팀장: 김보선 - 총괄
팀원: 이재혁 - 데이터 수집 / 분석
팀원: 곽준 - 데이터 분석 / 시각화
팀원: 유겸희 - 데이터 분석 / 시각화 / 발표
팀원: 김영환 - 데이터 수집 / Slack Bot 활용

```

### 1.3 프로젝트 기술

![Screenshot from 2024-03-06 16-24-03 (1)](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/2cac35c3-d4a6-43ef-9773-f928a6243d63)


---

## 2. 데이터 수집 및 분석

### 2.1 데이터 정보

6개의 대분류: 상의 / 하의 / 아우터 / 모자 / 신발 / 가방
대분류별 소분류 Top 90개 상품의 대한 정보

![Screenshot from 2024-01-23 09-37-22](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/4379decc-f104-4896-a19f-e61a7d43a2bc)

### 2.2 데이터 수집 1차
![Screenshot from 2024-01-23 14-04-03](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/556f56ef-7810-42bf-9b67-3ee1d60fef0e)

1차 데이터 수집 후 데이터베이스를 확인한 결과, 제대로 수집되지 않는 항목들이 존재했다
예: 총판패량, 연령 정보 누락

### 2.3 데이터 수집 2차
이를 해결하고자 
Inpect ➡ Network ➡️ Headers ➡️ Data
위와 같은 방버으로 접근하여 원하고자 하는 데이터를 수집할 수 있었다
![Screenshot from 2024-01-23 09-49-05](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/6a05498e-d2dd-4d49-929e-3c02820f154e)

### 2.4 데이터 베이스 (AWS)

