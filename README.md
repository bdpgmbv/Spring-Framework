1. Inversion of control
* Nothing but give the control to framework itself - you dont have to create every object.
* Consider there are 1000's of classes that you have created - each and every time you are creating the objects and destroying it for garbage collection.
* Its tedious.
* To do this - spring allows dependency injection

2. Dependency Injection
* Give the dependencies of different classes to different classes
* Suppose one class needs the object of the other class - we will give the control to spring to add those particular dependencies.

3. Other thing spring provides us is Aspect Oriented Programming
* used to tackle the cross cutting concerns
* When we are building an application - there are a lot of things that we might do repeatedly like logging the user data - the logs that we generate, doing logging in, doing securities.
* these type of things that we have to do for each and every request that is coming from the server.
* to do those things every time - its a tedious job, So what we do is - we seperate out all those cross cutting concerns - we seperate out using AOP.

4. From tight coupling of dependencies to loose coupling with spring
* we dont have to use new keyword or do anything to bring your dependency classes.
* we just have to annotate it or we can do the XML configuration as well - like this particular class might need this or we need this particular object.

5. WAYS that we can do dependency injection
* Contructor based
* Setter based

6. we can do dependency injection via
* XML configurations
* Annotations based Configurations
* Java configurations
