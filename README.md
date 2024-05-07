# Force Subscribe Bot for Telegram

This is a Telegram bot script designed to enforce subscription to a specific channel before allowing users to participate in a group chat. The bot sends a welcome message to new users who have already subscribed to the required channel, and restricts the messaging capabilities of those who haven't subscribed until they do so.

## Features

- Sends a welcome message to new users who have already subscribed to the specified channel.
- Restricts messaging capabilities of users who haven't subscribed until they join the channel.
- Provides an "Unmute Me" button for restricted users to easily join the channel and get unmuted.

## Requirements

- Python 3.x
- `telebot` library
- `emoji` library
- `decouple` library

## Installation

1. Clone or download the repository.

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up your bot token and other configurations in a `.env` file:
   ```
   BOT_TOKEN=your_telegram_bot_token
   CHANNEL=your_channel_username
   WELCOME_MSG=your_welcome_message
   WELCOME_NOT_JOINED=your_welcome_message_for_users_not_joined
   ```

4. Run the script:
   ```
   python bot.py
   ```

## Configuration

- `BOT_TOKEN`: Your Telegram Bot API token.
- `CHANNEL`: The username of the channel users must subscribe to.
- `WELCOME_MSG`: The welcome message to be sent to users who have subscribed to the channel.
- `WELCOME_NOT_JOINED`: The message to be sent to users who have not subscribed to the channel, along with the restriction.

## Usage

Once the bot is running and added to your Telegram group, it will automatically send welcome messages to new users who have subscribed to the specified channel. For users who haven't subscribed, it will restrict their messaging capabilities and provide an "Unmute Me" button to join the channel and get unmuted.

## Contributors

- [Force-Subscribe-Bot-for-Telegram)(https://github.com/Mustkeem324/Force-Subscribe-Bot-for-Telegram)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
