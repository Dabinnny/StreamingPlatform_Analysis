# StreamingPlatform_Analysis

## ✔️ Disney+ vs Netflix Analysis  

<div align="center">
<img src="https://podecomparar.com.br/sites/podecomparar.com.br/files/2020-12/disney-plus-vs-netflix-825x293.png"></div>

> [이미지 출처](https://podecomparar.com.br/telecom/comparativas/plataformas/qual-melhor-streaming-netflix-disney-plus)  

</br> 

넷플릭스와 디즈니+는 전 세계적으로 가장 인기 있는 Media Streaming Platform입니다.  
두 플랫폼의 주요 콘텐츠, user들의 특성을 비교하고 분석한 프로젝트입니다.  

</br> 

## ✔️ Data 특성  

**1. 데이터 크기**  

|Netflix|Disney+|
|:---:|:---:|
|8807 x 11|1450 x 11| 

</br> 

**2. 데이터 특성**  
- `show_id` : user ID
- `type` : 영화 or TV show
- `title` : 제목
- `director` : 감독
- `cast` : 출연진
- `country` : 콘텐츠 생산국
- `date_added` : 플랫폼 추가 날짜
- `release_year` : 개봉 날짜
- `rating` : 관람등급
- `duration` : 상영시간
- `listed_in` : 장르
- `description` : 줄거리  

</br> 

**3. 분석 내용**  
(1) 주요 콘텐츠(Movie or TV show)는 무엇일까?  
(2) 연도별, 월별로 추가 콘텐츠 수에 차이가 있을까?  
(3) 인기있는 장르는 무엇일까?  
(4) 나라별 시청 비율은 어떻게 될까?  
(5) 시청 상위 10개 나라에 대한 user들의 나이 분포는 어떻게 될까?  
(6) 제목의 주요 keyword WordCloud로 나타내기

</br> 

## ✔️ 분석 결과  

### 1. 주요 콘텐츠(Movie or TV show)는 무엇일까?  

- 두 플랫폼 모두 Movie Contents가 많다.  
- TV show는 시리즈물로 제작될경우 한 시리즈당 여러 회차가 포함되어 있지만 하나의 Contents로 들어가는것이 적은 비율에 영향을 주었을 것이다.

<div align="center">
<img src="https://user-images.githubusercontent.com/90162819/162562554-d4d89667-4506-4102-bd3a-914c2a95357a.png" ></div>  

</br> 
</br> 

### 2. 연도별, 월별로 추가 콘텐츠 수에 차이가 있을까?  

**(1) 연도별 추가 콘텐츠 비교**  

- Netflix : 2014년 부터 Online Streaming으로 주 전환을 시작함에 따라 2015년부터 많은 Contents가 추가되었다. 2019년 이후 코로나의 영향으로 Contents 제작이 주춤함에 따라 추가수는 다소 감소하였다.  

- Disney+ : 2019년 첫 출시와 동시에 많은 양의 Contents가 추가되었다. Promotion campaign event(2019. 11. 12.)로 신규가입자를 Targeting하기 위함으로 보인다.  [출처](https://www.disneyplusinformer.com/disney-day-announced-for-november-12/)   

<div align="center">
<img src="https://user-images.githubusercontent.com/90162819/162562629-f9ffeea7-bb67-4f24-b7df-e2af275fead7.png" ></div>  

<div align="center">
<img src="https://user-images.githubusercontent.com/90162819/162562631-180da92b-e4ef-459b-bcbf-7692bf8cb006.png" width=470></div>  

</br> 

**(2) 월별 추가 콘텐츠 비교**  

- Netflix : 월별로 크게 변동이 없이 꾸준하게 New Contents를 제공한다.

- Disney+ : 평균적으로 10월에 New Contents들이 많이 Update가 된다. 연말에 맞춰 Targeting하기 위함으로 보인다.

<div align="center">
<img src="https://user-images.githubusercontent.com/90162819/162562656-6fc8f3f7-744b-4fdf-b195-d18c3c63a8e6.png" ></div>  

</br> 
</br> 

### 3. 인기있는 장르는 무엇일까?  

Top 4 알아보기

- Netflix 
  (1) TVshow의 장르로 미스테리,드라마 등 종합장르를 나타낸다.
  (2) 다큐멘터리
  (3) 드라마
  (4) 어린이 & 가족영화

- Disney+ 
  (1) 가족
  (2) 애니메이션
  (3) 코미디
  (4) 액션-모험

<div align="center">
<img src="https://user-images.githubusercontent.com/90162819/162562746-bc981664-ea2a-439f-96d5-13003b764fe2.png" width = 800 ></div>   

</br> 
</br>

### 4. 나라별 시청 비율은 어떻게 될까?  

- Netflix : 미국이 1위이다. 미국회사이기 때문에 다른 나라에 출시 전 자국고객을 많이 확보했을 것이다. 인도가 2위인것은 발리우드 영향이 있을것으로 본다.

- Disney+ : 미국이 압도적으로 많다. 전 세계적으로 출시가 된지 얼마되지 않아 여러 나라의 User들을 균형있게 확보하지 못한것으로 보인다.

<div align="center">
<img src="https://user-images.githubusercontent.com/90162819/162562767-7dcdaf35-d391-42ff-9e40-bcee327f5f97.png" ></div> 

</br> 
</br>

### 5. 시청 상위 10개 나라에 대해 상영 등급 분포는 어떻게 될까?  

- Netflix : 인도, 이집트를 제외하고 사위 10개 나라에 대해 성인 등급이 대다수를 차지한다. 각 나라별로 문화와 환경에 따라 제공되는 Contents가 상이함을 알 수있다.  

- Disney+ : 성인등급으로 지정된 Contents는 없다. 대부분 어린이/전체관람가 등급이다.

<div align="center">
<img src="https://user-images.githubusercontent.com/90162819/162562812-90900e93-a075-4e72-a2af-6facd9454236.png" width = 750></div>  

</br> 

<div align="center">
<img src="https://user-images.githubusercontent.com/90162819/162562815-11220848-ee1a-4c5e-b768-f8d326744021.png" width = 750 ></div>  

</br> 
</br>

### 6. 제목의 주요 keyword를 WordCloud로 나타내기

<div align="center">
<img src="https://user-images.githubusercontent.com/90162819/162562872-ed9d1352-bdd3-47dc-8c4e-8e12d28e5029.png" width = 750></div>  




