# ChatVault — Marketing Plan (First Sales)

**Goal:** Get first 50 paying customers at $19 = $950 revenue  
**Price:** $19 one-time  
**Window:** First 2 weeks after launch

---

## Before you launch — 2 things to do first

### 1. Set up Gumroad (10 min)
1. Go to https://gumroad.com and create a free account
2. Click **New Product** → choose "Digital product"
3. Name it "ChatVault", price $19
4. In the description, paste this:

   > ChatVault exports all your ChatGPT conversations to your computer in minutes. Private, automatic, one-time payment. Works with Free, Plus, Team and Business accounts. Mac & Windows included. Free updates forever.

5. Upload both the .exe and .dmg files as the product files
6. Copy your product URL (looks like `gumroad.com/l/chatvault`)
7. Replace every `GUMROAD_PLACEHOLDER` in `index.html` with your URL, then push to GitHub (Vercel will auto-redeploy)

### 2. Make the GitHub app repo public
The app repo (chatvault) is currently private. Make it public so people can see it's real:
- Go to https://github.com/rhm-haarslev/chatvault → Settings → Danger Zone → Change visibility → Public

---

## Week 1 — Free channels (do these in order)

### Day 1: Reddit posts

Post in these subreddits one at a time (not all at once — Reddit will flag it as spam).

**r/ChatGPT** (4.5M members) — best first post  
Title: `I built a desktop app to export your entire ChatGPT history — free to try, tell me what you think`  
Body:
> Been frustrated that there's no easy way to back up ChatGPT conversations, especially if you're on a Team plan. Built a small desktop app called ChatVault that handles it automatically — logs in, downloads everything, handles rate limits, resumes if interrupted.
>
> Works on Mac and Windows. Currently supports ChatGPT, with Claude/Gemini coming.
>
> Website: https://chatvault-website.vercel.app
>
> Happy to answer questions — curious if this solves a real problem for people here.

---

**r/productivity** (1.7M members) — post day 2  
Title: `Built a tool to back up your ChatGPT history locally — no cloud, no subscription`  
Body:
> If you use ChatGPT heavily, losing access to your conversation history is a real risk. Built ChatVault to solve this: it exports everything to your computer as files, automatically handles rate limits, and resumes if you close it.
>
> One-time $19, Mac & Windows: https://chatvault-website.vercel.app

---

**r/OpenAI** (1.2M members) — post day 3  
Title: `ChatVault — desktop app to export and back up your entire ChatGPT history`

---

**r/SideProject** — post day 4  
Title: `I shipped a desktop app in a week: ChatVault backs up your ChatGPT history`  
Body: Tell the building story — people love this on this sub.

---

### Day 2–3: Twitter / X

Tweet 1 (product launch):
> Built a desktop app called ChatVault 🔒
>
> It exports your entire ChatGPT history to your computer in minutes.
> — Handles rate limits automatically
> — Works with Team accounts
> — Resumes if interrupted
> — Nothing leaves your device
>
> Mac + Windows. One-time $19.
>
> 👉 chatvault-website.vercel.app

Tweet 2 (problem-first, 2 days later):
> Your ChatGPT history will disappear someday.
>
> OpenAI could delete it, change pricing, or shut down.
> You should have a local backup.
>
> ChatVault exports everything to your computer in one click.
> chatvault-website.vercel.app

Tweet 3 (social proof, once you have a review):
> Someone with 1,500+ ChatGPT conversations used ChatVault to export all of them overnight. It handled the rate limits automatically.
>
> $19 one-time: chatvault-website.vercel.app

---

### Day 4–5: Niche communities

- **Hacker News** — post in "Show HN": `Show HN: ChatVault – desktop app to back up your ChatGPT history (Mac/Windows)`
- **IndieHackers** — post your build story in the "Products" section
- **LinkedIn** — write a short post about building it (your professional network)

---

### Day 7: Product Hunt

Submit to Product Hunt for a full launch day. This can drive 100–500 website visits.

Steps:
1. Go to https://producthunt.com
2. Submit ChatVault as a new product
3. Tagline: "Back up your entire ChatGPT history in one click"
4. Schedule for a Tuesday/Wednesday (best days for tech audience)
5. Post in Reddit + Twitter the morning it launches to drive upvotes

---

## What to say when people ask "why not just use ChatGPT's built-in export?"

ChatGPT's export button:
- Puts you on a waitlist (can take days)
- Gives you one big ZIP — not individual files
- Doesn't work for Team accounts
- You have to repeat it manually every time

ChatVault:
- Instant, no waiting
- Individual files per conversation
- Works with Team/Business
- Resumes automatically

---

## Ongoing (week 2+)

| Channel | Action |
|---|---|
| SEO | Write a blog post: "How to export your ChatGPT history" targeting that keyword |
| YouTube | 60-second demo video showing the full flow |
| Cold outreach | Find people asking "how do I export ChatGPT?" on Reddit/Twitter, reply with a link |
| Affiliates | Offer 30% commission to anyone who refers buyers via Gumroad |

---

## Pricing rationale

**$19 one-time** is the right price because:
- Low enough to be an impulse buy (under the "do I really need this?" threshold)
- High enough to signal quality (free tools feel risky with private data)
- One-time removes subscription fatigue
- Comparable to other privacy/utility tools (e.g. CleanMyMac = $30/year, Acorn = $20)

Once you add Claude + Gemini support, you can test raising to $29.

---

## Success metrics

| Metric | Target (week 1) |
|---|---|
| Website visitors | 500+ |
| Gumroad page views | 100+ |
| Sales | 10–25 |
| Reddit post upvotes | 50+ |

If a Reddit post gets 100+ upvotes, double down — reply to every comment, DM people asking questions.
