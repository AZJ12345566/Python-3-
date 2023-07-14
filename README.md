# Python-3-
Python 学习笔记(3)
# p13 数据类型-整数类型
#可以表示正数，负数，0
n1=90
n2=-76
n3=0
print(n1,type(n1))
print(n2,type(n2))
print(n3,type(n3))
#整数可以表示为二进制，八进制，十进制，十六进制
print('十进制'，118)
print('二进制'，0b10101111)#二进制转十进制要加0b
print('八进制'，0o176)#八进制转十进制要加0o
ptint('十六进制'，0x1EAF)

# p14 数据类型-浮点类型
a=3.14159
print(a,type(a))
n1=1.1
n2=2.2
print(n1+n2)
#输出为3.300000000000003
#由此可见，浮点型进行运算有时候是不准确的
#解决方法：Decimal
from decimal import Decimal
print(Decimal('1.1')+Decimal('2.2'))

# p15 数据类型-布尔类型
f1=True
f2=False
print(f1,type(f1))
print(f2,type(f2))
#布尔值可以转换成整数计算
print(f1+1) #2  1+1的结果 True表示1
print(f2+1) #1  0+1的结果 False表示0

# p16 数据类型-字符串类型
# 字符串又被称为不可变的字符序列
# 单引号和双引号定义的字符串必须在一行
# 三引号定义的字符串可以发布在连续的多行
str1='balabala'
str2="balabala"
str3="""bala,
bala"""

str4='''bala
bala'''
print(str1,type(str1))
print(str2,type(str2))
print(str3,type(str3))
print(str4,type(str4))
