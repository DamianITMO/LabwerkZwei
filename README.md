# Лабораторная работа 2

Я присваиваю значение переменной "а" значение аргумента $1. 
Затем я разделил значение этой переменной на четыре разных, указав разделителем полей точку, используя команду "IFS".

Затем я одной длинной командой запускаю встроенный калькулятор командой "bc", перевожу каждую из переменных в двоичную систему командой "obase". Затем я "выдаю" результат этой операции на уровень выше, "заворачиваю" его как переменную и передаю в команду "printf". Там, я для сооветствия заданию форматирую каждый октет IP-адреса длиной в 8 символов и вывожу это в итог.

Для уменьшения количества строчек я использовал ";", чтобы скомпоновать команды в одну строку.

![image](/2.png)

В итоге этот скрипт мне вывел необходимый в задаче результат:

![image](/1.png)
