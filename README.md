# DataCrawlingScrapping
## 프로젝트의 목표
- 1. 웹상에 있는 다양한 형태의 데이터를 효과적으로 수집하는 방법을 익힌다.
- 2. 수집한 데이터를 전처리하는 방법을 익힌다.
- 3. 엑셀 파일로 저장하는 방법을 익힌다.
- 4. WordCloud, Map, plot 등으로 시각화하는 방법을 익힌다.
- 5. 각 변수들 간의 상관관계를 파악한다.

## 프로젝트의 대상
- 네이버 주식, 인스타, 다나와 쇼핑, 코로나 통계, 인터넷 강의 댓글

## 환경
- IDE : JupyterNotebook
- 언어 : Python3
- 라이브러리1 : BeautifulSoup(HTML 태그에서 필요한 정보 추출), webdriver(Selenium 라이브러리_크롬 웹브라우저 제어)

## Release
|기능|도구|예시|
|:--:|:--:|:--:|
|엑셀수집|openpyxl|
|이미지표시|IPython|

## 웹 크롤링할 때 주의점
특정사이트에서 짧은 시간 동안 많은 데이터를 수집할시 디도스 공격 등으로 감지되거나 웹 서버에 무리를 줄 수 있음.
