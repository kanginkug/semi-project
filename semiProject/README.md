
<div align="center">
<h1>🎺 Culture Shock 🎺</h1>
</div>



#### 공연의 모든 정보 컬쳐쇼크

> 어떤 공연을 볼지 고민중이신가요? <br>
> 뮤지컬, 연극, 국악, 클래식의 정보가 한 곳에 모였습니다! <br>
> 검색부터 예매까지 시작과 끝을 컬쳐쇼크와 함께해보세요! <br><br>
> 개발 기간 : 2022.07.11 ~ 2022.08.16

<br>
<br>

## 💡 프로젝트 구조

```
└─semi
            │      └─culture
            │          ├─common
            │          │  ├─filter
            │          │  ├─jdbc
            │          │  ├─util
            │          │  └─wrapper
            │          ├─mvc
            │          │  ├─member
            │          │  │  ├─controller
            │          │  │  └─model
            │          │  │      ├─dao
            │          │  │      ├─service
            │          │  │      └─vo
            │          │  ├─noticeboard
            │          │  │  ├─controller
            │          │  │  └─model
            │          │  │      ├─dao
            │          │  │      ├─service
            │          │  │      └─vo
            │          │  ├─qnaboard
            │          │  │  ├─controller
            │          │  │  └─model
            │          │  │      ├─dao
            │          │  │      ├─service
            │          │  │      └─vo
            │          │  ├─reviewboard
            │          │  │  ├─controller
            │          │  │  └─model
            │          │  │      ├─dao
            │          │  │      ├─service
            │          │  │      └─vo
            │          │  └─show
            │          │      ├─controller
            │          │      └─model
            │          │          ├─dao
            │          │          ├─service
            │          │          └─vo


```

<br>
<br>



## 💡 DB ERD
![image](https://github.com/kanginkug/semi-project/assets/83181058/08c42409-81ce-4104-b4a8-5a9c032c9a43)


<br>
<br>

## 💡 시스템 구성도

![시스템 구성도](https://github.com/kanginkug/semi-project/assets/83181058/7b147917-6e28-421a-a082-ac4d0c68af4d)

<br>
<br>

## 💡 기술 스택 및 사용 API

![기술](https://github.com/kanginkug/semi-project/assets/83181058/640cdb3d-2cba-44e0-b049-ac6775f01a3d)



<br>
<br>

## 💡 서비스 핵심 기능

### ✔main
[cultureMain.webm](https://github.com/kanginkug/semi-project/assets/83181058/c7fc8d14-d48d-47c0-be97-69fc272986a8)


#### 1. 상단 배너
뮤지컬, 연극, 클래식, 국악, 게시판, 로그인, 회원가입, 마이페이지로 넘어갈 수 있습니다.
마우스 오버 이벤트를 이용해 사용자가 클릭하는 행위를 자연스럽게 느낄 수 있습니다.
#### 2. 검색
전체 카테고리 키워드 검색이 가능합니다.
하단에는 각 카테고리의 추천 공연을 슬라이드 형식으로 확인할 수 있습니다.
#### 3. 중단 섹션
네비게이션 탭을 이용해 각 카테고리의 조회수가 높은공연을 확인할 수 있습니다.
#### 4. 하단 섹션
지역별로 조회수가 높은 공연들과 최근 리뷰, 공지, QnA 게시판의 게시글을 확인할 수 있습니다.

<br>
<br>
### ✔Musical Main
![뮤지컬 추천](https://github.com/kanginkug/semi-project/assets/83181058/ff8985ca-324a-461b-a335-c9b4e7d328bd)


#### 1. 검색 영역
공연명, 출연진, 지역, 날짜로 필터링해 원하는 뮤지컬을 검색할 수 있습니다.
#### 2. 가운데 섹션
조회수가 높은 추천 뮤지컬을 슬라이드 방식으로 확인할 수 있습니다.


![뮤지컬 전체목록](https://github.com/kanginkug/semi-project/assets/83181058/82a9f492-b7f5-4c54-a99a-9598545ebaf1)
<br>
<br>
#### 3. 하단 섹션
뮤지컬 목록을 확인할 수 있고 더보기 버튼을 누르면 전체 뮤지컬 목록을 확인할 수 있습니다.
<br>

<br>

### ✔Musicla Detail
![뮤지컬 상세](https://github.com/kanginkug/semi-project/assets/83181058/c89b4249-d43f-4eae-b6f0-8b0cfb87f524)


#### 1. 상세 정보
상세정보와 스토리를 네이게이션 탭을 이용해 확인할 수 있습니다.
#### 2. 상세 이미지 정보
상세이미지 버튼을 클릭하면 해당 뮤지컬의 상세 이미지 정보가 펼쳐져 더 자세한 정보를 확인할 수 있습니다.



### ✔Musical Reservation
[musicalReservation.webm](https://github.com/kanginkug/semi-project/assets/83181058/3c2a5407-d37a-4d56-a418-5f8d8346e529)

#### 1. 예매하기
pick-date 폼으롤 날짜를 선택하고 관객정보, 인원, 좌석정보를 선택 후 결제버튼을 누르면 예매가 완료됩니다.
해당 예약은 마이페이지에서 확인할 수 있고 취소 또한 가능합니다. 비회원은 해당 버튼을 사용할 수 없습니다.
<br>
<br>
### ✔My Page
[MyPage (2).webm](https://github.com/kanginkug/semi-project/assets/83181058/b5a1c232-c279-4629-aa5f-6aee16525d27)

#### 1. 네비게이션 탭
현재 예매내역, 공연날짜가 지난 과거예매내역, 사용자가 작성한 리뷰, 찜목록을 확인할 수 있습니다.
예매내역 공연에선 예매취소가 가능합니다.
과거예매내역에서 공연을 클릭하면 리뷰작성이 가능한 페이지로 이동할 수 있습니다.
사용자가 작성한 리뷰에선 리뷰 삭제,수정이 가능합니다.
찜목록에선 공연상세페이지로 넘어가 찜삭제가 가능합니다.

<br>
<br>
### ✔My Favorite
[favorite.webm](https://github.com/kanginkug/semi-project/assets/83181058/6b7845b3-fda3-4821-8bb9-101458eec1e8)

#### 1. 찜하기
찜하기를 해 마이페이지에서 확인할 수 있습니다. 비회원은 해당 버튼을 사용할 수 없습니다.

<br>
<br>
[ CultureShock의 더 자세한 설명
[culture_shock.pdf](https://github.com/kanginkug/semi-project/files/12827648/culture_shock.pdf)



<br>
<br>
                        




