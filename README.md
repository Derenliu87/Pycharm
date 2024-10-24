# Pycharm
Youtube pycharm

#1.string / age = 30, print("我的年纪" + str(age))
#2.integer(整数) / age = 50
#3.Float（浮点数）
#gpa = 3.3
#print(f'#我的GPA为 {gpa} 分')
#4.string
#name = “DerenSunan”
#print(f'我的名字是 {name} ')
#5.boolean (true, false)
#U_loveme = True
#print(f'你喜欢我吗？{U_loveme}')
#print(type(U_loveme))
from functools import total_ordering
from gettext import install
from tkinter.font import names

#6.type casting(类型转换)
# name = ”deren“
# age = 25
# gpa = 3.9
# student = True
#显性转换 and 隐性转换
# print(type(name))
# print(type(age))
# print(type(gpa))
# print(type(student))
#同理将gpa变成int,Student变成str
# student = str(student)
# print(student)
# print(type(student))

#7.input(取得使用者输入)
# name = input('您的名字是：')
# print(f'你的名字是{name}')

#设计填词游戏
# adj_1 = input("请输入第 1 个形容词:")
# noun = input("请输入名词:")
# adj_2 = input("请输入第 2 个形容词:")
# verb = input("请输入名词:")
# adj_3 = input("请输入第 3 个形容词:")
# print(f"今天我去了一个{adj_1}的动物园，在参观期间我看到了{noun}这个{noun}很{adj_2}，正在{verb}，我感到很{adj_3}")

#计算矩形面积
# length = float(input("请输入矩形的长度（公分）:"))
# width = float(input("请输入矩形的宽度（公分）:"))
# area = length * width
# print(f"面积为{area}平方公分")

#购物车程式
# item = input("你想购买什么物品？")
# price = float(input("价格多少？"))
# quantity = int(input("你需要多少件？"))
# total = price * quantity
# print(f"你购买了{item}{quantity}，总价值￥{total}")

#8.加减乘除
# apples = 10
# apples += 2
# print(apples)
# apples += 5
# print(apples)
# apples -= 12
# print(apples)
# apples *= 3
# print(apples)
# apples /= 2
# pprint(apples)

#9.指数（平方，三次方）
# apples = 4
# apples **= 2
# print(apples)
# apples **= 3
# print(apples)

#10.模数mod(余数)
# 10 mod 3 等于 3 余 1
# print(10 % 3)
# 11 mod 3 等于 3 余 2
# print(11 % 3)
# 12 mod 3 等于 4 余 0
# print(12 % 3)

#11.次方 pow（数学函数表示）
# print(pow(2,5))

#12.Max（最大值）Min（最小值）
# x = 1
# y = 2
# z = 3
# print(max(x,y,z))
# print(min(x,y,z))

#13.round(四舍五入)
# a = 3.67
# print(round(a))

#14.abs绝对值
# b = -100
# print("绝对值:",abs(b))

#15.round四舍五入（无条件进位/无条件舍去）
# import math
# x = 12.6
# print(round(12.6))
# print(math.ceil(x))
# print(math.floor(x))

#圆周率Π
# import math
# print(math.pi)

#圆的周长
# radius = float(input("请输入圆的半径"))
# a = 2 * math.pi * radius
# print(f"圆的周长为{round(a,2)}")

#圆的面积
# area = float(input("请输入圆的半径"))
# a = math.pi * radius ** 2
# print(f"圆的面积为{area(a,2)}")

#16.if,else,elif（else if）控制流程
# for_sale = True
# if for_sale:
#     print("此项目正在出售")
# else:
#     print("此项目未出售")

#注册流程检验
# age = int(input("请输入你的年龄："))
# if age > 65:
#     print("你年龄太大无法注册")
# elif age >=18:
#     print("你可以注册")
# else:
#     print("你必须年满18岁才可以注册")

#计算机程式 练习if,else,elif（else if）
# operator = input("请输入运算符（加法：+，减法：-，乘法：*，除法：/，）：")
# num1 = float(input("请输入第一个数字："))
# num2 = float(input("请输入第二个数字："))
#
# if operator == "+":
#     result = num1 + num2
# elif operator == "-":
#     result = num1 - num2
# elif operator == "*":
#     result = num1 * num2
# elif operator == "/":
#     result = num1 / num2
# else:
#     print("运算符号无效")
# print(f"运算结果是{result}")

#体重转换器
# weight = float(input("请输入你的体重："))
# unit = input("你的体重是公斤还是磅？（kg/lb）").upper()
# if unit == "KG":
#     weight *= 2.2
#     new_unit = "磅"
# elif unit == "LB":
#      weight /= 2.2
#      new_unit = "公斤"
# else:
#      print("单位不正确")
#      exit()
# print(f"你的体重是{round(weight)}{new_unit}")

#温度转换器
# unit = input("请输入当前的温度单位（摄氏 C，华氏 F）：").upper()
# temp = float(input("请输入温度："))
#
# if unit == "C":
#     temp = round(9 * temp / 5 + 32)
#     print(f"当前为 {temp} 华氏摄氏度")
# elif unit == "F":
#     temp = round((temp-32) * 5 / 9)
#     print(f"当前为 {temp} 摄氏度")
# else:
#     print("不符规格的温度计量单位")

