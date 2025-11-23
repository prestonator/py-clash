# py-clash-bot

**py-clash-bot** is an open-source automation tool that allows you to automate your Clash Royale gameplay on Windows using an emulated Android phone. The bot uses advanced image recognition, mouse control, and Android emulation to perform a comprehensive range of tasks automatically, letting you focus on strategy while it handles the daily grind.

_Join our [Discord server](https://discord.gg/nqKRkyq2UU) for support, updates, and community discussions!_

## ✨ Features

### 🎮 **Battle Automation**

- **Trophy Road 1v1 Battles** - Automatically fight in trophy road ladder matches
- **Path of Legends 1v1 Battles** - Battle in the competitive Path of Legends mode
- **2v2 Battles** - Team up with clan members for 2v2 matches
- **Random Decks** - Randomize your deck selection before each battle
- **Smart Battle Management** - Skip fights when chests are full, disable win/loss tracking

### 🎁 **Rewards & Collection**

- **Card Mastery Rewards** - Collect mastery rewards earned from battles
- **Card Upgrades** - Upgrade your current deck after each battle

### ⚙️ **Advanced Settings**

- **Emulator Support** - Works with BlueStacks 5
- **Render Mode Selection** - Choose between OpenGL, DirectX, and Vulkan rendering
- **Real-time Statistics** - Track wins, losses, chests opened, and more
- **Performance Monitoring** - Monitor bot runtime, failures, and account switches

## 🚀 Setup Instructions

### BlueStacks 5 Emulator

1. **Download BlueStacks 5** - Get it from the official site: https://www.bluestacks.com (ensure BlueStacks 5, not X/10)
2. **Install BlueStacks 5** - Run the BlueStacks 5 installer
3. **Download py-clash-bot** - Get the latest release from [https://github.com/pyclashbot/py-clash-bot/releases](https://github.com/pyclashbot/py-clash-bot/releases)
4. **Install py-clash-bot** - Run the installer
5. **Create the instance** - Start the bot, choose `Emulator Type: BlueStacks 5`, select a render mode (OpenGL/DirectX/Vulkan) under BlueStacks Settings and then click "Start" to let it automatically create the "pyclashbot-96" Bluestacks 5 emulator Instance. Alternativly open the BlueStacks Multi-Instance Manager and create a fresh Pie 64-bit instance and retry it will automatically rename/configure it as "pyclashbot-96"
6. **Install Clash Royale** - Install Clash Royale manually on the "pyclashbot-96" emulator via Google Play Store
7. **Complete setup** - Open Clash Royale manually, complete the tutorial, and optionally sign in to your account
8. **Close BlueStacks 5** - Fully close the BlueStacks 5 emulator
9. **Start automation** - Start the bot, choose `Emulator Type: BlueStacks 5`, select a render mode (OpenGL/DirectX/Vulkan) under BlueStacks Settings, then click "Start"

### Important Notes

- **Language Setting** - Ensure Clash Royale is set to English for optimal bot performance
- **Tutorial Completion** - The tutorial must be completed manually before starting the bot
- **Account Setup** - Sign in with SuperCell ID or create a new account as needed

## 🔧 Emulator Debugging

Having trouble with your emulator? This section provides troubleshooting tips.

### BlueStacks 5 Emulator Debugging

- Use BlueStacks 5 only (BlueStacks 10/X are not supported)
- Ensure install path exists: `C:\Program Files\BlueStacks_nxt`
- If startup fails, create a clean "Pie 64-bit (Android 9)" instance in Multi-Instance Manager (no Google account yet), then click Retry in the bot so it can auto-configure
- Switch render mode in the bot (OpenGL/DirectX/Vulkan) if you see black screens or poor performance, then start again
- Fully close BlueStacks if it becomes unresponsive; the bot will relaunch it

## 🎯 Demo

<img src="https://github.com/pyclashbot/py-clash-bot/blob/master/assets/demo-game.gif?raw=true" width="50%" alt="Game Demo"/><img src="https://github.com/pyclashbot/py-clash-bot/blob/master/assets/demo-gui.gif?raw=true" width="50%" alt="GUI Demo"/>

_Left: Bot automation in action | Right: User interface and controls_

## 🤝 Contributing

We welcome contributions from the community! Whether you have ideas for new features, bug reports, or want to help with development, there are many ways to get involved:

- **Report Issues** - Open an issue on [GitHub Issues](https://github.com/pyclashbot/py-clash-bot/issues)
- **Feature Requests** - Suggest new automation features or improvements
- **Code Contributions** - Check out our [Contributing Guide](CONTRIBUTING.md)
- **Community Support** - Help other users on our [Discord server](https://discord.gg/nqKRkyq2UU)

## ⚠️ Disclaimer

This tool is designed for educational and automation purposes. Please ensure you comply with Clash Royale's Terms of Service and use responsibly. The developers are not responsible for any consequences resulting from the use of this software.

---

**Made with ❤️ by the py-clash-bot community**

_Automate your Clash Royale experience and focus on what matters most - strategy and fun!_
