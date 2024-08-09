# Тестове завдання на позицію Full-stack розробника

## Стек технологій:
1. JavaScript/TypeScript, Node.js
2. React.js
3. PostgresQL, MongoDB

## Опис завдання:
Розробіть просту систему управління проєктами (CRM) для публічних проєктів GitHub.

### Основні функціональні вимоги:
- Система повинна підтримувати реєстрацію та авторизацію користувачів.
- Користувачі повинні мати можливість реєструватися за допомогою електронної пошти та паролю.
- Після входу в систему користувач переходить до списку проєктів, який відображає наступні дані:
  - Власник проєкту
  - Назва проєкту
  - URL проєкту
  - Кількість зірок (stars)
  - Кількість відгалужень (forks)
  - Кількість відкритих питань (issues)
  - Дата створення у форматі UTC Unix timestamp
  - Кнопки: оновити та видалити

### Додаткові функціональні вимоги:
- Для додавання нового репозиторію GitHub користувач повинен вказати лише шлях до репозиторію, наприклад: `facebook/react`.
- Після додавання система у фоновому режимі повинна запитати дані з GitHub API та зберегти всі необхідні поля в базу даних.

### Інші вимоги:
- Ви можете використовувати будь-які бібліотеки UI для React.js.
- Дизайн (UI/UX) не має значення.
- Система має швидко підніматись, радимо використати Docker та Docker Compose.

### Додаткові рекомендації:
- Зверніть увагу на структуру проєкту, вона має бути чистою і зрозумілою.
- Код повинен бути добре документований та відповідати загальноприйнятим стандартам.
- Використовуйте Git для контролю версій та надайте посилання на репозиторій із завданням.

## Критерії оцінки:
- Коректність роботи системи відповідно до вимог.
- Якість та зрозумілість коду.


Бажаємо успіху!
