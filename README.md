# DataScience_termProject_team4
데이터 과학 텀프로젝트 데이터 분석

1. data 소개
⭐️our Data: Covid data
https://www.kaggle.com/datasets/meirnizri/covid19-dataset

- 이 데이터셋은 익명화된 코로나 환자의 정보를 담고 있으며, feature의 수는 21개이고 sample의 수는 1,048,576개가 있다. 21개의 feature의 내용을 간단히 설명하면, numerical data 하나와 (나이), categorical data 20개가 있다. categorical data는 성별, 질병 유무를 표현한다. 1은 있음, 0은 없음, 97, 98, 99은 missing data를 표현한다.

- one numerical data
- 20 categorical data(1 - 'yes', 2 - 'no', 97, 98, 99 - missing data)

2. preprocessing

- categorical data encoding
1) v1: not one hot encoding
2) v2: apply one hot encoding

- standard scaling for 'AGE'

3. data analysis
1)decision tree
2)logistic
3)random forest
4)k-means
