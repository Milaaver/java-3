#  Отчет о тестировании Задачи №1 - Статистика
17.05.2022 - 18.04.2020 было выполнено задание "Статистика".

На тестирование 7 часов

В результате тестирования выявлены следующие дефекты:
* дефекты не выявлены

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Домашнее задание к занятию «2.4. Циклы, параметризованные тесты и аннотации»](https://github.com/netology-code/javaqa-homeworks/blob/master/params/README.md)


В качестве источника тестовых данных использовались данные составленные согласно требованиям Задачи №1 артефакта "Домашнее задание к занятию «2.4. Циклы, параметризованные тесты и аннотации»":
- [ ] Метод StatsServiceTest.calcSum:
 - 'Right data from task'; 8; 15; 13; 15; 17; 20; 19; 20; 7; 14; 14; 18; 180
 - 'Wrong data from task'; 8; 15; 13; 15; 17; 20; 19; 20; 7; 14; 14; 18; 181
 - 'Equal data'; 10; 10; 10; 10; 10; 10; 10; 10; 10; 10; 10; 10; 120
 - 'Zero data'; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0
- [ ] Метод StatsServiceTest.calcAverage:
 - 'Right data from task'; 8; 15; 13; 15; 17; 20; 19; 20; 7; 14; 14; 18; 15
 - 'Wrong data from task'; 8; 15; 13; 15; 17; 20; 19; 20; 7; 14; 14; 18; 18
 - 'Equal data'; 10; 10; 10; 10; 10; 10; 10; 10; 10; 10; 10; 10; 10
 - 'Zero data'; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0
- [ ] Метод StatsServiceTest.monthMax:
 - 'Right data from task'; 8; 15; 13; 15; 17; 20; 19; 20; 7; 14; 14; 18; 8
 - 'Wrong data from task'; 8; 15; 13; 15; 17; 20; 19; 20; 7; 14; 14; 18; 1
 - 'Equal data'; 10; 10; 10; 10; 10; 10; 10; 10; 10; 10; 10; 10; 12
 - 'Zero data'; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0; 12
- [ ] Метод StatsServiceTest.monthMin:
 - 'Right data from task'; 8; 15; 13; 15; 17; 20; 19; 20; 7; 14; 14; 18; 9
 - 'Wrong data from task'; 8; 15; 13; 15; 17; 20; 19; 20; 7; 14; 14; 18; 1
 - 'Equal data'; 10; 10; 10; 10; 10; 10; 10; 10; 10; 10; 10; 10; 12
 - 'Zero data'; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0; 12
- [ ] Метод StatsServiceTest.monthLessAverage:
 - 'Right data from task'; 8; 15; 13; 15; 17; 20; 19; 20; 7; 14; 14; 18; 5
 - 'Wrong data from task'; 8; 15; 13; 15; 17; 20; 19; 20; 7; 14; 14; 18; 6
 - 'Equal data'; 10; 10; 10; 10; 10; 10; 10; 10; 10; 10; 10; 10; 0
 - 'Zero data'; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0
- [ ] Метод StatsServiceTest.monthMoreAverage:
 - 'Right data from task'; 8; 15; 13; 15; 17; 20; 19; 20; 7; 14; 14; 18; 5
 - 'Wrong data from task'; 8; 15; 13; 15; 17; 20; 19; 20; 7; 14; 14; 18; 6
 - 'Equal data'; 10; 10; 10; 10; 10; 10; 10; 10; 10; 10; 10; 10; 0
 - 'Zero data'; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0; 0

