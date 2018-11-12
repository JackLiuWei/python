### 1 元组
```javascript
元组与列表的区别：
1.元组不像列表那样不能被改变
2.元组使用圆括号，而数组使用方括号

#空元组写成不含任何值的两个空括号 -
tup1 = ();
print (tup1)

tup2 = (1,2)
print (tup2)

tup3 = ('physics','chemistry',1997,2000)
tup4 = (1,2,3,4,5,6,7)
#元组具有索引，可通过索引对元组的索引切片
print ("tup3[0]",tup3[0:1])
print ("tup4[0]",tup4[0:7])
#元组的+运算
print (tup3+tup4)
#元组的*运算
print (tup2*20)
#元组的in运算
print (2 in tup2)

T = ('C++','Java','Python')
print (T)
```
