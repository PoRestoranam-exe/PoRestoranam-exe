# Алексей Николаев

Москва, Россия  
📞 +7 925 991 5583 | ✉️ [Nikolaev704@gmail.com](mailto:Nikolaev704@gmail.com)
---

## Образование
- **НИУ ВШЭ** — Москва, Россия  
  Бакалавр, Факультет Экономических наук, Экономика (2022)

- **НИУ ВШЭ** — Москва, Россия  
  Магистр, Факультет Финансы и Кредит, Корпоративные финансы (2024)

---

## Практический опыт
### Changellenge: выполнение кейсов
1. **Кейс: Анализ волатильных акций для инвестиционной компании**
   - Задачи и подходы: В первом подзапросе (CTE) daily_changes функция lag вычисляет изменение цены закрытия по сравнению с предыдущим днем для каждой акции, во втором подзапросе average_changes рассчитывается среднее ежедневное изменение с помощью avg, сгруппированное по акциям, в третьем подзапросе price_info используются оконные функции max, min, sum, count для определения максимальной/минимальной цены, объема торгов, количества дней, после чего производится фильтрация по требованиям.

2. **Кейс: Прогнозирование отказов от бронирования для оптимизации овербукинга в отелях**
   - Задачи и подходы: данные загружаются из CSV-файла, заполняются пропуски и удаляются дубликаты, признак adr (средняя дневная стоимость номера) нормализуется с помощью MinMaxScaler, преобразуются данные о месяце прибытия в числовой формат и создается полная дата прибытия, после этого удаляются ненужные колонки. Кодируются категориальные признаки hotel и country с помощью LabelEncoder, применяется метод get_dummies для преобразования категориальных признаков в бинарные, данные разделяются на тренировочный и тестовый наборы, используя метод traintestsplit, рассчитывается точность модели на тестовой выборке с использованием метрики accuracy_score и делаются итоговые выводы.

---

## Навыки
- **Технические навыки**:  
  - SQL (PostgreSQL)
  - Python (pandas, numpy, matplotlib)
  - Excel
  - Основы математической статистики
  - Tableau, PowerPoint

- **Языки**:  
  - Английский (B2)

---

## Дополнительные курсы и сертификаты
- **Changellenge** – аналитика данных (2024)


