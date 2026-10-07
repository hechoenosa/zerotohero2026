[← Week 1](../week-1/) · **Week 2 · Product sense + GitHub practice** · [Week 3 →](../week-3/)

# Week 2 · Product sense + GitHub practice

Week of Oct 26 · Build Hour moving from Sat 31 Oct (Halloween), new day TBC. Vlad leads on product sense: what makes a product good, what the problem is, and for whom. Discover phase, the wide part of the first diamond, so nothing narrows yet. Half the week goes to people (brainstorm and interviews), half to GitHub practice.

> **🎯 Your mission this week**
>
> 1. Finish anything left from Week 1 → Step 1
> 2. Brainstorm with Vlad and pick 3 problems to explore → Step 3
> 3. Practise GitHub: terminal, 5 changes by hand, pull, first issue → Steps 4–7
> 4. Interview 2 real people and write `discover.md` → Steps 8–10
> 5. Post your Week 2 update → Step 11
>
> **Due:** Sunday 1 November, 8 pm · **Post on:** your "I'm live" issue in hello-osa

## What every builder completes by Sunday 1 Nov, 8 pm

**Week 1 finished**

- [ ] Every Week 1 box ticked (setup help desk at Build Hour if not)

**Product sense**

- [ ] Brainstormed with Vlad at Build Hour, and left with 3 problems worth exploring
- [ ] Interviewed at least 2 real people about those problems
- [ ] At least one real quote, in the person's own words
- [ ] `discover.md` in your repo: what you heard and what surprised you

**GitHub practice**

- [ ] Ran all 7 terminal commands
- [ ] Changed their hello-osa page by hand: colours, photo, 3 places, console hello, click counter
- [ ] At least 6 new commits this week (one change = one commit)
- [ ] Edited a file on github.com, then brought it down with `git pull`
- [ ] Opened and closed their first issue (Quickdraw badge)

**Showing up**

- [ ] Week 2 update posted on their Wall issue


## Builder instructions

**Due: Sunday 1 November, 8 pm** · about 2½ hours · half with people, half on GitHub

Stuck on one step for more than 10 minutes? Post in the Hackathon group with a screenshot, what you tried, and what you expected to happen.

**Why GitHub practice this week?** On Sat 21 Nov, at the Vibe Jam, you'll build your product with AI and commit a lot, fast. Practice now, and on the day you only think about your product.

### STEP 1 · Finish Week 1 first 🔧

Any Week 1 box not ticked? Bring your laptop to Build Hour. Mentors will be available to help.

### STEP 2 · Watch the Week 2 videos 🎬

1. Emilie: Product sense
2. Zamir: Talking to strangers
3. Lee or another mentor: Your GitHub practice, step by step

### STEP 3 · At Build Hour: brainstorm with Vlad 🧠

Vlad runs this live. Sit with people whose idea is close to yours.

1. **Ask (2 min).** At the top of a big sheet: "How might we help \[who\] with \[problem\]?"
2. **Go wide (10 min).** Everyone writes every problem and every idea they can think of, one per sticky note. No bad ideas. The crazier the better.
3. **Share (5 min).** Read them out loud and stick them up.
4. **Pick 3 to explore (3 min).** Circle the 3 problems you most want to learn more about. Don't pick a solution yet. You'll find out which problem is real in your interviews.

Take a photo of the sheet.

### STEP 4 · GitHub practice A: the terminal 💻

The terminal is a way to talk to your computer by typing. These commands work the same on Mac and Windows inside VS Code.

1. Open your hello-osa folder in VS Code (**File → Open Folder**)
2. Open the terminal: **Terminal → New Terminal**
3. Type each command, press Enter, and read what comes back:

| Type this | What it does | What you'll see |
| --- | --- | --- |
| `pwd` | Where am I? | The path to your hello-osa folder |
| `ls` | What's in here? | `README.md`, `index.html`, `my-idea.md` |
| `cd ..` | Go up one folder | Run `pwd`: you're one folder up |
| `cd hello-osa` | Go back into your project | Run `pwd`: you're back |
| `git status` | What did I change since my last commit? | "nothing to commit, working tree clean" |
| `git log --oneline` | My project's history | Your commits from Week 1 |
| `clear` | Clean up the window | An empty terminal |

