# 🎮 Wolfenstein: Enemy Territory - Windows Configs

ET configs repository

## ⚙️ Installation & Setup

To use these configs, you need to place them in your game's **`etmain`** folder.

### 1. Locate your `etmain` folder

The location depends on which version of the game you are running:

* **ET: Legacy:** `%USERPROFILE%\Documents\ETLegacy\etmain\`

### 2. Add the Files

1. Download `plissje.cfg` from this repository and move it into the `etmain` folder located above.
2. **The Bootloader:** Since the game automatically looks for a file named `autoexec.cfg` on startup, you need to make sure one exists to "call" your custom file.

If you don't have an `autoexec.cfg`, create a new text file, rename it to `autoexec.cfg`, and add this single line:

```bash
exec plissje.cfg

```

## 🔄 Switching Between Configs

If you have multiple configuration files (e.g., `practice.cfg`, `match.cfg`) in the same folder, you can swap them while playing by opening the console (**~** or **`** key) and typing:

* **To load plissje:** `/exec plissje`
* **To load others:** `/exec [filename]`

*See you on the field!*

---

**Would you like me to add a specific section for common Windows "Gotchas," like fixing the "Read-Only" file attribute or screen scaling issues?**
