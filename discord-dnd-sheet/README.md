# Character Sheet: a Discord theme

This theme turns Discord into a parchment character sheet and attaches your character to your own account:

- Parchment colours, fantasy fonts, and double-ruled borders on popouts
- Your class, level, HP and AC after your name on your messages
- A gold ring around your avatar
- A full stat block at the top of your profile popout

> **Only you will see this.** Client themes change your own Discord app and nobody else's.
> To show your character to everyone, use the profile text in the last section below.

## Install

You need a client mod that loads themes. **Vencord** and **BetterDiscord** both work.

1. Open `CharacterSheet.theme.css` and edit section 1 to match your character.
2. Get your user ID: **Settings → Advanced → Developer Mode** on, then right-click your name → **Copy User ID**.
3. Find-and-replace every `YOUR_USER_ID` in the file with that number.
4. Load the theme:
   - **Vencord:** Settings → Vencord → Themes → Open Themes Folder, drop the file in, and enable it. You can also paste the file into QuickCSS.
   - **BetterDiscord:** Settings → Themes → Open Themes Folder, drop the file in, and toggle it on.

Note: client mods are against Discord's Terms of Service. Themes like this one are low risk, since they only change how things look, but you use them at your own risk.

## If something stops working

Discord renames its internal CSS classes now and then. The colours and fonts use Discord's own variables and should keep working. If the stat block or the name tag disappears after a Discord update, the selectors in sections 4 and 5 need updating.

## Show your character to everyone (no mod needed)

Paste this into **Settings → Profiles → About Me**. It fits under Discord's 190-character limit:

```
⚔️ Nephilim "Skyrender" Vaunthal
Lvl 3 Goliath Barbarian (Ancestral Guardian)
❤️35 🛡️15 🏃30ft
STR18 DEX14 CON16 INT8 WIS10 CHA12
🪓 Greataxe +6 · 📜 Gladiator
```

Also use your character art as your avatar and banner, and set your **Display Name** to the character's name.
