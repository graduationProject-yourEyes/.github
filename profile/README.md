# YourEyes <br>- 시각장애인의 디지털 정보 이용 도움 웹 서비스 (NLP Project)


많은 웹 사이트가 웹 콘텐츠 접근성 지침을 따르지 않으며, 코로나로 인한 비대면 상황에서 
  <br> **시각장애인과 비장애인의 디지털 정보 격차가 커지는 문제 상황**에 따라 
  <br> ➡️ 시각장애인을 위한 디지털 정보 이용 도움 웹 서비스 개발

<br/>

# 주요 기능

### 상품 정보 제공 서비스
- 네이버 쇼핑 리뷰 데이터를 크롤링하여 해당 상품에 대한 리뷰의 주제별 키워드 및 핵심 문장을 추출하여 제공한다.
- 크게 6단계(전처리, 감성분석, 문장임베딩, 클러스터링, 키워드 및 핵심문장 추출)에 걸쳐 자연어 처리를 진행한다.
<img src="https://user-images.githubusercontent.com/76774056/210547469-473296ae-e9e2-4f30-b063-8479e3d67883.png">
💡해당 로직을 기반으로 기재한 논문 (전자거래학회 2022년 추계학술대회)<br>
[상품 리뷰에 대한 효과적인 핵심 내용 추출 방법.pdf](https://github.com/graduationProject-yourEyes/.github/files/10343787/default.pdf)

<br /><br />
### 뉴스 요약 서비스
- 하루에 2번 네이버 뉴스 데이터를 크롤링 하여 주제별 뉴스 제공 및 한 줄 요약 서비스를 제공한다.
<img src="https://user-images.githubusercontent.com/76774056/210547659-7c4ec146-a5b0-4628-8567-8449d66cc846.png">

# 주요 화면

### 오늘의 뉴스
<img src="https://user-images.githubusercontent.com/76774056/210544392-20d5031f-dba9-4985-be59-8ebbcdc173d6.png">
<br />

### 오늘의 상품 
<img src="https://user-images.githubusercontent.com/76774056/210545558-5fe161e4-cf43-4e98-be0f-a8d51c2b1538.png">
<br />

### 시각장애인을 고려한 기능
<img src="https://user-images.githubusercontent.com/76774056/210545595-2aacfc91-cf3e-4f7d-a751-dc9ed4200b3a.png">
<img src="https://user-images.githubusercontent.com/76774056/210547115-8b9367f6-c1bf-4cca-9751-050b4e8ee53f.png">

# 서비스 아키텍처 및 ERD Diagram
<img src="https://user-images.githubusercontent.com/76774056/210544251-414cab20-2c6f-4a92-8e40-20783c12dd5a.png">


### Members
<table>
<tr>
    <td align="center"><a href="https://github.com/0standing2"><img src="https://github.com/0standing2.png" width="100px;" alt=""/><br /><sub><b>윤서영(NLP, BE)</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/minjung-sys"><img src="https://github.com/minjung-sys.png" width="100px;" alt=""/><br /><sub><b>조민정(NLP, FE)</b></sub></a><br /></td>
<tr>
</table>
