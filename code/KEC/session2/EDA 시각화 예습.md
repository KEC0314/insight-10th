EDA/ 시각화


# 1. EDA란?
EDA: Exploratory Data Analysis, 탐색적 데이터 분석 과정(데이터의 특징과 구조적인 관계를 알아내기 위한 포괄적 분석 기법)
-통계적인 방법, 데이터 시각화를 사용

-분석 과정의 방향성(가설, 검증에 대한 플랜)을 짜기 위해 데이터의 특성을 파악하는 과정
-------------------------------------------------------------------------------
# 2. Feature 분석 및 시각화
## (1) Feature의 종류:
범주형(명목형, 순서형)/수치형(이산형, 연속형)
## (2)Feature의 종류에 따른 시각화 방법
명목형 자료일 경우 bar plot, count plot, pie chart
자료의 개형에 따라 histogram, box plot, 줄기 잎 그림
시계열 및 변수 간 관계에 따라 time series plot(시계열 그래프), Scatter plot(산점도)

**시간에 따른 변화를 확인할 때 :  line chart, area chart, bar plot

비교와 랭킹이 필요할 때 -> bar plot

연관성을 확인하고 싶을 때 -> scatter plot

분포를 확인할 때 -> box plot, histogram

부분이 전체에 차지하는 정도를 확인할 때 -> pie chart, bar plot **

시각화 방법: Matplotlib, Seaborn

# 3. 수치형 데이터 시각화
히스토그램, 커널밀도추정 함수 그래프,막대그래프(barplot), 포인트플롯(pointplot * 막대 그래프와 모양만 다르고 동일한 정보 제공),박스플롯(중앙값, 이상치), 바이올린 플롯(분포), 카운트 플롯,파이그래프,라인 그래프, 산점도,여러 변수 간 산점도(pair plot)