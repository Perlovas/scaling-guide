Руководство по использованию

## Описание
Этот телеграм-бот предоставляет набор функций для выполнения расчетов в области экономики. В настоящем README рассматриваются основные функции и их использование.

## Установка

1. Склонируйте репозиторий:
git clone https://github.com/your_username/your_economics_bot.git


2. Установите зависимости:

pip install -r requirements.txt


3. Создайте файл `config.py` и добавьте следующие переменные:

# config.py
TOKEN = 'YOUR_TELEGRAM_BOT_TOKEN'


## Использование

1. Запустите бота:

python main.py

2. Откройте Telegram и найдите бота по имени пользователя.

3. Нажмите /start, чтобы начать взаимодействие.

## Функции

### 1. Построение общей КПВ

- Нажмите "Построение общей КПВ" в меню.
- Введите максимальные объемы производства товаров для каждого производителя.
- Получите график общей кривой предложения.

### 2. Нахождение точки рыночного равновесия

- Нажмите "Нахождение точки рыночного равновесия" в меню.
- Введите соответствующие параметры спроса и предложения.
- Получите точку рыночного равновесия.

### 3. Расчет объема дефицита/излишка

- Нажмите "Расчет объема дефицита/излишка" в меню.
- Введите коэффициенты функций спроса и предложения.
- Получите объем дефицита/излишка при заданном уровне цены.

### 4. Расчет прибыли фирмы

- Нажмите "Расчет прибыли фирмы" в меню.
- Введите данные о производстве и издержках.
- Получите расчет прибыли фирмы.

## Дополнительная информация

Дополнительные функции и изменения могут быть добавлены в будущем. Следите за обновлениями репозитория.
```

