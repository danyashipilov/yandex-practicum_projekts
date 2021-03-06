# **Проект по построению модели для предсказания коэффициента восстановления золота из золотосодержащей руды**

**Стек инструментов**
RandomForestRegressor,GridSearchCV,numpy ,matplotlib,seaborn

**Вводные данные**

В нашем распоряжении данные с параметрами добычи и очистки

**Цель**
Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.


**Структура проекта**
1  Подготовка данных

1.1  Загрузка и подготовка дынных
1.2  Проверка расчета эффективности обогащения
1.3  Анализ недоступных признаков
1.4  Предобработка данных

2  Анализ данных

2.1  Именения концентрации металлов
2.2  Сравним распределения размеров гранул
2.3  Исследуем суммарную концентрацию всех веществ

3  Модель

3.1  Функция sMAPE
3.2  Подготовим выборки
3.3  Обучение модели
3.4  Проверка на тестовой выборке

4  Выводы


**Общий вывод**

По итогу проеданной работы можно сделать выводы:

- Мы загрузили данные
- Проверили расчет эффективности обогащения
- Провели Анализ Недоступных признаков
- Провели предобработку данных
- Провели анализ изменения концентрации металлов
- Сравнили распределения размеров гранул
- Исследовали суммарную концентрацию всех веществ
- Написали функцию sMAPE
- Обучили модели и выбрали лучшую
- Провели финальную проверку на тестовой выборке
- И получили финальный результат погрешности в размере 7.9 и 9.6 % соответственно для двух целевых признаков

И итоговую погрешность по формуле равную 9,2 %
