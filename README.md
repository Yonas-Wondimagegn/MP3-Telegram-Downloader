# Telegram Audio Downloader Bot

This is a Telegram bot that downloads audio from YouTube and SoundCloud links and sends them to users in MP3 format. 

## Features

- **Download audio from YouTube and SoundCloud**: Send a link and get the audio file in MP3 format.
- **Automatic cleanup**: Deletes all `.mp3` files in the download folder every 5 minutes.
- **Manual cleanup**: Deletes all `.mp3` files in the download folder by using only /deletemp3 command on the bot.

## Commands

- `/start` - Start the bot and get a welcome message.
- `/download <link>` - Download audio from a provided YouTube or SoundCloud link.
- `/help` - Show help message with usage instructions.
- `/dev` - Contact the developer.
- `/deletemp3 <password>` - Clear all `.mp3` files in the download folder (requires password).

## Prerequisites

- Python 3.7 or later
- `python-telegram-bot` library
- `yt-dlp` library

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/telegram-audio-downloader-bot.git
   cd telegram-audio-downloader-bot


**2. Install dependencies:**

pip install -r requirements.txt

**3. Set up the environment variables:**

Copy .env.example to .env and fill in your Telegram bot token and password.
But you can simply add in the main.py


**4. Run the bot:**

python main.py


**Contributing**

Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.


