# Отчёт о тестировании KeyValidator
## Краткое описание

13.01.2021 - 13.01.2021 было проведено функциональное тестирование, тестирование безопасности приложения KeyValidator.

На тестирование затрачено: 1 час.


## Описание процесса тестирования

В качестве тестовых данных использовались данные :
* [Инструкция по установке OpenJDK 11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
* [Руководство использования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

### Ожидаемый результат тестирования:

Для валидных ключей "Result for <ключ>: OK;  
Для невалидных ключей "Result for <ключ>: FAIL

***В ходе тестирования выявлены следующие баги***:  
[Баг 1](https://github.com/dimonioi4/jl1t1/issues/1#issue-785112146)
[Баг 2](https://github.com/dimonioi4/jl1t1/issues/2#issue-785269376)
[Баг 3](https://github.com/dimonioi4/jl1t1/issues/3#issue-785271506)

1. Следующие ключи из списка валидных оказались невалидными:
* 80b427f8-92cd-3aae-ba04-3927fbe17c6 
* 387eedc6-12e9-3b32-9881-63b6b5e85317 

2. Следующие ключи из списка невалидных оказались валидными:
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 


Тестирование производилось в следующем окружении:

    <Windows 10 x64>
    <версия Java 11.0.9.1 2020-11-04>
   

