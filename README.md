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
- new project
- **JDK 11** or **JDK 8**
<img width="804" alt="스크린샷 2023-04-08 오후 9 49 03" src="https://user-images.githubusercontent.com/88091704/230722076-235032ac-a4b9-43ba-a6ee-41c87a917d82.png">

#### (2) test 빌드 확인하기
- build.gradle 에 test task 가 정상적으로 있는지 확인
  - 아래 이미지는 kotlin based gradle
  - groovy based gradle 은 아래와 같이 task 가 구성됨
  
  ``` groovy
  test {
    useJUnitPlatform()
  }
  ```
- import 된 Junit5 dependency 확인
  - 우측 코끼리 (gradle) -> Dependencies -> testCompileClasspath -> junit5 의존 확인
<img width="1714" alt="스크린샷 2023-04-08 오후 9 52 21" src="https://user-images.githubusercontent.com/88091704/230722193-72635c2a-6e60-4121-8d00-2df046c07032.png">

#### (3) Hello world!
<img width="793" alt="스크린샷 2023-04-08 오후 9 59 26" src="https://user-images.githubusercontent.com/88091704/230722483-76d2f3ae-65e7-42f3-ae06-d56f40fca5d2.png">

### xcode
swift

### vscode
js
