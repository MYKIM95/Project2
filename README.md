# Project2
날씨에 따른 야구 경기 승패 예측

# Project Background
- 맑은 날씨 에는 홈팀이 승리한 경우가 두드러지게 나타난다 (Kent & Sheridan, 2011).
- 득점 , 타율, 장타율, 그리고 홈런의 빈도수는 온도가 높을 때 증가된다(Koch & Panorska, 2012).
- 습도에 따라 야구공의 비거리는 17ft 이상 차이가 난다 (Kraft & Skeeter, 1995; Kingley, 1980; Rohli & Faiers, 2000).
- 야구공의 반발력은 온도에 따라 다르게 나타난다 (Drane & Sherwood, 2004).
- 선수들의 반응속도와 움직임은 온도와 직접적인 영향이 있다(Rammsayer, Bahner, & Netter, 1995).

# Project Description
- 2012년부터 2020년까지의 야구경기데이터를 Python의 크롤링을 이용하여 수집
- 기상청 자료 사이트를 통해 2012년부터 2020년 사이의 날씨 데이터를 수집
- 각 지역별 야구 경기장과 지역별 날씨 데이터를 매칭 시켜 자료를 전처리
- 전처리한 자료를 통해 각 자료들간의 상관관계를 도출
![cap](https://user-images.githubusercontent.com/77060863/114408019-fa0d7700-9be3-11eb-8055-f1ba1c840ca3.PNG)
- 기온에 따른 야구경기 승패 데이터를 그래프로 시각화

![캡처](https://user-images.githubusercontent.com/77060863/114408995-f29a9d80-9be4-11eb-9515-53a2b43e3c02.PNG)

- 다양한 머신러닝 모델을 활용하여, 가장 예측률이 높은 모델을 선정
- KNN 모델, KNN Scaler 적용, Decision Tree 모델, Naive Bayse 분류 모델, SVM 분류 모델, XGBOOST 모델, Stochastic Gradient Descent 모델, Adaboost 모델
![image](https://user-images.githubusercontent.com/77060863/114415546-c255fd80-9bea-11eb-96c1-8356622ae5d0.png)

# Weather API Usage
- 공공데이터 포털의 날씨 API를 활용하여 각 지역별 날씨 예보 정보를 수집
![image](https://user-images.githubusercontent.com/77060863/114413954-62128c00-9be9-11eb-9672-164365a7fa97.png)

# 머신러닝 결과를 피타고리안 기대 승률과 비교
- 야구경기 기대 승률을 잘 나타내어 주는 피타고리안 기대 승률과 머신러닝 결과를 비교
![image](https://user-images.githubusercontent.com/77060863/114414900-30e68b80-9bea-11eb-8920-c0cc49f07d3f.png)

# Project Technique
- Python, Jupyter Notebook, Selenium & BeautifulSoup를 통한 웹 크롤링 & 스크래핑
- HTML, CSS, JavaScript, Jquery를 활용한 웹 페이지 구현
- Eclipse와 Oracle DB를 통한 JDBC 연동
- Flask를 이용한 기상청 날씨 API 연동
![image](https://user-images.githubusercontent.com/77060863/114415767-f4fff600-9bea-11eb-888d-4dd75408fcf9.png)

