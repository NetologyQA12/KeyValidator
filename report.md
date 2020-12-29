# Отчёт о тестировании KeyValidator

## Краткое описание

25.12.2020 - 25.12.2020 было проведено Функциональное тестирование (functional testing) приложения KeyValidator.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:
* [Bug Report](https://github.com/NetologyQA12/KeyValidator/issues/2)
* [Bug Report](https://github.com/NetologyQA12/KeyValidator/issues/3)
* [Bug Report](https://github.com/NetologyQA12/KeyValidator/issues/4)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Инструкция к программе (https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)


В качестве тестовых данных использовались данные https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md:

Валидные ключи:
* Result for 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998: OK
* Result for 80b427f8-92cd-3aae-ba04-03927fbe17c6: FAIL
* Result for b295bc63-9f03-3b4b-af80-969b39f8c262: OK
* Result for 387eedc6-12e9-3b32-9881-63b6b5e85317: FAIL
* Result for c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180: OK

Невалидные ключи:
* Result for 18252235-78e0-44a5-8720-556f0c7da17a: FAIL
* Result for e66075b6-ddad-445e-baf6-161b3289522b: FAIL
* Result for b6d53250-f07e-4352-a293-6102ddf7f1ca: FAIL
* Result for c2bc778a-1cb9-46c6-b435-0489649d2a42: FAIL
* Result for 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: OK

Тестирование производилось в следующем окружении:
* ОС Windows 10 x64
* Java Version 11.0.8
* ПО IntelliJ IDEA Community Edition 2020.2.3 x64
