# Сравнение данных по контрольным точкам из различных источников

## Данные
Эталонный реестр мероприятий (выгрузка)
Контрольные точки в привязке к результатам федеральных проектов (выгрузка из ГИИС "Электронный бюджет" от Минфина России)
Выгрузка 4852 каталога эталонного реестра мероприятий (привязка контрольных точек к мероприятиям Эталонного реестра)

## Задача
Нужно сравнить количество контрольных точек (КТ) Эталонного реестра мероприятий с количеством КТ в ГИИС "Электронный бюджет". На выходе получить таблицу: ID/мероприятие/Кол-во КТ в Эталонном реестре/Кол-во КТ в Электронном бюджете

## Использованные методы и библиотеки
*Загрузка, сборка данных, обработка пропусков, дубликатов, соединение таблиц*

**Pandas**

## Результаты
Были загружены данные из трех источников, изучены, обработаны пропуски, удалены дубликаты, соединены в единую таблицу требуемого формата. 

## Статус проекта
Завершен

