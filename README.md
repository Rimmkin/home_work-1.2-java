# Отчёт о тестировании приложения Untitled

## Краткое описание

11.09.2020-12.10.2020 проведено функциональное тестирование приложения untitled.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* [Ошибка при введении валидного номера кредитной карты American](https://github.com/Rimmkin/home_work-1.2-java/issues/1)
* [Ошибка при вводе валидного номера кредитной карты Discover](https://github.com/Rimmkin/home_work-1.2-java/issues/2)
* [Ошибка при вводе валидного номера карты Diners Club - Carte Blanche](https://github.com/Rimmkin/home_work-1.2-java/issues/3)
* [Oшибка при вводе валидного номера карты Diners Club - International](https://github.com/Rimmkin/home_work-1.2-java/issues/4)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* Баг-репорт

В качестве тестовых данных использовались номера кредитных карт с сайта https://www.freeformatter.com/credit-card-number-generator-validator.html:
* VISA:4539852604778130  (OK)
* MasterCard:5362027885352215 (OK)
* American Express (AMEX):376159650288368  (FAIL)
* Discover:3542144085351788803 (FAIL)
* Diners Club - North America:5421915148201196  (OK)
* Diners Club - Carte Blanche: 30470157361832 (FAIL)
* Diners Club - International: 36815894500700 (FAIL)
* Maestro:6759163329410027 (OK)

Тестирование производилось в следующем окружении:
* Устройство: ноутбук ASUS N73S
* ОС: Windows 10 Pro-64 bit
* Java version: "11.0.8" 2020-07-14
