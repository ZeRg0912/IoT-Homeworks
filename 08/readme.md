# Домашнее задание к занятию 8. «Дистанционное управление по инфракрасному каналу»
### Инструкция по выполнению домашнего задания
**1.** Зарегистрируйтесь на сайте **[wokwi.com](https://wokwi.com/)**.<br>
**2.** Перейдите в раздел **Start from Scratch** и выберите создание нового проекта на основе платы **Arduion UNO**.<br>
**3.** После завершения проверки работоспособности сохраните проект с помощью кнопки **SAVE**.<br>
**4.** Скопируйте ссылку на проект с помощью кнопки **SHARE**.<br>
**5.** Скопированную ссылку на ваше решение ДЗ нужно отправить на проверку. Для этого перейдите в личный кабинет на сайте **[netology.ru](https://netology.ru/)**, в поле комментария к домашней работе вставьте скопированную ссылку и отправьте работу на проверку.

------------

## [Задача №1. Управление серводвигателем с помощью ИК пульта](IR_Remote)

Соберите в симуляторе Wokwi схему, состоящую из платы Arduino UNO, сервопривода, приёмника ИК, жидкокристаллического индикатора и пульта ИК. Подключите сервопривод к любому выводу, поддерживающему формирование ШИМ сигнала, а остальные элементы — к оставшимся свободным выводам. Пульт ИК никуда не подключается.<br>

Разработайте программу, которая управляет углом поворота сервопривода с помощью ИК пульта. Использовать кнопки от «0» до «9» для ввода значения угла, кнопку «С» для отмены ввода при ошибке, а кнопку «PLAY» — для заверешения ввода. На жидкокристаллическом индикаторе отображать процесс ввода нового угла. На привод информация о новом угле должна передаваться только после нажатия на кнопку «PLAY».<br>

Проведите моделирование работы в симуляторе.<br>

------------

## [Задача №2. Управление работой шагового двигателя с помощью внешних прерываний](Interrupts)

Соберите в симуляторе Wokwi схему, состоящую из платы Arduino UNO, шагового двигателя и двух кнопок. Подключите кнопки к входам внешних прерываний 0 и 1, выводы 2 и 3 соответственно, а шаговый двигатель — к любым оставшимся выводам платы Arduino UNO.<br>

Разработайте программу, которая опрашивает кнопки в подпрограммах обработки внешнего прерывания и управляет состоянием шагового двигателя и направлением его вращения: одна кнопка отвечает за запуск и останов двигателя, вторая — за переключение направления вращения.<br>

Проведите моделирование работы в симуляторе.<br>

------------

## [Задача №3. Формирование светового сигнала SOS по нажатию на кнопку](SOS)

Соберите в симуляторе Wokwi схему, состоящую из платы Arduino UNO, одной кнопки и одного светодиода. Подключите кнопку к входу внешнего прерывания 0, вывод 2, а светодиод — к любому оставшемуся выводу платы Arduino UNO.<br>

Разработайте программу, в которой реализуется формирование на светодиоде сигнала SOS (...---...) при нажатии на кнопку. Кнопка должна обрабатываться с помощью внешнего прерывания. Длительность точки — 200 мс, длительность тире — 600 мс. Формирование временных интервалов следует производить с помощью прерывания от таймера.<br>

Проведите моделирование работы в симуляторе.<br>
