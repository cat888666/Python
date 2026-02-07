# 一，汉语简单释义
1. **print**
实现打印输出功能·。
2. 变量
储存或者指代某个值（与C语言含义类似）
3. 


# 二，语法演示
# 1、print

## 示例

```python

# 单双引号均可

print("hello world")

print('hello world')

  

# 字符串拼接

print("hello"+"world")

print("hello "+"world")

#空格需手动添加

  

# 使用反斜杠"\"打印单双引号

print("I say Let\'s go!")

  

# "\n"为换行

print("第一行\\n\n第二行")

  

# 使用连续三个双(单)引号自动换行

print("""第一行  

第二行""")

```

### 输出

```Python

hello world

hello world

helloworld

hello world

I say Let's go!

第一行\n

第二行

第一行  

第二行

```

# 2、变量

  

 **命名规则**

1. 变量起名不能数字打头；不能有空格；不能用引号包裹；

2. 变量赋值：变量名="值"(这样在用print打印的时候不需要再给这个变量加引号，用+连接即可)；   变量="54188"   print(变量)即可

3. 变量转换赋值：变量1="54188"    变量2=变量1    变量1="114514"(一般定义三个变量，用以保存之前变量的同时调用新的变量)

## 示例

```Python

my_phone="136"  

print(my_phone)  

my_phone_two=my_phone  

my_phone="137"  

print(my_phone)  

print(my_phone_two)

```

### 输出

```Python

136

137

136

```

## 交换两个变量的值

```Python

a="1"

b="2"

print("交换前")

print("a: "+a+",b: "+b)

tem=a

a=b

b=tem

print("交换后")

print("a: "+a+",b: "+b)

```

### 输出

```Python

交换前

a: 1,b: 2

交换后

a: 2,b: 1

```
# 3、