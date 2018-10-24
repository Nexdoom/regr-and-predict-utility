Regression and Prediction Script
==================

**Цель проекта:** Разработать приложения, которое производит регрессионный анализ и оценивает случайную погрешность набора данных (экспериментальных или расчетных) по заданным пользователем параметрам.

**Функционал:**
1. Реализовать функционал фильтрации данных по абсциссе (*дополнительно:* по ординате, по обеим), загружаемых в формате .csv;

2. Дать пользователю возможность разделять данные на сегменты;

3. *Дополнение 1:* возможность осуществлять мат. операции (свдиг по оси или множетель);

4. Регрессионный анализ;

5. Оценка случайной погрешности (предсказание)

6. *Дополнение 2:* вычисление погрешности для расчета с сохранением результата в excel;

7. Вывод результата в виде графиков и таблиц, а так же сохранение в .csv;

**Ресурсы:**
1. Полученные данные из эксперимнета и расчета

**Задачи:**
1. Создать формат задания параметров и хранения набора данных (словарь с ключами параметров, потом его же наполнять данными);

2. Написать функцию, которая возврщает мне объект с отфильтрованными данными и сегментами, и будет содержать функции:

   * Загрузки данных из csv файла и сразу их хранить в структуре *DataFrame*, исользуя библеотеку *pandas*;

   * Фильтрования;

   * Разделения на сегменты

3. Отловить исключения при работе с пустыми структурами и некоректными параметрами;

4. Написать функцию на базе библиотеки *statsmodels* для получения регрессионой функции;

5. Написать функцию расчета производной ргерессионной функции;

6. Написать функцию для оценки случайной погрешности, именуемое предсаказанием;

7. Написать функции вывода результатов регрессии и предсказания;

8. Написать вспомогательную функцию для отрисовки графика с результатом сегментации и фильтрации;

9. Написать функцию, которая имеет разные конфигурации расчета в зависимости от  варианта задачи:

   * У эксперимента и расчета координаты оси абсцисс совпадают ;

   * У эксперимента и расчета координаты оси абсцисс не совпадают;

   * Динамический процесс, не совпадает время начала (или конца) процесса.
