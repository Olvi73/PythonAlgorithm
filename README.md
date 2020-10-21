# PythonAlgorithm
## Q1
>+ **编写一个Python程序文件，输出下面结果。**  
```
学习Python编程  
学习Python编程  
学习Python编程学习Python编程  
```
## Q2
>+ **编写程序，求解鸡兔同笼问题。一个笼子中有鸡X只，兔Y只，每只鸡有2只脚，每只兔有4只脚。若鸡和兔的总头数为H，总脚数为F。输入总头数和总脚数，输出笼中鸡和兔的数。**  
  

## Q3
>+ **某职工每天的工资是P元，本月他工作了D天，本月应缴工会会费为月工资的0.5%. 房租水电费为月工资的1.5%. 扣除公积金为月工资的3.5%及医药费27.83元。输入日工资和月工作天数计算出职工本月实得工资。**  
  

## Q4  
>+ **输入平面坐标系两点的坐标，计算显示两点间的距离。**
  

## Q5
>+ **由计算机随机产生一个整数，如果是90分以上，打印出“A”的评语，80分以上的，打印出“B”，70分以上的，打印出“C”，60分以上的打印出“D”，不及格的打印出”E”。**
  

## Q6
>+ **输入一个字符,判断该字符是大写字母. 小写字母，数字还是其他字符，并作相应的显示。**  
  

## Q7
>+ **给定一个序列，减去最大最小值，算出平均值。**  
  

## Q8
>+ **某编写程序，在10个数字和26个字母组成的列表中随机生成8个8位密码。**  
  

## Q9
>+ **编写程序，使用字典存储学生信息，包括学号和姓名，请根据学生学号从小到大输出学生的信息.**  
学号若要求从大到小排，怎么处理  
```python
order=sorted(stu.items(),key=lambda x:x[0],reverse=True)   #将原来的reverse=False改成reverse=True
```

## Q10
>+ **编程计算由下列公式确定的S值，其中n是用户输入的正整数。S = 2/1 + 3/2 + 5/3 + 8/5 + 13/8 + 21/13 + …**

## Q11
>+ **编写一个能输出由符号构成菱形图案的小程序，如若输出入5，则输出如下：**  
```
        *
    *   *   *
*   *   *   *   *
    *   *   *
        *
//输入的数字为1、3、5...
```

## Q12
>+ **设计一个字典，并编写程序，用户输入内容作为键，然后输出字典中对应的值，如果用户输入的键不存在，则输出“您输入的键不存在！ ”**  

## Q13
>+ **编写程序，生成一个包含20个随机整数的列表，然后删除其中所有奇数，并输出删除前后列表。**

## Q14
>+ **编写传统的石头、剪刀、布的游戏程序，单局胜负规则是，剪刀胜布，布胜石头，石头胜剪刀。用户玩家和计算机对阵，采用7局4胜制（为了简单便于判定，设计算机的出拳方式是固定的）。最后输出胜负或平局信息。请编程模拟实现。(若电脑出拳是随机的怎么实现？)**  

## Q15
>+ **编写函数，可以接收任意多个整数并输出其中的最大值和所有整数之和。**  

## Q16
>+ **编写函数求二元一次方程，返多个返回值。**  

## Q17
>+ **给定一个嵌套列表，递归实现嵌套列表求和，打印求和后的结果。**  

## Q18
>+ **用函数实现杨辉三角形输出。**  

## Q19
>+ **设计一个类Student,在类中定义两个方法，一个用于输入两门成绩，一个用于算总分和平均分。并测试类。**  

## Q20
>+ **设计一个类Bank,实现银行账号账目管理，包括建账号，存入和取出。并测试类。**  

## Q21
>+ **设计一个类Mlei,类中有公有类属性，私有类属性，构造方法，公有对象属性，私有对象属性。并测试。**  

## Q22
>+ **设计一个三维向量类， 并实现向量的加法、 减法以及向量与标量的乘法和除法运算。**  

## Q23
>+ **假设有一英文文本文件，编写程序读其内容，并将其中的大写字母变为小写字母，小写字母变为大写字母。**  

## Q24
>+ **编写程序，将包含学生成绩的字典保存为二进制文件，然后再读取内容并显示。**  

## Q25
>+ **读取一个文件，显示除了以井号(#)开头的行以外的所有行**  

## Q26
>+ **参考相关资料，读取一个EXCEL文件，并显示文件内容**  

## Q27
>+ **读取iris.CSV文件，并显示文件内容，并写回第二列均值**  

## Q28
>+ **编写一窗口，实现单击鼠标左、右键事件检测及键盘事件检测。**  

## Q29
>+ **编写一窗体，分别测试Packer、Grid、Place布局**

## Q30
>+ **利用Entry部件及Button编写一个任意数相加并得结果的GUI**  

## Q31
>+ **设计一个窗体，模拟QQ登录界面，当用户输入号码 123456 和密码 ABCD 时提示正确，否则提示错误。**  

## Q32
>+ **编写一个GUI,完成向文件添加一条记录**  

## Q33
>+ **建立一个SQLITE数据库Studb，内含Student表，表结构如下所示。**

| 字段名	| 类型和宽度 |	字段名 | 类型和宽度 |
| ---- | ---- | ---- | ---- |
| 学号 | 文本 | 姓名 | 文本 |
| 性别 | 文本 | 出生日期 | 文本 |
| 团员否 | 文本 | 年龄 | 数字 |
| 籍贯 | 文本 | 入学成绩 | 数字 |
| 奖学金 | 数字 | 个人简历 | 文本 |

+ 插入若干条记录  
+ 显示表头  
+ 显示并输出记录  
+ 显示并输出查询记录  
+ 添加、删除、修改记录并显示结果  
+ 导入CSV格式文件记录