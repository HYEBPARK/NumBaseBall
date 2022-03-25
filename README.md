## ⚾ 숫자 야구 게임

- 랜덤으로 발생한 숫자를 맞추는 게임입니다.
- 숫자의 길이는 **baseball/engine/BaseBall.java**의 **COUNT_OF_NUMBERS** final 상수를 통해 확장가능 (기본 : 3)
- **정답을 미리 확인하고 싶을때** :  **baseball/App.java 에서 NumberGenerator** 생성자를 **baseball/HackFakerNumberGenerator.java**로 인스턴스 생성 **(기본 설정) **
- **정답을 미리 확인하고 싶지 않을때** : **FakerNumberGenerator()**로 생성

## 🌳 프로젝트 tree
 
 src
    ├── main
    │   ├── java
    │   │   └── com
    │   │       └── programmers
    │   │           └── java
    │   │               └── baseball
    │   │                   ├── App.java
    │   │                   ├── Console.java
    │   │                   ├── FakerNumberGenerator.java
    │   │                   ├── HackFakerNumberGenerator.java
    │   │                   └── engine
    │   │                       ├── BaseBall.java
    │   │                       ├── io
    │   │                       │   ├── Input.java
    │   │                       │   ├── NumberGenerator.java
    │   │                       │   └── Output.java
    │   │                       └── model
    │   │                           ├── BallCount.java
    │   │                           └── Numbers.java
    │   └── resources
    └── test
        ├── java
        └── resources
        
 - [velog - 숫자 야구 게임](https://velog.io/@hye_b/TIL-%EC%88%AB%EC%9E%90-%EC%95%BC%EA%B5%AC-%EA%B2%8C%EC%9E%84)
