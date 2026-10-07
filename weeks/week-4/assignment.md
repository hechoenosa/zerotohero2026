[← Week 4 overview](README.md) · [Rules](../../RULES.md) · [Stuck?](../../STUCK.md) · **Week 4 · Assignment** · [Week 5 →](../week-5/)

# Week 4 · Assignment

**Due:** Sun 15 Nov, 8 pm. Stuck? Post on your team issue.

## STEP 1 · Screen list 🖼️

Lay your paper screens on the table. For each one write one line in TRD section 2: `Start screen · title, one sentence, Play button`.

## STEP 2 · Your data 📊

What facts does your product need? Tide times, prices, nest dates? Fill the section 3 table. Pick where it lives:

- **Level 1:** typed into the code
- **Level 2:** a Google Sheet
- **Level 3:** live from the internet

Start at the lowest level that works.

## STEP 3 · Files and tools 🗂️

Section 4: HTML, CSS, JavaScript, plus anything else (a map, confetti). Section 5: list the files, e.g. `index.html`, `game.html`, `style.css`, `data.js`.

## STEP 4 · Write your tests 🧪

Section 6. One line per thing that must work:

> When I tap **Play**, I should see the first beach photo.

At least 5. You'll tick these off in Week 6.

## STEP 5 · Turn on Copilot 🔌

Everyone, on their own computer:

1. Open VS Code. Update it if it asks.
2. Click the **Copilot icon** at the bottom right of the window (the Status Bar).
3. Click **Use AI Features** → **Sign in with GitHub**. Your browser opens. Click **Authorize**.
4. Back in VS Code, you're on **Copilot Free**.
5. Switch off data sharing: **Cmd+,** / **Ctrl+,** → search `telemetry` → **Telemetry Level** → `off`.
6. Open chat: **Ctrl+Cmd+I** (Mac) / **Ctrl+Alt+I** (Windows). Type `Explain what my index.html does in 3 short lines.` If it answers, you're ready.

**Copilot won't work?** Use Gemini at `gemini.google.com` (under 13: a parent sets it up through Family Link).

## STEP 6 · Ask AI to question your TRD 🤔

Paste your `TRD.md` into Copilot chat and type:

> Here is our TRD. Ask us 3 questions an engineer would ask before building it. Don't write any code.

Answer the questions yourselves, as a team, in section 8.

## STEP 7 · Your first branch and pull request 🌿

One person drives:

```bash
git pull
git checkout -b trd
git add .
git commit -m "Add our TRD"
git push -u origin trd
```

On GitHub, click **Compare & pull request** → **Create pull request**. Your mentor reviews, then **Merge**. Everyone: `git checkout main` then `git pull`.

## STEP 8 · One issue per screen 🎫

In your repo: **Issues → New issue**. Title: `Screen: Start`. Paste that screen's line from TRD section 2 and its tests from section 6. Label `week-4`. Repeat for each screen. This is your to-do list for the Vibe Jam.

## STEP 9 · Post your update 📣

On your team issue: the link to your merged pull request, how many screen issues you opened, and one question Copilot asked you.

## 🤖 AI tools

**Our pick: GitHub Copilot Free inside VS Code.** It uses the GitHub account you already have. **Backup: Gemini.** Final call after Lee's test, by **Mon 9 Nov**.

| Tool | Age | Cost | How kids sign in |
| --- | --- | --- | --- |
| GitHub Copilot Free | follows the GitHub account (Lee checks under-13 accounts) | free, monthly limit | GitHub account in VS Code |
| Gemini | 13+; under 13 through a parent's Family Link | free | Google account |
| ChatGPT | 13+ with parent permission | free tier | not our default |
| Claude | 18+ | n/a | **not for builders** |

## 🧠 AI rules

From this week on, the AI rules apply. Read them together before you open Copilot: **[RULES.md](../../RULES.md)**

## 🏫 No computer at home?

Sections 2, 3 and 6 work fine on paper. Bring them Saturday. Copilot gets set up on the Build Hour laptops.

## ✅ Done when

- [ ] `TRD.md` merged through a pull request
- [ ] Copilot (or Gemini) working for everyone
- [ ] One issue per screen
- [ ] At least 5 tests in section 6
- [ ] Update posted

## 🆘 Stuck?

Check **[STUCK.md](../../STUCK.md)** first. Still stuck after 10 minutes? Ask, with a screenshot, what you tried and what you expected.

¡Hecho en Osa! 🌴

---

[← Week 4 overview](README.md) · [Rules](../../RULES.md) · [Stuck?](../../STUCK.md) · **Week 4 · Assignment** · [Week 5 →](../week-5/)
