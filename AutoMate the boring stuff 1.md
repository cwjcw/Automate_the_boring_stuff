# 第一章 Python编程基础

## 1.1 前言

### 1.1.1 Python安装与编译器安装


```python
# https://www.python.org/ 下载最新的Python官方版本 并运行解释
```


```python
# https://www.jetbrains.com/pycharm 运行pycharm
```

## 1.2 表达式 


```python
print('hello world')
```

    hello world
    

## 1.3 整型、浮点型和字符串数据类型


```python
# 常见数据类型
# 整型 -2, -1, 0, 1, 2, 3, 4, 5
# 浮点型 -1.25, -1.0, --0.5, 0.0, 0.5, 1.0, 1.25
# 字符串 'a','aa', 'aaa', 'Hello!', '11 cats',  解释''和""
```

## 1.4 字符串连接和复制


```python
'Alice' + 'Bob'
```




    'AliceBob'




```python
'Alice' + 42
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-9-4e9a9e71481a> in <module>
    ----> 1 'Alice' + 42
    

    TypeError: can only concatenate str (not "int") to str



```python
42 + 24
```




    66




```python
'Alice ' * 5.2
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-15-e9d9d272095f> in <module>
    ----> 1 'Alice ' * 5.2
    

    TypeError: can't multiply sequence by non-int of type 'float'



```python
'Alice' * 'Bob'
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-14-9caa30780052> in <module>
    ----> 1 'Alice' * 'Bob'
    

    TypeError: can't multiply sequence by non-int of type 'str'


## 1.5 变量


```python
# 画图演示
```

### 1.5.1 变量赋值


```python
# 通过赋值语句完成变量的赋值
```


```python
# 赋值语句（左边变量，右边值）
spam = 40
print(spam)
eggs = 2
print(spam + eggs)
# 变量的覆盖
spam = spam + 5
print(spam)
```

    40
    42
    45
    

### 1.5.2 变量命名规则


```python
# 1．只能是一个词。
# 2．只能包含字母、数字和下划线。
# 3．不能以数字开头。
```


```python
# 注意事项： 大小写敏感
# 注意事项：驼峰与下划线
```

## 1.6 第一个程序

### 1.6.1 注释，print,input,len函数


```python
# This program says hello and asks for my name.
print('Hello world!') # 解释打印
print('What is your name?') # ask for their name
myName = input()
print('It is good to meet you, ' + myName)
print('The length of your name is:')
print(len(myName))
print('What is your age?') # ask for their age
myAge = input()
print('You will be ' + str(int(myAge) + 1) + ' in a year.')
```

    Hello world!
    What is your name?
    a
    It is good to meet you, a
    The length of your name is:
    1
    What is your age?
    a
    


    ---------------------------------------------------------------------------

    ValueError                                Traceback (most recent call last)

    <ipython-input-2-d3a21d08fa82> in <module>
          8 print('What is your age?') # ask for their age
          9 myAge = input()
    ---> 10 print('You will be ' + str(int(myAge) + 1) + ' in a year.')
    

    ValueError: invalid literal for int() with base 10: 'a'


### 1.6.2 数据类型及数据类型转换


```python
str(29)
print('I am ' + str(29) + ' years old.')
print('I am ' + 29 + ' years old.')
```

    I am 29 years old.
    


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-4-33f1b08a46e6> in <module>
          1 str(29)
          2 print('I am ' + str(29) + ' years old.')
    ----> 3 print('I am ' + 29 + ' years old.')
    

    TypeError: can only concatenate str (not "int") to str



```python
str(0)
str(-3.14)
int(1.25)
int('42')
int(1.99)
float('3.14')
float(10)
```




    10.0




```python
# input()输出的总是字符串
spam = input()
spam
```

    101
    




    '101'




```python

```
