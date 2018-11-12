# python
### 1.if else语句
```javascript
对于python中的if...else...必须按照以下的格式：
if ...:
  代码块1
else:         //注意此处的冒号，特殊点
  代码块2
```

##### 注意：1.if 表达式语句后需要添加" : "冒号，else后面也要添加" : ",这是python的语句特点


### 2 print函数（输入输出）
print ("xxxxxxxxxx")

注意：在python3.7版本中，print函数必须加上（）括号括起来

### 3 while循环语句
python的单目运算只能通过 x = x + 1的方式完成，x++其他方式不可以
```javascript
while 条件
  语句块1
  x = x + 1    //变量x自增1
```

#### 无限循环只需要if true条件一直为真
```javascript
while true
  执行语句块1
```

#### while语句可以配合else语句一起使用
```javascript
while 表达式A
  ...
else:
  ...
```
 
### 4 for循环语句
```javascript
for var in x (x可以是数组或者lamada表达式)
  表达式1
```

#### for循环可以遍历字符串
```javascript
for letter in 'PYTHON':
  print (letter)
```

#### for循环可以通过索引遍历数组(通过len函数获取长度，range函数迭代产生单个数值)
```javascript
fruit = ["apple","banana","juice"]
for index in range(len(fruit)):               //记得添加for后面的 ：
  print ("current fruit is ",fruit[index])    //print打印内容要加括号，在python3.7之后
```

### 5 数组
```javascript
list(range(5)) //通过内置函数迭代生成数字
```
#### 数组的索引遍历
```javascript
fruit = ["apple","banana","juice"]
for index in range(len(fruit)):               //记得添加for后面的 ：
  print ("current fruit is ",fruit[index])    //print打印内容要加括号，在python3.7之后
```
     
 
