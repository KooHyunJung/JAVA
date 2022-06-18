## 윤성우 열혈 JAVA 프로그래밍

- [01 변수의 이해와 활용](#1)
- [02 상수와 형 변환](#2)
- [03 연산자](#3)

---

<a name="1"></a>

## 01 변수의 이해와 활용

- 변수
  - 메모리 공간의 활용을 위한 도구
  - 메모리 공간의 할당과 접근을 위해 필요한 도구
  - 변수의 선언은 "메모리 공간의 할당"으로 이어진다

> 변수의 선언을 통해 결정하는 것 두 가지 [변수의 이름] [변수의 용도]

```java
class UseVariable {
    pbilc static void main(String[] args) {
        int num1;
        num1 = 10;

        int num2 = 5;
        int num3 = num1 + num2;
        System.out.println(num2);
    }
}
```

### 자바의 기본 변수 자료형

<img width="852" alt="스크린샷 2022-06-18 오후 12 14 34" src="https://user-images.githubusercontent.com/96563289/174420730-3b64effc-5564-46d0-a94e-51c289ea0da2.png">

- 변수 이름 짖기
  - 자바는 대소문자를 구분한다
  - 변수의 이름은 숫자로 시작할 수 없다
  - $와 \_ 이외의 특수문자는 변수의 이름에 사용할 수 없다
  - 키워드는 변수의 이름으로 사용할 수 없다

<a name="2"></a>

## 02 상수와 형 변환

- **상수(constants)**
  - **자바에서 말하는 상수**
    - 변수에 값을 딱 한번만 할당할 수 있으면 그것은 상수
    - 한 번 할당된 값은 변경이 불가능하다
    - 키워드 fianl 선언이 붙어있는 변수
  - **final 기반의 상수 선언의 예**
    - 상수의 이름은 모두 대문자로 짓는 것이 관례
    - 이름이 둘 이상의 단어로 이뤄질 경우 단어를 언더바로 연결하는 것이 관례

```java
    final int MAX_SIZE = 100;
    final char CONST_SIZE = "상";
```

- **리터럴(Literals)**
  - 자료형을 기반으로 표현이 되는 상수를 의미한다
  - 정수는 무조건 int형으로 인식하기로 약속되어 있음
  - 따라서 5와 7은 "정수형 리터럴"이다
  - 3.3, 3.4는 "실수형 리터럴"이다

<a name="2"></a>

## 03 연산자

<img width="595" alt="스크린샷 2022-06-18 오후 1 45 51" src="https://user-images.githubusercontent.com/96563289/174423138-044c2a03-e20a-477e-9109-aba154ace212.png">

### 대입 연산자, 산술 연산자

<img width="598" alt="스크린샷 2022-06-18 오후 1 58 41" src="https://user-images.githubusercontent.com/96563289/174423700-b175aab6-5291-4bb9-88f3-09440b33db5d.png">

### 관계, 논리, 비트 연산자

<img width="759" alt="스크린샷 2022-06-18 오후 2 09 10" src="https://user-images.githubusercontent.com/96563289/174423828-ea69d261-b848-4f12-abdb-95e22fa45874.png">

<img width="761" alt="스크린샷 2022-06-18 오후 2 09 40" src="https://user-images.githubusercontent.com/96563289/174423840-d955d247-f85a-4352-bf2d-18276ba47d02.png">

<img width="757" alt="스크린샷 2022-06-18 오후 2 09 54" src="https://user-images.githubusercontent.com/96563289/174423849-0d4d222a-1b1a-4cc6-9af5-13be398e5b22.png">

### 증가 감소 연산자

<img width="598" alt="스크린샷 2022-06-18 오후 2 24 05" src="https://user-images.githubusercontent.com/96563289/174424112-f48cc4e4-09ca-4e29-86bb-49386c0316d8.png">

---

## 참고 링크

- https://nullmaster.tistory.com/134
- https://soliloquiess.github.io/study/2021/03/07/java_%EC%97%B0%EC%82%B0%EC%9E%90.html
