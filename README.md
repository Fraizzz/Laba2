# Laba2
### Содержание
1. [Введение](#1)<br>
  1.1. [Назначение](#1.1)<br>
  1.2. [Бизнес требования](#1.2)<br>
    1.2.1. [Границы проекта](#1.2.1)<br>
2. [Требования пользователя](#2) <br>
  2.1. [Программные интерфейсы](#2.1) <br>
  2.2. [Интерфейс пользователяъ](#2.2) <br>
  2.3. [Характеристики пользователей](#2.3) <br>
  2.4. [Предложение и зависимости](#2.4) <br>
3. [Системные требования](#3) <br>
  3.1 [Функциональные требования](#3.1) <br>
  3.2 [Нефункциональные требования](#3.2) <br>
    3.2.1 [Атрибуты качества](#3.2.1) <br>
    3.2.2 [Внешний интерфейс](#3.2.2) <br>

Требования к проекту

### 1. Введение <a name="1"></a>

#### 1.1 Назначение <a name="1.1"></a>

Существует большое разнообразие тиров, но большинство из них травмоопасны, а это пожалуй, одно из важных требований.
А что, если создать симулятор интерактивного тира, который будет травмобезопасным, простоту использования, мобильность и возможность установки в неподготовленном помещении? Ответом на данный вопрос как раз служит данный проект – SL-Tir.

#### 1.2 Бизнес требования <a name="1.2"></a>

##### 1.2.1 Границы проекта <a name="1.2.1"></a>
Приложение позволит симулировать стрельбу с некоторого вида вооружения ВС РБ, а так же узнавать некоторую подробную информацию про них.

### 2. Требования пользователя <a name="2"></a>

#### 2.1 Программные интерфейсы <a name="2.1"></a>

Проект использует платформу на основе языка Java, JavaFX и не взаимодействует с внешними система и сервисами.

#### 2.2 Интерфейс пользователя <a name="2.2"></a>

Графический интерфейс проекта с помощью  главного окна и способа регулирования громкости. Отдельного рассмотрения требует главное окно.

|Клавиша|Реакция
---|---
|“Play”|Запускается симуляция в одиночку|
|“Play together”|Запускается симуляции с напарником|
|“Settings”|Выплывает меню настроек (громкости, графики, яркости изображения)|
|“Customize”|Выплывает окно настроек интерфейса и выбора тира|
|“Choose weapon”|Выплывает окно выбора оружия для симуляции|
|“Exit”|Выход из программы|



#### 2.3 Характеристики пользователя <a name="2.3"></a>

Целевая аудитория:

•	Люди любого возраста использующие данное приложение как развлечение.
•	Пользователи, которые хотели бы потренироваться в стрельбе и усовершенствовать свои навыки безопасно.

#### 2.4 Предложение и зависимости <a name="2.4"></a>

Данное приложение рекомендуется использовать вместе с проектором для вывода изображения на стену или телевизора с большой диагональю экрана.

### 3. Системные требования <a name="3"></a>

Запуск и работа приложения на следующих операционных системах:
•	Windows
•	Linux

#### 3.1 Функциональные требования <a name="3.1"></a>

Пользователю предоставлены возможности, представленные в таблице.

|Функция	| Требования|
---|---
|Запуск Симуляции в одиночку | Приложении должно запустить симуляцию стрельбы в тире без напарника, при нажатии клавиши “Play”|
|Запуск симуляции с напарником | Приложении должно запустить симуляцию стрельбы в тире с напарником, при нажатии клавиши “Play together” |
|Настройки приложения | Приложение должно предоставить возможность настроить симуляцию, а именно графику, яркость изображения, громкость звуков|
|Изменение интерфейса|Приложение должно предоставить возможность изменять интерфейс пользователя (Цвет и расположение информационных полей таких как количество|                      	   |патронов), а также выбор самого тира изменение места тира (поле либо помещение)|
|Выбор оружия | Приложение должно предоставить возможность изменить оружие для симуляции (пистолет (ПМ), автомат (АК-74 или АКС) или винтовка (СВД)|
|Выход | Приложение должно предоставить выйти из приложения|

#### 3.2 Нефункциональные требования <a name="3.2"></a>

##### 3.2.1 Атрибуты и качества <a name="3.2.1"></a>
	
Важными атрибутами качества данного приложения являются: быстрый запуск, малое потребление ресурсов и высокая производительность.
Также атрибутами качества являются : легкость использования засчет минималистичного интерфейса, быстрая скорость реагирования на изменение состояния кнопки, то есть задержка между нажатием клавиши и началом выполнения какой-либо функции, переносимость между системами Windows и Linux.

##### 3.2.2 Внешний интерфейс <a name="3.2.2"></a>
	
Приложение должно быть разработано в одном стиле.

