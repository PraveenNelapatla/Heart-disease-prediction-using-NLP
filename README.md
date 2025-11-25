1) Steps to Run Heart Disease Prediction via Telegram Bot
1. Set Up Telegram Bot
- Go to Telegram and search for BotFather.
- Start a chat and run:
/newbot
- Give your bot a name and username (must end with _bot).
- BotFather will give you a token (something like 123456789:ABC-DEF1234ghIkl-zyx57W2v1u123ew11).
- Copy And Paste that key in the code
  
2) Install Telegram Bot Library
In your Python environment:
pip install python-telegram-bot

 Run the Bot
- Save the script as bot.py.
- Run:
python bot.py
- Now, open Telegram, search for your bot, and start chatting.
- When you send health details, the bot will preprocess and run predictions using your NLP model.
