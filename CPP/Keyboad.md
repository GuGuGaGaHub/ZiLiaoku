### C++ 关键字
[教程链接](https://www.runoob.com/w3cnote/cpp-keyword-intro.html)|[C语言32个关键字与C++62个关键字详解](https://blog.csdn.net/qq_41687938/article/details/119349135)
###``C语言32个关键字与C++62个关键字详解``
### C语言32个关键字
|关键字|说明|
|----|---------|
|auto|声明自动变量|
|short|声明短整型变量或函数|
|int|声明整型变量或函数|
|long|声明长整型变量或函数|
|float|声明浮点型变量或函数
|double|声明双精度变量或函数|
|char|声明字符型变量或函数|
|struct|声明结构体变量或函数|
|union|声明共用数据类型|
|enum|声明枚举类型|
|typedef|用以给数据类型取别名|
|const|声明只读变量|
|unsigned|声明无符号类型变量或函数|
|signed|声明有符号类型变量或函数|
|extern|声明变量是在其他文件正声明|
|register|声明寄存器变量
|static|声明静态变量|
|volatile|说明变量在程序执行中可被隐含地改变|
|void|声明函数无返回值或无参数，声明无类型指针|
|if|条件语句|
|else|条件语句否定分支（与 if 连用）|
|switch|用于开关语句|
|case|开关语句分支
|for|一种循环语句|
|do|循环语句的循环体|
|while|循环语句的循环条件|
|goto|无条件跳转语句|
|continue|结束当前循环，开始下一轮循环|
|break|跳出当前循环|
|default	|开关语句中的“其他”分支|
|sizeof|计算数据类型长度|
|return|子程序返回语句（可以带参数，也可不带参数）循环条件|

---

### C++62个关键字详解
|  # | 关键字                | 简单描述                   | 分类    | 例子                                         |
| -: | ------------------ | ---------------------- | ----- | ------------------------------------------ |
|  1 | `asm`              | 嵌入汇编代码                 | 编译/底层 | `asm("nop");`                              |
|  2 | `auto`             | 自动推导变量类型               | 类型推导  | `auto age = 18;`                           |
|  3 | `bool`             | 布尔类型，`true/false`      | 基本类型  | `bool ok = true;`                          |
|  4 | `break`            | 立即跳出循环或 `switch`       | 流程控制  | `if (x == 5) break;`                       |
|  5 | `case`             | `switch` 的分支条件         | 流程控制  | `case 1: break;`                           |
|  6 | `catch`            | 捕获异常                   | 异常处理  | `catch (int e) {}`                         |
|  7 | `char`             | 字符/小整数类型               | 基本类型  | `char grade = 'A';`                        |
|  8 | `class`            | 定义类                    | 面向对象  | `class Player {};`                         |
|  9 | `const`            | 表示对象不能通过该方式修改          | 类型修饰  | `const int x = 10;`                        |
| 10 | `const_cast`       | 修改 `const/volatile` 属性 | 类型转换  | `const_cast<int&>(x)`                      |
| 11 | `continue`         | 跳过本轮循环剩余代码             | 流程控制  | `if (x == 0) continue;`                    |
| 12 | `default`          | `switch` 的默认分支         | 流程控制  | `default: break;`                          |
| 13 | `delete`           | 释放 `new` 分配的内存         | 内存管理  | `delete p;`                                |
| 14 | `do`               | 循环体至少执行一次              | 循环    | `do {} while (x < 5);`                     |
| 15 | `double`           | 双精度浮点数                 | 基本类型  | `double pi = 3.14159;`                     |
| 16 | `dynamic_cast`     | 运行时检查并转换多态类型           | 类型转换  | `dynamic_cast<Dog*>(animal);`              |
| 17 | `else`             | `if` 不成立时执行            | 流程控制  | `if (x) {} else {}`                        |
| 18 | `enum`             | 定义枚举类型                 | 自定义类型 | `enum Color { Red, Blue };`                |
| 19 | `explicit`         | 防止构造函数隐式转换             | 构造/转换 | `explicit Player(int hp);`                 |
| 20 | `export`           | 模板/模块导出相关关键字           | 模板/模块 | `export template<class T> ...`             |
| 21 | `extern`           | 声明其他地方定义的变量/函数         | 链接    | `extern int score;`                        |
| 22 | `false`            | `bool` 的假值             | 基本类型  | `bool ok = false;`                         |
| 23 | `float`            | 单精度浮点数                 | 基本类型  | `float speed = 3.5f;`                      |
| 24 | `for`              | `for` 循环               | 循环    | `for (int i=0; i<10; ++i) {}`              |
| 25 | `friend`           | 允许友元访问私有/保护成员          | 面向对象  | `friend void test();`                      |
| 26 | `goto`             | 无条件跳转到标签               | 流程控制  | `goto end;`                                |
| 27 | `if`               | 条件判断                   | 流程控制  | `if (score >= 60) {}`                      |
| 28 | `inline`           | 建议函数适合内联               | 函数    | `inline int add(int a,int b){return a+b;}` |
| 29 | `int`              | 整数类型                   | 基本类型  | `int score = 100;`                         |
| 30 | `long`             | 长整型整数                  | 基本类型  | `long money = 100000;`                     |
| 31 | `mutable`          | `const` 成员函数仍可修改该成员    | 类/修饰  | `mutable int count;`                       |
| 32 | `namespace`        | 组织名称并避免命名冲突            | 命名    | `namespace Game { int score; }`            |
| 33 | `new`              | 动态分配对象/内存              | 内存管理  | `int* p = new int(10);`                    |
| 34 | `operator`         | 实现运算符重载                | 运算符   | `operator+(const Player& p)`               |
| 35 | `private`          | 类外通常不能直接访问             | 访问控制  | `private: int hp;`                         |
| 36 | `protected`        | 类及派生类可访问               | 访问控制  | `protected: int hp;`                       |
| 37 | `public`           | 外部可以访问                 | 访问控制  | `public: void attack();`                   |
| 38 | `register`         | 历史上的寄存器变量提示            | 旧关键字  | `register int i;`                          |
| 39 | `reinterpret_cast` | 低层次重新解释类型              | 类型转换  | `reinterpret_cast<char*>(p)`               |
| 40 | `return`           | 从函数返回                  | 函数    | `return 0;`                                |
| 41 | `short`            | 短整型                    | 基本类型  | `short age = 18;`                          |
| 42 | `signed`           | 指定有符号整数                | 类型修饰  | `signed int x = -10;`                      |
| 43 | `sizeof`           | 获取类型/对象占用的字节数          | 运算符   | `sizeof(int)`                              |
| 44 | `static`           | 静态存储、内部链接或类共享成员        | 存储/类  | `static int count = 0;`                    |
| 45 | `static_cast`      | 编译期显式类型转换              | 类型转换  | `static_cast<int>(3.14)`                   |
| 46 | `struct`           | 定义结构体，默认成员 `public`    | 自定义类型 | `struct Player { int hp; };`               |
| 47 | `switch`           | 多分支条件判断                | 流程控制  | `switch (key) { case 1: break; }`          |
| 48 | `template`         | 实现泛型编程                 | 模板    | `template<typename T>`                     |
| 49 | `this`             | 指向当前对象                 | 类     | `this->hp = 100;`                          |
| 50 | `throw`            | 抛出异常                   | 异常处理  | `throw std::runtime_error("error");`       |
| 51 | `true`             | `bool` 的真值             | 基本类型  | `bool alive = true;`                       |
| 52 | `try`              | 包含可能抛出异常的代码            | 异常处理  | `try { func(); }`                          |
| 53 | `typedef`          | 为已有类型创建别名              | 类型    | `typedef unsigned int uint;`               |
| 54 | `typeid`           | 获取运行时类型信息              | RTTI  | `typeid(obj).name();`                      |
| 55 | `typename`         | 声明模板参数是类型              | 模板    | `template<typename T>`                     |
| 56 | `union`            | 多个成员共享同一块内存            | 自定义类型 | `union Data { int i; float f; };`          |
| 57 | `unsigned`         | 无符号整数类型                | 类型修饰  | `unsigned int score = 100;`                |
| 58 | `using`            | 创建别名或引入名称              | 类型/命名 | `using ID = unsigned int;`                 |
| 59 | `virtual`          | 实现运行时多态                | 面向对象  | `virtual void attack();`                   |
| 60 | `void`             | 表示无返回值/无具体类型           | 基本类型  | `void attack() {}`                         |
| 61 | `volatile`         | 表示值可能被外部因素改变           | 类型修饰  | `volatile int flag;`                       |
| 62 | `wchar_t`          | 宽字符类型                  | 字符类型  | `wchar_t c = L'中';`                        |
