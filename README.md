<h2>Telegram Bot That Generates Bank Card Numbers</h2>

Project Status:
🟢 Maintained (Active)

Goals and Objectives

Help QA engineers quickly obtain bank card numbers for testing in a test environment.

The bot generates test bank card numbers:

Card numbers pass Luhn algorithm validation

Supported card types: Visa, Maestro, Mastercard, JCB

🖼 Screenshots

Start menu:

![image](https://raw.githubusercontent.com/German-D/tg_credit_cards/main/static/bot_menu.png)

after choosing Visa:

![image](https://raw.githubusercontent.com/German-D/tg_credit_cards/main/static/visa_card.png)


💻 Technologies

Python

telebot library

faker library

⏬ Local Installation

Download the project
   
2.Create bot [@BotFather](https://t.me/BotFather) and insert your bot token into the project


3. Create a virtual environment inside the project folder.
Below are commands for macOS (Windows instructions are available here). [есть вот тут](https://realpython.com/python-virtual-environments-a-primer/#create-it))

``` markdown
python3 -m venv venv
```

``` markdown
source venv/bin/activate
```
4.install library 

``` markdown
python3 -m pip install pyTelegramBotAPI
```

``` markdown
python3 -m pip install faker
```

5. start
``` markdown
python3 card_bot.py
```

## Author

Anastasiia Polikarpova
