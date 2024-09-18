# Minecraft Bot for Aternos Server

This repository contains a Node.js bot designed to connect to an Aternos Minecraft server using the `mineflayer` library. The bot automatically handles reconnections, respawns, and periodic downtime.

## Features

- **Dynamic Username:** Connects with a new randomly generated username each time it starts.
- **Automatic Respawn:** Respawns the bot automatically upon death.
- **Periodic Reconnection:** Reconnects with a new username every 10 minutes.
- **Nightly Disconnection:** Disconnects for 25 seconds between 12 AM and 6 AM to simulate downtime.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/minecraft-bot.git
   cd minecraft-bot
Install Dependencies: Make sure you have Node.js installed. Then, run:
bash
Copy code
npm install
Configuration
Update Server Details: Edit bot.js to set your Minecraft server address and port.

Replit Configuration (Optional): If using Replit, ensure your .replit file includes:

ini
Copy code
modules = ["nodejs-20"]
run = "node bot.js"
Usage
Start the bot with:


node bot.js
Contributing
Contributions are welcome! Please submit issues or pull requests to improve the bot.

License
This project is licensed under the MIT License.
