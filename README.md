# practice_thinking
java培训课后作业

## 课后作业答案
### * Why should you have minimum scope forvariables?
将局部变量的作用域最小化，可以增强代码的可读性和可维护性，并降低出错的可能性
### * Why should you understand performance of String Concatenation?
Concat会重新分配内存,采用该方法，会影响效率；
### * What are the best practices with Exception Handling?
+ Clean up Resources in a Finally Block or Use a Try-With-Resource Statement
+ Prefer Specific Exceptions
+ Document the Exceptions You Specify
+ Throw Exceptions With Descriptive Messages
+ Catch the most specific exception first
+ Don’t catch Throwable
+ Don’t ignore exceptions
+ Don’t log and throw
+ Wrap the Exception Without Consuming it
### * When is it recommended to prefer Unchecked Exceptiongs?
If a client can reasonably be expected to recover from an exception, make it a checked exception. If a client cannot do anything to recover from the exception, make it an unchecked exception.
### * When do you use a Marker Interface?
+ 如果标记只应用给类和接口，那么就标记接口
+ 如果要定义一个任何新方法都不会与之关联的类型
### * Why are ENUMS important for Readable Code?
The benefits of using enumerations include: Reduces errors caused by transposing or mistyping numbers. Makes it easy to change values in the future. Makes code easier to read, which means it is less likely that errors will creep into it
### * Why should you minimize mutability?
Immutable objects are thread safe, because the state of that object will never be changed, so when different process/thread try to read that object will always get the same result. So it makes concurrent programming a lot cleaner and easier to write.
### * What is functional programming?
函数式编程是种编程方式，它将电脑运算视为函数的计算。函数编程语言最重要的基础是λ演算（lambda calculus），而且λ演算的函数可以接受函数当作输入（参数）和输出（返回值）。
### * Why should you prefer Builder Pattern to build complex objects?
+ Builder模式实现的对象更利于使用
+ 方便用户创建复杂的对象
### * Why should you avoid floats for Calculations?
floasts为半精度，超过精度能表示的范围就会产生误差；
### * Why should you build the riskiest hign priority features first?

