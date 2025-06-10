# Discord Bot

This project is a simple Discord bot built using TypeScript and the discord.js library. It serves as a foundation for creating more complex bots with various commands and functionalities.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Commands](#commands)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/discord-bot.git
   ```

2. Navigate to the project directory:
   ```
   cd discord-bot
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Create a `.env` file in the root directory and add your Discord bot token:
   ```
   DISCORD_TOKEN=your_token_here
   ```

## Usage

To start the bot, run the following command:
```
npm start
```

Make sure to replace `your_token_here` with your actual Discord bot token.

## Commands

The bot currently supports a basic command structure. You can add more commands by extending the `CommandHandler` class in `src/commands/index.ts`.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.