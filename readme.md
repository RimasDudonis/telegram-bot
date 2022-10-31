Бот написан на Python 3.10. Для работы бота необходимо дополнительно установить библиотеки 
«Requests», «pyTelegramBotAPI», «python-telegram-bot-calendar», «python-dotenv», «loguru». 
Бот использует API "rapidapi.com". Для работы с БД используется sqlite3. Бот состоит из следующих файлов:

1. «config.py» – содержит конфигурационные настройки, такие как API key, token для telegram бота и остальные настройки.
2. «data_base.py» - содержит функции для работы с БД.
3. «commands.py», «history.py» - модули отвечают за выполнение основных команд бота 
4. «keyboard.py» - модуль отвечает за создание клавиатуры
5. «main.py» - Основной модуль. Содержит процедуры для анализа ответов пользователя и вывода результатов в чат.
6. «search_dest_id.py», «search_hostels.py», «search_photos.py» - модули для работы c API
7. «user_data.db» - файл базы данных.

Для запуска бота необходим установленный интерпретатор Python версии 3.10, а также 
нужен файл .env куда нужно сохранить ключ RAPIDAPI_KEY и токен от вашего бота. 