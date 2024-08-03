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

------------

## Задача №2. Ультразвуковой парктроник

Соберите в симуляторе Wokwi схему, состоящую из платы Arduino UNO, ультразвукового дальномера, жидкокристаллического индикатора 16 х 2, трёх резисторов номиналом 300 Ом и одного RGB-светодиода. Подключите ультразвуковой дальномер, жидкокристаллический индикатор и RGB-светодиод к выводам платы Arduino UNO.<br>

Разработайте программу, которая измеряет расстояние до препятствия с периодичностью в 100 мс. Информация об измеренной дальности должна отображаться на жидкокристаллическом индикаторе в метрах с точностью до десятых долей. Если расстояние находится в диапазоне от 2 до 4 метров, то RGB-светодиод должен непрерывно светиться. Если расстояние находится в диапазоне от 1 до 2 метров, то RGB-светодиод должен моргать жёлтым светом с периодичностью 500 мс. Если расстояние менее 1 метра, то RGB-светодиод должен моргать красным светом с периодичностью 100 мс. Выделите законченные логические блоки программы в отдельные функции.<br>

Проведите моделирование работы в симуляторе.<br>

------------

## Задача №3. Управление освещением с помощью датчика движения

Соберите в симуляторе Wokwi схему, состоящую из платы Arduino UNO, жидкокристаллического индикатора 16 х 2, аналогового джойстика, резистора номиналом 300 Ом, светодиода и датчика движения. Джойстик подключите к линиям питания GND и +5V, его аналоговые выводы подключите к аналоговым входам платы Arduino UNO, а выход кнопки джойстика — к любому входу платы Arduino UNO. Подключите жидкокристаллический индикатор, светодиод и датчик движения к оставшимся свободным выводам платы Arduino UNO.<br>

Разработайте программу, в которой светодиод включается при наличии сигнала от датчика движения. Светодиод должен выключиться через время, которое задаётся с помощью джойстика и жидкокристаллического индикатора, алгоритм взаимодействия джойстика и индикатора нужно разработать самостоятельно. Время работы светодиода должно задаваться в диапазоне от 2 до 10 секунд с шагом 1 секунда. Выделите законченные логические блоки программы в отдельные функции.<br>

Проведите моделирование работы в симуляторе.<br>
