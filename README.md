# 📋 나의 메모


## 프로젝트 개요

#### 메모를 관리하는 앱입니다.
#### 메모앱은 사용자의 메모를 추가, 편집, 삭제하고 완료된 메모를 확인할 수 있는 기능을 제공합니다.
#### 또한, 카테고리별로 메모의 중요도를 나눌 수 있으며 무작위 강아지 이미지를 보여주고 더보기 버튼으로 새로운 강아지사진을 볼 수 있습니다.
#### 이 앱은 스토리보드를 사용하지 않고 MVC패턴을 채용하여 코드로 UI를 구성하였으며, Swift 언어와 Xcode 개발환경을 사용하여 개발되었습니다.

<br><br>
- - -
## 🛠️ 사용한 기술 스택 (Tech Stack)
<img src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=Swift&logoColor=white"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
- - -

<br><br>
- - -
## 🗓️ 개발 기간
* 2023-08-21(월) ~ 2023-09-01(금), 10일간
- - -
<br><br>

## 📌 주요 기능

* 		메모 화면 (ViewController):
    * 할 일 목록 보기, 완료한 일 보기, 강아지 사진 보기 화면으로 이동할 수 있습니다.
* 		메모 관리 기능 (TodoViewController):
    * 메모를 생성, 편집 및 스와이프 하여 삭제할 수 있는 기능이 있습니다.
    * 메모는 중요도에 따라 세 가지 카테고리로 분류됩니다.
    * 메모는 완료 여부에 따라 스위치로 표시되며, 완료된 메모는 취소선이 그어집니다.
    * 메모는 추가 버튼을 통해 다이얼로그 형태로 작성할 수 있습니다.
* 		완료된 메모 보기 (CompleteViewController):
    * 완료된 메모 목록을 표시하는 화면입니다.
    * 완료된 메모는 수정할 수 없으며, 스위치는 비활성화됩니다.
* 		메모 상세 보기 및 편집 (DetailViewController):
    * 메모의 내용을 상세하게 보여주고 편집할 수 있는 화면입니다.
    * 메모 내용 변경 후 뒤로 가기 시 자동으로 변경된 내용이 반영됩니다.
* 		무작위 강아지 이미지 표시 (ShowDogViewController):
    * DogApi를 이용해 강아지 이미지를 무작위로 가져와서 표시하는 화면입니다.
    * "더 보기" 버튼을 클릭하면 새로운 무작위 강아지 이미지가 표시됩니다.
    * 네트워킹을 통해 이미지를 가져오는 동안 로딩중인 아이콘을 표시하여 사용자가 인지 할 수 있습니다.

- - -

## 💥 미완성된 기능

#### ⭐️ 추가할 기능
- 앱의 디자인에 맞는 폰트 색상 
- 메모 상세보기 페이지에서 카테고리 변경 기능
<br><br>

#### 🚨 확인된 오류
- 메모 편집(완료여부, 수정, 추가)시 다른 메모에 취소선이 그어지는 이슈
<br><br>

#### ✅ 해결된 오류

