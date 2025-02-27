# 1.1 Класс Лоренц-векторов

Реализуйте класс `LorentzVector`, описывающий Лоренц-векторы и содержащий

1. Конструктор по умолчанию
2. Конструктор из четырех переменных `double`
3. Методы чтения компонент вектора
4. Методы модификации компонент вектора
5. Метод вывода компонент в стандартный поток
6. Методы, реализующие операции
   + сложение векторов
   + вычитание векторов
   + скалярное произведение векторов
   + умножение вектора на число
   + нахождение нормы вектора
   + преобразование в систему, движущуюся со скоростью *βc* вдоль оси *z*.

Определение класса `LorentzVector` приведено в файле `LorentzVector.h`.

## Указания

+ Определение классов стандартного вывода находятся в заголовочном файле `<iostream>`.
+ Реализуйте инкапсуляцию данных (пользователь не знает, как конкретно хранятся данные в вашем классе, а все манипуляции с компонентами вектора могут производиться только с помощью методов класса).
+ Объявляйте константными методы, которые не изменяют состояние объекта.
+ Избегайте копирования при передаче вектора в качестве аргумента функции (метода). Используйте константные ссылки `const LorentzVector&`.
+ Разделите реализацию класса на два файла: заголовочный файл с объявлением класса `LorentzVector.h` и файл с реализацией методов `LorentzVector.cpp`.