#17.逻辑运算符 and 和 not
# temp = int(input("请输入现在的温度："))
# if temp >= 18 and temp <= 30:
#     print("温度很舒适")
# else:
#     print("温度不适宜")

#18.字串方法（`len()`,`find()`,`capitalize()`,`upper()`,`lower()`,`count()`,`replace`,查询完整字符串help(str).
#使用者全名
# name = "code shibao 倒霉蛋"
#
#几个字元 len
# length = len(name)
# print("您的全名共有", length, "个字元。")
#
#找到第一个空格 find
# space_pos = name.find(" ")
# print("第一个空格出现在第", space_pos, "个字元。")
#
# capitalize(开头第一个字母变大写)`
# name_capitalized = name.capitalize()
# print("你的全名(第一个字母大写)：", name_capitalized)
#
# upper(你的字母全部大写)
# name_upper = name.upper()
# print("你的全名(全部大写)：", name_upper)
#
# lower（你的字母全部小写）
# name_lower = name.lower()
# print("你的全名（全部小写）：", name_lower)
#
# count()
# phone_number = input("请输入你的电话号码")
# dash_count = phone_number.count("-")
# print("你的电话号码中共有", dash_count, "个短横线。")

# replace()
# phone_number = input("请输入你的电话号码")
# phone_number = phone_number.replace("-","")
# print("您的电话号码（短横线换成空格）:", phone_number)

#验证使用者输入的合法性(你的使用者名称不能超过12个字元，不能包含空格，不能包含数字，如都符合显示 欢迎 + 使用者名称)
# username = input("请输入你的使用者名称：")
# if len(username) > 12:
#    print("你的使用名称不能超过12个字元。")
# elif " " in username:
#     print("你的使用名称不能包含空格。")
# elif not username.isalpha():
#     print("你的使用名称不能包含数字。")
# else:
#     print("欢迎" + username)

#19.索引运算符(第一个字元，第二个字元，第五个字元，最后一个字元)
# credit_number = "1234-5678-9999-8888"
# first_char = str(credit_number)[0]
# print("第一个字元 is", first_char)

# credit_number = "1234-5678-9999-8888"
# second_char = str(credit_number)[1]
# print("第二个字元 is", second_char)
#
# credit_number = "1234-5678-9999-8888"
# five_char = str(credit_number)[0:6]
# print("第五个字元 is", five_char)
#
# credit_number = "1234-5678-9999-8864"
# last_char = str(credit_number)[-1]
# print("最后一个字元 is", last_char)
#
# credit_number = "1234-5678-9999-8864"
# last_two_char = str(credit_number)[-2]
# print("最后两个字元 is", last_two_char)

#Email程式
# email = "derensunan@gmail.com"
# index = email.index("@")
# print(index)
# print(email[:index])
# print(email[(index+1):])

#20.f-string字符串格式化(精准取小数)
# price_1 = 32.38128
# price_2 = -3234
# price_3 = 7.212
#
# print(f"price 1 is {price_1:.2f}\n"
#       f"price 2 is {price_2:.2f}\n"
#       f"price 3 is {price_3:.1f}\n")

#需要显示字符前正负符号
# print(f"price 1 is {price_1:+.2f}\n"
#       f"price 2 is {price_2:+.2f}\n"
#       f"price 3 is {price_3:+.1f}\n")

#需要显示字符向左，向右，置中（<, >, ^）
# print(f"price 1 is {price_1:^20.2f}\n"#^后的数字代表位数
#       f"price 2 is {price_2:^20.2f}\n"
#       f"price 3 is {price_3:^20.1f}\n")

#混合不同符号,需要显示字符20位并置中，并显示正负
# print(f"price 1 is {price_1:^+20.2f}\n"#^后的数字代表位数
#       f"price 2 is {price_2:^+20.2f}\n"
#       f"price 3 is {price_3:^+20.1f}\n")

#21.while(无限循环)登录程式循环验证，直到不满足While条件
# name = ""
# while name == "":
#     name = input("Your name:")
# print(f"Hello, {name}!")

#该死的小可爱
# food = input("please enter your favorite food")
# while food != "fuck you":
#     print(f"Turns out you like such disgusting that {food}")
#     food = input("please enter your favorite food:")
# print("Good Bye!~")

# num = int(input("PLS enter a number from 1 to 100 :"))
# while num < 1 or num > 100:
#     print(f"You sb read the question clearly and then answer it again")
#     num = int(input("PLS enter a number from 1 to 100 :"))
# print(f"Your right !!!")

#复利计算机(总金额=本金*（1+（利率/100））)**时间
amount = 0
rate = 0
time =0

while amount <= 0:
    amount = float(input("PLS enter your principal :"))
    if amount <= 0:
        print("The principal cannot be less than or equal to zero")
print("Your principal is", amount)

while rate <= 0:
    rate = float(input("PLS enter rate percent:"))
    if rate <= 0:
        print("The rate cannot be less than or equal to zero")
print("Your rate percent is", rate)

while time <= 0:
    time = int(input("PLS enter your holding period :"))
    if time <= 0:
        print("The period cannot be less than or equal to zero")
print("Your holding period is", time)

#(总金额=本金*（1+（利率/100））)**时间
total_amount = amount * (1 + (rate / 100)) ** time
profit = total_amount -amount

print("Your total amount is :", round(total_amount, 3))
print("Your profit is :", round(profit,3))
