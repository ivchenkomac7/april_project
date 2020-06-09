#STACK:
1) Telebot
2) Flask (flask restfull)
3) MongoDB
4) VPS - virtual private server, Google Cloud
5) Webhook
6) Marshmallow

#Functionality
1) Бот
1.1. Предоставлять пользователю список доступных категорий (с подкатегорями);
1.2. Предоставлять пользователю список доступных продуктов, определенной категории
1.3. Просмотр информации о продукте (изображение, описание, цена, скидка)
1.4. Корзина
1.5. Оформление заказов
1.6. Просмотр содержимого корзины
1.7. Просмотр продуктов со скидкой
2) REST API
2.1. Просмотр заказов
2.2. CRUD

#Implementation
1) Категории
2) Продукты
3) Корзины
4) Пользователи бота
5) Тексты
6) Заказы
7) Админы

#Практика №1
1) Реализовать колекцию текстов (choices внутри колекцию)
2) Реализовать бот, который будет на старте
2.1. Приветствовать юзера
2.2. Отправлять список шаблонных кнопок
(Товары со скидкой, категории, моя корзина)
2.3. Описать хэндлер к кнопке "категории" (InlineKeyboardMarkup)
