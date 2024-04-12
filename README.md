# Говорящий бот

Бот, который умеет превращать ваши текстовые сообщения в голосовые


## Инструкции по использованию бота

В pycharm:
- Напишите в терминале pycharm: git clone https://github.com/aleksandrapp/tts_bot.git
- Получите токен в BotFather в telegram, сщздайте файл .env, вставьте токен в этот файл так: BOT_TOKEN=...
- Получите в yandexGPT IAM токен и folder_id, вставьте их в файле .env так: IAM_TOKEN=... и FOLDER_ID=...
- Запустите код

В telegram:
- Найдите бота @textt_speech_bot, запустите его командой /start
- Чтобы бот преобразовал текст в аудио, пишите /tts
