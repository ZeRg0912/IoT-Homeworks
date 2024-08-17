# Домашнее задание к занятию 3 «Устройства ввода данных»
### Инструкция по выполнению домашнего задания
**1.** Зарегистрируйтесь на сайте **[wokwi.com](https://wokwi.com/)**.<br>
**2.** Перейдите в раздел **Start from Scratch** и выберите создание нового проекта на основе платы **Arduion UNO**.<br>
**3.** После завершения проверки работоспособности сохраните проект с помощью кнопки **SAVE**.<br>
**4.** Скопируйте ссылку на проект с помощью кнопки **SHARE**.<br>
**5.** Скопированную ссылку на ваше решение нужно отправить на проверку. Для этого перейдите в личный кабинет на сайте **[netology.ru](https://netology.ru/)**, в поле комментария к домашней работе вставьте скопированную ссылку и отправьте работу на проверку.

------------

## [Задача №1. Вывод угла поворота потенциометра в последовательный порт](Potenciometer_filter_to_Angle)

Соберите в симуляторе Wokwi схему, состоящую из платы Arduino UNO и потенциометра. Крайние выводы потенциометра подключите к GND и +5V, средний вывод подключите к любому аналоговому входу платы Arduino UNO.<br>
Разработайте программу, которая определяет угол поворота движка потенциометра в градусах, полный угол поворота движка потенциометра — 270 градусов. За нулевой угол взять центральное положение движка, то есть угол поворота может быть как положительный, так и отрицательный. Должна быть предусмотрена программная фильтрация сигнала с потенциометра с помощью фильтра скользящего среднего с окном в 10 отсчётов. Период опроса сигнала с выхода потенциометра — 100 мс. Результат необходимо выводить в последовательный порт. Выделите законченные логические блоки программы в отдельные функции.<br>
Проведите моделирование работы в симуляторе.<br>

![Схема](Potenciometer.jpg "Схема")