# 📊 패션 트렌드 분석 EDA Project 📊

## Exploratory Data Analysis Project - (Fashion Trend Data Analysis)


![Screenshot from 2024-03-06 16-05-12](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/b96088ff-ee1d-4819-be2b-bdf59cefb798)

---

# 1.🤔 프로젝트 소개 🤔

## 1.1 프로젝트 목표 🎯 

```
- 무신사라는 온라인 패션 플랫폼을 크롤링하여 데이터를 추출한다
- 무신사 이용자들의 패션 트렌드 현황을 시각화를 통해 분석한다
- 유의미한 결과들을 모으고 우리 조만의 계산식을 통해 트렌드에 맞게 상품을 추천해준다

```

## 1.2 프로젝트 멤버 👥

```
팀명: 유신사
팀장: 김보선 - 총괄
팀원: 이재혁 - 데이터 수집 / 분석 (ACE)
팀원: 곽준 - 데이터 분석 / 시각화
팀원: 유겸희 - 데이터 분석 / 시각화 / 발표
팀원: 김영환 - 데이터 수집 / Slack Bot 활용

```

## 1.3 프로젝트 기술 🛠💡

![Screenshot from 2024-03-06 16-24-03 (1)](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/2cac35c3-d4a6-43ef-9773-f928a6243d63)


---

# 2. 🗂️ 데이터 수집 및 데이터베이스 🗂️

## 2.1 데이터 정보 ℹ️

6개의 대분류: 상의 / 하의 / 아우터 / 모자 / 신발 / 가방
대분류별 소분류 Top 90개 상품의 대한 정보

![Screenshot from 2024-01-23 09-37-22](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/4379decc-f104-4896-a19f-e61a7d43a2bc)

## 2.2 데이터 수집 1차 ⛏️

![Screenshot from 2024-01-23 14-04-03](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/556f56ef-7810-42bf-9b67-3ee1d60fef0e)

1차 데이터 수집 후 데이터베이스를 확인한 결과, 제대로 수집되지 않는 항목들이 존재했다

예: 총판패량, 연령 정보 누락

## 2.3 데이터 수집 2차 ⛏️

이를 해결하고자 

Inspect ➡ Network ➡️ Headers ➡️ Data

위와 같은 방법으로 접근하여 원하고자 하는 데이터를 수집할 수 있었다

![Screenshot from 2024-01-23 09-49-05](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/6a05498e-d2dd-4d49-929e-3c02820f154e)

## 2.4 데이터 베이스 (AWS) 🗃️

총 5670개의 데이터를 정리하고 다루기 위해서는 아마존에서 제공하는 AWS Database를 사용했다

아래는 데이터를 AWS에 저장하기 위한 코드이다

![Screenshot from 2024-03-06 17-18-00](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/7df3aa1b-e7b0-4a28-9c2f-02e3bf22deee)

***

# 3. 데이터 분석 및 시각화

## 3.1 방향성

우선 가설을 세우기보다는 방향성을 잡고 데이터를 분석해보자라는 의견이 모여 

대분류별 트렌드 분석 / 연령 및 성별 트렌드 분석 으로 크게 나누어 진행하기로 했다

이 분석을 통해 유의미한 결과가 나온다면 그 결과를 바탕으로 슬랙봇을 사용할 에정이다

![Screenshot from 2024-03-06 17-31-54](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/37fff6f7-b18a-4df4-b42b-1710287c3426)

***

# 4. 시각화
## 4.1 대분류별 
![image](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/03834a13-ae89-47c1-8ca7-b23fba0add51)

## 4.2
![image](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/36d31dac-b69d-4fc5-afef-15194785aa22)

## 4.3
![image](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/4eb6a9ec-f10e-4e52-a0fc-cd5fec4673a7)

## 4.4
![image](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/9ecde54d-526e-40e0-9aa9-8d5166dfae09)

## 4.5
![image](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/b0591d2a-59a7-4012-83d4-03e7dc38cc1a)


## 4.6
![image](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/8521e07b-6fc1-448c-8907-b8dfa9f2d40b)

## 4.7
![image](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/285a7937-cd7a-4568-8083-1eb6760f2606)

## 4.8
![image](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/8803e845-664f-42a9-aabf-d939f5575947)

## 4.9
![image](https://github.com/addinedu-ros-4th/eda-repo-3/assets/155615876/64e6c175-2715-4b46-a4a6-a0770a27626d)
