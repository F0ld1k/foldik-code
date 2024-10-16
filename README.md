# foldik-code
age = int(input("Введите свой возраст: "))
if age > 14:
    print ("Добро пожаловать!")
elif age < 14:
    print ("Вам ещё рано!")
elif age == 14:
    print ("Вам 14 лет! Поздравляю!")
           
secret = int(input("Введите секретный пароль:"))
password = int(input("Введите пароль: "))
if password == secret:
   print ("Доступ разрешён!")
else:
    print("Доступ запрещён!")

simb = input("Введите символ: ")
number = ("0, 1, 2, 3, 4, 5, 6, 7, 8, 9.")
alfabet = ("a, b, c, d, f, i, k, s.")
if simb in number:
    print ("Это цифра!")
elif simb in alfabet:
    print ("Это буква!")
else:
    print ("Это не буква и не цифра!")

total = 0
towar = input("Введите стоимость товара: ")
if  towar > 1000:
    total = towar * 0.9
    print (total)
elif 500 < towar <= 1000:
    total = towar * 0.95
    print (total)
elif 0 < towar <=500:
    total = towar
    print (total)
