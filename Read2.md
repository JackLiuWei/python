### 1 字符串
```javascript
var = 'Hello_Word!'        //[]字符串范围切片，截取一部分值
print (var[0:5])           //得到的结果时Hello,而不是Hello_ ,因为var[0]为H,var[5]为_,
                           //但0：5只取前var[0]，var[5]前的一个值
```
### 字符串常用操作符号
print ('aaaa'+'bbbbb')     //+连接操作符号,这里输出：aaaabbbb
print ('H' in var)         //in是否存在字符串,这里输出：True
print ('H' not in var)     //in是否不存在字符串,这里输出：False
print (r'\n')              //r禁止转义的，这里打印：\n
