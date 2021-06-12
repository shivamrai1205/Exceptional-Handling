# Exceptional-Handling


An excpetion is an abnormal condition that arises in a code sequence at runtime (Exception is an runtime error).

 When an exception is occurrs in java, an object of type **Exception** representing the exception is created and thrown inside the method that caused it on. Either method can hadle it or pass it on. If an exception is caught the execution will be normal.
 Exceptions can be generated at runtime by JVM or manually by code. JVM throws exception if sequence of code violates any rule of java. Manually thrown exception if caller violates any developer defined rules.
 
 Exception can be handled using 5 keywords : **try, catch, finally, throw, throws**
 
 If we want to monitor exception inside a sequence of code, we can use **try** block, exception occurred inside try block can be handled by **catch** block. Runtime Exceptions are thrown by JVM, but to throw a manual exception inside a method we can **throw** keyword. If an exception is thrown inside a method, then it should be specified in method declaration using **throws** clause. Any code that absolutely must be executed after a try block completes should be placed in **finally** block.

Example : 

![image](https://user-images.githubusercontent.com/85785848/121773297-aba33700-cb98-11eb-865d-5d657fabbd72.png)

**Exception Type**

All exception types are subclasses of the built-in class **Throwable**. **Exception** class is used for exceptional conditions that user programs should catch. This is also the
class that you will subclass to create your own custom exception types. RuntimeException is a subclass of Exception, exceptions of this type are automatically defined for the programs that you write and include things such as division by zero and invalid array indexing.

![image](https://user-images.githubusercontent.com/85785848/121773526-1e60e200-cb9a-11eb-9ae5-1fc34f3c2a60.png)
