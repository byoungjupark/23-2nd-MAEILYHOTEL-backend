<div align=center><img width="343" alt="maielyhotel_logo" src="https://user-images.githubusercontent.com/63541271/136644619-c71efda3-942d-458d-8085-8455f79952de.png"></div>

# MAEILYHOTEL Project
## Description
- 숙소 플랫폼 "데일리 호텔"을 모티브로 하여 국내 숙소 예약 서비스 개발
- 개발 기간 : 2021.08.17 ~ 2021.08.27
- 개발 인원 : Front-end 3명 Back-end 2명
- [Front-end GitHub link](https://github.com/wecode-bootcamp-korea/23-2nd-MAEILYHOTEL-frontend)
- 프로젝트 기간이 길지 않아 전체가 아닌 일부 기능에 집중해 기획했습니다.
- 개발은 초기 세팅부터 전부 직접 구현했으며, 아래 데모 영상에서 보이는 부분은 모두 백엔드와 연결하여 실제 사용할 수 있는 서비스 수준으로 개발한 것입니다.

<br>

## Demo Video
https://youtu.be/qDQXFb2oayE

<br>

## What I've done
- 숙소 검색 시 지역별, 날짜별 필터링 API를 구현하여 기능 고도화
- 불필요한 데이터를 줄이고자 Django Subquery와 Case, When 메소드를 사용하여 날짜별 잔여 방 개수 추출
- 유지보수를 고려하여 리뷰 생성 시 이미지 파일 업로드는 AWS S3로 진행
- 사용자의 요청에 따른 회원등급 변경 API 작성으로 등급별 할인율 적용

### My Application Demo
#### 숙소 지역별, 날짜별 검색 조회 기능
![](https://images.velog.io/images/byoungju1012/post/2d1e076c-7d25-4494-80ab-08f56293fb04/search.gif)

#### 숙소 종류별 조회 기능
![](https://images.velog.io/images/byoungju1012/post/34f1e5b4-c7b9-4b9c-a702-baa650db3b2e/list.gif)

#### 회원등급 변경 기능
![](https://images.velog.io/images/byoungju1012/post/020d11e9-bee3-4206-99ef-6773a3e838fe/userlevel.gif)

#### 리뷰 생성 기능
![](https://images.velog.io/images/byoungju1012/post/fa1a6657-44ee-45cd-9ad1-f021e3cc1745/review.gif)

<br>

## Tech Stack
- Front-End : React, sass
- Back-End : Python, Django web framework, Bcrypt, My SQL, Docker, S3, boto3
- Common : KAKAO social login, RESTful API, AWS(RDS/EC2)
- Communication: Slack, Trello, Goolge Docs

<br>

## Entity Relationship Diagram
- [Aquery URL](https://aquerytool.com/aquerymain/index/?rurl=9a7c97b5-1b11-4929-abf7-d8bbaeccd1a7&)
- Aquery password : avmk7m
- ERD as below
<img width="1034" alt="MAEILYHOTEL-modeling" src="https://user-images.githubusercontent.com/63541271/136644770-cec9f9eb-231e-4c45-95d1-e8c71a798b5f.png">


## Reference
- 이 프로젝트는 [DAILYHOTEL](https://www.dailyhotel.com/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.

