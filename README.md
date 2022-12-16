"def calculator():
  num1 = float(input(""请输入第一个数字: ""))
  operator = input(""请输入运算符(+、-、*、/): "")
  num2 = float(input(""请输入第二个数字: ""))

  if operator == ""+"":
    print(num1 + num2)
  elif operator == ""-"":
    print(num1 - num2)
  elif operator == ""*"":
    print(num1 * num2)
  elif operator == ""/"":
    print(num1 / num2)
  else:
    print(""无效的运算符"")

calculator()
"
![image](https://user-images.githubusercontent.com/120620843/208042921-fdcafd73-95af-49f3-8e6d-44f67122a39d.png)
