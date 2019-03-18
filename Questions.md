## C# Questions 1

1. What is a namespace?
> A namespace acts like a container or outer block that separates code.  There can be multiple namespaces for each program, but they do not extend to other programs.  Namespaces contain classes and almost all of the code in a program.

2. What are value types?
> Value types are objects that have a copy of the data, and contains the actual value inside its own "memory allocation". Operations on the variable will affect the object itself when referenced.  

3. What are reference types?
> Reference types point to a location in the memory that actually contains the data.  Reference types do not contain the data itself, just a reference of the location of it; therefore, operations on the variable do not affect the data itself.  

4. What is an automatic property and how is it useful?
> Automatic properties allow you to make concise property declarations that are only accessed when the program references or uses get and set accessors. They are useful because they are already in the .NET library, so they are auto-implemented.  This saves time and makes the code more readable and efficient.  

5. What is the purpose of using statement?
> The using keyword is placed at the very beginning of the program's code, which tells .NET to release the objects (or code) that is used during run time, after it is over.  Sometimes there are functions contained within the system that allows the program to solve more problems.  

6. What are dynamic type variables?
> Dynamic type variables are defined using a "dynamic" keyword, and does not get compile-checked.  Basically, the variable type is assigned at runtime, and viewed as an object before it is compiled.  

7. What is the purpose of the is operator?
> The is operator is a boolean type that returns "true" if the object given is of the same type.

8. What are generics and how is using them useful?
> Generics allow you to define a class using <> placeholders for the type of method or class.  They create collections that are replaced with types at compile time.  They are useful because it improves performance efficiency, since the collections in generics store objects, and they provide type-safe code with re-usability.  

9. What is the scope of a public member of a class?
> A scope of a public member can be accessed by any other code in the assembly or others that reference it.  There are little to no restrictions on a public variable, method, or class.

10. Can you create a function that can accept a varying number of arguments?
> Yes, you just include multiple parameters in the function declaration.

11. How do you sort an array?
> To sort an array, there are methods you can use to sort string or integer arrays, however, to do it manually, you use a "bubble sort".  This takes each element in the array and compares it to the next, and if it is of higher value, it is sorted to the end of the array.  Each element is then printed in the new order.

12. What is a nullable type and what purpose does it serve?
> “Nullable types represent value-type variables that can be assigned the value of null.” A variable cannot be assigned the value of 0, since 0 is a number and numerical value.  Therefore, there are variables that can either contain numerical values or null, which allows the program to have a variable with "no value" without having to assign it to a negative number.    

13. What is an enumeration?
> Enumeration is a manually-defined set of integer constants that are made by the programmer, which use the enum keyword that are present only in that specific namespace.  It does not get defined to use in other programs. Enum contains its own values and do not get inherited.

14. What is inheritance?
> Inheritance is the ability to create classes that can pass on behaviors to other classes or methods.  The new class is derived from the base class, and can inherit or possess the same parameters or characteristics as it.

15. Is multiple inheritance supported?
> No, class behaviors can only be inherited once.  

16. What is the purpose of as operator?
> The as operator converts between compatible reference or null types.  If compatible with the given type, then the as operator returns the object.  

17. What is an object?
> An object is an instance of a class that is created dynamically.  The user can assign any type to variables in type object, because it holds the values for the properties.  Everything in c# inherits from Object, so therefore it contains any value type needed.  

18. What is the difference between a struct and a class?
>A struct is a value type where a class is a reference type.  Classes have the ability to inherit characteristics or properties, but structs do not.  Structs members are always public, and when you reference a struct, it helps make a single variable hold related data of different types that represent a record.

19. What is the difference between continue and break statements?
>A continue statement calls an action that keeps the code going, and sends it to the next function.  A break statement just ends a loop such as switch. It can also keep the code going to the next function or line.

20. What is this and how is it used?
> The .this keyword is used to refer to an instance of a class.  This differentiates between a method parameter and a class field when they have the same name.  This makes the code clearer for these instances, and qualifies constructors of the same name to be used.  

21. What is try and catch and when are they used?
> Try is a block that contains code that can cause the exception.  It tells the exception what it is looking for essentially, similar to catch.  Catch statements handle the exception, which comes after the try block.  Catch is used when an exception is thrown, and looks for the catch during runtime. If catch is not found, the program is no longer executed.

22. How is exception handling done?
> Exception handling contains 4 keywords, try, catch, finally, and throw.  An exception is a response to an "exceptional circumstance" that comes up while a program is running that is illogical.  The keywords help to try (find the exception), catch (handle it), finally (runs despite thrown exception), and throw (at end of catch block).  

23. What is finally and what is its purpose?
> The finally block allows the user to execute certain code whether or not an exception is thrown.  This basically executes the program if something is found, or even when nothing exceptional is found.

24. List the differences between Array and ArrayList.
> An array is a group of elements that are stored as fixed sizes, and they are all of the same data type. An ArrayList is similar to an array, but you can add or remove items in the ordered list using an index, and it can be done automatically.

25. Define constructor.
> A constructor is a method of the same name as the class that automatically gets invoked whenever an instance of the class is created.  A constructor is used to assign initial values to data members of the same class.

26. When can var be used to declare a variable and how is the type for the variable determined?
> The type for a variable is determined when the data type is stated before the variable name, such as string, int, or double.  Var can be used when a local variable is declared and initialized in the same statement, but cannot be initialized to null or to a method group.

27. What is an abstract class?
> Abstract classes are declared without implementation, and are created to allow for child classes, or subclasses to do the implementation itself.  Abstract classes are used for large amounts of data and larger programs, so that it is easier to keep track of each type of class and what its purpose of that class is.

28. What is an interface?
> An interface contains only declarations of methods, properties, and events, but not implementation, similar to abstract classes.  The class itself will implement the members of the interface.  This is useful for smaller amounts of data, and can easily maintain a program.  

29. What is a method?
> A method is a code block where every execution instruction is performed.  It is like a function, where the program calls a method to execute a loop, problem, or any type of instruction.  

30. What is a property?
> A property is a member that acts as a public data member, but is actually computing values of private fields.  They are accessors that can make a variable a readonly or write-only that accesses the object of the class.

31. What is an access specifier?
> Access specifiers define what kind of access the program has to certain variables or methods, which can be defined as public, private, static, or void. This just states the scope of restriction that is accessible in a certain class for a method or variable.

32. What access specifiers are supported and what do they mean?
> Public --> no restriction; private --> scope only within the class it is declared in; protected --> limited to class it is derived in; internal --> access within the program that contains the declarations within same assembly level.

33. What is a collection?
> A collection is a specialized class used for data storage that supports stacks, lists, queues, and hash tables.

34. What is a Hash Table?
> A hash table is a class that represents a collection of key-and-value pairs that uses the key to access elements in the collection.  When a key is defined, the table sorts the information and looks for the key.  If it exists, then the value itself exists.  
