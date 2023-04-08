# guide
## Hello world Test 만들기
- intellij
  - java, kotlin
- xcode
  - swift
- vscode
  - js

# intellij
kotlin, java based on **Junit5**

#### (1) 새 프로젝트 생성하기
- **JDK 11** or **JDK 8**
<img width="804" alt="스크린샷 2023-04-08 오후 9 49 03" src="https://user-images.githubusercontent.com/88091704/230722076-235032ac-a4b9-43ba-a6ee-41c87a917d82.png">

#### (2) test 빌드 확인하기
- build.gradle 에 test task 가 정상적으로 있는지 확인
  - kotlin based gradle
- import 된 Junit5 dependency 확인
  - 우측 코끼리 (gradle) -> Dependencies -> testCompileClasspath -> junit5 의존 확인
<img width="1714" alt="스크린샷 2023-04-08 오후 9 52 21" src="https://user-images.githubusercontent.com/88091704/230722193-72635c2a-6e60-4121-8d00-2df046c07032.png">

  - java based gradle
<img width="1725" alt="스크린샷 2023-04-08 오후 10 03 01" src="https://user-images.githubusercontent.com/88091704/230722617-18337bea-95eb-460e-adb9-96de614dd822.png">



#### (3) Hello world!
<img width="793" alt="스크린샷 2023-04-08 오후 9 59 26" src="https://user-images.githubusercontent.com/88091704/230722483-76d2f3ae-65e7-42f3-ae06-d56f40fca5d2.png">

### xcode
references
- [ios test project setting](https://zdodev.github.io/ios/xctest/Xcode-iOS-App-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%EC%97%90-Unit-Test-%EC%B6%94%EA%B0%80%ED%95%98%EA%B8%B0/)
- [unit test with swift](https://silver-g-0114.tistory.com/142)
- SwiftUI

<img width="730" alt="스크린샷 2023-04-08 오후 10 17 38" src="https://user-images.githubusercontent.com/88091704/230723961-34dcb479-3319-41ce-b664-0bc0eb77fc5d.png">

#### (1) Unit Test Bundle
<img width="1469" alt="스크린샷 2023-04-08 오후 10 20 56" src="https://user-images.githubusercontent.com/88091704/230723969-8c051d1e-928e-48fc-994a-0fd4cd5c2630.png">

#### (2) Hello wolrd!
- 유의 사항
  - import XCTest 확인
  - func 이름은 test prefix 로 시작해야한다.
<img width="1196" alt="스크린샷 2023-04-08 오후 10 31 36" src="https://user-images.githubusercontent.com/88091704/230724085-6f47842e-831a-428b-a8bf-5b0ae38ae579.png">

- test failed
<img width="1092" alt="스크린샷 2023-04-08 오후 10 32 59" src="https://user-images.githubusercontent.com/88091704/230724157-5d61246d-d71d-48b7-b6e4-325975ed10a3.png">


### vscode
references
 - [mocha vs jest](https://velog.io/@binimini/Mocha-vs-Jest-JS-Test-Framework)
- jest
  - [docs](https://jestjs.io/docs/getting-started)
  
#### (1) npm build
 <img width="1017" alt="스크린샷 2023-04-08 오후 11 04 48" src="https://user-images.githubusercontent.com/88091704/230725491-8fafc8e0-652b-464d-8069-6f708f8db806.png">

#### (2) package.json script 추가
<img width="914" alt="스크린샷 2023-04-08 오후 10 54 19" src="https://user-images.githubusercontent.com/88091704/230725515-2077df5e-941c-45d7-8b93-f44a2474de61.png">

#### (3) hello world!
<img width="791" alt="스크린샷 2023-04-08 오후 11 06 28" src="https://user-images.githubusercontent.com/88091704/230725529-26cc4a3f-3eca-40d9-b2b0-ba2c04ed4695.png">
<img width="608" alt="스크린샷 2023-04-08 오후 11 06 47" src="https://user-images.githubusercontent.com/88091704/230725549-96e288c7-1773-4e42-bd9d-6937ac2a4e36.png">
