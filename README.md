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

![none](https://github.com/Hashmat-H/Hashmat-H/blob/main/Лаб2.1.png)
## Декомпозиция
![image](https://github.com/Hashmat-H/Hashmat-H/blob/main/Лаб2.2.png)

* А1 - Принять сообщение.
Сообщение поступает в программу.
* А2 - Формирование заявки.
Программа преобразует сообщение в заявку.
* А3 - Проверить выполнимость заявки.
Специалист проверяет выполнимость заявки.

## DFD-диаграмма (А2)
![image](https://github.com/Hashmat-H/Hashmat-H/blob/main/Лаб2.3.png)
Специалист проверяет выполнимость заявки, исходя из полученного сообщения в заявке и присутствия объекта в БД обслуживаемых объектов:
* Если задача невыполнима, то специалист отказывает клиенту в сообщении.
* Если задача выполнима, то специалист сообщает, что принял заявку на выполнение.

## Диаграмма прецедентов
![image](https://github.com/Hashmat-H/Hashmat-H/blob/main/Лаб2.4.png)



## Лабораторная работа 3


DFD-диаграмма :
![IFD0](https://github.com/Leo-alt-droid/Leonid-Cheshkov/blob/main/lab1/model0.png)
Диаграмма последовательности:
![IFD0](https://github.com/Leo-alt-droid/Leonid-Cheshkov/blob/main/lab1/ZLFTYXCn6Bt_dYBi_Rw05xBMX_0wROCjxKo6DECY8hGL1DsoHV1AS1TzWjdAk7NQdNc5Bs_a-JAsTK1X1vAGvFoSazABcTVEvycKPfDncccd4wK7tZhrXdfwC7dfR9uEdzifJbwCnjxGC-ViPNlGcm91FUk6nlrzyfPqxcsQ9ttZY5gvC_x63PVXFM-vu1rlmo8ipvIUgNm6L5zij7iDt1UkUSzDM8Nhi0H.png)
* Специалист вводит поисковый запрос
* Идет поиск обслуживаемых объектов и лиц в соответствующих БД
* Специалист принимает решение и пишет ответ пользователю

ER - диаграмма:  
![IFD0](https://github.com/Leo-alt-droid/Leonid-Cheshkov/blob/main/lab1/Untitled%20Diagram.drawio.png)
