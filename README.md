# Домашнее задание к занятию «Kubernetes. Причины появления. Команда kubectl» - Михалёв Сергей

### Цель задания

Для экспериментов и валидации ваших решений вам нужно подготовить тестовую среду для работы с Kubernetes. Оптимальное решение — развернуть на рабочей машине или на отдельной виртуальной машине MicroK8S.

------

### Задание 1. Установка MicroK8S

1. Установить MicroK8S на локальную машину или на удалённую виртуальную машину.
2. Установить dashboard.
3. Сгенерировать сертификат для подключения к внешнему ip-адресу.

**Решение**

Установил MicroK8S</br>
<img src="images/Task_1.1.png" alt="Task_1_1.png" width="600" height="auto"></br>

Установил dashboard</br>
<img src="images/Task_1.2.png" alt="Task_1_2.png" width="600" height="auto"></br>
В браузере</br>
<img src="images/Task_1.3.png" alt="Task_1_3.png" width="400" height="auto"></br>

------

### Задание 2. Установка и настройка локального kubectl
1. Установить на локальную машину kubectl.
2. Настроить локально подключение к кластеру.
3. Подключиться к дашборду с помощью port-forward.

**Решение**

Установил на вторую локальную машину kubectl</br>
<img src="images/Task_2.1.png" alt="Task_2_1.png" width="250" height="auto"></br>
Проверил подключение</br>
<img src="images/Task_2.2.png" alt="Task_2_2.png" width="250" height="auto"></br>
Создал пользователя с правами, достаточными для работы с дашбордом</br>
<img src="images/Task_2.4.png" alt="Task_2_4.png" width="500" height="auto"></br>
Дашборд</br>
<img src="images/Task_2.3.png" alt="Task_2_3.png" width="700" height="auto"></br>

------

