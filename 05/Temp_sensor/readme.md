# Домашнее задание к занятию 5. «‎Обработка датчиков»
### Инструкция по выполнению домашнего задания
**1.** Зарегистрируйтесь на сайте **[wokwi.com](https://wokwi.com/)**.<br>
**2.** Перейдите в раздел **Start from Scratch** и выберите создание нового проекта на основе платы **Arduion UNO**.<br>
**3.** После завершения проверки работоспособности сохраните проект с помощью кнопки **SAVE**.<br>
**4.** Скопируйте ссылку на проект с помощью кнопки **SHARE**.<br>
**5.** Скопированную ссылку на ваше решение ДЗ нужно отправить на проверку. Для этого перейдите в личный кабинет на сайте **[netology.ru](https://netology.ru/)**, в поле комментария к домашней работе вставьте скопированную ссылку и отправьте работу на проверку.

------------

## Задача №1. Измерение температуры в нескольких точках

Соберите в симуляторе Wokwi схему, состоящую из платы Arduino UNO, трёх NTC-термисторов и жидкокристаллического индикатора 16 х 2. Подключите выход термисторов к аналоговым входам платы Arduino UNO, а жидкокристаллический индикатор — к оставшимся свободным выводам.<br>

Разработайте программу, которая считывает показания датчиков температуры с периодичностью 100 мс, выполняет их программную фильтрацию с помощью усреднения за 10 измерений (по каждому каналу измерения) и выводит на жидкокристаллический индикатор следующую информацию: максимальное значение температуры из трёх датчиков, минимальное значение температуры из трёх датчиков, среднее значение температуры по трём датчикам.<br>

Проведите моделирование работы в симуляторе.<br>

![Схема](Temp_sensors.jpg "Схема")