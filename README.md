# WOTW-NX

**Unofficial Nintendo Switch homebrew port of Tom and Jerry: War of the Whiskers (Original Xbox, 2003)**, featuring **four-player local multiplayer** and customizable controller layouts.

I originally started this project because I wanted to enjoy Tom and Jerry: War of the Whiskers on my Nintendo Switch, both solo and with friends.

After extensive development, testing, and optimization, the game now runs smoothly and is fully playable in tested game modes!

## 🎮 Features

- Original Xbox gameplay on Nintendo Switch, with custom Switch-style button prompts.
- Local multiplayer for up to four players.
- Switch-style and PlayStation-style controller layouts.
- Original game audio, music, characters, and arenas.
- Support for saving and loading game progress.
- Optimized performance for Nintendo Switch.

## 🚀 Performance Improvements (v0.80.0)

This update introduces major improvements compared to earlier builds:

- **ARM64 JIT Optimization:** Improved Xbox x86-to-ARM64 code translation for faster game execution.
- **Graphics Optimization:** Reduced rendering overhead through improved draw-call batching and graphics processing.
- **Geometry Optimization:** Reduced unnecessary mesh processing and improved character rendering efficiency.
- **Faster Calculations:** Optimized floating-point operations to improve CPU performance.
- **Improved Compatibility:** Better audio handling, game stability, and overall compatibility.
- **Reduced Slowdowns:** Significantly smoother gameplay, including demanding four-player matches on Ice and Desert arenas.

The game now delivers a smooth and enjoyable experience, including four-player local multiplayer.

## 📥 Installation

**You must provide your own compatible original Xbox game files. Game assets are not included.**

### Option 1: Windows Installer (Recommended)

1. Download `Setup-WOTW.exe` from the latest release.
2. Run the installer and follow the instructions to prepare your game files.
3. Copy the prepared game folder to your Nintendo Switch microSD card.
4. Launch the game through the Homebrew Menu.

### Option 2: Manual Installation

1. Download your preferred package:
   - `WOTW-NX-v0.80.0-Switch-controls.zip`
   - `WOTW-NX-v0.80.0-PlayStation-layout.zip`
2. Extract the ZIP and follow the included installation instructions.
3. Add your compatible original Xbox game files.
4. Launch the game through the Homebrew Menu.

## 🛠️ Development Status

**Current Version: v0.80.0**

WOTW-NX has progressed from an experimental prototype to a smooth, playable release.

The latest version has passed 47 regression test suites and 524,288 input-state validation checks, alongside successful gameplay testing.

The source code is available for anyone interested in studying, modifying, or improving the project. Future updates may include additional improvements or fixes.

## ❤️ Credits

This project uses [shihabal3amri's Tom and Jerry: War of the Whiskers PC port](https://github.com/shihabal3amri/tom-jerry-war-of-the-whiskers-pc/releases) as the foundation for the Nintendo Switch version.

Full credit for the original PC port goes to its author and contributors.

Special thanks to the homebrew community and everyone who contributed to the tools and resources that made this project possible.

**Disclaimer:** This is an unofficial fan-made project and is not affiliated with the original game's developers or publishers. Players must provide their own legally obtained game files.

---

**Enjoy Tom and Jerry: War of the Whiskers on Nintendo Switch!**
