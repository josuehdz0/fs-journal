# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Had to google this:
- Abstraction: The user can only see relevent information.
- Encapsulation: Grouping data and functions to an object for easier management.
- Inheritance: An object can inherit properties and methods of an existing object. 
- Polymorphism: Lets an object different forms. Like the ability of a method can treat different objects in different ways. Letting this method work with multiple objects in a generic way. 
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
Without using property variable:
console.log(staff.name)
Using property value:
console.log(staff[property])
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is the grouping of related data and functions into an object. It makes it easier to manage the data and functions and prevents unwanted issues when making changes to the data. It also restricts access from outside the bundle. 
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
It stands for Single Responsibilty Principle. 
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is the blueprint of what all the objects will have. It defines the properties and methods that the objects will have.

An instance of a class is a specific opject that is created from the class. It will have unique properties and methods and have values assigned to those properties.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy is middleware for Javascript Objects. It acts as a middleman between another object and the code that interacts with it. It lets you control how the original object recieves code without actually changing the original object. An example would be giving the object a default value of a property even thought the original opject doesnt have that property defined. 
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The purpose of MCV is to seperate the jobs of an application. So that changes of one job does not affect the others. This makes the code easier to modify and maintain. 
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller acts as the middle man between the model and the view. It listens to the users requests, and updates the model or view however requested. It also keeps the user from accesing the model or view directly.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The Service is responsible for handling the business logic and communicating with the data (AppState). It is the bridge between the Model and the Controller. 
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The Model represents the data of the application. It is responsible for representing the data in an structured and organized way. It encapsulates the data and business logic of the application which makes it easier to manage, test, and reuse. 
```
