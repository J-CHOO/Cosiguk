# (코시국에 어디를 가나요)

- 코로나가 발생한 이후로 지하철과 버스 이용량이 어떻게 변화하였는지 데이터 분석 및 시각화를 통해 사용자에게 인사이트를 제공하는 사이트
- 시작페이지
<img width="80%" src="https://user-images.githubusercontent.com/95010590/156295214-5bbf31b4-e05e-4d55-a35e-b9682aeffd76.gif"/>
- 지하철페이지
<img width="80%" src="https://user-images.githubusercontent.com/95010590/156296151-6b56602e-c7bd-4064-b735-da1270c593a6.gif"/>
<img width="80%" src="https://user-images.githubusercontent.com/95010590/156296274-806badfc-2507-4087-9817-020df47011cf.gif"/>
- 버스페이지
<img width="80%" src="https://user-images.githubusercontent.com/95010590/156296565-23c96b16-baad-46cd-82e6-1ad17386e667.gif"/>


## 1. 프로젝트 소개

**어떠한 데이터셋와 도구 및 기술을 사용했는지에 대한 설명과 유저에게 보이는 웹서비스에 대한 소개**

- 프로젝트 개발 기간: 2021.11.08~2021.12.02(4주)
- 데이터: 서울특별시 코로나19 확진자 발생동향(서울열린데이터광장) : https://data.seoul.go.kr/dataList/OA-20461/S/1/datasetView.do <br>
  2008~2020 서울교통공사 연도별 일별 시간대별 역별 승하차 인원: https://data.seoul.go.kr/dataList/OA-12921/F/1/datasetView.do <br>
  서울시 지하철호 선별 역별 승하차 인원 정보: https://data.seoul.go.kr/dataList/OA-12914/S/1/datasetView.do# <br>
  2015~2020 서울시 버스노선별 정류장별 승하차 인원 정보: https://data.seoul.go.kr/dataList/OA-12912/S/1/datasetView.do# <br>
  2020 6월 ~ 2021년 10월 지역별, 시간대별 승차 버스 데이터(인스파일러) : https://insfiler.com/detail/rt_transit_day-0005?category=total <br>

- 기술 스택 (python, spark, pandas, jupyter, javascript, html, css, Tableau, AWS, flask 등)

- 사용된 라이브러리 (pyspark, numpy, matplotlib, datetime, holidays, CategoricalDtype, SparkSession, timedelta, animate등)


## 2. 프로젝트 목표

**데이터 분석 결과로 도출되는 인사이트와 웹서비스의 해결과제에 대한 논의 (50자 이상)**

코로나로 거리두기단계 격상이 되었는데, 대중교통(지하철, 버스)이용량의 변화는 실감할 수 없었다.코로나 전후로 얼만큼 변화했을지 다양한 방면으로 분석을 하고, 얻을 수 있는 인사이트는 어떤 것이 있을지 알아볼려고 한다. 그리고 데이터 분석을 토대로 시각화하여 사용자에게 다양한 정보를 제공하려고
한다.



## 3. 프로젝트 기능 설명

**웹서비스의 유용성, 편의성 및 시각화의 실용성에 대한 설명**

- 주요 기능 (주된 활용성) 및 서브 기능
  -- 코로나 전후의 지하철 하루 이용자수의 변화량, 노선별 이용자수 변화율, 역별 코로나 전후 이용자 수 변화율, 금일 지하철 평균 이용자 수 등 다양한 데이터 시각화 확인 가능
  -- 코로나 전후의 버스 하루 이용자수의 변화량, 버스 종류별 이용자수 변화율

- 프로젝트만의 차별점, 기대 효과
  -- 다양한 데이터 분석을 통한 시각화를 볼 수 있다.
  -- 사용자에 맞게 동적인 시각화 컨트롤이 가능하다.
  -- 다방면한 데이터 시각화를 통한 유용성 ex)방역계획(어떤 역에 방역을 강화해야 하는지), 공공 일자리, 옥외광고등의 마케팅(이용자 수에 따른 어떤 역에 설치를 하는 것이 좋을지), 교통실수요 예상 등

## 4. 프로젝트 팀원 역할 분담

| 이름   | 담당 업무                 |
| ------ | ------------------------- |
| 이상우 | 팀장/웹    |
| 김태정 | 발표/웹           |
| 조도흔 | 데이터 분석/데이터 수집   |
| 안창혁 | 데이터 분석/데이터 수집   |
| 추　준 | 데이터 시각화/데이터 분석 |
| 남기윤 | 데이터 시각화/데이터 분석 |

## 5. FAQ

- 자주 받는 질문 정리
