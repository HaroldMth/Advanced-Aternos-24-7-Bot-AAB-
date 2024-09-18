Minecraft Bot for Aternos Server(ATRB)
This repository contains a Node.js Minecraft bot designed to connect to an Aternos Minecraft server, automatically respawn on death, and handle periodic disconnections and reconnections. The bot is built using the mineflayer library and includes scheduling functionality to manage disconnections and reconnections effectively.

Features
Dynamic Username: The bot connects with a randomly generated username every time it starts.
Automatic Respawn: The bot automatically respawns if it dies in the game.
Scheduled Reconnection: The bot reconnects with a new username every 10 minutes.
Nightly Disconnection: The bot disconnects for 25 seconds during specified night hours to simulate periodic downtime.
