# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the word 'polymorphism' mean?

    Polymorphism in relation to programming is when a class can perform different actions or take different forms in different circumstances 

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

    It means that a class can do different things in different circumstances

    We did this in an example by having a computer be able to have an IConnect interface which is implemented by monitors/printers etc rather than hard-coding a computer having a monitor (tightly coupled).

3. What can we use to implement polymorphism in Java?

    Either inheritance or interfaces

4. How many 'forms' can an object take when using polymorphism?

    Many!

5. Give an example of when you could use polymorphism.

    An example that we did in class was to replace the requirement that a computer class object have a monitor with an IConnect, which was an interface implemented by monitors, printers etc. This meant that the computer could connect to different devices and would be more flexible in that it could do different things depending on the output device.


# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?

    When a class has a property which is another class or multiple classes, it is composed of that class or those classes.

7. When would you use composition? Provide a simple example in Java.

    When a component wouldn't exist outwith the class:

    public class House() {
        this.roof = new Roof();
    }

8. Give a difference between composition and aggregation?

    In composition, a class will generate its components when it is created. In aggregation, the components exist outwith the class and are created seperately

9. What is/are the advantage(s) of using composition/aggregation?

    It allows the use of another object's methods without having to extend an abstract class, which could result in multiple unneccassary methods on the new class.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?

    It is destroyed

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

    It is not destroyed