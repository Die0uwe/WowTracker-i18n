# WowTracker-i18n

Translations for [WowTracker](https://github.com/Die0uwe/WowTracker).

## Add your language

1. **Fork** this repository
2. Copy `locales/enUS.lua` → `locales/xxXX.lua` (your locale code)
3. Translate all strings
4. Submit a **Pull Request**

## Locale format

```lua
-- locales/nlNL.lua
local L = {}
L["GUILD_TAB"]       = "Gilde"
L["DELVES_TAB"]      = "Verkenningen"
L["BOUNTY_TAB"]      = "Premie"
L["ROSTER_TAB"]      = "Roster"
L["ARMORY_TAB"]      = "Wapenrusting"
L["CURRENCY_TAB"]    = "Valuta"
L["SEARCH_HINT"]     = "Zoek karakter..."
L["MOTD_LABEL"]      = "Bericht van de dag"
L["ONLINE_LABEL"]    = "Online"
L["LOADING"]         = "Laden..."
return L
```

## Supported locales

| Code | Language | Status |
|------|----------|--------|
| enUS | English (US) | ✅ Complete |
| nlNL | Nederlands | ✅ Complete |
| deDE | Deutsch | ⬜ Needed |
| frFR | Français | ⬜ Needed |
| esES | Español | ⬜ Needed |
| koKR | 한국어 | ⬜ Needed |
| zhCN | 中文 | ⬜ Needed |

## Links
[WowTracker](https://github.com/Die0uwe/WowTracker) · [Slayer Alliance](https://slayeralliance.com)
