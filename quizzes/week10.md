# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
To associate the file with the proper scope of the project.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Class methods are default private, struct methods are default public
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
public, meaning it is completely open as a method to reference
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
The type of data the method will return
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
From the class being instantiated
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
That it will be attached to the car, but not directly a part of the car as an object
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, internal, protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only other things within that class
```