# Отчёт о тестировании Precision

## Краткое описание

12/08/2021 - 12/08/2021 было проведено функциональное тестирование приложения Precision.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Приложение по подсчёту бонусов делает неверные расчёты](https://github.com/quechuloo/Java1.2task2hola/issues/1)


В качестве тестовых данных использовались данные [с источника](https://github.com/netology-code/javaqa-homeworks/tree/master/programming):
* regularBonus = 0,3 ; specialBonus = 0,6
* totalBonus = regularBonus + specialBonus
* Ожидаемый результат: totalBonus = 0,9
* Фактический результат: totalBonus = 0.8999999999999999

Тестирование производилось в следующем окружении:
* Windows 10 Home
* 64 bits
* openjdk version "11.0.11" 2021-04-20 OpenJDK Runtime Environment AdoptOpenJDK-11.0.11+9 (build 11.0.11+9) 
* OpenJDK 64-Bit Server VM AdoptOpenJDK-11.0.11+9 (build 11.0.11+9, mixed mode)
