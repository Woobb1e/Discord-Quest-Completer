# QuestMaster — Discord Quest Completer

<div align="center">
   
[![GitHub](https://img.shields.io/badge/GitHub-Woobb1e-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Woobb1e)
[![Discord](https://img.shields.io/badge/Discord-Join%20Server-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/GBUZU7saue)

</div>

---
## Requirements

- Discord desktop application 
- Developer tools enabled (see Installation)

---

## Installation

1. Enable the console in your Discord `settings.json`:
   - Windows: `%appdata%\discord\settings.json` (use the equivalent path for PTB or Canary)
   - Add the following line, save the file, and restart Discord:

     ```json
     "DANGEROUS_ENABLE_DEVTOOLS_ONLY_ENABLE_IF_YOU_KNOW_WHAT_YOURE_DOING": true
     ```

2. Open Discord and press **Ctrl + Shift + I** to open the developer console.
3. In the Console tab, type `allow pasting` and press Enter (required once per session).
4. Paste the full contents of `quest_completer.js` and press Enter.

**Vencord users:** enable Settings → Vencord → Developer Settings, then open the console with **Ctrl + Shift + I**.

---

## Troubleshooting

| Issue | Solution |
| --- | --- |
| Console rejects pasting | Type `allow pasting` in the console first. |
| Game or stream quests remain at 0% | These tasks require the native desktop client to run the activity; video quests are handled automatically. |

---

## Disclaimer

This script automates quest progression, which conflicts with the Discord Terms of Service. It is provided for educational purposes only. Use at your own risk; no liability is accepted for account restrictions or sanctions resulting from its use.

---

## Sources

- [discord-quest-auto-completer](https://github.com/power0matin/discord-quest-auto-completer) by power0matin.

---
