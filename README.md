# PeakFinance Price Bot Overview

This is a Node.js-based Discord bot built to fetch and display the live price of the PEAK token from external APIs. It posts updates to a specific Discord channel on a regular interval.

## Main Structure

### `index.js`
Main application file that initializes the bot, connects to Discord, loads the environment configuration, and triggers periodic price updates.

### `price-checker.js`
Handles the logic for fetching the token price from an external API and formatting a Discord message embed.

## Configuration

### `config.json`
Contains all secrets, including the client id, guildid and discord bot token.

## Dependencies

From `package.json`:
- `discord.js` – For Discord API interaction.
- `dotenv` – For handling environment variables.
- `node-fetch` – For making API calls to fetch token data.

-----

**Peak Finance** is a protocol designed to maintain the PEAK token to the value of $METIS. This process is known as seigniorage.

This simply monitors the price of the 'Peak' Token and displays it in a discord voice channel.

This bot was built and proudly hosted by Azoria for the Peak Finance Discord group located at https://discord.gg/SZtDmPh4 - Since Shut Down and no longer trading.
