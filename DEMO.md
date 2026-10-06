# Miner Dash: Claude Code live demo (15 min)

**Goal:** go from an empty folder to a playable, UTEP-themed browser game, then let the audience steer.

## Before you go on stage
- Make a fresh empty folder (`mkdir miner-dash && cd miner-dash && git init`) and open a terminal with a big font.
- Run `claude` once beforehand so you're logged in.
- **Backup:** `backup/index.html` in this repo is a finished version of the game. If Wi-Fi or the API fails, open it in a browser and narrate the prompts anyway.
- Pre-open a browser tab for the game.

## Run of show

| Time | Prompt to paste | What to say |
|---|---|---|
| 0-1 | *(none)* | "This is an empty folder. Claude Code is an AI that works in your terminal: it reads files, writes code, and runs commands." |
| 1-4 | `Build a single-file browser endless-runner game called Miner Dash in index.html. A miner with a pickaxe and hard hat runs through a cave, jumps over rocks and bats, and collects gems. Use UTEP orange (#ff8200) and blue (#041e42). Space or tap to jump, with a double jump. Show score and best score.` | Let it work. Point out that it chose the files and structure itself. |
| 4-5 | `Open it so I can play` (or open `index.html` in your browser) | Have 1-2 volunteers play. |
| 5-9 | Audience picks 2-3: `Add a shield power-up that protects me from one hit` / `Make the game speed up the further you go` / `Add a sound effect when I grab a gem` / `Add a boss: a giant rolling boulder every 1000 points` / `Add a leaderboard that saves top 5 scores in the browser` | "I'm not typing code. I'm describing what I want." |
| 9-11 | Paste a screenshot of any game or logo: `Restyle the game to match this look` | Shows multimodal input. |
| 11-13 | `Write a few tests for the collision and scoring logic, run them, and fix anything that fails.` | "It checks its own work, which is the part that makes it more than autocomplete." |
| 13-15 | `Commit this with a good message and push it to a new GitHub repo` (or deploy to GitHub Pages) | End with a live link students can open on their phones. |

## Talking points to weave in
- **Plan Mode** (Shift+Tab): ask it to plan before it edits, which is good for bigger projects.
- **CLAUDE.md:** a file where you tell Claude about your project once, so it remembers.
- **You stay in control:** it asks permission before running commands or editing files.
- **Learning:** ask it "explain how the collision code works" and it teaches you your own code.
- It's a tool for building and learning, not for skipping your coursework. Check with your professors on AI policies.

## If something goes wrong
- Bug on stage? That's a feature: say "let's see how it debugs" and paste the error or describe the problem.
- Out of time? Skip the screenshot and test steps; the gameplay and audience requests are the core.
