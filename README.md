# Stabucks-Ediya

⦁ make_df & map : Selenium, BeautifulSoup, Pandas, Folium, Googlemaps
   ◦ 스타벅스 및 이디야 매장 정보 크롤링 후 pandas를 활용한 dataframe 생성
   ◦ 생성한 dataframe을 기반으로 folium을 활용한 지도 시각화 수행

⦁ make_df_with_SQL : Selenium, BeautifulSoup, MySQL, GoogleMaps, AWS
   ◦ make_df & EDA의 크롤링을 그대로 사용하되, 이번에는 dataframe이 아닌 AWS에 
       MySQL을 활용하여 데이터 베이스를 생성
   ◦ Tableau 시각화를 위해 최종적으로는 하나의 스타벅스에 모든 이디야 매장을 연결시킨
       dataframe을 데이터베이스로부터 가져와 생성함
