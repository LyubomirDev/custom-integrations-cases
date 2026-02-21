# 📚 Реалізація системи відповідей у Slack

## 🧩 Задача

Необхідно реалізути функціонал для автоматизованої або напівавтоматизованої взаємодії з користувачами у Slack.
## Key Features
- Бот має отримувати інформацію із зовнішніх джерел
- Бот має формувати запити в канали
- Бот має формувати повідомлення в DM
- Бот має відправляти кастомні запити
- Бот має отримувати інформацію з внутрішнього каналу Slack

## 🧠 Мій підхід

- Провів детальний аналіз поставленої задачі
- Визначив ключові запити команди розробки
- Склав схему проєкту в Miro
![Frame 1](https://github.com/user-attachments/assets/021b8fa5-3fbd-40c9-921a-e5bcb9a530ee)
- Створив і налаштував Slack App
  - Додав Scopes
    
    <img width="585" height="757" alt="image" src="https://github.com/user-attachments/assets/99e8fbba-36f9-41a0-b197-a178923d3c23" />
  - Налаштував Івенти бота
    <img width="791" height="404" alt="image" src="https://github.com/user-attachments/assets/c167fe6c-2423-4c0a-be82-0437319a8898" />
  - Провів тестовий запуск публікації таски
    <img width="1515" height="240" alt="image" src="https://github.com/user-attachments/assets/9d0b7528-065c-45e5-924f-a2db8e86c8db" />
    <img width="552" height="420" alt="image" src="https://github.com/user-attachments/assets/14cbca33-a171-401d-98ad-c347df9580f6" />
    <img width="1377" height="366" alt="image" src="https://github.com/user-attachments/assets/b1c7f1c3-ef29-47d4-a074-db70329544d9" />
   - Провів тестовий запуск реакцій
     <img width="1523" height="413" alt="image" src="https://github.com/user-attachments/assets/dbd94bae-f5ae-44c6-a73b-804d211d4768" />
     <img width="555" height="536" alt="image" src="https://github.com/user-attachments/assets/cb1b8b9e-2a00-4993-9cac-5fcf41e3180d" />

- Реалізував повноцінний n8n проєкт, котрий оптимізує роботу команди
  <img width="1188" height="528" alt="image" src="https://github.com/user-attachments/assets/5ee6fa95-925f-468c-a0d6-f5ba175f1d9c" />


## 🛠️ Інструменти

- Slack API
- Slack App
- Slack Workflow
- `n8n` — оплатформа для автоматизації
- `JavaScript` — перевірка запитів і побудова кастомної логіки, обробка токенів
- `Base64`, `timestamp`, робота з cookie/session storage, загальне розуміння інформації що передається

## ✅ Результат

- Отримано повний доступ до необхідних даних у рамках існуючого користувацького доступу
- Побудована інтеграція дозволила автоматично обробляти інформацію

------------------------------------------------------------------------------------------------------------------------------------------

> ⚠️ Проєкт є оглядовою версією, створеною задля демонстрації професійних навичок інтегратора 
