A store with the functionality of multi-cities, multi-merchants. Бот - магазин в Телеграм с гибким каталогом, спраочник городов и управление продажами и продавцами.

<img src="tggoodsinbot.gif" width="100"/>


##Модули
- управление локацией пользователя, хранение города пользователя
- управление языками интерфейса(Русский, Английский)
- управление товарами и категориями товаров
- управление магазинами
- управление местами отдыха, артистами, событиями
- управление кружками, местами обучения
- управление частными объявлениями
- управление балансами пользователей
- управление заказами и доставкой товаров
- управление рассылками сообщений, постов

##Подсистема рассылок и публикаций постов, новостей и анонсов позиций
- создание постов, новостей и анонсов
- создание списков каналов для публикации и групп для рассылки
- рассылка по расписанию

##Интеграция с МойСклад
- получение товаров по складам
- получение остатков по складам
- получение цен
- создание заказа покупателя

##Функции для пользователя
- каталог двух уровней, категория - товар
- корзина
- поддержка (контакты) - ссылка в диалог с администратором
- FAQ - сообщение для пользователей с HTML разметкой
- подробная Статистика бота: кол-во пополнений, покупок, пользователей, позиций, категорий, чистой прибыли
- определение местонахождения пользователя
- пополнение счет в рублях через ЮМани, USDT TRC20, BTC BEP20

##Функции администратора
- режим технических работ
- проверка наличия обнолвения при запуске
- активация/деактивация функций продажи и оплаты
- добавление неограниченного количества глобальных администраторов
- роль администратора магазина, управляющего своими товарами в каталоге
- добавление неограниченного количества администраторов магазинов
- удобная и многофункциональная админ панель
- определение и хранение города нахождения товара
- поиск покупателей и просмотр профилей
- поиск чеков покупок
- рассылка сообщений всем пользователям бота
- изменение и пополнение баланса пользователя
- отчет о продажах продавцов

##Оплата товаров
- используется библиотеки YooMoney, Crypto платежи
- настраивается администратором бота через админку
- проверка работоспособности из админки
- вывод баланса кошелька в любой из валют

##Каталог и товары
- User-friendly каталог
- товары имеют одно изображение
- гибкое управление товарами администраторами
- выгрузка всех товаров

##Защита
- админ-фильтры на все хендлеры, гарантирующие приватность админ функционала
- защита от оплаты в тенге при пополнении баланса
- защита от неправильного HTML синтаксиса
- защита от повторной выдачи баланса
- защита от спама в боте (Middlewares)

##настройки settings.ini
- установить токен Бота, полученный у @BotFather
- установить Telegram ID администратора
- установить в таблице storage_users значение в поле user_role = "Admin"

##Настройка
1. Требуемая версия Python 3.9, рекомендуемая Python 3.10.
2. Скопируйте папку бота. Перейдите в папку бота.
3. Выполните в командной строке "pip install -r requirements.txt".
4. Заполните файл settings.ini.
5. Стартовать бот в командной строке: python3 main.py.
6. Заполнить информационные поля.
7. Наполнить каталог товарами.
8. Привлекать пользователей в каталог.

##Процесс администрирования площадки
- согласование продавцов.
- администрирование каталога.
- администрирование денежных средств.
- поддержка и ведение сделок, разрешение споров.

##Процесс покупки для покупателя
1. Выбор товара.
2. Пополнение счета.
3. Ожидание звонка продавца и уточнение параметров домтааки.
4. Получение товара.
5. Подтверждение получения.
6. Отправка отзыва о покупателей.

##Процесс продажи для продавца
1. Получение сообщения о заказе.
2. Звонок покупателю.
3. Отправка товара покупателю.
4. Получение отзыва о покупателей.

<!-- TODO:
- расчет доставки сборного заказа
- поиск в каталоге -->

Работающий экземпляр уже в 192 городах России: https://t.me/Goodsindemobot
Чтобы торговать своими товарами, отправьте запрос на продавца из бота, нажав "Я продавец" или напишите мне, чтобы развернуть Вам полностью всего бота или его часть(платная опция).
По вопросам пишите пожалуйста в телеграм: @raclear
**Преимущества нашего бота**
Существует множество преимуществ для торговли цифровыми товарами через Интернет, но вот некоторые из наиболее значимых:

1. Возможность покупки и продажи в любое время и в любом месте, где есть доступ к Интернету.
2. Быстрое и удобное совершение покупок онлайн.
3. Большой выбор цифровых товаров высокого качества.
4. Низкие цены за счет отсутствия посредников.
5. Удобная система оплаты и доставки.
6. Продвинутые функции маркетинга и аналитики для эффективного продвижения вашего бизнеса в Интернете.
7. Высокая степень конфиденциальности и защиты персональных данных покупателей.
8. Возможность работы с клиентами 24/7, без необходимости посещения физического магазина.
9. Возможность отслеживания статуса заказа и получения уведомлений об изменениях.
10. Широкая аудитория пользователей, которая может быть настроена на вашу целевую аудиторию.

    
##Telegram Ra
**Telegram Ra функционал**
- добавление аккаунтов Телеграм
- учет исключений и ограничений платформы
- парсинг групп Телеграм
- ведение базы собранных аккаунтов
- инвайт собранной аудитории в целевую группу
- ведение прогресса инвайта собранной аудитории
- плавная безостановочная работа
- управление параметрами привлечения
- интерфейс из терминала, возможность запустить процесс как на ПК, так и на сервере или удаленно

по вопросам пишите в ТГ: @raclear
