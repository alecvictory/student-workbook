# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
used to provide a space where your application presides
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
structs are value types
classes are reference types
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void method
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
the access modifier is when the function start is used the console will return vroooooom
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
the string is the indication of start method being a string
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
declaring the start method without implementation
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
an implimentation of the base class using the method's basic functionality
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
private 
public
internal
protected

```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only the methods inside the actual file
```