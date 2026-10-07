[← All weeks](README.md)

# 🆘 Stuck?

Find what you see on your screen, then do what it says.

**Still stuck after 10 minutes?** Post a screenshot, what you tried, and what you expected to happen:
- **Weeks 1–2:** in the Hackathon WhatsApp group
- **Weeks 3–8:** on your team issue in zerotohero2026

Restarting the computer fixes more than you'd think.

## 🛠️ Setup (Week 1)

| What you see | What to do |
|---|---|
| Windows: `'git' is not recognized…` | Close VS Code completely and open it again. Still broken? Restart the computer. |
| Mac: the developer tools install seems frozen | Give it 15 minutes. Still frozen? Restart the Mac and type `git --version` again. |
| Author identity unknown | You skipped Week 1 Step 6. Do it, then run `git commit` again. |
| Permission denied or 403 when pushing | You cloned hechoenosa/hello-osa instead of your-handle/hello-osa. Do Week 1 Step 8 again and pick yours. |
| GH007: Your push would publish a private email address | Week 1 Step 6 used your real email. Run the email line again with your noreply address, then type `git commit --amend --reset-author --no-edit` and `git push`. |
| Still stuck on Week 1 setup in Week 2 | Build Hour help desk with your laptop. |

## 🌐 Your website

| What you see | What to do |
|---|---|
| The website shows 404 | Wait 2 more minutes. In Settings → Pages, the branch must be `main` and the folder `/ (root)`. |
| You changed the file but the website didn't change | Did you save and push? Check the file on github.com. If your change is there, wait 1 minute and refresh. |
| The page went blank or looks broken | You probably deleted a `<`, `>` or `"`. Press Cmd + Z / Ctrl + Z until it works, then try again slowly. |
| The photo shows a broken image icon | The name in `src="…"` must match the file exactly, including .jpg or .png and capitals, and the photo must sit next to `index.html`. |
| The button stopped working | Open the console. A red message names the line with the problem. Check every `(`, `{` and `"` has its closing partner. |
| Works on laptop, broken on phone | Ask the AI: `Make this page fit a phone screen.` Then retest. |

## 🌳 Git and GitHub

| What you see | What to do |
|---|---|
| `git push` says "rejected" | GitHub has a change you don't have. Run `git pull`, then `git push` again. |
| "Your local changes would be overwritten" | Run `git add .`, then `git commit -m "My changes"`, then `git pull`, then `git push`. |
| `CONFLICT` in a file | Nothing is lost. VS Code shows **Accept Current / Incoming / Both**. Pick, save, commit, push. |
| Pull request says "conflicts" | Click **Resolve conflicts**, keep the right lines, delete the `<<<<` `====` `>>>>` markers, **Mark as resolved**. |
| No **Compare & pull request** button | Go to **Pull requests → New** and pick your branch as the compare branch. |
| `error: pathspec 'main'` | Your branch might be called `master`. Run `git branch` to see. |
| No team repo invite by Wednesday (Week 3) | Check handle spelling on the team issue, then tag Anastasia there. |

## 🎙️ People and interviews

| What you see | What to do |
|---|---|
| Nobody to interview | Ask a mentor at Build Hour. Family counts. |
| Everyone says "great idea!" | You explained your idea too early. Ask only about their life. |

## 📝 PRD and TRD

| What you see | What to do |
|---|---|
| The team can't agree on PRD section 4 | Ask what your persona would do first. Still stuck? Your mentor decides. |
| You don't know where your data comes from | Write it in TRD section 8. Ask Anastasia on the team issue. |
| Running out of time | Move the feature to PRD section 7. Shipping less is a skill. |

## 🤖 AI and Copilot

| What you see | What to do |
|---|---|
| No Copilot icon in the Status Bar | Update VS Code and restart it. |
| "You've reached your monthly limit" | Switch to Gemini for the rest of the month. Tell your mentor. |
| The AI built 5 screens when you asked for 1 | Undo (**Cmd+Z** / **Ctrl+Z**) and say: `Only the Start screen. Nothing else.` |
| It looks nothing like your sketch | Paste PRD section 6 (look and feel) again and attach a photo from `sketches/`. |

## 🎤 Presentation

| What you see | What to do |
|---|---|
| PDF over 10 MB | Export with smaller images, or use fewer photos. |
| Someone doesn't want to speak | They run the demo clicks. Everyone still has a role. |

**¡Hecho en Osa!** 🌴
