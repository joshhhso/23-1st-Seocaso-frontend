# 서카소 (왓챠피디아 클론코딩)

<div align="center"> 
  <img alt="main" src="https://user-images.githubusercontent.com/79290170/129485664-93e1dafe-f31e-4baa-8ea8-eab834306aaa.png">
  <br>
  <br>
</div>

## Seocaso Project Teammate

- F.E<br>
  [소진수(PM)](https://github.com/joshhhso)<br>
  [문주영](https://github.com/moonjuyoung1)<br>
  [김다슬](https://github.com/cocacollllla/)<br>
  <br>
- B.E<br>
  [최혜림](https://github.com/rimi0108)<br>
  [장호준](https://github.com/bigfanoftim)<br> 
  <br>

## What is Seocaso Project?

- 영화란 영화는 다 모인 [왓챠피디아](https://www.watchapedia.com/) 클론 프로젝트
- 촉박한 프로젝트 기간이었지만 실제 사용가능한 사이트를 새롭게 제작고자 기획을 동시에 진행했습니다.
- "서울의 카페를 소개합니다"를 주제로 영화를 카페로 대체하여 소개하는 웹 사이트를 제작했습니다.
- wecode Bootcamp에서 배운 React, Javascript, HTML/CSS, Scss, Django, Python을 바탕으로 구현할 수 있는 기능들과<br>
  그 외에 툴인 Github, Git, Trello등 을 추가로 사용하여 프로젝트 진행을 관리했습니다.
- 개발은 초기 세팅부터 직접 구현했으며, 프론트와 백을 연결해 실제 사용 가능한 수준으로 개발했습니다.

### 개발 인원 및 기간

- 개발기간 : 2021/8/2 ~ 2021/8/13
- 개발 인원 : 프론트엔드 3명, 백엔드 2명
- [B.E github 링크](https://github.com/wecode-bootcamp-korea/23-1st-Seocaso-backend)

### 프로젝트 선정이유

- 평소 자주 이용하던 사이트 였으며 영화 추천기능과 평점 기능을 구현하고 싶었습니다.
- 유저에게 독단적인 정보 제공보다 다수의 정보를 수집하여<br>타 이용자에게 보다 나은 정보를 공유한다는 의미에 매력을 느꼈습니다.
- 실제 고민에서 시작하여 아이디어로 발전하였고 이를 필요로하는 니치가 있다고 판단했습니다.

## 적용 기술 및 구현 기능

### 적용 기술

> -Front-End : javascript, React.js framwork, sass<br>
> -Back-End : Python, Django web framework, MySQL, Bcrypt, pyjwt<br>
> -Common : POSTMAN, RESTful API

### 구현 기능
- 바닐라 자바스크립트로 구현

#### 회원가입 / 로그인페이지

- 회원가입 시 정규식을 통한 유효성 검사. (소문자, 대문자, 특수문자의 조합)
- 로그인을 이후 토큰 발행, 계정 활성화
- 계정 없을 시 바로 회원가입으로 이동할 수 있도록 구현
- 로그인 / 회원가입 모달창 구현

#### 메인페이지

- 바닐라 자바스크립트 캐러셀 구현(translateX)
- 별점 순, 리뷰 순 데이터에 따른 리스트 구현
- 검색바에서 키워드 검색시 검색결과 상단에 검색 값에 해당되는 카페 리스트 페이지로 이동.
- 하단 푸터를 통한 사이트 설명

#### 검색 페이지

- 키워드(카페명, 지역명) 필터링.
- 클릭시 상세 페이지로 이동.

#### 상세페이지

- **별점 기능 구현(currentTarget,nativeEvent)**
- **좋아요 기능 구현**
- **댓글 기능 구현**
- **이미지 모달창**
- **클릭시 상세 페이지로 이동**
- **데이터에 따른 그래프 자동기능 구현**
- **댓글 좋아요 기능 구현**

#### 마이페이지

- **별점 순, 별점 역순, 필터링 기능 구현**
- **캐러셀 기능 구현**
- **이미지 클릭시 상세페이지 이동**

#### 최종 결과물

  [![Video Label](http://img.youtube.com/vi/V38oqwMjnoI/0.jpg)](https://youtu.be/V38oqwMjnoI)

## Reference

- 이 프로젝트는 [왓챠피디아](https://www.watchapedia.com/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
