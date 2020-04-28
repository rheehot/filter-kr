# filter-kr

**uBlock** filter for websites (mainly Korean) which has ad but didn't erase.

- [Discord 서버에서 업데이트 받기](https://discordapp.com/invite/vAEBXWY)

## 목차

- [설치하기](#설치하기)
- [필터](#필터), 현재 제공하는 필터 목록입니다.

----

# 설치하기

1. 웹 브라우저에서 uBlock 확장 프로그램 팝업을 열고 대시보드를 엽니다.

2. 보조 필터 탭을 끝까지 내려 사용자 지정 보조 필터의 불러오기 체크박스를 클릭하고 올바른 필터 URL(아래의 필터 섹션을 참조)을 추가합니다.

3. 우측 상단의 '변경 사항 적용' 버튼을 클릭하고 스크롤을 가장 위로 올려 '지금 업데이트' 버튼을 클릭합니다.

## 업데이트하기

1. 웹 브라우저에서 uBlock 확장 프로그램 팝업을 열고 대시보드를 엽니다.

2. 보조 필터 탭에서 Seia-Soto/filter-kr 필터를 찾은 다음 옆의 시계 아이콘을 클릭하고 스크롤을 가장 위로 올려 '지금 업데이트' 버튼을 클릭합니다.

# 필터

필터 URL을 얻으려면 아래에서 필터를 선택한 다음 필터 파일에서 `raw` 버튼을 우클릭 후 링크를 복사하면 됩니다.

## `base`

기본으로 제공하는 필터입니다. 사용하면서 주기적으로 제거되지 않은 광고가 있다면 필터에 추가합니다.

- [filter.txt](filter.txt)

## `extra`

추가 필터입니다. 특정 목적에 따라 따로 만듭니다.

### [`twitterTrends.txt`](extra/twitterTrends.txt)

트위터 웹 앱 우측에 표시되는 트랜드를 제거합니다.

### [`ebsocPopup.txt`](extra/ebsocPopup.txt)

EBS 온라인클래스에서 표시되는 팝업과 로그인 페이지의 간접 광고를 제거합니다.
