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
    
#列表函数
print ()
print ('长度len : ',len(list1))
print ('最大值max : ',max(list1))
print ('最小值min : ',min(list1))

#列表的方法
list1.append(10)
print ("append追加一个object",list1)
print ('count计算10出现的次数：',list1.count(10))

print ("index返回该值的最低索引值 ： ",list1.index(10))
print ("pop移除并返回列表中的最后一个对象：",list1.pop())
list1.reverse()
print ("reverse逆转列表的顺序 ： ",list1)
list1.sort()
list1.append(10)
list1.append(7)
list1.append(12)
print ("sort排序列表：",list1)
```

#### 
