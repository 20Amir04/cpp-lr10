<img width="1920" height="1080" alt="Screenshot (1683)" src="https://github.com/user-attachments/assets/76f72789-cfc2-42e3-89f2-a7d7697649bb" />

У файл app.js було додано реєстрацію сервіс-воркера через navigator.serviceWorker.register('/sw.js'). 
Було досліджено, що navigator — це об’єкт Web API браузера, а navigator.serviceWorker дає змогу працювати із сервіс-воркерами. 
Після реєстрації сервіс-воркера було перевірено роботу застосунку в офлайн-режимі. Також було з’ясовано, що для коректної роботи Service Worker сайт слід відкривати через localhost або HTTPS.
