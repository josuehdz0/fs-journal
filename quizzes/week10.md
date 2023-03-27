# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
It provides a scope and is used to organize code into groups to prevent name collision that can occur when there are several libraries. 
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Struct are value types and Classes are reference types.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
Public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
Represents text as a sequence
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It prevents the inheritance of a class that were previously marked virtual.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
It is used to override the base class member
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
- public access
- private access
- protected access
- internal access
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
It can only be accessed by code within the same class or struct.
```