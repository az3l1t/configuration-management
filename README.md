# configuration-management
# First-file.
Разработать эмулятор командной строки vshell. 
В качестве аргумента vshell принимает образ файловой системы известного формата (tar, zip).
Обратите внимание: программа должна запускаться прямо из командной строки, 
а файл с виртуальной файловой системой не нужно распаковывать у пользователя.
В vshell должны поддерживаться команды pwd, ls, cd и cat. 
Ваша задача сделать работу vshell как можно более похожей на сеанс bash в Linux. 
Реализовать vshell можно на Python или других ЯП, но кроссплатформенным образом.
# Second-file
Написать на выбранном вами языке программирования программу, 
которая принимает в качестве аргумента командной строки имя пакета, 
а возвращает граф его зависимостей в виде текста на языке Graphviz. 
На выбор: для npm или для pip. Пользоваться самими этими менеджерами пакетов запрещено. 
Главное, чтобы программа работала даже с неустановленными пакетами и без использования pip/npm.
