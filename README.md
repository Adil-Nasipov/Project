Realme — QA Portfolio by Nasipov Adil
📌 О проекте
Этот репозиторий содержит мои практические работы по тестированию:
SQL — запросы и анализ данных в DBeaver;
API Testing (Postman) — тестирование REST API;
UI Automation (Selenium) — автоматизация тестов входа в систему EKDP.
Все работы выполнены в рамках обучения и практики QA Engineer.

Структура проекта
Realme/
│
├── SQL/
│   ├── QA-70 Nasipov Adil SQL 1.docx
│   ├── README.md
│
├── API_Postman/
│   ├── Rest api Postman.docx
│   ├── README.md
│
├── Selenium/
│   ├── Selenium Auto test.docx
│   ├── README.md
│
└── README.md

SQL — Работа с базами данных
Инструменты: DBeaver, SQLite
Основные задания:
Использование операторов LIKE, BETWEEN, IN
Агрегации: SUM, MIN, MAX, COUNT
Объединения таблиц (JOIN)



REST API Testing — Postman
Инструменты: Postman, Swagger, JSON
Проекты:
EKDP API — импорт данных, проверка претензий и долговых уведомлений
Swagger Petstore — CRUD-тестирование модулей Pet, Store, User
Проверялось:
Структура JSON
Статус-коды (200, 400, 404, 500)
Обработка ошибок
Корректность запросов и ответо
Коллекции Postman:
EKDP API Collection
Swagger Petstore Collection
Добавление, удаление, выборка данных


Selenium Auto Test
Инструменты: Selenium WebDriver, Python / Java
Сценарий:
Открытие браузера
Переход на страницу входа в систему EKDP
Ввод логина и пароля
Проверка успешного входа по наличию элемента на главной странице
Результат:
Тест добавлен в фреймворк, запускается автоматически после обновлений кода.
📎 Видео-демо и автотест


Автор
Nasipov Adil
QA Engineer | API & UI Testing | SQL | Selenium | Postman
📍 Казахстан   









🧩 Realme — QA Portfolio by Nasipov Adil

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

🔗 REST API Testing — Postman
Инструменты: Postman, Swagger, JSON
Проекты:

EKDP API — импорт данных, проверка претензий и долговых уведомлений.

Swagger Petstore — CRUD-тестирование модулей Pet, Store, User.

Проверялось:

Структура JSON

Статус-коды (200, 400, 404, 500)

Обработка ошибок

Корректность запросов и ответов

Файл: Rest api Postman.docx

🤖 Selenium Auto Test
Инструменты: Selenium WebDriver, Python / Java
Сценарий:

Открытие браузера

Переход на страницу входа в систему EKDP

Ввод логина и пароля

Проверка успешного входа по наличию элемента на главной странице

Результат:
Тест добавлен в тестовый фреймворк и запускается автоматически для проверки стабильности авторизации после изменений в коде.

Файл: Selenium Auto test.docx

👨‍💻 Автор
Nasipov Adil
QA Engineer | API & UI Testing | SQL | Selenium | Postman
📍 Казахстан, Уральск
📧 nasipov.adil@example.com