Bonus: `open .` (🍎 Mac) or `start .` (🪟 Windows) opens your folder. The `.` means "this folder."

### STEP 5 · GitHub practice B: change your page by hand ✏️

**One change = one commit.** After each change below:

1. Save (**Cmd + S** / **Ctrl + S**)
2. Refresh your page in the browser (**Cmd + R** / **Ctrl + R**) and check it worked
3. Commit and push: `git add .` → `git commit -m "Describe what you changed"` → `git push`

**Change 1 · Your colours 🎨** In `index.html`, find `background: #f4efe6;`. Pick a new colour at htmlcolorcodes.com/color-picker and replace `#f4efe6` with it. Change the text colour on the next line (`color: #1d1d1b;`) so you can still read it. Commit: `Change my colours`

**Change 2 · A photo 📸** Take a photo of a place you love in Osa, with no people's faces. Move it into your hello-osa folder and rename it `photo.jpg`. iPhone `.HEIC` files don't show in browsers, so screenshot the photo and name it `photo.png` instead. Under your sentence (the line starting with `<p>`), add:

```
<img src="photo.jpg" alt="The beach at Uvita" width="300">
```

Change the `alt` words to describe your photo. Screen readers say them out loud for blind people. Commit: `Add my photo`

**Change 3 · Your 3 places 🗺️** Under your photo, add:

```
<h2>My 3 favourite places in Osa</h2>
<ul>
  <li>Playa Ventanas</li>
  <li>The waterfall at Ojochal</li>
  <li>My grandmother's kitchen</li>
</ul>
```

Change them to your 3 places. `<h2>` is a smaller heading, `<ul>` is a list, `<li>` is one item. Commit: `Add my favourite places`

**Change 4 · Hello world 👋** Programmers start every language by making the computer say hello. Near the bottom of `index.html`, add one line inside `celebrate()` so it reads:

```
function celebrate() {
  console.log("¡Hola, Osa!");
  confetti({ particleCount: 150, spread: 80 });
}
```

Save, refresh, and open the console: 🍎 **Cmd + Option + J** · 🪟 **Ctrl + Shift + J** (Chrome). Click your button and "¡Hola, Osa!" appears. At the Vibe Jam, red messages here will tell you what's broken. Commit: `My first JavaScript`

**Change 5 · Count the clicks 🔢** Replace the whole `<script>` part at the bottom (from `<script>` to `</script>`) with:

```
<script>
  let clicks = 0;

  function celebrate() {
    clicks = clicks + 1;
    console.log("¡Hola, Osa! Clicks: " + clicks);
    document.querySelector("button").textContent = "🐋 " + clicks;
    confetti({ particleCount: 150, spread: 80 });
  }
</script>
```

`let clicks = 0;` makes a **variable**, a box with a name that holds a value. `clicks = clicks + 1;` adds 1 to it. `document.querySelector("button")` finds your button. Click it 10 times, then swap 🐋 for your own emoji. Commit: `Count the clicks`

### STEP 6 · GitHub practice C: edit on the website, then pull ⬇️

At the Vibe Jam, your teammates will change files while you work. `git pull` is how you get their changes. Practise it with yourself:

1. On github.com, open your hello-osa repo → click `README.md` → click the pencil ✏️
2. Add one line at the top: `My first website, made in Week 1 of Hecho en Osa.`
3. Click **Commit changes…** → **Commit changes**
4. Back in VS Code, in the terminal: `git pull`
5. Open `README.md` in VS Code: your new line is there.

**Rule from now on: `git pull` before you start, `git push` when you stop.**

### STEP 7 · GitHub practice D: your first issue 🐛

At the Vibe Jam, every bug becomes an issue. Try one now, and earn a badge.

1. In your hello-osa repo on github.com, click **Issues → New issue**
2. Title: `My first issue`
3. In the box:

```
What I did:
What I expected:
What happened:
```

4. Click **Create**, then click **Close issue** within 5 minutes
5. Check your profile: the Quickdraw badge ⚡ appears within a day.

### STEP 8 · Get your interview questions ready 📝

Take your 3 problems from the brainstorm. Pick 5 questions and write them on paper:

