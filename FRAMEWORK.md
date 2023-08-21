# intellij Community Edition 

## Spring Boot + Git  + Gradle 프로젝트 구성

### 구성 전 사전 설치 필요 항목

* git bash, gradle, jdk

#### git bash 설치
* Github 프로젝트 임포트 시 필수 입니다.  

[git bash 다운로드](https://git-scm.com/downloads) 사이트 이동 후 OS 환경에 맞게 Standalone Installer를 다운로드 진행 하시면 됩니다.

![gitbash](https://user-images.githubusercontent.com/51108248/183009646-62ec4c1f-3efc-4f38-9ed0-53cb518b86bb.PNG)



#### Gradle 설치

* Gradle  (JDK 1.8이상에서 사용 가능) : build 1.8.0_151-b12이상
  [openJDK사이트](https://jdk.java.net/java-se-ri/8-MR4)에서 다운로드 시 최소 JDK9 이상에서 사용 가능합니다. 
 해당 사이트에 있는 JDK8은 ``build 1.8.0_42-b03`` gradle이 최소 지원하는 JDK버전 보다 하위 버전입니다.  

  [어떤 JDK를 써야 할까?](https://github.com/dogixp/intelliJOpenSources/blob/master/JDK.md)
 

  ![javaversion](https://user-images.githubusercontent.com/51108248/182503565-9052c8d8-5f2f-4179-9d6e-9b23d6c75c53.PNG)


  [gradle 다운로드](https://gradle.org/releases/)

* 설치 완료 후 path 설정 필요 (path , GRADLE_HOME 설정) 
* version 확인  (cmd 창에서 단축키 : 윈도우 + R -> cmd입력) 버전 관련 내용이 출력되면, 설치 완료.

```
 gradle -v
```


#### Spring Initializr and Assistant ( SpringBoot 자동완성 플러그인)

* 2022.1.2 버전 까지는 무료 
* 2022.2.1 부터 유료 플러그인으로 전환  ( 구독 방식)
* 플러그인 명칭이 ``Spring Boot Helper`` 로 변경 되었습니다.


![SpringBootHelper](https://user-images.githubusercontent.com/51108248/184289435-40d6cddb-91e6-4f36-b06e-d1575c10e504.PNG)