#### 基本运算符

###### 算数运算符

`+`     加法  &emsp;&emsp;- 对操作符的两侧增加值&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;a + b = 30  
`_`	    减法  &emsp;&emsp;- 减去从左侧操作数右侧操作数&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;a - b = -10  
`*`	    乘法  &emsp;&emsp;- 相乘的运算符两侧的值&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;a * b = 200    
`/`	    除法  &emsp;&emsp;- 由右侧操作数除以左侧操作数 &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;b / a = 2    
`%`	    模  &emsp;&emsp;&emsp;- 由右侧操作数和余返回除以左侧操作数&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;b % a = 0    
`**`	指数&emsp;&emsp;-执行对操作指数（幂）的计算&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;a**b = 10的20次幂    
`//`	地板除&emsp;-操作数的除法，其中结果是将小数点后的位数被除去的商&emsp;9//2 =  4 而 9.0//2.0 = 4.0    

###### 比较运算符

`==	`    检查两个操作数的值是否相等，如果是则条件变为真&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; (a == b) 为false    
`!=	`    检查两个操作数的值是否相等，如果值不相等，则条件变为真&emsp;&emsp;&emsp;&emsp; (a != b) 为 true.    
`> `	 检查左操作数的值是否大于右操作数的值，如果是，则条件成立&emsp;&emsp;&emsp;&emsp;(a > b) 不为 true.    
`< `检查左操作数的值是否小于右操作数的值，如果是，则条件成立&emsp;&emsp;&emsp;&emsp; (a < b) 为 true.    
`>=`	检查左操作数的值是否大于或等于右操作数的值，如果是，则条件成立&emsp;(a >= b) 不为 true.    
`<=`	检查左操作数的值是否小于或等于右操作数的值，如果是，则条件成立&emsp;(a <= b) 为 true.    

###### 赋值运算符

`=`	简单的赋值运算符，赋值从右侧操作数左侧操作数&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;c = a + b将 a + b的值赋给 c  
`+=	`加法AND赋值操作符，它增加了右操作数左操作数和结果赋给左操作数&emsp;&emsp;&emsp;&emsp;&emsp;c += a 相当于 c = c + a  
`-=	`减AND赋值操作符，它减去右边的操作数从左边操作数，并将结果赋给左操作数&emsp;c -= a 相当于 c = c - a  
`*=`	乘法AND赋值操作符，它乘以右边的操作数与左操作数，并将结果赋给左操作数&emsp;c *= a 相当于 c = c * a  
`/=`	除法AND赋值操作符，它把左操作数与正确的操作数，并将结果赋给左操作数&emsp;&emsp;c /= a 相当于c = c / a  
`%=`	模量AND赋值操作符，它需要使用两个操作数的模量和分配结果左操作数&emsp;&emsp;&emsp;&emsp;c %= a 相当于 c = c % a  
`**=`	指数AND赋值运算符，执行指数（功率）计算操作符和赋值给左操作数&emsp;&emsp;&emsp;&emsp;&emsp;c **= a 相当于 c = c ** a  
`//=`	地板除，并分配一个值，执行地板除对操作和赋值给左操作数&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;c //= a 相当于 c = c // a  

交叉赋值 a,b = b,a  
解压赋值 a,b,c,d,e = [10,20,30,40,50]

###### 逻辑运算符

`and`	所谓逻辑与运算符。如果两个操作数都是真的，那么则条件成立。&emsp;&emsp;&emsp;(a and b) 为 true.  
`or`	所谓逻辑OR运算符。如果有两个操作数都是非零然后再条件变为真。&emsp;&emsp;(a or b) 为 true.  
`not	`所谓逻辑非运算符。用于反转操作数的逻辑状态。如果一个条件为真，则逻辑非运算符将返回false。&emsp;not(a and b) 为 false.  

逻辑运算符优先级not>and>or    

短路运算：  
`and`连接多个条件，会按照从左到右的顺序依次判断，一旦某一个条件为False，则无需再往右判断，可以立即判定最终结果就为False  
`or`连接多个条件，会按照从左到右的顺序依次判断，一旦某一个条件为True，则无需再往右判断，可以立即判定最终结果就为True

###### 身份运算符

`is`	is判断两个标识符是否引用自一个对象	        x is y,如果id(x)等于id(y) ，返回True    
`is not`	is not判断两个标识符是否引用不同的对象	x is not y,如果id(x)不等于id(y)，返回True

###### 成员运算符

`in`      in判断前一个对象是否包含于后一个对象     'h' in 'hello',返回ture  
`not in ` in判断前一个对象是否没有包含于后一个对象  'h' not in 'hello',返回False

#### 流程控制

