# python_chatgpt_dummy
Just a Pyhton ChatGPT interacted dummy template project

0. Get Telegram API token and ChatGPT API token (too lazy to google it) and create your telegram bot with @BotFather in Telegram. Get bot token. 
Create config.env file in project root with following content:
``` [API_KEYS] ```
``` TELEGRAM_TOKEN=<your_telegram_bot_token> ```
``` CHATGPT_TOKEN=<your_chatgpt_token> ```

1. Initiate venv
``` python -m venv venv ```

2. Start venv
``` python -m venv venv venv\Scripts\activate.bat ``` for Windows
``` source venv/bin/activate ``` for Linux

3. Install requirements
``` pip install -r requirements.txt ```

4. Start application
``` python dummy.py ```
OR using Docker
``` docker build -t python_chatgpt_dummy . ```
``` docker run -d --name python_chatgpt_dummy python_chatgpt_dummy ```

5. Text to your bot in Telegram

6. ...

7. PROFIT!