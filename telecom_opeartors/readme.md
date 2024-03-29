# Поиск неэффективных операторов
* [Telecom_opeartors.ipynb](https://github.com/AleksandrK86/practicum/blob/main/telecom_opeartors/Telecom_operators.ipynb)</code> (Jupiter Notebook)
* [Презентация](https://github.com/AleksandrK86/practicum/blob/main/telecom_opeartors/presentation.pdf) (PDF)
* [Дашборд](https://public.tableau.com/views/Telecom_16738978921550/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) (Tableau)

## Описание проекта
Компания - оператор связи "Нупозвони", клиентами которой являются колл-центры, как работающие с входящими вызовами, так и специализирующиеся на обзвонах, прорабатывает идею нового сервиса: определение неэффективных операторов колл-центров.

**Задачи проекта:**  Определить пороги значений признаков неэффективности операторов, исходя из количества неэффективных оперторов в колл-центрах выявить долю клиентов, которым потенциально может быть интересен данный сервис. Сделать выводы о потенциальной востребованности сервиса

## Навыки и инструменты
* Python
* Pandas
* Matplotlib
* Seaborn
* проверка статистических гипотез
* визуализация данных
* Tableau
* построение дашбордов

## Общие выводы:
**Признаки неэффективности и пороги**

1. Средняя доля пропущенных вызовов в день: порог эффективности определён на уровне не более 22% пропущенных вызовов для операторов, специализирующихся на входящих вызовах.
2. Среднее время ожидания ответа на вызов: не более 32 секунд для операторов, специализирующихся на входящих вызовах
3. Количество исходящих вызовов в день: не менее 3, установлен для операторов, специализирующихся на исходящих вызовах.
4. Средняя продолжительность разговора: не менее 37 секунда, установлен для операторов, специализирующихся на исходящих вызовах.

**По статистическому анализу**

* Различия в критериях эффективности статистически значимы по всем четырём критериям у операторов, признанных неэффективными и у операторов с нормальной эффективностью. 
* По остальным критериям критерия "средняя продолжительность исходящего звонка" можно сделать вывод, что они статистически лучше в колл-центрах, где работают только операторы с нормальной эффективностью.

**Результаты анализа эффективности операторов**

1. Четверть всех операторов определены как неэффективные.Такие операторы определены в 46% колл-центров.
2. Доля неэффективных операторов в большинстве колл-центров, где такие операторы есть - от 30% до 50%.

**Колл-центры, потенциально заинтересованные в новом сервисе**
1. Неэффеективные операторы определены в 46% колл-центров;
2. Штат, состоящий из не менее 3 операторов - у 25% колл-центров;
3. Доля колл-центров, где в день совершается более 10 звонков, составляет 16%;
4. Одним из вышеназванных признаков обладает 9% клиентов, двумя - 13%, тремя - 8%;
5. Всего доля потенциальных клиентов, которая обладает хотя бы одним признаком потенциальной заинтересованности в сервисе - 30%.
