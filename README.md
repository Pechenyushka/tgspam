# tgspam

Spammer Telegram Bot Builder

Запуск и настройка (termux):

pkg update && pkg upgrade

pkg install coreutils
(пишем на всякий случай)

apt install git

apt install python3

git clone https://github.com/Pechenyushka/tgspam/

cd tgspam

pip3 install colorama

pip3 telebot

python3 builder.py

1. Создаем нового бота в @BotFather, копируем токен.

2. Вставляем токен в терминал.

3. Придумываем и пишем команду, которая будет активировать спам в боте.

4. Далее запускаем создавшийся файл tgspam.py:

python3 tgspam.py

5. Вводим количество пар сообщений, который отправит бот после его активации.

6. Вводим сообщение, которым будет спамить бот.

7. Переходим в телеграм, добавляем бота в чат, в который нужно спамить.

8. Пишем /КомандаКоторуюВыПисалиВбилдере

9. Для отключения бота пишем в терминал ctrl+z (или ctrl+c)

P.s Если в терминал пишется сообщение ERROR, значит телеграм частично блокирует спам запросы.

Автор скрипта (tg: @PechenyushkaUWU)
© 2023 All right reserved / Все права защищены
