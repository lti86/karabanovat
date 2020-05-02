a = input("Введите Ваше имя: ")
b = int(input("Введите Ваш возраст: "))
c = float(input("Введите любимое число: "))

print(a, b, c)


time_in_sec = int(input("Enter your local time in sec: "))
hours = time_in_sec // 3600
residue = time_in_sec % 3600
minutes = residue // 60
sec = residue % 60
print(f"Now is {hours}:{minutes}:{sec} ")


number = input("Enter number: ")
a = int(number + number)
b = int(number+number+number)
summa = int(number) + a + b

print(summa)


number = input("Enter number: ")
x = 0
for i in number:
    while int(i) > x:
        x = int(i)
print(x)


выручка = int(input("Введите значение выручки, млн.: "))
издержки = int(input("Введите значение издержек, млн.: "))
if выручка > издержки:
    доход: int = выручка-издержки
    рентабельность = доход/выручка
    print(f"Вы отлично заработали. Ваша прибыль - {доход} миллионов рублей")
    сотрудник = int(input("Сколько человек работает: "))
    print(f"{доход/сотрудник} на одного сотрудника")
elif выручка == издержки:
    print("Нужно лучше")
else:
    print("Упс...")
    
    
    a = float(input("Сколько км в первый день: "))
b = float(input("Сколько км в последний день: "))
day = 1
if a > b:
    print(day)
while a < b:
    a = a + a/10
    day += 1
print(day)