程序设计的基本结构分为三种：顺序，选择和循环。任何简单或复杂的算法都可以由顺序结构、选择结构和循环结构这三种基本结构组合而成。

###### 顺序结构

程序开始运行后，从上到下按顺序执行.

###### 选择结构

选择结构也称分支结构，表示程序需要根据某个特定的条件选择其中一个分支执行。选择结构有单重、双重、多重选择以及选择的嵌套，用if，elif和else关键字来实现分支结构
```Python
#单重分支
if (a%2 == 0)：
    print('a是偶数!'')

#双重循环
if (a%2 == 0)：
    print('a是偶数!'')
else:
     print('a是奇数!'')

#多重循环
if (a%2 == 0)：
    print('a是2的倍数!'')
elif (a%3 == 0):
     print('a是3的倍数!'')
else：
    print('a既不是2，也不是3的倍数!'')

#嵌套循环
if(grade <60):
    不及格
else：
    if(grade >= 90):
        优秀
    elif(grade >= 80):
        良好
    else:
        及格
```

###### 循环结构

循环结构就是重复执行某段代码块，python中有for与while两种循环机制

####### for循环语法如下

```python
# for 变量名 in 可迭代对象: # 可迭代对象可以是字符串、列表、元组、字典等序列对象，循环结束的条件就是对象被遍历完成。
# 1. for 变量名 in 已有的可迭代对象
l= ["","lili","nini","jingjing"]
for name in l:
    #print(name)
    if name == "jingjing":
          print("我最爱的{0}出现了".format(name))
    else:
          print("同学，你好")

# 2. for 变量名 in range()   #通过range()函数来生成一个数值序列

# 函数原型：range( [start,]  stop [, step])
# start: 计数从 start 开始。默认是从 0 开始。例如range（5）等价于range（0， 5）;
# stop: 计数到 stop 结束，但不包括 stop。例如：range（0， 5） 是[0, 1, 2, 3, 4]没有5
# step：步长，默认为1。例如：range（0， 5） 等价于 range(0, 5, 1)

# range() 函数的返回对象表现为它是一个列表，但事实上它并不是，range()函数并不是在调用时一次生成整个序列，而是遍历一次才产生一个值，以减少内存的占用，其本质是一个迭代器。

# 循环嵌套

# 打印九九乘法表
for i in range(1,10):
    for j in range(1,i+1):
        print('%d*%d=%d' %(i,j,i*j),end=' ')
    print()

# 冒泡排序  
l = [1, 7, 4, 89, 34, 2]

for i in range(len(l)):                     # i控制外层循环，循环次数
     flag = False                           
     for j in range(0, len(l)-1):           # j控制内层循环，控制列表元素
         if l[j] > l[j+1]:
            l[j], l[j+1] = l[j+1], l[j]
            flag = True                     # 如果发生交换，就重新赋值b
     if not flag:                           # 如果整轮没发生交换 就跳出循环
         break
# print(l)

# 打印金字塔
#      *        
#    * * *       
#   * * * * *      
#  * * * * * * *    
# * * * * * * * * *   

Num = 5
for i in range(Num):
    for j in range(Num - i):
        print(' ',end='') # 在一行中打印空格
    for k in range(2*i+1):
        print('* ',end='') # 在一行中打印'* '
    print()

# 同理可打印直角三角形，等腰三角形，倒三角以及菱形
```

####### while循环语法如下
```python
# while 条件表达式：
#     代码块

# 1.对while循环，给定某一条件，只要满足条件，循环一直进行
# 例:猜数字:计算机出一个1到100之间的随机数，玩家输入自己猜的数字，计算机会给出相应的提示信息（猜大了、猜小了或猜对了），如果玩家猜中了数字，游戏结束。
import random

num = random.randint(1, 100)
while 1: # 相当于ture
    guess_num = int(input('请输入您猜的数字: '))
    if guess_num < answer:
        print('猜小了！')
    elif guess_num > answer:
        print('猜大了！')
    else:
        print('猜对了!')
        break
print('这个数字是:{}'.format(num))

# 2.break和continue的作用
# break结束本层循环，而continue则用于结束本次循环，进行下一次循环
num = 10
while num > 0:
    num -= 1
    if num == 5:
        continue # 结束掉本次循环，所以5不会打印，而是直接进入下一次循环
    print(num)

# 练习：求两个正整数的最大公约数、最小公倍数
a = int(input('请输入a的值'))
b = int(input('请输入b的值'))
sum = a*b
while(a%b):                        # 辗转相除法
    c = a % b
    a = b
    b = c
print('最大公约数是%d' %a)               
print('最小公倍数是%d' % (sum // a)  # 最小公倍数=两数乘积/最大公约数

```