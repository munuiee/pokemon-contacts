
![ ](https://github.com/user-attachments/assets/e5f1a4a3-ecf6-4692-a957-7511ff918de1)


# 👾 pokemon-contacts
## iOS 앱 개발 숙련 주차 과제 - 포켓몬 연락처 앱 만들기

<br>

**포켓몬 연락처 앱** 

> 네트워크 통신을 이용해서 서버에서 랜덤 포켓몬 이미지를 불러오고, 연락처를 저장하는 앱을 개발합니다.

```swift
PokeContact
│
├─ Controller
│     ├─ MainViewController
│     └─ PhoneBookViewController
│
├─ Delegate
│     ├─ AppDelegate
│     └─ SceneDelegate
│
├─ Models
│     ├─ CoreDataManager
│     ├─ Entity+CoreDataClass
│     ├─ Entity+CoreDataProperties
│     ├─ PokeContact.xcdatamodeld
│     └─ Pokemon
│
├─ Utils
│     └─ PhoneFormatter
│
└─  View
      └─ TableViewCell
```

<br>

### 🛠️ 개발 환경
Xcode UIKit CodeBase ONLY <br>
SnapKit Library <br>
CoreData <br>

<br>

### 📆 프로젝트 기간
2025.09.26 - 2025.10.09

<br>

### 🖥️ 구현 기능
- 연락처 추가 / 수정 / 삭제
- Core Data에 연락처 이름, 전화번호, 이미지 URL 저장
- 저장된 연락처를 테이블 뷰 목록으로 표시
- 이미지 비동기 로드 + 캐싱 처리
- 이름순 정렬 
- View Lifecycle 활용해 데이터 갱신

<br>

### 🖥️ 추가 구현기능
1. 스와이프 삭제 및 편집 삭제 기능
2. 수정 또는 작성 중 뒤로가기 버튼 클릭시 알럿 띄우기


<br>

### 트러블 슈팅 & TIL

#### 🎯 트러블슈팅 모음
[pokemon-contacts](https://github.com/users/munuiee/projects/5)


#### 📝 TIL

[👾 포켓몬 연락처 앱 만들기 TIL](https://hachkoi.tistory.com/74)

