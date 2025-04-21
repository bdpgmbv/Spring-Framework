1. Inversion of control
* Nothing but give the control to framework itself - you dont have to create every object.
* Consider there are 1000's of classes that you have created - each and every time you are creating the objects and destroying it for garbage collection.
* Its tedious.
* To do this - spring allows dependency injection

2. Dependency Injection
* Give the dependencies of different classes to different classes
* Suppose one class needs the object of the other class - we will give the control to spring to add those particular dependencies. 
