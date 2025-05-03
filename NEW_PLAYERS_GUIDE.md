# 🧭 New Player GitHub Guide

Welcome! This guide is for players who are new to GitHub and want to participate in this collaborative Vampire: The Masquerade storytelling universe.

---

## 🧱 Step 1: Install Git (if you don’t have it)

- **Windows**: Download from https://git-scm.com/download/win
- **Mac**: Download from https://git-scm.com/download/mac
- **Linux**: Use your package manager (`sudo apt install git`, `sudo dnf install git`, etc.)

After installation, open a terminal (Command Prompt or Terminal app) and run:

```bash
git --version
```

You should see something like `git version 2.40.1`.

---

## 🗂 Step 2: Fork or Clone the Repository

Option 1 – Use GitHub Website:
1. Go to the main repo (your Game Master or DM will give you the link)
2. Click the **"Fork"** button (top right)
3. Then click **"Code" > "Open with GitHub Desktop"** (recommended) or copy the URL

Option 2 – Use Git in Terminal:

```bash
git clone https://github.com/your-username/vtm-descent-into-madness.git
cd vtm-descent-into-madness
```

---

## ✍️ Step 3: Add Your Player Folder

Inside the project, go to:

```
players/
```

Create a folder using your character’s name or your name, for example:

```
players/seraphine/
```

Inside, copy or create your files using the provided templates:

- `ghost_protocols/`
- `transcripts/`
- `summaries/`
- `inventory_lore/`

You can copy the example folder from `players/example_player/` to get started quickly.

---

## 🧪 Step 4: After Each Session

Add or update:
- Your **transcript** (`transcripts/01_last_light_transcript.md`)
- A **summary** (`summaries/01_last_light_summary.md`)
- An updated **Ghost Protocol** (`ghost_protocols/ghost_protocol_v2.md`)
- Any new **artifacts or memories**

Then commit your changes:

```bash
git add .
git commit -m "Added session 01 for Seraphine"
git push
```

---

## 📬 Step 5: Submit a Pull Request

Go to your forked repo on GitHub and click **"Pull Request"** → **"New Pull Request"**

Use this naming convention:

```
player/<yourname>/session-01
```

Example title:

```
PR: player/seraphine/session-01
```

Describe your changes. Once submitted, a world admin will review and merge it into the official world!

---

## 🆘 Need Help?

Ask in Discord or email the moderator of your campaign.

---

Happy hunting, neonate.
