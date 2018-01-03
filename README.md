# helloword
just my first reposity
package com.oop.polymorphism;
/*
 * 测试动物的叫声
 */
public class Test {
//	public static void TestAnimalVoice(Cat c) {//没有多态时的做法
//		c.voice();
//	}
//	public static void TestAnimalVoice(Dog c) {
//		c.voice();
//	}
	
	public static void TestAnimalVoice(Animal c) {
			c.voice();
	}
public static void main(String[] args) {
	Cat c =new Cat();
	TestAnimalVoice(c);
	//或者
	Animal a=new Cat();
	Animal b=new Dog();
	TestAnimalVoice(a);
	TestAnimalVoice(b);
}
}

