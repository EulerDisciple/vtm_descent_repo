# Contributing to Descent into Madness

Welcome! Follow these steps to submit a new session, character, or lore update:

## 1. Fork or Clone the Repo

```bash
git clone https://github.com/<your-username>/vtm-descent-into-madness.git
cd vtm-descent-into-madness
git switch -c player/<yourname>/session-01
```

## 2. Create Your Folder

```bash
mkdir -p players/<yourname>/{transcripts,summaries,ghost_protocols,inventory_lore}
```

## 3. Add Files

- Add a transcript file in `transcripts/`
- Add a session summary in `summaries/`
- Update your Ghost Protocol in `ghost_protocols/`
- Add items/lore if applicable in `inventory_lore/`

## 4. Commit and Push

```bash
git add .
git commit -m "Added session 01 for <yourname>"
git push origin player/<yourname>/session-01
```

## 5. Open a Pull Request

Use the PR template. Admins will review and help with merges. 
