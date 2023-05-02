---
layout: default
title: 자바 객체지향 기초
parent: Java
nav_order: 1
---

# 자바 객체지향 기초
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---
## 📌 클래스(Class)

객체를 정의한 <font color='dodgerblue'>'설계도(blueprint)'</font> 혹은 <font color='dodgerblue'>'틀(frame)'</font>을 지칭한다. <br> 
클래스는 자바에서 객체를 생성하는데 사용되며, 객체는 클래스에 정의되고 설계된 내용 그대로 생성된다. 클래스를 통해 생성된 객체를 해당 클래스의 <font color='dodgerblue'>'인스턴스(instance)'</font>라고 부르며, 객체를 만드는 과정을 <font color='dodgerblue'>'인스턴스화(instantiate)'</font>라고 부른다.

### 클래스의 선언
```
접근제어자 class 클래스명 {
    // 내용 생략
} 
```

### 클래스의 구성요소
```
public class ExampleClass {
	int x = 10; // 필드
	void printX() {...} 메서드
	ExampleClass {...} 생성자
	class ExampleClass2 {...} 이너 클래스
}
```

클래스는 <font color='dodgerblue'>필드(field), 메서드(method), 생성자(constructor), 이너 클래스(inner class)</font>의 구성되어 있다. <br>

필드(Field) : 클래스의 속성을 나타내는 변수, 예를 들면 모델명, 컬러, 바퀴의 수 등 <br>
메서드(Method) : 클래스의 기능을 나타내는 함수, 예로 들면 시동하기, 가속하기, 정지하기 등 <br>
생성자(Constructor) : 클래스의 객체를 생성하는 역할 <br>
이너 클래스(Inner Class) : 클래스 내부의 클래스를 의미 <br>

## 📌 객체(Object)
클래스에서 정의한 것을 토대로 메모리(실제 저장공간)에 할당된 것으로 프로그램에서 사용되는 데이터 또는 식별자에 의해 참조되는 공간을 의미한다. <br>
객체는 크게 속성과 기능이라는 두 가지 구성요소로 이뤄져 있다. 속성과 기능은 각각 필드와 메서드로 정의되는데, 일반적으로 하나의 객체는 다양한 속성과 기능의 집합으로 이뤄져 있다. 그리고 이러한 속성과 기능은 이너클래스와 함께 객체의 <font color='dodgerblue'>'멤버(member)'</font>라고 칭한다.

| ![Image Alt 텍스트]({{"/assets/images/Java 객체지향 기초/객체의 속성과 기능.png"| relative_url}}) | 
|:--:| 
| 여기에 캡션을 작성합니다. |