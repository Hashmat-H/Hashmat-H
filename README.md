## Лабораторная работа 1

### IDEF0-диаграмма

![](https://github.com/Hashmat-H/Hashmat-H/blob/main/1.png)

**Предложение:** менеджер принимает записи, состоящие из сообщений в заявках и с помощью телеграмм-бота оповещает о записи.

### Class Diagram

![](https://github.com/Hashmat-H/Hashmat-H/blob/main/2.png)

### Usecase Diagram

![](https://github.com/Hashmat-H/Hashmat-H/blob/main/3.png)

## Лабораторная работа 2

## IDEF0-диаграмма

![none](https://github.com/Leo-alt-droid/Leonid-Cheshkov/blob/main/lab1/model1.png)
## Декомпозиция
![image](https://github.com/Leo-alt-droid/Leonid-Cheshkov/blob/main/lab1/model2.png)

* А1 - Принять сообщение.
Сообщение поступает в программу.
* А2 - Формирование заявки.
Программа преобразует сообщение в заявку.
* А3 - Проверить выполнимость заявки.
Специалист проверяет выполнимость заявки.

## DFD-диаграмма (А2)
![image](https://github.com/Leo-alt-droid/Leonid-Cheshkov/blob/main/lab1/model4.png)
Специалист проверяет выполнимость заявки, исходя из полученного сообщения в заявке и присутствия объекта в БД обслуживаемых объектов:
* Если задача невыполнима, то специалист отказывает клиенту в сообщении.
* Если задача выполнима, то специалист сообщает, что принял заявку на выполнение.

## Диаграмма прецедентов
![image](http://www.plantuml.com/plantuml/png/hL7DIiD04BxlKmmvwQ7W0uYqzLp8pVEIh6recfND5WzMI28gs5u4ZuBu1ZMa6fhQliBC6pdjMka360ZCVZ_VpEosKokD7OzYaGwZv4eQEG8PM6tWHW1_NHaC-qQFa_1SnunU32AhTap767tjm6xCAYVN9bJc4Bqz21wdAf2f-h_eM5rQi1fCr1zO22EZ0XlfHBWD_1EGANYKuveAokWEA_p66fVUhw3d1FYAQwoORcYsftp7lEC65_J0fZasM5DEnP_PAPxn1TZ-mLqQZlXaQSdY1QveIlUEUkBZaWgkIq_iBw7Z_6-KRN7kad5-GJF0agQuOR3PJRlYwND7V75mXNDwnDeJFhHQSDGv5lnlovxWVKydNFcYny3aZFSJRPM4_Be_)



## Лабораторная работа 3
