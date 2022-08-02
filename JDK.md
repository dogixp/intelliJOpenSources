# 어떤 JDK를 써야 할까?
## JDK 버전별 소개 및 OpenJDK 벤더별 종류
#### whichjdk.com은 다양한 JDK의 특성과 Release 기간 등을 정리해 놓은 사이트로 openJDK 선택 시 참고할만 합니다.

-- 자료출처: https://whichjdk.com/

---

## JDK release model


| JDK 버전 | 타입     | 릴리즈 연월 | 특징               |
| ---------- | ---------- | ------------- | -------------------- |
| 8        | **```LTS```**  | 2014/03     | Lambdas            |
| 9        | non‑LTS | 2017/09     | Modules            |
| 10       | non‑LTS | 2018/03     | var                |
| 11       | **```LTS```**  | 2018/09     | New HTTP Client    |
| 12       | non‑LTS | 2019/03     |                    |
| 13       | non‑LTS | 2019/09     |                    |
| 14       | non‑LTS | 2020/03     | Switch expressions |
| 15       | non‑LTS | 2020/09     | Text blocks        |
| 16       | non‑LTS | 2021/03     | Records            |
| 17       | **```LTS```**  | 2021/09     | Sealed Classes     |
| 18       | non‑LTS | 2022/03     | UTF-8 by Default   |

* LTS(Long Term Support)는 장기 지원되는 버전을 의미 (JDK8,11,17)

## JDK 및 OpenJDK 벤더별 종류


| 배포본                                  | 권장사항                                                                                                                           |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| OpenJDK builds by Oracle (jdk.java.net) | LTS 버전을 계속 사용하려는 경우에는 Oracle에 의한 OpenJDK 빌드를 사용하지 마십시오.                                                |
| Oracle Java SE Development Kit (JDK)    | 변호사와 상담하기 전에 Oracle Java SE Development Kit(JDK)를 사용하지 마십시오.                                                    |
| **```Adoptium Eclipse Temurin```**     | ```Adaptium Eclipse Temurin OpenJDK 빌드를 사용하는 것이 좋습니다.```                                                                    |
| AdoptOpenJDK                            | 더 이상 AdoptOpenJDK를 사용하지 마십시오. 대신 Adoptium Eclipse Temurin을 사용하십시오.                                            |
| **```Azul Zulu```**                           | ```OpenJDK의 Azul Zulu 빌드가 좋은 선택입니다.```                                                                                        |
| Azul Zing                               | GC 일시 중지 시간이 문제인 경우 Azul Zing / Azul Platform Prime을 고려하십시오. 라이센스 없이 프로덕션 환경에서 사용하지 마십시오. |
| **```BellSoft Liberica JDK```**               | ```BellSoft Liberica JDK 빌드는 좋은 선택입니다.```                                                                                      |
| **```IBM Semeru Runtime```**                  | ```OpenJ9 가상 시스템이 필요한 경우에만 IBM Semeru Runtime을 사용하십시오.```                                                            |
| **```Amazon Corretto```**                     | ```특히 AWS의 Amazon Linux 2에서 Java 애플리케이션을 직접 실행하는 경우에는 Corretto 빌드가 좋습니다.```                                 |
| **```Microsoft Build of OpenJDK```**          | ```Azure에서 Java 애플리케이션을 직접 실행하는 경우에만 Microsoft Build of OpenJDK를 사용하십시오.```                                    |
| Alibaba Dragonwell                      | 정부에서 강제하지 않는 한 Alibaba Dragonwell을 사용하지 마십시오.                                                                  |
| **```SapMachine```**                          | ```SAP 서버에서 Java 애플리케이션을 실행하는 경우에만 SAP 시스템을 사용하십시오.```                                                      |
| **```Red Hat OpenJDK```**                     | ```Red Hat Enterprise Linux에서 Java 애플리케이션을 직접 실행하는 경우에만 Red Hat OpenJDK를 사용하십시오.```                            |
| GraalVM                                 | 검증된 권장 사항을 자세히 설명할 수 있도록 프로덕션의 Graal VM에 대한 경험을 공유하십시오.                                         |

---

### Liberica JDK (feat. BellSoft)

* https://spring.io/quickstart
* spring.io 사이트에서 Liberica JDK 버전 8 또는 11 사용을 권장한다는 내용

  <img src="https://img.shields.io/badge/OpenJDK-1F6B75?style=for-the-badge&logo=OpenJDK&logoColor=black">

