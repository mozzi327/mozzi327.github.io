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
## 클래스(Class)

객체를 정의한 '설계도(blueprint)' 혹은 '틀(frame)'을 지칭한다. 클래스는 자바에서 객체를 생성하는데 사용되며, 객체는 클래스에 정의되고 설계된 내용 그대로 생성된다. 클래스를 통해 생성된 객체를 해당 클래스의 인스턴스(instance)라고 부르며, 객체를 만드는 과정을 인스턴스화(instantiate)라고 부른다.

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