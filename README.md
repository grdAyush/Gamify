# Gamify Discord Bot



Gamify is a Discord bot that brings a variety of games to your server, providing entertainment and fun for your community. The bot is built using the discord.js v14 library and heavily relies on the npm package called discord-gamecord. Gamify exclusively utilizes slash commands for an enhanced user experience.

## Features

Gamify offers a wide range of interactive games for Discord users to enjoy. Here are some of the available games:

- **2048**: A popular puzzle game where players slide numbered tiles on a grid to combine them and reach the elusive 2048 tile.
- **8ball**: A classic fortune-telling game where the bot provides a random response to yes or no questions.
- **Connect4**: A strategic board game where two players take turns dropping colored discs into a grid with the goal of connecting four discs in a row.
- **TTT**: A text-based version of Tic Tac Toe, a simple game where two players take turns placing their marks (X or O) on a 3x3 grid to form a line of three.
- **Rps**: A Rock, Paper, Scissors game where players make hand gestures and the bot determines the winner.
- **MatchPairs**: A memory game where players have to find matching pairs of cards within a grid.
- **MineSweeper**: A single-player puzzle game where players strategically uncover tiles on a grid to avoid mines.
- **FastType**: A typing speed challenge where players have to type the displayed words as quickly and accurately as possible.
- **FindEmoji**: A game where players have to guess the name of an emoji based on a provided description.
- **HangMan**: A word-guessing game where players try to uncover a hidden word by suggesting letters within a limited number of attempts.
- **Slot**: A virtual slot machine game where players pull the lever and hope for a winning combination.
- **Snake**: A classic Snake game where players control a snake to eat food and grow longer while avoiding collisions with walls or their own body.
- **Wordle**: A word-guessing game where players have to guess a five-letter word within six attempts based on hints provided.
- **WoodYouRather**: A game where players have to choose between two options and compare their choices with others.

## Usage

To use Gamify in your Discord server, follow these steps:

1. Invite the bot to your server using the following [link](https://discord.com/oauth2/authorize?client_id=YOUR_BOT_CLIENT_ID&permissions=YOUR_PERMISSIONS&scope=bot%20applications.commands) and replacing `YOUR_BOT_CLIENT_ID` with your bot's client ID and `YOUR_PERMISSIONS` with the required bot permissions. Make sure you have the necessary permissions to invite the bot.
2. Once the bot is added to your server, create a channel for the bot to operate in.
3. Use the `/games` command to view the available games and select the game you want to play.
4. Follow the instructions provided by the bot within the game to play and interact.
5. Have fun and enjoy playing games with your friends!

## Requirements

- Node.js version 16 or higher
- discord.js v14
- discord-gamecord npm package

## Installation

To install and run Gamify locally, follow these steps:

1. Clone this repository to your local machine or download the source code.
2. Install the required dependencies by running the following command:

   ```
   npm install
   ```

3. Set up your bot token and any other necessary configuration variables in a `.env` file. Refer to `.env.example` for the required variables.
4. Start the bot by running the following

   ```
   npm run start
   ```
