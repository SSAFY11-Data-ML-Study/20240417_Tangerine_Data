# 20240417_Tangerine_Data

Link : https://dacon.io/competitions/official/236176/leaderboard

## Goals
* 특산물 가격 예측

## Dataset
1. train.csv

train 데이터 : 2019년 01월 01일부터 2023년 03월 03일까지의 유통된 품목의 가격 데이터
item: 품목 코드    
TG : 감귤     
BC : 브로콜리     
RD : 무     
CR : 당근     
CB : 양배추    
corporation : 유통 법인 코드     
법인: A부터 F 존재     
location : 지역 코드    
J : 제주도 제주시      
S : 제주도 서귀포시      
supply(kg) : 유통된 물량, kg 단위    
price(원/kg) : 유통된 품목들의 kg 마다의 가격, 원 단위      


2. international_trade.csv

관련 품목 수출입 정보      
중량 단위 kg     
금액 단위 천 달러     


3. test.csv

test 데이터 : 2023년 03월 04일부터 2023년 03월 31일까지의 데이터


4. sample_submission.csv

제출을 위한 양식           
2023년 03월 04일부터 2023년 03월 31일까지의 price(원/kg)을 예측               
ID는 품목, 유통 법인, 지역 코드로 구성된 식별자                
해당 ID에 맞춰 price(원/kg) 예측값을 answer 컬럼에 기입해야 함                

## 평가 방식
* RMSE

## 진행 기간
2024.04.15 ~ 2024.04.24

## 발표
AdaBoost
