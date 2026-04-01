# 🐾 Awesome Claude Code Buddies

<div align="center">

![Stars](https://img.shields.io/badge/Collection-Rare%20Buddies-purple?style=for-the-badge)
![Species](https://img.shields.io/badge/Species-18-blue?style=for-the-badge)
![Shiny](https://img.shields.io/badge/Shiny-✨-gold?style=for-the-badge)

**🦄 A collection of rare Claude Code Buddy UserIDs!**

[简体中文](README_CN.md) | English

<img src="images/my-buddy.png" alt="My Buddy" width="300"/>

</div>

---

## 🎯 What is this?

Claude Code has a `/buddy` feature that lets you adopt a personalized pet buddy. Each UserID corresponds to a fixed buddy with specific species, rarity, eyes, hat, stats, etc.

This repo collects **pre-computed UserIDs** for rare buddies so you don't have to roll millions of times!

---

## 📚 Tutorial Source

The script and method in this repo are from: [Claude Code /buddy 宠物系统逆向分析 —— 如何重置并刷到你想要的宠物 - 开发调优 - LINUX DO](https://linux.do/t/topic/1871870)

---

## ✨ Features

- 🏆 **Legendary** rarity buddy UserIDs
- ✨ **Shiny** buddies
- 🎩 Rare hats (crown, tophat, halo, wizard...)
- 📊 Max stats buddies

---

## 📁 Directory Structure

UserIDs organized by species in `buddies/` folder:

```
buddies/
├── dragon/          # 🐉 Dragon
├── cat/             # 🐱 Cat
├── duck/            # 🦆 Duck
├── owl/             # 🦉 Owl
├── capybara/        # 🦫 Capybara
├── axolotl/         # 🦎 Axolotl
├── ghost/           # 👻 Ghost
├── mushroom/        # 🍄 Mushroom
├── robot/           # 🤖 Robot
├── rabbit/          # 🐰 Rabbit
├── penguin/         # 🐧 Penguin
├── turtle/          # 🐢 Turtle
├── octopus/         # 🐙 Octopus
├── snail/           # 🐌 Snail
├── blob/            # 🫧 Blob
├── goose/           # 🪿 Goose
├── chonk/           # 🐷 Chonk
└── cactus/          # 🌵 Cactus
```

Each folder contains `.md` files with UserIDs and corresponding buddy attributes.

---

## 🛠️ Usage

### Method 1: Use collected UserIDs directly

1. Find your desired species folder in `buddies/`
2. Open the `.md` file
3. Copy the UserID
4. Change the `userID` field in `~/.claude.json` to the corresponding value.

### Method 2: Search with the script

This repo provides `buddy-reroll.js`:

```bash
# Using Bun (recommended, matches Claude Code results)
bun buddy-reroll.js --species dragon --rarity legendary --shiny

# Using Node (results may not match)
node buddy-reroll.js --species cat --rarity epic

# Check what buddy a UserID produces
bun buddy-reroll.js --check <your-userid>
```

Run `bun buddy-reroll.js --help` for more options.

---

## 🤝 Contributing

PRs are welcome! Share your rare buddy UserIDs!

---

## ⚖️ License

MIT
