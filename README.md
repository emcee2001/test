# Your First Day with Coding + GitHub (Absolute Beginner)

You said you’re brand new. Perfect — this guide is for your **very first day**, not experts.

## What you need to know in 60 seconds

- **Coding** = writing instructions for a computer.
- **Git** = save history of your file changes.
- **GitHub** = website where your Git project lives online.

Think:
- `git commit` = save point
- `git push` = upload to GitHub
- Pull Request (PR) = “please merge my changes”

---

## Zero-confusion glossary

- **Repository (repo):** your project folder
- **Branch:** safe copy/lane to make changes
- **Commit:** saved snapshot of changes
- **Push:** send commits to GitHub
- **Pull Request:** ask to merge branch changes
- **Merge:** apply PR changes into main branch

---

## Your first successful Git workflow (copy/paste)

Run these commands in order:

```bash
# 1) check current state
git status

# 2) create and switch to your branch
git checkout -b my-first-change

# 3) make a small edit in README.md, then save it

# 4) stage + commit
git add README.md
git commit -m "My first GitHub change"

# 5) upload branch to GitHub
git push -u origin my-first-change
```

If each command succeeds, you just did real developer workflow ✅

---

## GitHub website clicks (after push)

1. Open your repo on GitHub.
2. Click **Compare & pull request** (or **Contribute → Open pull request**).
3. PR title example: `My first GitHub change`.
4. Click **Create pull request**.
5. Click **Merge pull request** when ready.

---

## What to do when you see errors

Use this exact method:

1. Read the **exact** error line.
2. Copy-paste the error into search.
3. Change **one thing only**.
4. Run command again.
5. If fixed, commit.

Errors are normal. Debugging is a core skill.

---

## First-week plan (simple and realistic)

### Day 1
- Learn `git status`, `git add`, `git commit`, `git push`
- Open and merge 1 PR

### Day 2
- Learn basics of one language (Python or JavaScript)
- Build tiny app: calculator or number guess

### Day 3
- Push project to GitHub
- Make 3+ commits with clear messages

### Day 4–7
- Repeat with one new tiny project
- Focus on consistency, not complexity

---

## Good commit message examples

- `Add beginner README`
- `Fix typo in setup steps`
- `Create number guessing script`

Avoid vague messages:
- `update`
- `changes`
- `stuff`

---

## Next step

If you want, I can give you a **one-command-at-a-time live practice script** for your terminal and wait for your output after each step.
