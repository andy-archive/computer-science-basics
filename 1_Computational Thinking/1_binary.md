컴퓨터 과학이 무엇인지 알아 보자. 사람이 정보를 어떻게 표현하는지 생각해 보고, 컴퓨터는 정보를 어떻게 표현할 수 있는지 그 방법에 대해 알아 보자.

<br><br>

### 📌 컴퓨터 과학(Computer Science)

강의에서 교수님은 컴퓨터 과학에 대해 아래와 같이 설명했다.

> What is computer science? It's just a process of solving problem.
>
> 컴퓨터 과학(Computer science)은 무엇일까? 이것은 문제를 해결하는 과정(a process of solving problem)일 뿐이다.

그렇다면 문제를 해결하는 것은 무엇일까?

![image of input, process and output](https://computersciencewiki.org/images/a/a9/Ipo.png?20170722115047)

[Inputs and outputs - Computer Science Wiki](https://computersciencewiki.org/index.php/Inputs_and_outputs)

바로 문제를 입력(input) 받아 적절한 답안의 출력(output)을 구하는 문제 해결 과정(a process of solving problem)이라 할 수 있다.

<br><br>

### 📌 숫자를 나타내는 체계

이제 컴퓨터를 통하여 문제를 해결하기에 앞서, 컴퓨터가 정보를 표현 방법에 대해 알아 보자.

#### 1\. 컴퓨터의 언어: 이진법(binary)

> 주어진 데이터를 숫자 0과 1로만 표현하는 것을 **이진법(binary)**이라고 한다.

#### 2\. 사람의 언어: 십진법(decimal)

사람에게 정보의 표현은 숫자를 세는 걸로 시작한다. 이를 '단일 표기법(unary notation)'이라 한다.

너무 자연스럽게 이해할 수 있는 숫자 _123_은 왜 _123_일까?

아래와 같은 약속을 통해 이루어진다.

```
123 = (100 * 1) + (10 * 2) + (1 * 3) = 100 + 20 + 3
```

즉,100의 자리, 10의 자리, 1의 자리를 나누어 각각의 자리에 곱셈을 더해서 나타낸다.

이를 십진법(decimal)이라 한다.

<br><br>

### 📌이진법을 통한 정보의 표현

![an image of two lightbulbs, turned on means 1 and turned off means 0](https://sandbox.mc.edu/~bennet/cs110/textbook/bulbs.gif)

[CSC 110 MODULE 1.3](http://sandbox.mc.edu/~bennet/cs110/textbook/module1_3.html)

0과 1로만 표현하는 이진법을 이용해 전구가 켜지거나 꺼지는(전기가 있거나 없는, 1이거나 0을, 참이거나 거짓인) 상태를 나타낼 수 있다.

<br>

이진수 011 또한 십진법의 약속처럼 아래와 같이 나타낼 수 있다.

```c
011 = (4 * 0) + (2 * 1) + (1 * 1)
```

<br><br>

### 📌 비트(bit)와 바이트(byte)

![비트는 0과 1을 나타내는 이진수를, 바이트는 8개의 비트를 나타낸다.](https://learnworthy.net/wp-content/uploads/2020/03/The-amazing-history-of-the-Data-Byte.png?ezimgfmt=ng%3Awebp%2Fngcb12%2Frs%3Adevice%2Frscb12-1)


[The amazing history of the Data Byte | Learnworthy.net](https://learnworthy.net/the-amazing-history-of-the-data-byte/)

> 비트(bit)는 이진수(binary digit)을 요약한 단어이며, 0과 1로만 값을 나타내는 측정 단위이다.

<br>

하나의 비트로는 수많은 양의 데이터를 표현하기에 많이 부족해 보인다. 따라서 몇 개의 비트를 하나로 묶어 어느 정도 가짓수를 가진 새로운 단위를 만들었다. 그게 바로 바이트(byte)이다.

<br>

> 바이트(byte)는 8개의 비트가 모여 이진수 00000000부터 이진수 11111111까지 나타낼 수 있는 8자리의 이진수이다.

1 byte는 십진법으로 0부터 255까지 나타낼 수 있다.

![바이트는 8개의 전구를 각각 끄거나 키는 방식으로 숫자를 표현한다.](https://sandbox.mc.edu/~bennet/cs110/textbook/significance.gif)

[CSC 110 MODULE 1.3](http://sandbox.mc.edu/~bennet/cs110/textbook/module1_3.html)

-   강의에서 나온 8개의 전구는 1 바이트를 나타내며, 전구를 끄거나 켜서 주어진 숫자를 표현한다.
-   교수님은 트랜지스터 또한 이러한 방식으로 전기를 저장하거나 저장하지 않음으로써 데이터를 표현한다고 설명한다.