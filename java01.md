## 윤성우 열혈 JAVA 프로그래밍

> 자바 8버젼

- [01 자바 프로그램과 실행 원리에 대한 이해](#1)
- [02 자바 프로그램의 관찰과 응용](#2)

---

<a name="1"></a>

## 01 자바 프로그램과 실행 원리에 대한 이해

<img width="500" alt="스크린샷 2022-05-29 오후 7 31 32" src="https://user-images.githubusercontent.com/96563289/170863902-b79b8a57-f36d-4832-8b4b-982c6c661606.png">

- 일반적인 구조는
  - 운영체제가 프로그램을 실행 시켜주는 구조이다.

> 여기서 자바 프로그램을 실행시킬 때 다른 점은 !

- **자바 프로그램이 실행되기 위해서는**
  - 먼저 `자바 가상 머신`이 실행되어야 한다

> 이것은 자바만의 도특한 구조가 아니라 `가상 머신` 위에서 동작하는 형태의 소프트웨어 산업 여러 곳에서 존재하고 있다.

<img width="414" alt="스크린샷 2022-05-29 오후 7 40 13" src="https://user-images.githubusercontent.com/96563289/170863912-ec44447d-896e-451a-8368-fa82460b33cd.png">

- 자바 장점!!
  - **자바 프로그램을 한번 적성하면 모든 운영체제에서 동작 가능하다**
    - 반대 예시로 C 언어는 운영체제마다 코드를 다시 작성해야 한다.
    - 프로그램이 운영체제에 의존적이기 때문이다
    - 이를 자바에서는 가능하게 하는 요인이 바로 `가상 머신`이다

<details>
  <summary>
    <h3> 자바 컴파일러와 자바 바이트코드 </h3>
  </summary>

- **자바 컴파일러(javac.exe)**

<img width="438" alt="스크린샷 2022-05-29 오후 7 49 55" src="https://user-images.githubusercontent.com/96563289/170864464-ef2098ff-e68a-4b64-a121-64c582bf8386.png">

- `소스파일` : 자바 코드가 작성되어 있는 파일 .java
- `클래스파일` : 자바 바이트코드 .class
- 소스파일에 있는 코드는 사람이 알아 들을 수 있는 언어일뿐 자바 가상 머신은 어떤 의미인지 모른다. 따라서 자바 컴파일러를 통해 자바 가상 머신이 이해할 수 있게 변형시켜 준다. 컴파일 과정을 통해 클래스파일을 생성한다.

- **자바 런처(java.exe)**
  - 자바 프로그램 자바 가상머신을 처음 구동하는 소프트웨어
    - JDM을 구동시키고 그 위에 자바 프로그램을 구동하는 역할을 하는 것이다
  - 클래스 파일을 대상으로 구동 시작

</details>

<a name="2"></a>

## 02 자바 프로그램의 관찰과 응용

<details>
  <summary>
    <h3> 자바 프로그램의 골격과 구성 </h3>
  </summary>

<img width="698" alt="스크린샷 2022-05-29 오후 7 54 49" src="https://user-images.githubusercontent.com/96563289/170864498-a629e8f2-bb75-4a7a-b086-83be294f3ae5.png">

</details>

---

### 관련 내용 참조

- https://cafe.naver.com/cstudyjava?iframe_url_utf8=%2FArticleRead.nhn%253Fclubid%3D19799898%2526page%3D3%2526menuid%3D312%2526boardtype%3DL%2526articleid%3D103233%2526referrerAllArticles%3Dfalse
