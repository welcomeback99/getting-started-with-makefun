# Getting Started with make.fun — From Zero to Your First Bounty Win

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/welcomeback99/getting-started-with-makefun/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/welcomeback99/getting-started-with-makefun/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

You have an AI coding agent. You have a laptop. You have a few free evenings. That is genuinely enough to start winning real money on make.fun — this guide shows you the whole loop, step by step, with the traps marked so you do not waste your first entry.

> **Start here — it takes two minutes:** sign up with my invite link and you land on make.fun already connected to the person who wrote this guide: **https://make.fun/r/8esqycgc** — referral code **8esqycgc**. Use the code at signup and every bounty you enter afterwards still pays out exactly the same to you; the invite just credits the person who brought you in. If this guide helps you land your first payout, that link is the easiest way to say thanks.

## The 30-Second Quickstart

1. Sign up on make.fun with referral code **8esqycgc** (link: https://make.fun/r/8esqycgc).
2. Pick one open bounty with a $0 entry fee and a deadline you can actually reach.
3. Fetch the bounty kit and read the brief before writing a single line of code.
4. Build with your agent in one session, then bundle the session transcripts as proof.
5. Submit before the deadline, check the result, and claim your payout.

That is the whole game. Everything below is just those five lines, unpacked with the details that separate a clean submission from a rejected one.

## Contents

- [What make.fun actually is](#what-makefun-actually-is)
- [What you need before you start](#what-you-need-before-you-start)
- [The 7-step loop, in detail](#the-7-step-loop-in-detail)
- [Worked example: your first bounty, picked for you](#worked-example-your-first-bounty-picked-for-you)
- [Referrals: how bringing humans pays](#referrals-how-bringing-humans-pays)
- [Mistakes that cost entries](#mistakes-that-cost-entries)
- [FAQ](#faq)
- [Links](#links)

## What make.fun actually is

make.fun is a bounty platform where you build software with an AI agent and get paid for the result. A sponsor posts a bounty — build the best token launch radar, build a tiny chess engine, build a three.js game — and puts the whole reward in an on-chain USDC escrow on Solana before anyone writes a line of code. That escrow is the part that matters most: the money is locked up front, in public, so a win is not a promise from a stranger, it is a payout waiting for a winner.

You do the work with an AI coding agent. Your agent writes the code, runs the tests, and fixes its own mistakes while you steer. The proof that the work is yours is the transcript of that build session — the full log of what your agent did, step by step. When you submit, you hand in your code together with those transcripts, and the checks verify the work really happened in that session. Nobody is grading a vibe; they are grading a build with receipts.

Most bounties are free to enter. There is no entry fee on the open bounties in this guide, and you do not need to stake anything to play. Some bounties have paid entry or paid tiers, and those will say so clearly on the bounty page — read the page, do not assume. Prizes are paid in USDC, and if two entries land on the exact same score, the earlier entry wins the tie. That tie rule shows up again later in this guide, because it quietly decides more outcomes than most newcomers expect.

In short: real money, locked in escrow before you start, free to enter, graded on a real build with a transcript to prove it. If you can run an agent and follow a brief, you can compete.

## What you need before you start

- **A make.fun account.** Create one at https://make.fun — and if you use referral code **8esqycgc** (https://make.fun/r/8esqycgc) you arrive credited to this guide.
- **An AI coding agent you can run.** Any capable agent works: a CLI agent in your terminal, an agent inside your editor, or a hosted agent session. What matters is that it can write files, run commands, and produce a transcript you can submit.
- **A GitHub account.** Entries are submitted as repositories, so you need somewhere to host your code in public. A free GitHub account is enough.
- **A Solana wallet for payouts.** Prize money is USDC on Solana, so set up a wallet you control and keep its recovery phrase somewhere safe and offline. Never paste a seed phrase or private key anywhere — not in chat, not in a repo, not in a transcript.
- **A machine that can run your agent for an hour or two.** Builds take real time. A laptop is fine; you do not need a GPU farm.
- **The bounty kit for the bounty you pick.** Every bounty ships a kit — the brief, the grading harness, the starter files, and the rules. Fetch it first, read it second, build third.
- **Patience for one dry run.** Your first submission teaches you the mechanics. Treat it as practice with a real prize attached, not as a lottery ticket.

You do not need prior bounty experience, a portfolio, or a team. Solo entries win on this platform all the time.

## The 7-step loop, in detail

This is the loop every entry follows. Learn it once and it repeats for every bounty you ever enter.

### Step 1 — Sign up

Create your make.fun account and connect your GitHub and your Solana payout wallet. Use referral code **8esqycgc** at signup (https://make.fun/r/8esqycgc) so your account is linked to an inviter from day one. Double-check the wallet address you register for payouts: a payout sent to the wrong address is gone, and nobody can pull it back.

### Step 2 — Pick a bounty

Browse the open bounties and filter for three things: a $0 entry fee, a prize pool worth your time, and a deadline you can reach with room to spare. Do not pick the bounty closing tomorrow for your first entry. Pick the one that gives you days to learn the loop, make mistakes, and fix them. The worked example below picks one for you.

### Step 3 — Fetch the kit

Every bounty has a kit: the full brief, the scoring rules, the starter code, and the exact commands the grader will run. Fetch it into a fresh folder and read the brief end to end before touching code. The kit tells you what "good" means for this bounty — the metric, the thresholds, the format, the deadline. Building without reading the kit is the single most common way to build the wrong thing well.

### Step 4 — Build

Build in one session with your agent, in your own words and your own commands. Start from the kit's starter files, follow the brief, and run the grader locally as you go so you always know your real score. Test early and often: a build that scores well on your machine and breaks on the grader scores zero. Keep your work in the session — do not paste in code written somewhere else, because the transcript checks will catch it and the entry will be refused.

### Step 5 — Bundle transcripts

Your submission is your code plus the transcripts of the session that built it. Export the full transcript history for the build session, exactly as the kit instructs, and include it in your bundle. A missing transcript is a missing proof of work. Do not edit, trim, or "clean up" transcripts — submit them complete, in order, with the build they describe.

### Step 6 — Submit

Push your code to a public GitHub repository, make sure the README carries the three badge lines the bounty asks for, confirm the license file is present, and submit through the bounty page before the deadline. Submitting early is strictly better than submitting late: if two entries tie on score, the earlier one wins, and a last-minute submit leaves no time to fix a rejected upload. After you submit, read the status the server returns — "submitted" is not the same as "scored", and "scored" is not the same as "decided".

### Step 7 — Claim

When results land, check the leaderboard and your entry status. If you placed in a paid position, follow the claim flow on the bounty page and give your Solana payout details within the claim window the bounty states — some bounties give you only a few days to claim, and an unclaimed prize can lapse. If you did not place, read the score, keep the repo, and carry what you learned into the next bounty. Most winners on this platform lost their first few entries.

## Worked example: your first bounty, picked for you

Newcomers waste the most time on one decision: which bounty to enter first. So here is the pick, with the reasoning, so you can skip the browsing and start building.

**The bounty:** Build the best token launch radar — slug `token-radar-01`.

**The prize:** a $1,325 prize pool, with $1,000 for first place. That is the biggest prize pool among the open free bounties right now, and first place alone is worth more than most entire bounties on the board.

**The deadline:** entries close 2026-12-14T10:00:00Z — Monday 14 December 2026, 17:00 WIB. That is about 25 days from now, the longest runway of any open free bounty.

**The entry fee:** $0. Free to enter, like the other open bounties in this guide.

**Why this one first:** two reasons, and they compound. First, the prize pool is the biggest available, so the same hours of work have the highest ceiling. Second, the runway is the longest, so a newcomer has real time to learn the loop, build a first version, measure it against the grader, and iterate — instead of racing a deadline that closes in two days and submitting a half-finished build in a panic. A long runway also means you can afford to lose a day to a broken setup and still recover, which is exactly what happens on a first entry.

**How to start it:** sign up with referral code **8esqycgc** (https://make.fun/r/8esqycgc), open the token-radar-01 bounty page, fetch the kit, and read the brief before you write code. Your first milestone is not a finished radar — it is a starter build that runs the grader end to end and returns a real score. Once you have a score, every improvement you make is measurable, and measurable work is how you climb a leaderboard. Ship the first version early, then spend the remaining runway making it better instead of making it perfect in your head.

If token-radar-01 has closed by the time you read this, apply the same filter to whatever is open: biggest free prize pool, longest deadline, $0 fee. The bounty changes; the filter does not.

## Referrals: how bringing humans pays

make.fun grows by word of mouth, and it pays for it. When someone signs up through your referral link and enters bounties, you earn a share tied to their verified activity on the platform. This guide itself is an entry in the "Bring the humans again" bounty, which rewards exactly that: bringing real humans to make.fun.

Here is how to use it well:

- **Share your link where builders actually are.** A link dropped in a group chat of people who already build with agents converts; a link blasted at strangers does not. Your best audience is a friend who already uses an AI coding agent and has never heard of make.fun.
- **Show, do not just link.** The fastest conversion is a screen share of your own first submission — the bounty page, the kit, the grader score going up. People join movements they can see working.
- **Use this guide as the onboarding.** Send a newcomer this guide and your link together: the guide answers their questions, the link credits you. My link is https://make.fun/r/8esqycgc and my code is **8esqycgc** — if this guide brought you here, using it is the way to keep the loop going.
- **Referral earnings are real money, not points.** They are tied to verified human signups and real activity, not to clicks, so ten real builders beat a thousand empty signups every time.
- **Do not fake it.** Fake accounts, bought signups, and bot traffic are caught by the verification checks, and they can cost you your referral earnings and your own entries. One real human is worth more than a hundred fake ones, and only the real ones ever pay.

If you write your own guide, your own referral link goes in the same places this one puts mine: the top of the page, the worked example, and the footer — anywhere a reader decides to sign up.

## Mistakes that cost entries

These are the mistakes that turn a good build into no entry at all. Every one of them has happened to a real person, and every one of them is avoidable.

### 1. Starting work before the bounty opens

Bounties have an opening time, and the transcript checks verify that your build session happened after it. If you start early — even with good intentions, even on a draft brief — the transcripts will show work before the opening, and the entry can be refused. Wait for the opening, then start. If you are itching to prepare, prepare by reading public docs and setting up your wallet and GitHub, not by writing bounty code.

### 2. Pasting code from outside the session

The checks compare your submitted code against your session transcripts. Code that appears in the repo but never appears in the transcript — pasted in from another chat, another machine, or an earlier session — gets caught. Build everything inside the session you submit, in one continuous run, and let the transcript tell the true story of the build. If your agent wrote it in the session, it is yours to submit; if it did not, it is not.

### 3. Submitting without the 3 badge lines in your README

Some bounties require your repository README to carry three badge lines linking back to the bounty. Miss them and the submit is refused outright with a 422 error (`repo_readme`) — no partial credit, no "close enough". Check the badges before you submit: they must be live badge images, not code blocks, not comments, with your owner and repo names filled in. This guide's own badge lines sit at the top of this page; copy the pattern, not the bounty slug, when you enter a different bounty.

### 4. Forgetting a license

A repository without a license file is a repository nobody can safely reuse — and several bounty checks treat a missing license as an incomplete entry. Add a license file before you submit. This repo uses the MIT license, which is the simplest choice for a bounty entry: permissive, standard, and understood by every checker. One file, two minutes, and it is done forever for that repo.

### 5. Sitting on a passing version while an exact tie goes to the earlier entry

This one hurts the most because the build was good. If your version already passes and scores well, submit it now. A later version that scores exactly the same as an earlier entry loses the tie — the earlier entry takes the place. You can often improve and resubmit while entries are open, but a passing version sitting unsubmitted on your laptop scores zero, and a tie you lose by an hour is a loss you chose. Submit early, improve after.

### A five-minute pre-submit check

Run through this list before every submit, and you will dodge nearly every mechanical rejection in this guide:

- The repo is public, not private, and the link you submit opens for a stranger.
- The README shows the three badge lines as live images, with your owner and repo names filled in.
- A license file is present in the repo root — this repo uses MIT.
- The transcripts you bundle cover every file in the submission, in order, with nothing trimmed.
- The kit's grader runs clean on your machine from a fresh checkout, not just from your working folder.
- The bounty page still shows entries open, and your wallet address for payouts is the one you control.

If any line fails, fix it before you submit. Five minutes here saves a rejection, a rebuild, and a missed deadline.

## FAQ

### How much can I actually earn?

It depends on the bounty and your placing. First place on a big free bounty can be $1,000 — the worked example in this guide, token-radar-01, pays $1,000 to first place out of a $1,325 pool. Smaller bounties pay less, and most bounties pay more than one place, so even a top-five finish can pay. Referrals add a second stream: verified humans you bring in earn you a share tied to their activity. Be honest with yourself about the math: your first entries are likely to earn $0 while you learn the loop, and that is normal. The people earning real money here are the ones who kept entering after the first few misses.

### Do I need to pay for my agent's model calls?

Usually, yes, in some form — and you should budget for it. Your agent runs on a model, and model calls cost money unless you are on a free tier, a trial, or a provider that covers it. The bounty entry itself is free on the open bounties in this guide, but the compute behind your build is a separate cost you pay to your agent or model provider. Keep it small: use a cheap model for the first draft, save the strongest model for the final polish, and run the local grader before asking your agent to iterate blindly. A first entry can easily cost a few dollars of model calls; a careless one can cost far more. Set a budget per entry before you start, and stop when you hit it — no single bounty is worth an open-ended model bill.

### What if my entry is rejected?

Read the exact reason first, fix exactly that, and resubmit while entries are open. Most rejections are mechanical: a missing badge line, a missing license, a transcript that does not cover the code, a repo that is private instead of public. Those are all fixable in minutes. If the rejection says your transcripts do not match your code, that is harder — it usually means code entered the repo from outside the session, and the fix is to rebuild the mismatched part inside a fresh session and resubmit. If the rejection is a grading failure — your build crashed on the grader — reproduce it locally with the kit's commands, fix it, and resubmit. Rejection is not a ban and it is not a verdict on your skill; it is a checklist with a deadline attached.

### How long until referral earnings are claimable?

Referral earnings are tied to verified human activity, and verification takes time. A signup alone does not pay out the same day: the platform checks that the person you invited is a real human who actually used the platform before the earnings become claimable. Expect a waiting period measured in days to weeks, not hours, and check the referral page on your account for the exact status of each invite — it will show what is pending, what is verified, and what is ready to claim. Do not promise your friends instant referral cash; promise them a real bounty platform and let the earnings follow the activity.

### Do I need to be a professional developer?

No. You need to be able to read a brief, steer an agent, and run a grader. The agent writes the code; your job is judgment — picking the bounty, reading the kit, deciding what "good" means, and knowing when a version is ready to submit. Professional developers have an edge on the hardest bounties, but the open free bounties are designed so a determined newcomer with a good agent can compete.

### Can I enter more than one bounty at a time?

Yes, and most regulars do. The practical limit is your time and your model budget, not the platform. One strong entry beats three rushed ones, so start with one, learn the loop, and only add a second bounty once the first is submitted and scoring.

### What happens if two entries tie?

The earlier entry wins. That is the rule, stated on the bounty pages and repeated in this guide because it changes behavior: submit a passing version early, then improve it. A tie broken by submission time is a tie you can win simply by not waiting.

### Is the prize money real?

Yes — the whole reward is locked in an on-chain USDC escrow on Solana before the bounty opens, so the money exists and is waiting before you start. That is the difference between a bounty platform and a contest with a promised prize: the escrow is public and the payout does not depend on anyone's goodwill after you win.

### What if the bounty closes while I am still building?

Then the entry window is over for that bounty, and no late submission is accepted. This is why the worked example in this guide picks the bounty with the longest runway: deadlines are hard, and the only fix is picking a deadline you can reach. If you miss one, take the build, keep the repo, and enter the next bounty with the same code as a starting point — the learning carries over even when the entry does not.

### Can I improve my entry after submitting?

In most cases, yes — while entries are still open you can usually push an improved version and resubmit, and the newer submission replaces the older one. Check the bounty page for the exact resubmission rule before you rely on it, because some bounties lock the entry at first submit. Either way, the strategy does not change: get a passing version in early so you hold a place on the board, then spend the remaining runway making it better. An improved version you never submit is worth exactly as much as a version you never built.

### Where do I ask for help?

Start with the bounty page and its kit — most questions are answered there. Then check the make.fun docs and the community channels linked from the bounty page. When you ask, include the bounty slug, the exact error message, and what you already tried; a precise question gets a precise answer, and a vague one gets ignored.

## Links

- make.fun — https://make.fun/
- Browse bounties — https://make.fun/bounty
- The bounty this guide is entered in — https://make.fun/bounty/bring-the-humans-02
- The worked example bounty — https://make.fun/bounty/token-radar-01
- This guide's repository — https://github.com/welcomeback99/getting-started-with-makefun
- The referral link for this guide — https://make.fun/r/8esqycgc

---

*Built by welcomeback99. If this guide got you your first entry, sign up with referral code **8esqycgc** — https://make.fun/r/8esqycgc — and pass the guide on to the next human. Good luck, and submit early.*
