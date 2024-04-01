# Golang Telegram Bot Project

This repository is dedicated to a Telegram bot developed in the Go programming language, utilizing powerful libraries and API interactions to create a responsive and functional bot. This project is ideal for beginners looking to gain fundamental programming skills in Go and experience working with external APIs.

## Overview

The purpose of this project is to develop a Telegram bot capable of processing and responding to user messages. By completing this project, developers will gain hands-on experience with Go, understand how to work with the Telegram Bot API, and learn how to design and implement bot functionality to interact with users.

## Features

- **Language**: Golang
- **Frameworks/Libraries**: `github.com/spf13/cobra` and `gopkg.in/telebot.v3`
- **Functionality**:
  - Message handler functions that reply to user messages in Telegram.
  - Integration of message handler functions into `telebot.Bot` methods.
  - Processing messages based on their type and content.

## Getting Started

### Prerequisites

- Golang installed on your system.
- Basic understanding of Git and GitHub.
- A Telegram account to create and manage your bot.

### Setup

1. **Environment Setup**: If you're using Codespaces, it comes pre-configured with the necessary settings. Otherwise, ensure Golang is correctly installed and set up on your system.

2. **Project Initialization**:
   - Create a new project on GitHub and clone it to your local machine.
   - Navigate to your project directory.

3. **Dependencies**:
   - Add `github.com/spf13/cobra` to your project by importing it in your Go files.
   - Install `gopkg.in/telebot.v3` by running `go get gopkg.in/telebot.v3`.

4. **Telegram Bot Creation**:
   - Use BotFather in Telegram to create a new bot and obtain a bot token.
   - Save the bot token in an environment variable `TELE_TOKEN`.

5. **Development**:
   - Import the necessary libraries in your Go files.
   - Create a `telebot.Bot` object with the bot token.
   - Implement message handler functions and attach them to the bot.
   - Compile and run your bot to test its functionality.

### Running Your Bot

1. Compile your bot using `go build -ldflags "-X="github.com/illia-ilin/kbot/cmd.appVersion=v1.0.2`.
2. Run the compiled executable.
3. Interact with your bot in Telegram to test its responses.

## Example Usage

After setting up your bot and running it, you can interact with it on Telegram. Here's a simple command you can start with:

```
\start hello
```

Your bot should respond with a greeting message or a similar response based on your implementation.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or create issues for bugs and feature requests.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgments

- This project was inspired by the desire to learn Golang and explore the capabilities of the Telegram Bot API.
- Thanks to the developers of `cobra` and `telebot.v3` for their excellent libraries that make bot development more accessible.

