# QuestMaster — Discord Quest Completer

QuestMaster is a userscript for the Discord desktop application that automatically completes Discord quests — watching videos, playing games, streaming, and achievements — and claims the resulting rewards.

| | |
| --- | --- |
| **Version** | v1.3.0 |
| **Platform** | Discord desktop application only — not compatible with the browser client or mobile |

---
## Preview

<img width="431" height="488" alt="Untitled-1" src="https://github.com/user-attachments/assets/82227d75-cd9a-4f1a-8c26-893b95ba2b15" />

<img width="431" height="488" alt="3" src="https://github.com/user-attachments/assets/ab37d194-8eff-4988-996b-e2cfb611f3d2" />


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

## Links

- Original source: <https://github.com/power0matin/discord-quest-auto-completer>
- Discord server: <https://discord.gg/GBUZU7saue>
