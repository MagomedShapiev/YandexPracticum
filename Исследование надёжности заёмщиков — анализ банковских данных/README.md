# Исследование надёжности заёмщиков

## Статус
Завершен

## Описание проекта

Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.
Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

## Навыки и инструменты

- **pandas**
- **EDA**
- **Feature engineering**

## Цель исследования

Проверить, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок?
Есть ли зависимость между количеством детей и возвратом кредита в срок?
Есть ли зависимость между семейным положением и возвратом кредита в срок?
Есть ли зависимость между уровнем дохода и возвратом кредита в срок?
Как разные цели кредита влияют на его возврат в срок?

## Ход исследования

О качестве данных ничего не известно. Поэтому перед проверкой гипотез понадобится обзор данных.

Нужно проверить данные на ошибки и оценить их влияние на исследование. 

Таким образом, исследование пройдёт в три этапа:

Обзор данных.
Предобработка данных.
Проверка гипотез.

## Описание данных

- children — количество детей в семье
- days_employed — общий трудовой стаж в днях
- dob_years — возраст клиента в годах
- education — уровень образования клиента
- education_id — идентификатор уровня образования
- family_status — семейное положение
- family_status_id — идентификатор семейного положения
- gender — пол клиента
- income_type — тип занятости
- debt — имел ли задолженность по возврату кредитов
- total_income — ежемесячный доход
- purpose — цель получения кредита

## Вывод по итогам исследования

В ходе данного иследования были выполнены следующие действия: предобработка данных (удаление дубликатов явных и неявных, заполение пропущенных значений, исправление аномальных данных), типизация и категоризация данных. 

В ходе анализа полученных данных был сделан вывод, что на погашение кредита в срок вляет множество факторов: количество детей в семье, цель кредита, ежемесячный доход, семейное положение. 
Соответственно, при построении скоринговой модели особое внимание стоит уделить количеству детей в семье, ежемесячному доходу, семейному положению и цели кредита.
