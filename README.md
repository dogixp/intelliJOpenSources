# IntelliJ Community Edition 2022.1.3 Tutorial

-- intelliJOpenSources

### IntelliJ User interface

---

#### User Interface structure

<img width="900" src="https://resources.jetbrains.com/help/img/idea/2022.1/ij_mainWindow_default.png">

#### IntelliJ 툴에서 F1 단축키를 누르면, 시작하기 가이드 페이지로 이동

# settings

## appearance

* use custom font : ```시스템 폰트 ( 변경시 툴 모든 화면에서 서체가 변경됨.)```
* Editor -> Font : ```에디터 폰트 ```
* Editor -> File Encodings : ```프로젝트 인코딩 방식 변경 가능 (properties ascii 변환여부 설정 가능)```
*

## keymap ( get more keymaps in Settings | Plugins )

* ``Based on Eclipse Keymap (이클립스 keymap)``
* ``이클립스에서 사용하던 단축키를 일부 사용 가능``
* ``intelliJ <-> 이클립스를 스위칭 하면서 사용하는 경우 유용한 기능``

### keymap settings

*단축키 추가설정*

* Add keyboard shortcut (키보드 단축키 추가)
* Add mouse shortcut    (마우스 단축키 추가)
* Add abbreviation

  * 약어 추가 기능. 단축키로 추가하긴 애매하고, 알고는 있어야 할 때 사용
  * 추가 시킨후 더블 shift ( Main Menu -> Navigate -> Search EveryWhere ) 실행후 추가한 약어 검색

-- 그외 (에디터에서 주로 쓰이는 기능 eclipse keymap 기준)

* Select File in Project View : ``에디터 선택된 파일이 좌측에 있는 Project View(Project tool Window)에 해당 파일이 표시된다. ``
* Always Select Opened File ( 이전에는 AutoScroll from Source로 불리던 기능 ) :  ``활성화시 에디터에서 선택된 파일은 항상 Project View에 해당 파일이 표시된다.``
* Ctrl + T : method 위에서 단축키 입력시 해당 method로 이동하거나, 인터페이스 구현체인 경우 구현체 method로 이동한다.
* Ctrl + Click : method 위에서 단축키 입력시 해당 method로 이동합니다.
* Ctrl + L : 라인번호를 입력하면, 해당 라인으로 바로 이동
* Ctrl + E : 최근 편집한 파일 찾기
* Ctrl + H : 특정 문자가 들어있는 파일 찾기

### Plugins (marketplace)

* eclipse marketplace와 비슷하지만, UI가 직관적임.
* 설치 및 제거가 용이

#### 유용한 플러그인

*CodeGlance Pro*

* 우측에 미니맵 형태로 나타나게 됨. 원하는 위치로 쉽게 이동 가능.

  ![CodeGlance Pro](https://user-images.githubusercontent.com/51108248/181162792-1337e0bd-8235-49dd-a554-9da13279f5a4.PNG)

---

*GitToolBox*

* 소스에 선택한 라인에 커밋한 계정/시간/커멘트를 볼 수 있다.

  ![GitToolBox](https://user-images.githubusercontent.com/51108248/181162625-0df38b53-6ea6-4d70-a707-bd0838491813.PNG)

---

*Key Promoter X*

* 툴에서 마우스 클릭으로 인해 동작하는 기능에 대해 단축키를 알려준다.
* 단축키 숙지하는데 용이

![keyPromoterX](https://user-images.githubusercontent.com/51108248/181167429-e3631dee-ad72-4085-b7b3-0774dd7f1e6c.PNG)

---

*Spring Initializ and Assistant*

* 유료버전 Ultimate 기본적으로 포함되어 있지만, 커뮤니티 버전은 따로 설치 해야 한다.
* New 프로젝트 생성시 Spring 애플리케이션 개발 지원 자동완성 기능
* start.spring.io 사이트에서 Spring Initializr 통해 프로젝트를 생성 하던 기능을 플러그인을 통해 지원.
* spring helper라는 명칭으로 바뀌고, 유료 버전으로 변경되었습니다. (30일 체험판 이용 가능)

  ![spring](https://user-images.githubusercontent.com/51108248/181162087-f6c59678-3a64-4827-a102-bd14956cd2f5.PNG)

---

---

### Build, Execution, Deployment

#### Annotation Processors

* Enable annotation processing 활성화 : ``annotation 외부 라이브러리(lombok)등을 이용하기 위해 활성화 필요``
* 공통 적용되지 않으니, 프로젝트별로 따로 설정해 주어야 한다.

<img src="https://img.shields.io/badge/IntelliJ IDEA-000000?style=for-the-badge&logo=IntelliJ IDEA">
