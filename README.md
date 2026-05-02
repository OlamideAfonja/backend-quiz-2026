# PHP & Backend Development — Master Quiz

150 questions across 7 sections with full answer key. Deployable to Vercel in 60 seconds.

## 📋 Sections
| # | Topic | Questions |
|---|-------|-----------|
| 1 | Introduction to Backend Development | 20 |
| 2 | Introduction to PHP | 20 |
| 3 | Variable Scope & Constants | 20 |
| 4 | PHP Coding Structure & Syntax | 20 |
| 5 | PHP Data Input | 20 |
| 6 | Control Structures (Selection & Looping) | 20 |
| 7 | Arrays & Functions | 20 |

## 🚀 Deploy to Vercel

### Option A — Vercel CLI (fastest)
```bash
npm install -g vercel
vercel --prod
```

### Option B — Vercel Dashboard
1. Go to https://vercel.com/new
2. Choose "Deploy from template" → Browse files
3. Upload the folder containing `php_quiz.html` and `vercel.json`
4. Click Deploy ✓

### Option C — GitHub + Vercel
1. Create a GitHub repo and push both files
2. Connect repo in Vercel dashboard
3. Auto-deploys on every push

## 🎮 Features
- **Quiz Mode** — answer questions, submit for grading with instant feedback
- **Answer Key Mode** — reveals all correct answers + explanations immediately
- **Difficulty badges** — Easy / Medium / Hard per question
- **Progress bar** — tracks completion across all 150 questions
- **Score report** — % score, correct/wrong/skipped breakdown with grade
- **Section tabs** — jump between any of the 7 topic sections
- **Fully static** — no server, no database, works offline

## 📁 Files
- `php_quiz.html` — the entire quiz (self-contained, no dependencies except Google Fonts)
- `vercel.json` — Vercel routing config
