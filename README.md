[![image](https://github.com/avfawkes/Hackathon_Severstal/assets/65026452/469a86c9-fa33-440c-b1be-a6962557b9a9)](https://serverchallenge.ru)

# Hackathon_Severstal
![Jupyter](https://img.shields.io/badge/Jupyter-%23f37726?logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-%23150458?logo=pandas&logoColor=white)
![Numpy](https://img.shields.io/badge/numpy-%234d77cf?logo=numpy&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-%23424672)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23105278)
![Sklearn](https://img.shields.io/badge/Sklearn-%23ff9c34?logo=scikit-learn&logoColor=white)

https://serverchallenge.ru/

**Тема:** "Анализ контрагентов в разрезе своевременной оплаты."

**Задание:** Построить модель машинного обучения, которая сможет прогнозировать своевременность поступления оплаты от клиента.

**Предоставлены данные:**
- Финансовые показатели за 2016-2020 годы
- Факты под номерами
- Данные по задолженности

**Команда SF76**
 - Колесник Наталья
 - Андрей Фокин

**Описание хода работы:**

  1. Анализ Контрагентов 
     - анализ имеющихся признаков и формирование новых
     - корректировка аномальных значений
     - формирование разных датасетов с признаками и целевыми переменными
     - выгрузка файлов с датасетами и переменными в папку "database"
  2. Борьба с корреляцией признаков 
     - поиск признаков с высокой корреляционной зависимостью для дальнейшего их удаления.
     - определение важности признаков
  3. Отбор признаков для ML
     - отбор признаков с помощью разных методик и сохранение их в файлы (иерархия важности соблюдена)
  4. Обучение
     - прогон на разных моделях ML с разными наборами признаков
     - построение моделей ML под разные критерии
