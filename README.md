## Setup
1. ```bash
git clone https://github.com/Krap1v/chatgpt_telegram_bot
  ```

2. Get your [OpenAI API](https://openai.com/api/) key

3. Get your Telegram bot token from [@BotFather](https://t.me/BotFather)

4. Edit `config/config.example.yml` to set your tokens and run 2 commands below (*if you're advanced user, you can also edit* `config/config.example.env`):
    ```bash
    mv config/config.example.yml config/config.yml
    mv config/config.example.env config/config.env
    ```

5. 🔥 And now **run**:
    ```bash
    docker-compose --env-file config/config.env up --build
    ```
