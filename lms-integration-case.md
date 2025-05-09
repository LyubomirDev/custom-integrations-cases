# 📚 Інтеграція з внутрішньою освітньою платформою (без відкритого API)

## 🧩 Задача

Автоматизація взаємодії з LMS-платформою, яка не надавала публічного API для зовнішніх інтеграцій. Потрібно було отримувати інформацію про задачі, користувачів та об'єкти в системі, а також здійснювати окремі дії (наприклад, створення або оновлення).

## 🧠 Мій підхід

- Провів детальний аналіз мережевої активності вебінтерфейсу використовуючи DevTools
- Визначив ключові запити, які відповідають за авторизацію, перегляд та зміну даних
- Витягнув механізм роботи сесій, включно з кукі, токенами та заголовками
- Емулював запити на локальному пристрої мовою JS з використанням Fetch() і додатковими хедерами
- Реалізував повноцінний флоу через n8n, котрий автоматизує логін, обробку токенів та взаємодію з системою

## 🛠️ Інструменти

- `n8n` — оплатформа для автоматизації
- `DevTools` — аналіз мережевих запитів
- `JavaScript` — перевірка запитів і побудова кастомної логіки, обробка токенів
- `Base64`, `timestamp`, робота з cookie/session storage, загальне розуміння інформації що передається

## ✅ Результат

- Отримано повний доступ до необхідних даних у рамках існуючого користувацького доступу
- Побудована інтеграція дозволила оновлювати сторонні системи без ручного втручання
- Реалізовано повторну авторизацію через збережену кукі-модель

------------------------------------------------------------------------------------------------------------------------------------------

> ⚠️ Назва платформи навмисно не вказується з поваги до внутрішніх правил використання.  
> Кейс демонструє універсальний підхід до роботи з вебінтерфейсами без офіційного API, коли потрібна інтеграція в рамках наявного доступу.
