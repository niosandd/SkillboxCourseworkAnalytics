# Анализ образовательных данных

## 1. Описание и начальная работа с данными

📊 **Подготовка данных и описание:**

- Объединили датасеты (кроме students.scv) в один общий для дальнейшей работы.
- Создали отдельный датасет для расчета среднего возраста студентов курсов.
- Посчитали:
  - общее количество курсов в датасете;
  - количество модулей на каждом курсе;
  - количество уроков в каждом модуле на каждом курсе;
  - медианное количество уроков в модуле на каждом курсе;
  - количество учеников на каждом курсе;
  - минимальный, максимальный, средний, медианный возраст студентов;
  - минимальный, максимальный, средний, медианный возраст студентов на каждом курсе.

📈 **Bar-chart:**
- Отражает количество студентов на каждом курсе.
- Ticks развернуты для читаемости.

📊 **Горизонтальный bar-chart:**
- Отражает количество студентов на каждом курсе.
- Заголовок присутствует, значения отсортированы.
- Цвет столбцов содержит информацию о сфере курса, прозрачность установлена на 0.5.
- Нанесена линия медианы с уникальным цветом.

### **Аналитический вывод:**
- Получен полный набор метрик, описывающих основные характеристики данных.

## 2. Расчет потенциальной нагрузки на преподавателей

📈 **Line-graph:**
- С отображением прироста студентов в каждом месяце для каждого курса (15 графиков).
- С несколькими линиями, отражающими прирост студентов в каждом месяце для каждого курса (15 линий).

📊 **Line-graph:**
- С отображением количества прогрессов в каждом месяце для каждого курса (15 графиков).
- С одним line-graph для всех курсов (15 линий).

### **Аналитический вывод:**
- Получены данные о нагрузке на преподавателей в разрезе месяцев и курсов.

## 3. Выявление проблемных модулей

📈 **Line-graph:**
- С медианным временем прохождения каждого модуля для каждого курса (15 графиков).

📈 **Line-graph:**
- С линиями для каждого курса с медианным временем выполнения домашней работы по месяцам (15 линий).

### **Аналитический вывод:**
- Получены данные о времени прохождения модулей и выявлена сезонность в выполнении домашних работ.

**Общий вывод:**
- Проведен обширный анализ данных, включающий описание, графики и расчеты метрик по различным аспектам обучения. Получены ценные инсайты для оптимизации учебного процесса. 🚀
