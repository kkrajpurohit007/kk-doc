*********************************
Java Questions
*********************************

Java Platform
--------------

#. Why is Java so popular?
#. What is platform independence?
#. What is bytecode?
#. Compare JDK vs JVM vs JRE
#. What are the important differences between C++ and Java?
#. What is the role for a classloader in Java?

Wrapper Classes
----------------------------------------------------

#. What are Wrapper classes?
#. Why do we need Wrapper classes in Java?
#. What are the different ways of creating Wrapper class instances?
#. What are differences in the two ways of creating Wrapper classes?
#. What is auto boxing?
#. What are the advantages of auto boxing?
#. What is casting?
#. What is implicit casting?
#. What is explicit casting?

Strings
----------------------------------------------------

#. Are all String’s immutable?
#. Where are String values stored in memory?
	.. Hint::
		- Heap memory & stack memory

#. Why should you be careful about String concatenation(+) operator in loops?	
	.. Hint::
		- str1 = str2 + str2; ... If you concatenate Stings in loops for each iteration a new intermediate object is created in the String constant pool. This is not recommended as it causes memory issues. Therefore, concatenating strings in loops as shown in the following example is not recommended.

#. How do you solve above problem?
	.. Hint::
		Using string builder & string buffer

#. What are differences between String and StringBuffer?
#. What are differences between StringBuilder and StringBuffer?
#. Can you give examples of different utility methods in String class?

.. Hint::
	- https://www.youtube.com/watch?v=hdgRaJ-G5DE
	- https://www.youtube.com/watch?v=7Eums_vwcPs

Object oriented programming basics
----------------------------------------------------

#. What is a class?
#. What is an object?
#. What is state of an object?
#. What is behavior of an object?
#. What is the super class of every class in Java?
#. Explain about toString method ?
#. What is the use of equals method in Java?
#. What are the important things to consider when implementing equals method?
#. What is the Hashcode method used for in Java?
#. Explain inheritance with examples .
#. What is method overloading?
#. What is method overriding?
#. Can super class reference variable can hold an object of sub class?
#. Is multiple inheritance allowed in Java?
#. What is an interface?
#. How do you define an interface?
#. How do you implement an interface?
#. Can you explain a few tricky things about interfaces?
#. Can you extend an interface?
#. Can a class extend multiple interfaces?
#. What is an abstract class?
#. When do you use an abstract class?
#. How do you define an abstract method?
#. Compare abstract class vs interface?
#. What is a constructor?
#. What is a default constructor?
#. Will this code compile?
#. How do you call a super class constructor from a constructor?
#. Will this code compile?
#. What is the use of this()?
#. Can a constructor be called directly from a method?
#. Is a super class constructor called even when there is no explicit call from a sub class constructor?

Advanced object oriented concepts
----------------------------------------------------

#. What is polymorphism?
#. What is the use of instanceof operator in Java?
#. What is coupling?
#. What is cohesion?
#. What is encapsulation?
#. What is an inner class?
#. What is a static inner class?
#. Can you create an inner class inside a method?
#. What is an anonymous class?

Modifiers
----------------------------------------------------

#. What is default class modifier?
#. What is private access modifier?
#. What is default or package access modifier?
#. What is protected access modifier?
#. What is public access modifier?
#. What access types of variables can be accessed from a class in same package?
#. What access types of variables can be accessed from a class in different package?
#. What access types of variables can be accessed from a sub class in same package?
#. What access types of variables can be accessed from a sub class in different package?
#. What is the use of a final modifier on a class?
#. What is the use of a final modifier on a method?
#. What is a final variable?
#. What is a final argument?
#. What happens when a variable is marked as volatile?
#. What is a static variable?

conditions & loops
----------------------------------------------------

#. Why should you always use blocks around if statement?
#. Guess the output
#. Guess the output
#. Guess the output of this switch block .
#. Guess the output of this switch block?
#. Should default be the last case in a switch statement?
#. Can a switch statement be used around a String
#. Guess the output of this for loop
#. What is an enhanced for loop?
#. What is the output of the for loop below?
#. What is the output of the program below?
#. What is the output of the program below?

Exception handling
----------------------------------------------------

#. Why is exception handling important?
#. What design pattern is used to implement exception handling features in most languages?
#. What is the need for finally block?
#. In what scenarios is code in finally not executed?
#. Will finally be executed in the program below?
#. Is try without a catch is allowed?
#. Is try without catch and finally allowed?
#. Can you explain the hierarchy of exception handling classes?
#. What is the difference between error and exception?
#. What is the difference between checked exceptions and unchecked exceptions?
#. How do you throw an exception from a method?
#. What happens when you throw a checked exception from a method?
#. What are the options you have to eliminate compilation errors when handling checked exceptions?
#. How do you create a custom exception?
#. How do you handle multiple exception types with same exception handling block?
#. Can you explain about try with resources?
#. How does try with resources work?
#. Can you explain a few exception handling best practices?

Miscellaneous topics
----------------------------------------------------

