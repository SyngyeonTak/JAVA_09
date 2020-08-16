# JAVA_09

## polymorphism

Polymorphism is the ability of an object to take on many forms. The most common use of polymorphism in OOP occurs when a parent class reference is used to refer to a child class object <br>
Any Java object that can pass more than one IS-A test(IS-A relationship is inheritance) is considered to be polymorphic. In Java, all Java objects are polymorphic since any object will pass the IS-A test for their own type and for the class Object. <br>

It is important to know that the only possible way to access an object is through a reference variable. A reference variable can be of only one type. Once declared, the type of a reference variable cannot be changed. <br>

Example <br>
Let us look at an example. <br>

public interface Vegetarian{}  <br>
public class Animal{} <br>
public class Deer extends Animal implements Vegetarian{} <br>

Now, the Deer class is considered to be polymorphic since this has multiple inheritance. Following are true for the above examples − <br>

A Deer IS-A Animal <br>
A Deer IS-A Vegetarian <br>
A Deer IS-A Deer <br>
A Deer IS-A Object <br>
