# Wisetracker Integration Guide
'더블유컨셉' 앱, 웹, 모바일웹에 와이즈트래커를 연동하는데 필요한 기술문서입니다. 연동 중 발생하는 문의사항은 아래 연락처로 보내 주시기 바랍니다.

> 와이즈트래커 개발팀, tech@wisetracker.co.kr, humblejohn@wisetracker.co.kr



# Index

* [클릭 분석 API](./wconcept.md#클릭-분석-API)
	* [적용 예시](./wconcept.md#적용-예시)
	* [매핑 테이블](./wconcept.md#매핑-테이블)



## 클릭 분석 API

아래 매핑 테이블에 있는 버튼, 메뉴 등이 클릭되는 시점에 코드를 추가합니다.



**앱용 코드**

``` javascript
WiseTracker.sendClickData("EVT", "name");
// name은 매핑 테이블 참고
```

**PC & 모바일웹용 코드**

``` javascript
_trk_clickTrace(\"EVT\", \"name\");
// name은 매핑 테이블 참고
```



#### 적용 예시

유저가 앱의 메인 페이지 상단에 있는 검색버튼(돋보기)을 클릭하는 경우, 클릭이 발생한 시점에 아래 코드 추가.

``` javascript
WiseTracker.sendClickData("EVT", "[M_SEARCH]");
// name은 매핑 테이블 참고
```

유저가 PC 웹사이트의 메인 페이지 상단에 있는 검색버튼(돋보기)을 클릭하는 경우, 클릭이 발생한 시점에 아래 코드 추가.

``` javascript
_trk_clickTrace(\"EVT\", \"[SEARCH]\");
// name은 매핑 테이블 참고
```


#### 매핑 테이블

| 분류 | 대상 | 객체 | name | 참고 설명 |
| --- | --- | --- | --- | --- |
| PC | 메인 페이지 | 검색버튼(돋보기) | [SEARCH] | [참고 이미지](http://www.wisetracker.co.kr/wp-content/uploads/2020/05/wcon000.png) |
| PC | GNB -> NEW | 상품 배너 1번 | [GNB_NEW_BANNER1] | [참고 이미지](http://www.wisetracker.co.kr/wp-content/uploads/2020/05/wcon002.jpg) |
| PC | GNB -> NEW | 상품 배너 2번 | [GNB_NEW_BANNER2] | |
| PC | GNB -> NEW | 상품 배너 3번 | [GNB_NEW_BANNER3] | |
| PC | GNB -> NEW | 상품 배너 4번 | [GNB_NEW_BANNER4] | |
| PC | GNB -> BRAND | 브랜드 배너 1번 | [GNB_BRAND_BANNER1] | [참고 이미지](http://www.wisetracker.co.kr/wp-content/uploads/2020/05/wcon003.jpg) |
| PC | GNB -> BRAND | 브랜드 배너 2번 | [GNB_BRAND_BANNER2] | |
| PC | GNB -> BRAND | 브랜드 배너 3번 | [GNB_BRAND_BANNER3] | |
| 모바일웹 & APP | 메인 페이지 | 검색버튼(돋보기) | [M_SEARCH] | [참고 이미지](http://www.wisetracker.co.kr/wp-content/uploads/2020/05/wcon001.jpg) |
| 모바일웹 & APP | 검색 페이지 | 하단 배너 | [M_SEARCH_BANNER] | [참고 이미지](http://www.wisetracker.co.kr/wp-content/uploads/2020/05/wcon004.jpg) |
| 모바일웹 & APP | LNB | 하단 배너 | [M_LNB_BANNER] | [참고 이미지](http://www.wisetracker.co.kr/wp-content/uploads/2020/05/wcon005.jpg) |
