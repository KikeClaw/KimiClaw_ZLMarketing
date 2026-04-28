# ZeroLimitAI — Marketing Command Center

## 🚀 Quick Start

1. **Open `index.html`** in your browser (double-click it)
2. Every morning, check **"TODAY'S MISSION"**
3. **Copy the tweet** → Post on Twitter → Click **"Done — Next Day"**
4. **Update metrics** in the Metrics Tracker tab every Monday

---

## 📁 Files

| File | What it is |
|------|-----------|
| `index.html` | **Dashboard** — open this every day. Shows today's task, metrics, calendar. |
| `CONTENT_BANK.md` | **30 days of tweets**, email templates, Reddit posts, blog outlines. Copy from here. |
| `README.md` | This file. Instructions and tips. |

---

## 🎯 Daily Workflow (5 minutes)

1. Open `index.html`
2. Read **"TODAY'S MISSION"**
3. Click **"Copy Tweet"** or copy manually
4. Open Twitter → Paste → Post
5. Spend 3 more minutes replying to 2-3 tweets from big accounts in your niche
6. Click **"Done — Next Day"** to advance
7. Close dashboard. Done.

---

## 📊 Weekly Review (Monday, 10 minutes)

1. Open **Metrics Tracker** tab
2. Fill in last week's numbers:
   - Signups (from your DB / GA)
   - Conversions (from Stripe)
   - Revenue (from Stripe)
3. Check which channel drove the most traffic
4. Adjust this week's focus based on what worked

---

## 🔗 Quick Links (in dashboard)

- Twitter Compose
- Reddit Submit (r/indiehackers)
- Product Hunt Dashboard
- HackerNews Submit
- Google Analytics
- Stripe Dashboard

---

## 💡 Tips for Maximum Impact

### Twitter
- **Post between 9-11am EST** for best engagement
- **Threads > single tweets** for reach
- **Reply to big accounts** (@sama, @natfriedman, etc.) to borrow their audience
- **Use images** — tweets with images get 2x engagement
- **Pin your best tweet** to your profile

### Reddit
- **Participate first** — comment genuinely for 1 week before posting
- **Use "Showoff Saturday"** on r/indiehackers
- **Never copy-paste the same post** to multiple subreddits
- **Respond to every comment** on your post

### Product Hunt
- **Prepare assets 2 weeks early**
- **Launch on Tuesday or Wednesday**
- **Be online for 4 hours** after posting to reply to comments
- **Ask your users to upvote** (but don't brigade)

### Email
- **Send newsletters on Tuesday or Thursday, 10am**
- **Subject lines: curiosity + benefit**
- **One CTA per email**
- **A/B test subject lines** if you have >100 subscribers

---

## 🎨 Customizing the Dashboard

### To change the goals:
Edit the HTML file, find these lines and update the numbers:
```html
<div class="metric" id="signup-metric">0 / 500</div>
<div class="metric" id="revenue-metric">$0 / $2,450</div>
```

### To add more tweets:
Edit the `tweets` array in the `<script>` section of `index.html`.

### To change the accent color:
Edit CSS variable `--accent` in the `<style>` section.

---

## 📈 UTM Parameters

Always add UTM parameters to track which channel works:

```
?utm_source=twitter&utm_medium=social&utm_campaign=ditch_monthly
?utm_source=reddit&utm_medium=social&utm_campaign=ditch_monthly
?utm_source=producthunt&utm_medium=referral&utm_campaign=ditch_monthly
?utm_source=hackernews&utm_medium=referral&utm_campaign=ditch_monthly
```

Check results in Google Analytics → Acquisition → All Traffic → Source/Medium.

---

## 🆘 Need Help?

If something breaks or you want new features:
1. Take a screenshot
2. Tell me what's wrong
3. I'll fix it or add it

---

*Built for ZeroLimitAI. Now go get those conversions!* 🔥
