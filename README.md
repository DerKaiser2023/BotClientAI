# BotClient AI for Minecraft 1.7.10

## Overview
This project is an autonomous AI bot for Minecraft 1.7.10, utilizing **MCProtocolLib** to interact with the game as a real player. The AI makes dynamic decisions based on its environment, allowing it to explore, fight, gather resources, trade with NPCs, and establish independent societies.

## Features
- **Fully Autonomous AI**: The bot decides its actions based on prioritized needs.
- **Multiple Bot Instances**: Supports multiple AI bots in a single session, with even distribution among factions.
- **Dynamic Behavior**:
  - **Exploring**: Roams the world looking for interesting locations.
  - **Combat**: Engages enemies when necessary.
  - **Resource Gathering**: Mines, farms, and collects materials.
  - **Trading**: Interacts with NPCs and vending systems.
  - **Infrastructure Building**: Constructs bases and settlements for long-term survival.
  - **Technological Advancement**: Determines when to progress into HBM mechanics, including nuclear power and weaponry.
  - **Faction Formation**: Ensures AI balance to establish separate societies.

## Requirements
- **Minecraft Server 1.7.10** (Vanilla or Modded, But it can support LAN play)
- **Java 8 or higher**
- **MCProtocolLib**
- **Tyrants and Plebieans REVIVED** install it at *insert modpack url here*
- **If you run Minecraft on a lower-end computer, a scaled-down version with support for the mods in BotClientAI is in the works**

## Installation
1. **Clone the repository:**
    ```sh
    git clone https://github.com//DerKaiser2023/MCBotClientAI.git
    cd BotClientAI
    ```
2. **Set up dependencies:**
   - Download **MCProtocolLib** and add it to the project.
   - Ensure your Minecraft server or LAN world is running.
3. **Compile and Run:**
   ```sh
   javac BotClient.java
   java BotClient
   ```

## Configuration
- Modify `numBots` in `BotClient.java` to adjust the number of AI players.
- Customize AI behavior by modifying:
  - `explore()`
  - `fightEnemies()`
  - `gatherResources()`
  - `tradeWithNPCs()`
  - `buildInfrastructure()`
  - `advanceToHBM()`

## Future Enhancements
- Pathfinding for smarter exploration.
- Machine learning for adaptive decision-making.
- Faction diplomacy and alliances.
- Automated asteroid mining operations.

## Contributing
Feel free to fork the repository, submit pull requests, or suggest improvements!

## License
MIT License
