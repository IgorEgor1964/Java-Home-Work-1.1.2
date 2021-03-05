## Отчёт о тестировании Credit Card Number Validator.

### Краткое описание:

04.03.2020 - 04.03.2020 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 3 часа

В результате тестирования не выявлены дефекты.

### Описание процесса тестирования:

В процессе тестирования использовались следующие артефакты:

* программа IntelliJ IDEA Community Edition 2020.3

В качестве тестовых данных использовались валидные и невалидные номера банковских карт:

**Номера валидных банковских карт:**

- ВИЗА: 4485827184862433               Result is OK
- ВИЗА: 4110235313563299               Result is OK
- MasterCard: 5573898281996598         Result is OK
- MasterCard: 5305817938329339         Result is OK
- MasterCard: 5297921904135157         Result is OK
- Visa Electron: 4844367907424290      Result is OK
- Visa Electron: 4913115893057749      Result is OK
- Visa Electron: 4844987290894302      Result is OK

**Номера невалидных банковских карт:**

- ВИЗА: 4532928047652816594            Result is FAIL
- MasterCard: 54909223454135157        Result is FAIL
- Visa Electron: 4800981110894459      Result is FAIL

Тестирование производилось в следующем окружении:

* Windows 10 Домашняя 20H2, 64-разрядная операционная система, процессор x64
* Java version 11.0.10 2021-01-19 LTSJava
* IntelliJ IDEA Community Edition 2020.3