1. Tell me about your week. What does a normal day look like?
2. What's the hardest part of \[the problem\]?
3. Tell me about the last time that happened. What did you do?
4. How do you handle it today? An app, WhatsApp, paper, asking someone?
5. What's annoying about the way you do it now?

When they say something interesting, ask: "Why?" · "Can you tell me more?" · "When was the last time?"

**Never ask** "Would you use this?" or "Do you like my idea?" Everyone says yes to be nice.

### STEP 9 · Interview real people 🎙️

Talk to at least 2 people, about 15 minutes each. This is your do-it-scared step this week.

**Safety rules:** people you or your family know, or with a parent nearby · in person, at Build Hour, or on a call with a parent in the room · ask before recording anything · first names only.

**Rules:** ask about their life, not your idea · ask about the past, not the future · talk less, listen more.

**Write down for each person:** first name or role · their day in one line · their biggest problem, **in their exact words** · how they deal with it today · something that surprised you.

Next week you'll turn these notes into a persona, so keep them.

### STEP 10 · Write it down on GitHub 📌

1. In VS Code, `git pull`, then **New File** → `discover.md`
2. Copy this in and fill it out:

```
# What I discovered

## The 3 problems from our brainstorm
1.
2.
3.

## Who I talked to
- [first name or role]: "[their exact words]"
- [first name or role]: "[their exact words]"

## What surprised me

## Which problem looks most real now, and why
```

3. Save, then `git add .` → `git commit -m "What I discovered"` → `git push`

### STEP 11 · Post your Week 2 update 📣

1. Open your Wall issue (your bookmark from Week 1)
2. Scroll to "Add a comment", paste, fill in, click **Comment**:

```
## Week 2 update

🗣️ Best quote from an interview: ""
🤔 The problem that looks most real:
💾 Commits this week: [number from git log --oneline]
✅ Done:
🔜 Next:
🧱 Stuck: (or "nothing")
🔗 Link: https://your-handle.github.io/hello-osa
```

Optional: in the Hackathon WhatsApp group, write "Week 2 posted ✅".

### ⭐ Bonus for the Vibe Jam

Want to feel ready on 21 Nov? Do GitHub's free **Introduction to GitHub** course in your browser (under 1 hour): github.com/skills/introduction-to-github → **Copy Exercise**. It teaches branches and pull requests, which teams use at the Jam.

### 🏫 No computer at home?

- Steps 2, 3, 8 and 9 happen anywhere.
- Steps 4–7 and 10: at Build Hour, open your repo and press `.` for the browser editor. Skip the terminal; use the branch icon → message → **Commit & Push** after each change.
- Step 11: post from your phone's browser.
- Always sign out of GitHub on shared computers.

### ✅ Done when

- [ ] Every Week 1 box is ticked
- [ ] 3 problems from the brainstorm, 2+ interviews, a real quote
- [ ] `discover.md` is in your repo
- [ ] Your live page has your colours, photo, places and a click counter
- [ ] `git log --oneline` shows 6+ new commits
- [ ] You edited on github.com and pulled it down
- [ ] Your first issue opened and closed
- [ ] Week 2 update posted

### 🆘 Stuck?

| What you see | What to do |
| --- | --- |
| Still stuck on Week 1 setup | Build Hour help desk with your laptop. Check the Week 1 Stuck table first. |
| The photo shows a broken image icon | The name in `src="…"` must match the file exactly, including .jpg or .png and capitals, and the photo must sit next to `index.html`. |
| The page went blank or looks broken | You probably deleted a `<`, `>` or `"`. Press Cmd + Z / Ctrl + Z until it works, then try again slowly. |
| The button stopped working | Open the console. A red message names the line with the problem. Check every `(`, `{` and `"` has its closing partner. |
| `git push` says "rejected" | GitHub has a change you don't have. Run `git pull`, then `git push` again. |
| "Your local changes would be overwritten" | Run `git add .`, then `git commit -m "My changes"`, then `git pull` again. |
| Nobody to interview | Ask a mentor at Build Hour. Family counts. |
| Everyone says "great idea!" | You explained your idea too early. Ask only about their life. |

¡Hecho en Osa! 🌴


---

[← Week 1](../week-1/) · **Week 2 · Product sense + GitHub practice** · [Week 3 →](../week-3/)
