### 1 字符串
```javascript
var = 'Hello_Word!'        //[]字符串范围切片，截取一部分值
print (var[0:5])           //得到的结果时Hello,而不是Hello_ ,因为var[0]为H,var[5]为_,
                           //但0：5只取前var[0]，var[5]前的一个值
```
### 字符串常用操作符号
```javascript
print ('aaaa'+'bbbbb')     //+连接操作符号,这里输出：aaaabbbb
print ('H' in var)         //in是否存在字符串,这里输出：True
print ('H' not in var)     //in是否不存在字符串,这里输出：False
print (r'\n')              //r禁止转义的，这里打印：\n

#字符串格式化运算符号%
print("My name is %s and weight is %d kg!"%('Zara',22))
#输出：
My name is Zara and weight is 22 kg!

#字符串三目运算符"""..."""
para_str = """this is long story of myself,
where I am,but I did not kown.\nSometime I will thinking about
what where I am from,\tbut no result
"""
print (para_str)
输出：
My name is Zara and weight is 22 kg!
this is long story of myself,
where I am,but I did not kown.
Sometime I will thinking about
what where I am from,	but no result

#反斜杠在字符串中没有特殊的含义\
print ('C:\\program file')
#禁止转义符号，r'expression'
print (r'C:\\program file')
```

### 2 字符串的内置函数
...
