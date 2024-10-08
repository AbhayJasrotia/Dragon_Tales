# Dragon Repeller - RPG Game

## 🏆 About the Project

**Dragon Repeller** is an interactive RPG game where players embark on a quest to defeat the mighty dragon. Set in a fictional world, you can explore different locations, fight monsters, and collect weapons. As you gain experience, collect gold, and upgrade your gear, you get closer to facing the ultimate challenge—the Dragon!

The game is available as a desktop application (Windows `.exe`) and can be built for mobile (Android APK) using Cordova.

## 🎮 Features

- **Multiple Locations**: Explore different places such as the Town Square, Store, Cave, and more.
- **Interactive Combat**: Fight against monsters like Slimes, Fanged Beasts, and the mighty Dragon.
- **Inventory & Upgrades**: Collect weapons like daggers, hammers, and swords. Upgrade your inventory to defeat stronger enemies.
- **Gold & XP**: Earn gold by defeating monsters and purchase items to improve your health and equipment.
- **Replayable**: Lose or win? Restart and play again to explore all possible outcomes!

## 🖥️ Screenshots

### 1. **Landing Page**
![Landing Page](https://github.com/user-attachments/assets/496bb8b9-cb1c-48aa-92fe-8e08ae8adb35)

### 2. **Store**
![Store](https://github.com/user-attachments/assets/618992d8-4223-4d0d-a43a-0976865d996d)

### 3. **Cave**
![Cave](https://github.com/user-attachments/assets/c0503698-6203-441e-9317-02d85f652e02)

### 4. **Dragon Fight**
![Dragon Fight](https://github.com/user-attachments/assets/ed352174-f646-4e4d-96a0-7ead075ee960)

## 💻 Installation

### Desktop (Windows)

You can download and play the game on your Windows PC by clicking the button below:

[![Download Dragon Repeller](https://img.shields.io/badge/Download-Dragon_Repeller-blue.svg?style=for-the-badge&logo=windows)](https://github.com/AbhayJasrotia/Dragon_Tales/releases/download/Install/RPGGame.exe)

## 📄 How to Play

1. **Start the Game**: You'll begin at the Town Square. Use the buttons to navigate through the game.
2. **Visit Locations**: 
   - **Store**: Buy weapons and health.
   - **Cave**: Fight monsters and gather rewards.
   - **Fight the Dragon**: Once you're ready, challenge the dragon to win the game!
3. **Upgrade Weapons**: Collect gold to purchase more powerful weapons in the Store.
4. **Defeat Monsters**: Each location presents different monsters. Use your skills to defeat them and collect XP.

## 🔧 Development & Build Instructions

### Prerequisites
- Node.js
- Cordova CLI
- Java JDK (for Android build)
- Android SDK (for Android build)

### Build the Game

1. Clone the repository:
    ```bash
    git clone https://github.com/AbhayJasrotia/Dragon_Tales
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. To run the game locally:
    ```bash
    cordova run browser
    ```

4. To build for Android:
    ```bash
    cordova build android --release
    ```

5. For Windows executable:
    - Follow the instructions for **Electron** setup as outlined in the project’s `dist/README.md`.

## 🤝 Contributing

We welcome contributions! If you have suggestions or would like to report bugs, please feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create a new branch for your feature (`git checkout -b feature/feature-name`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/feature-name`)
5. Open a Pull Request

## 🛠️ Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript**
- **Electron** (for desktop app)
- **Cordova** (for mobile APK)
- **Node.js**

## 📂 Folder Structure

```bash
|-- myGameApp
    |-- platforms/     # Cordova platforms for Android and others
    |-- www/           # HTML, CSS, JS source files
    |-- dist/          # Electron distribution files (Windows .exe)
    |-- img/           # Image files used in the game
    |-- package.json   # Project configuration and dependencies
    |-- README.md      # Project documentation
    |-- config.xml     # Cordova configuration file
```

## 📢 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Thanks for playing **Dragon Repeller**! If you enjoyed the game, please give us a ⭐ on [GitHub](https://github.com/AbhayJasrotia/Dragon_Tales).
