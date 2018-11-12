### 1 列表
```javascript
var = ['physic','history',1997,2000]
print (var[0:4])
del var[3]          //使用del语句，当你知道删除的元素的时候，当你不知道的时候可以使用reomove(后面将涉及到)
print (var[0:4])

#基本列表操作
# + 号操作符，用于连接
list1 = [1,2,3]
list2 = [4,5,6]
print (list1+list2)
# * 号操作符，用于重复
list3 = ['hello']
print (list3*4)
# in 号操作符，用于判断是否存在
print (3 in [1,2,3])
# for in ,用于迭代使用
for x in [1,3,5,7]:
    print (x,end = ' ')
```

#### 