#. What are the default values in an array?
#. How do you loop around an array using enhanced for loop?
#. How do you print the content of an array?
#. How do you compare two arrays?
#. What is an enum?
#. Can you use a switch statement around an enum?
#. What are variable arguments or varargs?
#. What are asserts used for?
#. When should asserts be used?
#. What is garbage collection?
#. Can you explain garbage collection with an example?
#. When is garbage collection run?
#. What are best practices on garbage collection?
#. What are initialization blocks?
#. What is a static initializer?
#. What is an instance initializer block?
#. What is tokenizing?
#. Can you give an example of tokenizing?
#. What is serialization?
#. How do you serialize an object using serializable interface?
#. How do you de-serialize in Java?
#. What do you do if only parts of the object have to be serialized?
#. How do you serialize a hierarchy of objects?
#. Are the constructors in an object invoked when it is de-serialized?
#. Are the values of static variables stored when an object is serialized?

Collections
----------------------------------------------------

#. Why do we need collections in Java?
#. What are the important interfaces in the collection hierarchy?
#. What are the important methods that are declared in the collection interface?
#. Can you explain briefly about the List interface?
#. Explain about ArrayList with an example?
#. Can an ArrayList have duplicate elements?
#. How do you iterate around an ArrayList using iterator?
#. How do you sort an ArrayList?
#. How do you sort elements in an ArrayList using comparable interface?
#. How do you sort elements in an ArrayList using comparator interface?
#. What is vector class? How is it different from an ArrayList?
#. What is linkedList? What interfaces does it implement? How is it different from an ArrayList?
#. Can you briefly explain about the Set interface?
#. What are the important interfaces related to the Set interface?
#. What is the difference between Set and sortedSet interfaces?
#. Can you give examples of classes that implement the Set interface?
#. What is a HashSet?
#. What is a linkedHashSet? How is different from a HashSet?
#. What is a TreeSet? How is different from a HashSet?
#. Can you give examples of implementations of navigableSet?
#. Explain briefly about Queue interface?
#. What are the important interfaces related to the Queue interface?
#. Explain about the Deque interface?
#. Explain the BlockingQueue interface?
#. What is a priorityQueue?
#. Can you give example implementations of the BlockingQueue interface?
#. Can you briefly explain about the Map interface?
#. What is difference between Map and sortedMap?
#. What is a HashMap?
#. What are the different methods in a Hash Map?
#. What is a TreeMap? How is different from a HashMap?
#. Can you give an example of implementation of navigableMap interface?
#. What are the static methods present in the collections class?

Advanced collections
----------------------------------------------------

#. What is the difference between synchronized and concurrent collections in Java?
#. Explain about the new concurrent collections in Java?
#. Explain about copyonwrite concurrent collections approach?
#. What is compareandswap approach?
#. What is a lock? How is it different from using synchronized approach?
#. What is initial capacity of a Java collection?
#. What is load factor?
#. When does a Java collection throw UnsupportedOperationException?
#. What is difference between fail-safe and fail-fast iterators?
#. What are atomic operations in Java?
#. What is BlockingQueue in Java?

Generics
----------------------------------------------------
#. What are Generics?
#. Why do we need Generics? Can you give an example of how Generics make a program more flexible?
#. How do you declare a generic class?
#. What are the restrictions in using generic type that is declared in a class declaration?
#. How can we restrict Generics to a subclass of particular class?
#. How can we restrict Generics to a super class of particular class?
#. Can you give an example of a generic method?

Multi threading
----------------------------------------------------
#. What is the need for threads in Java?
#. How do you create a thread?
#. How do you create a thread by extending thread class?
#. How do you create a thread by implementing runnable interface?
#. How do you run a thread in Java?
#. What are the different states of a thread?
#. What is priority of a thread? How do you change the priority of a thread?
#. What is executorservice?
#. Can you give an example for executorservice?
#. Explain different ways of creating executor services .
#. How do you check whether an executionservice task executed successfully?
#. What is callable? How do you execute a callable from executionservice?
#. What is synchronization of threads?
#. Can you give an example of a synchronized block?
#. Can a static method be synchronized?
#. What is the use of join method in threads?
#. Describe a few other important methods in threads?
#. What is a deadlock?
#. What are the important methods in Java for inter-thread communication?
#. What is the use of wait method?
#. What is the use of notify method?
#. What is the use of notifyall method?
#. Can you write a synchronized program with wait and notify methods?

Functional Programming - Lamdba expressions and Streams
---------------------------------------------------------------
#. What is functional programming?
#. Can you give an example of functional programming?
#. What is a stream?
#. Explain about streams with an example?

what are intermediate operations in streams?
----------------------------------------------------
#. What are terminal operations in streams?
#. What are method references?
#. What are lambda expressions?
#. Can you give an example of lambda expression?
#. Can you explain the relationship between lambda expression and functional interfaces?
#. What is a predicate?
#. What is the functional interface - function?
#. What is a consumer?
#. Can you give examples of functional interfaces with multiple arguments?

New Features
----------------------------------------------------
#. What are the new features in Java 5?
#. What are the new features in Java 6?
#. What are the new features in Java 7?
#. What are the new features in Java 8?