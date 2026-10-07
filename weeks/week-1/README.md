[← All weeks](../../README.md) · **Week 1 · Your first website** · [Week 2 →](../week-2/)

# 🌴 Week 1 · Your first website

> ## 🎯 Your mission this week
>
> 1. Get your GitHub account and tools ready → Steps 1–6
> 2. Put your first website online → Steps 7–11
> 3. Write down your idea → Step 12
> 4. Join the Wall and post your update → Steps 13–14
> 5. Show your site to one adult and one friend → Step 15
>
> **Due:** Sunday 25 October, 8 pm · **Post your update:** your "I'm live" issue in [hello-osa](https://github.com/hechoenosa/hello-osa/issues)

**Due: Sunday 25 October, 8 pm** · about 1-2 hours · do the steps in order

Stuck on one step for more than 10 minutes? Post in the Hackathon group with a screenshot, what you tried, and what you expected to happen. Try to restart the computer and attempt again.

## ✅ Week 1: what every builder completes by Sunday 25 Oct, 8 pm

**Accounts**

- [ ] A GitHub handle: no surname, birth year or school name
- [ ] A GitHub account with that handle (under 13: created by a parent, with the parent's email)
- [ ] Email kept private (GitHub Settings → Emails → Keep my email addresses private)

**Tools on their computer**

- [ ] VS Code installed and opening
- [ ] Git installed (`git --version` shows a number in the VS Code terminal)
- [ ] Git set up with their handle and their private noreply email
- [ ] VS Code signed in to GitHub (this happens the first time they clone)

No computer at home: they skip the tool steps and do everything else in the browser

**Their first website**

- [ ] Their own copy of hello-osa on their GitHub account
- [ ] Made it theirs: their handle, a sentence about them, an emoji
- [ ] First commit pushed to GitHub
- [ ] Live on the internet at their-handle.github.io/hello-osa, and it opens on a phone

**Their idea**

- [ ] `my-idea.md` in their repo: what the idea is, who it's for, the problem, one person they can talk to
- [ ] Second commit pushed

**Showing up**

- [ ] On the Wall: their "I'm live: handle" issue, with the link, in hechoenosa/hello-osa
- [ ] First weekly update posted as a comment on that issue
- [ ] Shown their site to one adult and one friend

## 🎬 Watch first

| # | Video | Who | Length |
|---|---|---|---|
| 1 | Do it scared + Intro | Zamir | ≤ 4 min |
| 2 | The impostor feeling | Alex | ≤ 4 min |
| 3 | What is a product? What is a problem? | Emilie | ≤ 4 min |
| 4 | Think like a product leader | Vlad | ≤ 4 min |
| 5 | What engineers do + pick your handle | Lee | ≤ 10 min |
| 6a | Setup on Mac | Lee/mentor | ~14 clips, ≤ 2 min each |
| 6b | Setup on Windows | Lee or a mentor with Windows | ~14 clips, ≤ 2 min each |
| 7 | How I learned to code at 33 + deadline setting | Anastasia | ≤ 4 min |

<!-- Paste each video's link from the locked "Week 1 videos" issue. -->

---

## STEP 1 · Choose your handle 🏷️

Your handle is your developer name. It goes in your website link and on everything you build, so choose it like a superhero name.

- ❌ No surname, no birth year, no school name
- ✅ Short, easy to say out loud, something you'll still like at 25
- Examples: `ballena-dev`, `rip-spotter`, `ojochal-builds`

**Check it's free:** type `github.com/the-name-you-want` in your browser. If you see a 404 page, the name is free 🎉

## STEP 2 · Create your GitHub account 👤

1. Go to github.com/signup
2. Enter an email, a password and your handle as the username
3. Solve the puzzle and enter the code GitHub emails you

**Under 13?** A parent creates the account with their own email. You choose the handle together.

## STEP 3 · Keep your email private 🔒 (parents can help)

Your projects will be public, so your real email must stay hidden.

1. On GitHub, click your profile picture (top right) → **Settings**
2. In the left menu, click **Emails**
3. Tick ✅ **Keep my email addresses private**
4. Tick ✅ **Block command line pushes that expose my email**
5. Under the first box, find an address like `12345678+your-handle@users.noreply.github.com`. Copy it and paste it somewhere (Notes, a text file). You need it in Step 6.

## STEP 4 · Install VS Code 💻

VS Code is where you'll write code. Go to code.visualstudio.com and click the big **Download** button.

**🍎 Mac**

1. Open your Downloads folder and double-click the .zip file
2. Drag **Visual Studio Code** into your Applications folder
3. Open it from Applications. If the Mac asks "Are you sure you want to open it?", click **Open**

**🪟 Windows**

1. Open the downloaded installer
2. Accept the agreement → **Next**
3. On the "Select Additional Tasks" screen, tick all of these:
   - ✅ Add "Open with Code" action to Windows Explorer file context menu
   - ✅ Add "Open with Code" action to Windows Explorer directory context menu
   - ✅ Add to PATH
4. **Next → Install → Finish**

## STEP 5 · Install Git 🌳

Git is a time machine for your code. It saves every version so you can always go back.

**🍎 Mac**

1. Open VS Code
2. In the top menu: **Terminal → New Terminal**. A panel opens at the bottom.
3. Type this and press Enter:
   ```
   git --version
   ```
4. If a window pops up about the "command line developer tools", click **Install** and wait. It can take 5–15 minutes.
5. When it's done, type `git --version` again

**🪟 Windows**

1. Go to git-scm.com/download/win. The download starts by itself. If it doesn't, click "Click here to download".
2. Open the installer and click **Next** on every screen, except one: on the screen called "Choosing the default editor used by Git", pick "Use Visual Studio Code as Git's default editor"
3. Click **Install → Finish**
4. Close VS Code completely and open it again
5. **Terminal → New Terminal**, type `git --version`, press Enter

✅ It worked if you see something like `git version 2.47.0`. Any number is fine.

## STEP 6 · Tell Git who you are 🪪

In the VS Code terminal, type these two lines, pressing Enter after each. Use your handle and the noreply email from Step 3:

```
git config --global user.name "your-handle"
git config --global user.email "12345678+your-handle@users.noreply.github.com"
```

Nothing happens on screen. That's normal, and it means it worked.

## STEP 7 · Make your own copy of the starter 📄

Most code in the world is already written, and developers copy and remix all the time. You're starting with a page we made for you.

1. Go to github.com/hechoenosa/hello-osa
2. Click the green **Use this template** button → **Create a new repository**
3. Fill in:
   - Owner: you
   - Repository name: `hello-osa`
   - Public ✅
4. Click **Create repository**

You now have your own repo at github.com/your-handle/hello-osa.

## STEP 8 · Bring it to your computer 📥

1. In VS Code, open the Command Palette:
   - 🍎 Mac: **Cmd + Shift + P**
   - 🪟 Windows: **Ctrl + Shift + P**
2. Type `Git: Clone` and press Enter
3. Click **Clone from GitHub**
4. Your browser opens. Sign in to GitHub and click **Authorize**. If the browser asks to open VS Code, click **Open**.
5. Back in VS Code, pick your-handle/hello-osa from the list
6. Choose where to save it: make a folder called `hecho-en-osa` inside Documents, select it, and click **Select as Repository Destination**
7. When VS Code asks "Would you like to open the cloned repository?", click **Open**

You'll see `README.md` and `index.html` on the left.

## STEP 9 · Make it yours ✏️

1. Click `index.html` on the left
2. Find the three lines marked ✏️ and change them:
   - `@your-handle` → your handle
   - the sentence → one sentence about you
   - 🐋 → your emoji
3. Save:
   - 🍎 **Cmd + S**
   - 🪟 **Ctrl + S**

**See it:**

1. Right-click `index.html` on the left
   - 🍎 **Reveal in Finder**
   - 🪟 **Reveal in File Explorer**
2. Double-click `index.html`. It opens in your browser.
3. Click your button 🎊

That confetti? Someone else wrote that code and shared it for free. You got it with one line. Look at the top of `index.html` to find it.

## STEP 10 · Your first commit 💾 Always Be Commiting!

A commit is a saved snapshot of your work. Back in the VS Code terminal (**Terminal → New Terminal** if it's closed), type these three lines, pressing Enter after each:

```
git add .
git commit -m "My first commit"
git push
```

What just happened:

- `git add .` chooses what to save
- `git commit` takes the snapshot, with a message
- `git push` sends it up to GitHub

🪟 **Windows:** if a window pops up asking you to sign in, choose **Sign in with your browser** and approve it.

✅ It worked if your repo on github.com shows your handle in `index.html`.

## STEP 11 · Go live 🚀

1. Go to github.com/your-handle/hello-osa
2. Click **Settings** (top menu of the repo)
3. In the left menu, click **Pages**
4. Under **Branch**, choose `main`, leave the folder as `/ (root)`, and click **Save**
5. Wait 2 minutes, then refresh the page
6. At the top you'll see: "Your site is live at…"

**https://your-handle.github.io/hello-osa**

Open it on your phone. That's yours, on the internet. 🌎

## STEP 12 · Write down your idea 💡

1. In VS Code, hover over the folder name on the left and click the **New File** icon (a page with a +)
2. Name it `my-idea.md` and press Enter
3. Copy this in and fill it out:

```
# My idea

- What it is:
- Who it's for:
- Their problem:
- One person I can talk to about it:
```

For the person: a first name or a role only, like "my uncle who fishes in Uvita". No surnames.

4. Save (**Cmd + S** / **Ctrl + S**)
5. In the terminal:

```
git add .
git commit -m "Add my idea"
git push
```

That's your second commit.

## STEP 13 · Join the Wall 🧱

The Wall is where every builder's first website shows up.

1. Go to github.com/hechoenosa/hello-osa/issues
2. Click **New issue**
3. Title: `I'm live: your-handle`
4. In the big box: paste your link, `https://your-handle.github.io/hello-osa`
5. Click **Create**

Bookmark this issue. It's where your weekly updates go.

## STEP 14 · Post your first weekly update 📣

1. Open your Wall issue (the bookmark from Step 13)
2. Scroll to the bottom to the box that says "Add a comment"
3. Copy this in and fill it out:

```
## Week 1 update

✅ Done: what I finished this week
🔜 Next: what I'll do before the next Build Hour
🧱 Stuck: what's blocking me (or "nothing")
😬 Scariest part of setup:
🔗 Link: https://your-handle.github.io/hello-osa
```

4. Click **Comment**

Optional: in the Hackathon WhatsApp group, write "Week 1 posted ✅" with the link.

## STEP 15 · Do it scared 💪

Show your live website to one adult and one friend. Watch their face when they click the button.

---

## 🏫 No computer at home?

Reach out to organizers for Build Hour, and we will support

- Do Steps 1, 2, 3, 7, 11, 13, 14 and 15 in the browser.
- Skip Steps 4, 5, 6, 8 and 10.
- For Steps 9 and 12: open github.com/your-handle/hello-osa and press the `.` key. An editor opens in the browser. Make your changes, then click the branch icon on the left, type a message, and click **Commit & Push**.
- Always sign out of GitHub before you leave.

## ✅ Done when

- [ ] GitHub account with your handle, email set to private
- [ ] VS Code and Git installed, and `git --version` works
- [ ] your-handle.github.io/hello-osa opens on a phone and shows your handle
- [ ] `my-idea.md` is in your repo
- [ ] Your "I'm live" issue is on the Wall
- [ ] Your Week 1 update is posted
- [ ] Shown to one adult and one friend

## 🆘 Stuck?

| What you see | What to do |
|---|---|
| Windows: `'git' is not recognized…` | Close VS Code completely and open it again. Still broken? Restart the computer. |
| Mac: the developer tools install seems frozen | Give it 15 minutes. Still frozen? Restart the Mac and type `git --version` again. |
| Author identity unknown | You skipped Step 6. Do it, then run `git commit` again. |
| Permission denied or 403 when pushing | You cloned hechoenosa/hello-osa instead of your-handle/hello-osa. Do Step 8 again and pick yours. |
| GH007: Your push would publish a private email address | Step 6 used your real email. Run the email line again with your noreply address, then type `git commit --amend --reset-author --no-edit` and `git push`. |
| The website shows 404 | Wait 2 more minutes. In Settings → Pages, the branch must be `main` and the folder `/ (root)`. |
| You changed the file but the website didn't change | Did you save and push? Check the file on github.com. If your change is there, wait 1 minute and refresh. |
| The page looks broken after your change | You probably deleted a `<`, `>` or `"`. Press Cmd + Z / Ctrl + Z until it works, then try again slowly. |

**¡Hecho en Osa!** 🌴

---

[← All weeks](../../README.md) · **Week 1 · Your first website** · [Week 2 →](../week-2/)
