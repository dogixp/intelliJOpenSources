# intellij Community Edition 

## Spring Boot + Git  + Gradle 프로젝트 구성

### 구성 전 사전 설치 필요 항목

#### git bash 설치
* Github 프로젝트 임포트 시 필수 입니다.  

[git bash 다운로드](https://git-scm.com/downloads) 사이트 이동 후 OS 환경에 맞게 Standalone Installer를 다운로드 진행 하시면 됩니다.

![gitbash](https://user-images.githubusercontent.com/51108248/183009646-62ec4c1f-3efc-4f38-9ed0-53cb518b86bb.PNG)



#### Gradle 설치

* Gradle  (JDK 1.8이상에서 사용 가능) : build 1.8.0_151-b12이상
  [openJDK사이트](https://jdk.java.net/java-se-ri/8-MR4)에서 다운로드 시 최소 JDK9 이상에서 사용 가능합니다. 
 해당 사이트에 있는 JDK8은 ``build 1.8.0_42-b03`` gradle이 최소 지원하는 JDK버전 보다 하위 버전입니다.

  ![javaversion](https://user-images.githubusercontent.com/51108248/182503565-9052c8d8-5f2f-4179-9d6e-9b23d6c75c53.PNG)


  [gradle 다운로드](https://gradle.org/releases/)

* 설치 완료 후 path 설정 필요 (path , GRADLE_HOME 설정) 
* version 확인  (cmd 창에서 단축키 : 윈도우 + R -> cmd입력) 버전 관련 내용이 출력되면, 설치 완료.

```
 gradle -v
```

* GRADLE_HOME_USER 패스를 설정하면, IntelliJ에서 ``자동``으로 스캔합니다.
  GRADLE_HOME_USER 패스를 설정하지 않아도, IntelliJ에서 ``수동``으로 설정 가능합니다.




