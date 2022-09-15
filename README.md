# springboot_webservice
웹 애플리케이션 개발 및 배포 학습

#### 해당 리포지토리는 이동욱님의 '스프링 부트와 AWS로 혼자 구현하는 웹 서비스'를 따라가며 학습하고 직접 구축하는 것을 위한 저장소입니다.
----
##### 학습 환경 (Macbook Air M1 2020)
- IntelliJ IDEA 2022.1.3 (Ultimate Edition)
- Spring Boot 2.1.7.RELEASE
- Java 1.8
---
##### 학습간의 변경 사항
- Gradle의 버전 업으로 인해 더 이상 의존성 명시할 때 'compile'이 사용되지 않는다. 이에 따라 변경된 'implementation'을 사용했다.
- Spring Security 5.5 이상의 버전을 사용할 시 '@EnableWebSecurity' 어노테이션과 webSecurityConfigureAdapter가 사용이 불가했다. 학습 교재를 따라가기 위해 부득이하게 Spring Security를 버전 다운했다. -> 해당 부분에서 오류가 발생할 경우, 낮은 버전으로 명시적으로 표시해 줄 필요가 있다. 
---
#### 배포 현황
- 현재 AWS를 통해 배포 중
- [게시판 링크](http://ec2-43-200-158-190.ap-northeast-2.compute.amazonaws.com:8080)
