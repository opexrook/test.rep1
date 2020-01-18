def spisok (a,d,c):
    if c == "+":
        return a+d
    elif c == "-":
        return a-d
    elif c == "*":
        return a*d
    elif c == "**":
        return a**d
    elif c== "/":
        return a/d
    elif c == "//":
        return a//d
    elif c == "%":
        return a%d
    else:
        return "неизвестная операция"
result =  spisok (int(input("number1: ")),int(input("number2: ")), input("when operacion?: "))
print("Результат: ", result)
