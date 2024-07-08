# <목  차>

## Ⅰ. 프로젝트의 목적 및 필요성

## Ⅱ. 작품 설계
### 2.1 개발 목표
### 2.2 주요 부품의 구성 및 동작
### 2.3 작품 제작에 사용된 도구
### 2.4 제작 일정
### 2.5 작품의 동작 시나리오

## Ⅲ. 작품 개발
### 3.1 작동화면
### 3.2 프로젝트 수행 시 문제점 및 해결방안

## Ⅳ. 결론

### 프로젝트 수행 후기

### 참고문헌




--------------------------------------------------------------------------------------------------------------------------------------





## Ⅰ. 프로젝트의 목적 및 필요성
+ 머신러닝에 활용되는 여러 필터링을 기반으로 유저의 취향에 맞게 추천하는 웹사이트를 제작한다.
+ 필터링 기반 추천 시스템은 넷플릭스같은 OTT나 CGV같은 극장 관련 앱에 추가 요소로 활용될 수 있다.

## Ⅱ. 작품 설계
### 2.1 개발 목표
 Demographic Filtering(인구통계학적 필터링), Content Based Filtering(컨텐츠 기반 필터링), Collaborative Filtering(협업 필터링)을 기반으로 영화 추천 웹사이트를 제작한다.

### 2.2 주요 부품의 구성 및 동작
 1. Demographic Filtering(인구통계학적 필터링)
       - 많은 사람들이 일반적으로 좋아하는 영화로 필터링
       - 관객 수가 많은 영화나 평점이 좋은 영화로 필터링
 2. Content Based Filtering(컨텐츠 기반 필터링)
       - 특정 영화와 유사한 영화로 필터링
       - 영화의 줄거리를 기반으로 필터링
       - 영화의 요소(배우, 감독)를 기반으로 필터링
 3. Collaborative Filtering(협업 필터링)
       - 비슷한 취향을 가진 사람끼리 매칭시켜서 필터링
       - 유저의 리뷰 기반으로 필터링

### 2.3 작품 제작에 사용된 도구
Jupyter Notebook  
Visual Studio Code  
Kaggle의 Dataset과 Data와 공식  
The Movie Database의 Dataset과 Data와 공식

### 2.4 제작 일정
1주차 - 프로젝트 주제 선정  
2주차 - 프로젝트의 방향성 설정  
3주차 – 프로젝트의 세부내용 설정  
4주차 – 프로젝트에 필요한 데이터셋 찾아보기  
5주차 – 프로젝트 시작  
6주차 – 인구통계학적 필터링으로 영화 추천 데이터 만들기  
7주차 – 컨텐츠 기반 필터링으로 영화 추천 데이터 만들기  
8주차 – 협업 필터링으로 영화 추천 데이터 만들기  
9주차 – 웹사이트 만들기  
10주차 – 컨텐츠 기반 필터링을 웹사이트와 연동하기  
11주차 – 인구통계학적 필터링과 컨텐츠 기반 필터링을 혼합하여 웹사이트에 연동하기  
12주차 – 협업 필터링을 혼합하여 웹사이트에 연동하기  
13주차 – 프로젝트 마무리하기  
14주차 – 프로젝트 완성  
15주차 - 프로젝트 보고서 작성

### 2.5 작품의 동작 시나리오
Content Based Filtering을 이용하여 영화의 줄거리, 배우, 감독, 장르를 기반으로 유사한 영화를 추천한다.

## Ⅲ. 작품 개발
### 3.1 상세 회로도

### 3.2 소스 프로그램
첨부 파일에 소스 첨부

### 3.3 작동화면
![작동화면 이미지](https://i.esdrop.com/d/f/3X5MiUW5Gr/lV3fvTUVny.png)

### 3.4 프로젝트 수행 시 문제점 및 해결방안
웹사이트를 제작할 때 포스터 이미지가 없는 경우 에러가 나는 문제를 해결하기 위해 포스터 이미지가 없을 경우에 빈 이미지를 나오게 하는 코드를 추가하였다.
대문자와 소문자, 띄어쓰기 등 때문에 벡터화에 어려움이 있어 문자를 빈칸을 없애고 소문자로 모두 바꾸었다.

## Ⅳ. 결론
이러한 필터링 기반 추천 시스템은 넷플릭스같은 OTT나 CGV같은 극장 관련 앱에 추가 요소로 활용될 수 있을 것으로 기대된다.

### 프로젝트 수행 후기
머신러닝에 활용되는 라이브러리나 벡터화 등 한번도 접해보지 않은 것들을 접하고 다루어보게되는 계기가 된 것 같다.
여러 필터링을 추가하거나 사용자가 검색하는 영화를 학습하여 추천 시스템에 영향을 주는 기능을 넣지 못하여 아쉬웠고, 시간이 된다면 이러한 아쉬운 부분을 보완하고 싶다.


### 참고문헌
https://www.kaggle.com/code/ibtesama/getting-started-with-a-movie-recommendation-system
https://developers.themoviedb.org/3/movies/get-movie-details
