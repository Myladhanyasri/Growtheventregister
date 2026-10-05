# Growtheventregister
# NxtWave AI Growth Experience

A gamified registration and referral platform for NxtWave's free workshop, **"Build Your First AI Project in 60 Minutes."** It was built for the NxtWave Growth Intern challenge, with a goal of 500 registrations in 7 days on a ₹2,000 budget.

**Build. Compete. Connect. Unlock.**

> **Prototype notice:** All leaderboard names, admin numbers, expert profiles and reward values are simulated demo data. Data is stored in the visitor's own browser (localStorage), so referrals do not count across different devices.


---

## The idea

A webinar is passive. This is an experience. A student registers and sees four steps right away:

1. **Refer** friends and earn +150 points each
2. **Play** AI games and challenges
3. **Ask** industry experts and earn +50 per question
4. **Unlock** learning rewards with the points

Referring is the fastest route to a reward, so every registered student becomes a distribution channel.

**Growth loop:** Register → Earn → Refer → Friend registers → Unlock → Share → More registrations

## Features

| Area | What it does |
|---|---|
| Landing page | Hero with countdown, live preview card, how-it-works path, 7-day campaign plan |
| Registration | Name, email, phone, college, branch, graduation year. Unique code such as `DHA123`, and `#/register?ref=CODE` links |
| Dashboard | Points, level, progress to the next reward, "ways to earn", personalised recommendations, points history |
| Referral engine | Copy link, WhatsApp share, copy message, tracked clicks, registrations and conversion rate |
| Challenges | AI Trivia, Debug the AI, Guess the AI Output, Prompt Battle (criteria-scored), Project Idea Challenge |
| Industry Connect | Demo expert profiles, question submission, popular answered questions |
| Leaderboard | Ranked list, your position, 5 levels (Explorer to AI Champion) |
| Rewards | 5 tiers from 500 to 5,000 points, locked/unlocked states, confetti on unlock |
| Live event | 5-minute challenge, project step, attendance points |
| Admin | 347/500 target tracker, acquisition sources, 8-step funnel, editable point values, "Why this works" |
| Demo mode | One click loads a sample student (Dhanya, 1,250 points, 3 referrals) |

## Quick demo (about 2 minutes)

1. Open the site and click **Demo mode (Dhanya)**.
2. On the dashboard, click **Simulate friend registering** to see +150 points.
3. Open **Challenges**, win a game and watch the points and progress bar update.
4. Open **Industry Connect** and submit a question for +50 points.
5. Open **Leaderboard** to see your rank, then **Rewards** to unlock a course.
6. Open **Admin** to see the funnel and growth metrics.

## Run locally

No build step or dependencies. It is a single file.

```bash
git clone <your-repo-url>
cd <your-repo>
open index.html        # or double-click the file
```


## Tech

- Plain HTML, CSS and JavaScript in a single `index.html`
- State saved with `localStorage`
- Google Fonts (Space Grotesk)
- No frameworks, no backend

## Point system (editable in Admin)

| Activity | Points |
|---|---:|
| Register | 50 |
| Complete profile | 25 |
| Refer a friend | 100 |
| Friend registers | 150 |
| Attend workshop | 100 |
| Ask an expert | 50 |
| Complete AI challenge | 100 |
| Win a mini-game | 50 |
| Complete final project | 200 |
| Help a participant | 25 |

## Roadmap

- Real backend (Supabase or Firebase) so referrals and the leaderboard work across students
- Expert answers delivered in-app
- Anti-fraud checks (phone/email verification, daily referral caps)
- Configurable 7-day campaign schedule
- Share-your-reward cards for social posts

## Growth plan summary

- **Target:** 500 registrations in 7 days
- **Budget:** ₹2,000 with no paid ads (₹1,000 top-referrer vouchers, ₹600 club lead thank-yous, ₹400 reserve)
- **Assumed math:** 150 seeded sign-ups with a referral factor of 0.65 gives about 430, plus about 80 from social and email. These are planning assumptions, not results.
- **Tests:** post-registration share screen, share message wording, community positioning

## Disclaimer

Reward names and values (₹499 to ₹4,999) are demonstration values until NxtWave supplies actual rewards. No real professionals, companies, testimonials or registrations are represented.
