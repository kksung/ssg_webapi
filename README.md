# 프로젝트 소개
> Flask Web Framework를 활용한 웹사이트 구축 및 기능 구현


## 웹사이트 구축 - 한걸음, first-step
1 - 사용자들 간 자유로운 대여 커뮤니티 환경 생성 2 - 공공 기관 대여 환경을 조성하여

   한걸음 더 좋은 세상으로 나아가는 통합 대여 사이트(플랫폼)입니다. 

<br>

## 프로젝트 기획
1. DB 구성
2. 페이지 기능 구현
3. 공공 데이터 작업&통합

<br>

## 팀명, 도메인
> 한걸음
> > first-step.shop (가비아에서 구매)

<br>

## 아키텍처
> 클라이언트 (Web) <-> Flask <-> MySQL 
<img src='https://github.com/kksung/ssg_project/assets/110016279/d622d7bc-cba7-44e9-ac33-106911ee1cb3'>

- front-end, back-end, DB  

<br>

## 역할 분담
|담당|이름|역할|
|---|---|---|
|팀원|김기성|로그인 기능, ppt 작성 및 발표|
|팀장|김서연|회원가입 기능, DB table(SQL), EC2|
|팀원|신명호|회원탈퇴 기능, 기획서 작성|
|팀원|조수아|게시글 작성 및 수정 기능, 게시글 페이징, HTML/CSS|

<br>

## DB ERD
<img src="https://github.com/kksung/ssg_project/assets/110016279/041ca7d6-d65f-49a6-b8b3-874038dfd9d8" width=700 height=500>

<br>

## DB, back-end 연동
> MySQL 설치 및 DB 생성 -> 생성한 DB와 Flask 연동

```
db = pymysql . connect(host="localhost", 
                     user="root", password="passwd", 
                     db="test3",
                     charset="utf8")
```

- user, password, db의 값은 사용자에 맞추어 변경

<br>

## 기능 flow
<img src="https://github.com/kksung/ssg_project/assets/110016279/80774f48-7023-42c5-8ecc-b97357e5dd4b" width=730 height=550>

<br>

## 느낀점
- 프로젝트 기간 내 완수 가능한 적절한 목표 및 분량 설정의 중요성
- 분담한 역할 수행 도중 해결하기 어려운 문제가 있을 때 팀에 진행상황 공유 및 도움 요청이 필요
  - 혼자 해결하는 것도 중요하지만 적절한 밸런스 찾기

<br>

## 피드백
- 도메인 접근통제부분
  - 안보이는 게시글도 도메인에 검색하면 나오는 문제 발생 
- API라는 용어보다는 기능이라는 용어가 더 적절 
- 도메인을 구매하여 진행한 것은 긍정적

<br>

## 레퍼런스
[참고 팀원](https://github.com/Suah-Cho/SSG_PROJECT01)
