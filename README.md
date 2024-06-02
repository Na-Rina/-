데이터셋 정보
1. train.csv
설명: 100개 건물들의 2022년 6월 1일부터 2022년 8월 24일까지의 데이터
컬럼:
DateTime: 데이터의 시간 정보
Temperature: 해당 시간의 기온
Precipitation: 강수량
WindSpeed: 풍속
Humidity: 습도
SolarRadiation: 일사량
Sunshine: 일조 시간
PowerUsage(kWh): 전력 사용량 (킬로와트시)
2. building_info.csv
설명: 100개 건물에 대한 정보
컬럼:
BuildingNumber: 건물 고유 번호
BuildingType: 건물 유형
TotalArea: 건물 총 면적
CoolingArea: 냉방 면적
SolarCapacity: 태양광 용량
ESSCapacity: ESS(에너지 저장 시스템) 용량
PCSCapacity: PCS(전력 변환 시스템) 용량
3. test.csv
설명: 100개 건물들의 2022년 8월 25일부터 2022년 8월 31일까지의 예보 데이터
컬럼:
DateTime: 데이터의 시간 정보
Temperature: 예보된 기온
Precipitation: 예보된 강수량
WindSpeed: 예보된 풍속
Humidity: 예보된 습도
4. sample_submission.csv
설명: 제출을 위한 양식
컬럼:
num_date_time: 건물 번호와 시간으로 구성된 ID
answer: 각 ID에 맞춰 예측한 전력 사용량 (kWh)
배경
안정적이고 효율적인 에너지 공급을 위해서는 전력 사용량에 대한 정확한 예측이 필요합니다. 따라서 한국에너지공단에서는 전력 사용량 예측 시뮬레이션을 통한 효율적인 인공지능 알고리즘 발굴을 목표로 본 대회를 개최합니다.

주제
전력사용량 예측 AI 모델 개발
