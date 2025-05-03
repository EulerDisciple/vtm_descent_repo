# Vampire: The Masquerade – Descent into Madness

Welcome to your solo or shared chronicle. This repo supports players running story-driven campaigns with ChatGPT as the GM. Each player stores session logs, Ghost Protocol summaries, and character histories in their folder.

## Structure

- `scenarios/`: Markdown-based solo scenarios
- `players/<name>/`: Transcripts, summaries, and Ghost Protocol sheets
- `shared_lore/`: NPCs, events, and recurring symbols
- `tools/`: Prompts, templates, and dice macros

To begin, copy a scenario from `scenarios/` into your session log and start playing using the instructions in the prompt file.


---

## 🔁 After Each Scenario

Every player should create or update their own folder inside `players/`, structured like this:

```
players/<your_character_name>/
├── transcripts/
├── summaries/
├── ghost_protocols/
└── inventory_lore/
```

After completing a scenario:
- Add a transcript of your gameplay
- Summarize your character’s arc
- Update your Ghost Protocol Sheet
- Archive new items or symbols

Once done, zip your player folder and push it to GitHub. This keeps your story and character evolution versioned and accessible.


---

## 📬 Submitting Your Character and Session

Rather than zipping and uploading, **fork the repo or create a branch**, then:

1. Add your files under `players/<your_character_name>/`
2. Include:
   - A session transcript
   - A scenario summary
   - An updated Ghost Protocol Sheet
   - Any new lore or item entries
3. Create a Pull Request

Your PR will be reviewed by a world admin for lore continuity and merged into the shared universe.

### Branch Naming Convention

```
player/<your_name>/session-<scenario_number>
```

Example:
```
player/seraphine/session-01
```


---

## 📘 First Time Using GitHub?

Check out `NEW_PLAYERS_GUIDE.md` for step-by-step help, from installing Git to submitting your first PR.
