# Reel Engine

A blank, browser-based shot-list builder for AI video. Add shots, fill in
frame/motion/negative prompts, export as JSON. No account, no install,
nothing leaves your browser.

**Open it:**

- **[GitHub Pages](https://github.com/Stynka/reel-engine)** - no login needed
- **[Claude.ai](https://claude.ai)** - requires Claude account (free or paid)

---

## What it does

- **Add shot** - title, beat, duration, engine (Kling I2V / Motion Control /
  Still / Other), camera type, lens, frame/start/end prompts, motion prompt,
  negative prompt, director's commentary, working notes
- A timeline strip builds itself automatically from your shots, color-coded
  by engine. Click any segment to jump to that shot.
- **Copy full prompt block** - assembles one shot's fields into the exact
  text you paste into your generation tool
- **Export as JSON** - saves your whole shot list as a file
- **Import JSON** - load a saved file back in, on this computer or any other
- **Export all prompts as .txt** - every shot's prompt block in one file

## How it saves your work

Everything you type saves automatically to this browser, tied to this exact
page. That means:

- Refreshing the page keeps your work
- A different browser, or a different copy of this file, starts blank
- Export is your real backup. If you want your work to survive a browser
  switch, a new computer, or sharing with someone else, export the JSON and
  keep the file.

Nothing is sent anywhere. There's no server behind this - it's a single
HTML file that runs entirely in your browser.

## Sharing with someone else

Send them this same page, or the repo link. They fill in their own shots,
or use Import to load a JSON file you've exported as a starting point.
Your two sessions never touch each other.

## Running it yourself

No build step. Download `index.html`, open it in a browser, done.

To host it as a shareable link with GitHub Pages:

1. New repo, upload `index.html`
2. Settings > Pages > Deploy from branch > `main` / root > Save
3. Your URL appears at the top of that Pages settings page after about a
   minute

---

## Accessing on Claude.ai

To use reel-engine directly in Claude:

1. Visit https://claude.ai
2. Start a new conversation
3. Upload the `index.html` file
4. Claude will render it so you can build your shot list in chat

You need a Claude account (free or paid) to do this. The GitHub Pages version
above works in any browser with no login.
