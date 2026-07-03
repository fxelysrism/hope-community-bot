# 💜 Hope Esports Discord Bot

> *The official Discord bot powering the Hope Esports community.*

## Overview

The **Hope Esports Discord Bot** is a custom-built community bot designed to enhance the **Hope Esports** Discord server. It provides utility commands, moderation features, member engagement tools, and automated server events while maintaining a clean and interactive experience for the community.

From welcoming new members to displaying user avatars and server statistics, the bot helps keep the Hope community active, organized, and connected.

## Features

* 👋 **Automated Welcome System** – Greets every new member with a custom embedded welcome message.
* 📊 **Server Utilities** – View latency, member count, and user avatars instantly.
* 💬 **Messaging Tools** – Send announcements, direct messages, and repeat messages with ease.
* 🗑️ **Message Sniping** – Recover recently deleted messages within a limited time.
* 🔄 **Developer Restart Command** – Securely restart the bot without redeployment.
* 🌐 **Social Media Hub** – Quickly access Hope Esports' official social platforms.
* 🎙️ **Voice Channel Support** – Automatically connects to a designated voice channel when online.

## Commands

### Utility

| Command           | Description                                      |
| ----------------- | ------------------------------------------------ |
| `h!ping`          | Displays the bot's current latency.              |
| `h!membercount`   | Shows the current server member count.           |
| `h!avatar [user]` | Displays your avatar or another member's avatar. |
| `h!socials`       | Shows Hope Esports' official social media links. |

### Community

| Command                | Description                                                        |
| ---------------------- | ------------------------------------------------------------------ |
| `h!say <message>`      | Repeats your message in chat.                                      |
| `h!dm @user <message>` | Sends a direct message to a member (requires permissions).         |
| `h!snipe`              | Displays the most recently deleted message in the current channel. |

### Administration

| Command     | Description                                |
| ----------- | ------------------------------------------ |
| `h!restart` | Restarts the bot (developer-only command). |

## Automated Events

The bot automatically manages several server events, including:

* 🎉 Welcoming new members with a custom embed
* 📢 Connecting to a designated voice channel on startup
* 📝 Tracking recently deleted messages for the snipe feature
* ⚡ Maintaining a persistent online presence

## Technology

* Python
* Discord.py
* AsyncIO
* PyNaCl (Voice Support)
* Environment Variables
* Discord API

## Design Goals

* Fast and reliable performance
* Clean, modern embed responses
* Community-first experience
* Easy moderation and administration
* Minimal maintenance

## Use Cases

* Esports organizations
* Gaming communities
* Creator communities
* Competitive teams
* Public Discord servers

## Disclaimer

This bot was developed exclusively for the **Hope Esports** Discord server to provide community utilities, moderation tools, automated events, and a better overall member experience.

---

**Built for the Hope Esports Community** 💜
