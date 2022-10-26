# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
the namespace is basically the name of your project and groups files into that project
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
structs are basically a light version of a class
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void, maybe?
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
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
the data type for what the Start method must return
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
abstract prevents the class from being used by itself, instead it must be implemented elsewhere
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
virtual allows that method to be overwritten by a derived class
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, internal, protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only the current file or class
```