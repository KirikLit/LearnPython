# Урок 2 #
***
### Сегодня на уроке мы пройдём: ###
+ Кортежи
+ Списки
+ Словари
+ Форматирование текста
***
### Полезный материал по уроку ###
```python
a = ('Program', 15)           # Кортеж
b = ['Game 1', 12, True]     # Список
c = {'Name': 'Danya',      # Словарь
     'Gun': True,
     'Kills': 13}

# Форматирование текста
form1 = '{0}. Player {Name} have {Kills} kills}!'.format(*b, **c)
form2 = f'Program: {a[1]}, Game: {b[0]}, player: {c["Name"]}'

print(form1)
print(form2)
```
> В словари, кортежи и списки можно вставлять любые типы данных, включая словари, кортежи и списки

> При использовании команды _.format_ не стоит забывать, что список это _*args_ объект, а словарь _**kwargs_ объект,
> соответственно правильно будет _.format(*список или **словарь)_
***
### Полезные ссылки по материалам урока ###
+ [Словари](https://pythonru.com/osnovy/kortezhi-python)
+ [Списки](https://pythonru.com/primery/python-spiski-primery)
+ [Словари](https://pythonru.com/osnovy/python-dict)
+ [Функция .format](https://pythonru.com/osnovy/formatirovanie-v-python-s-pomoshhju-format)
+ [Функция f.''](https://pythonru.com/osnovy/formatirovanie-v-python-s-pomoshhju-f-strok)
