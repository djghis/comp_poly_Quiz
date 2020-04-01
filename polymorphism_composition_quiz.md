# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

It means that it can take many forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

Polymorphism refers to a programming language's ability to process objects differently depending on their data type or class.

public class OtherThings extends Things implements ISomething.
ArrayList<ISomething> something.



3. What can we use to implement polymorphism in Java?

We can use Interface or Abstract classes.
you can overload or override a method.


4. How many 'forms' can an object take when using polymorphism?

Lots?


5. Give an example of when you could use polymorphism.

When you need a class to behave in different ways from their original function.
To make your code more DRY (can you say DRYer?)



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

That object/class can be made up of other objects/classes.

7. When would you use composition? Provide a simple example in Java.
When you need to add methods to more than 1 object.
class Car
Engine engine;
GearBox gearbox;
Class Motorbike
Engine engine;
GearBox gearbox;

8. What is/are the advantage(s) of using composition?

as objects are composed from other objects we do not force behaviour like inheritance does.
but we can add functionality to more than 1 other objects and change behaviour at runtime.

9. When an object is destroyed, what happens to all the objects it is composed of?
They are still there to be reused for another object later/when needed.
