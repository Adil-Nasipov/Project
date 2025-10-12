# 🧩 Realme — QA Portfolio by Nasipov Adil

## 📌 О проекте
Этот репозиторий содержит мои практические работы по тестированию:

- **SQL** — запросы и анализ данных в DBeaver;  
- **API Testing (Postman)** — тестирование REST API;  
- **UI Automation (Selenium)** — автоматизация тестов входа в систему EKDP.  

Все работы выполнены в рамках практики QA Engineer.

---

## 📂 Структура проекта
Realme/
│
├── SQL/
│ ├── QA-70 Nasipov Adil SQL 1.docx
│ ├── README.md
│
├── API_Postman/
│ ├── Rest api Postman.docx
│ ├── README.md
│
├── Selenium/
│ ├── Selenium Auto test.docx
│ ├── README.md
│
└── README.md

pgsql
Копировать код

---

## 🧠 SQL — Работа с базами данных
**Инструменты:** DBeaver, SQLite  
**Основные задания:**
- Использование операторов `LIKE`, `BETWEEN`, `IN`  
- Агрегации: `SUM`, `MIN`, `MAX`, `COUNT`  
- Объединения таблиц (`JOIN`)  
- Добавление, удаление, выборка данных  

**Примеры запросов:**

```sql
-- 1. Имена сотрудников, начинающихся на "A"
SELECT * FROM Employee e
WHERE FirstName LIKE 'A%';

-- 2. Общее количество сотрудников
SELECT COUNT(*) AS total_employees FROM Employee;

-- 3. Сотрудники с email, содержащим '.com'
SELECT * FROM Employee WHERE email LIKE '%.com%';
Файл: QA-70 Nasipov Adil SQL 1.docx






Обработка ошибок

Корректность запросов и ответов

Файл: Rest api Postman.docx
