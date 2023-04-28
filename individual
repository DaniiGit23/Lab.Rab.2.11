#!/usr/bin/env python3
# # -*- coding: utf-8 -*-

# Сначала объявляется функция tagg, которая принимает
# на вход тег и возвращает внутреннюю функцию stroka,
# которая заключает переданную ей строку в тег из внешней функции.
def tagg(tag):
    def stroka(s):
        return f"<{tag}>{s}</{tag}>"
    return stroka


# Запрос у пользователя тег и происходит создание экземпляра внутренней функции
# Соответствующий этому тегу
tag = input("Введите тег: ")
text = input("Введите строку: ")

#
enclose_text = tagg(tag)(text)

if __name__ == "__main__":
    print(enclose_text)
