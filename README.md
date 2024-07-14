# Stabucks-Ediya
이디야는 스타벅스 근처에 매장을 입장시킨다는 의심을 종종 받는다.    
실제 이디야와 스타벅스 매장 정보를 크롤링하여 이를 기반으로 이 의심이 진짜인지 아닌지, 개인적인 결론 내 보고자 함

## 파일1. make_df & map 
- Selenium, BeautifulSoup, Pandas, Folium, Googlemaps 활용
- 스타벅스 및 이디야 매장 정보 크롤링 후 pandas를 활용한 dataframe 생성    
- 생성한 dataframe을 기반으로 folium을 활용한 지도 시각화 수행     


## 파일2. make_df_with_SQL    
- Selenium, BeautifulSoup, MySQL, GoogleMaps, AWS 활용
- make_df & EDA의 크롤링을 그대로 사용하되, 이번에는 dataframe이 아닌 AWS에 MySQL을 활용하여 데이터 베이스를 생성   
- Tableau 시각화를 위해 최종적으로는 하나의 스타벅스에 모든 이디야 매장을 연결시킨 dataframe을 데이터베이스로부터 가져와 생성함
