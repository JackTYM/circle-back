# Circle Back

**Text Cubbie about anyone you meet. It remembers them, reminds you when it matters, and writes the follow-up.**

A [Cubbie](https://hackathon.cubbie.ai) Skill for students. Built for the Cubbie Hackathon, **Track 1**.

> ### Vote for Circle Back
> **https://tinyurl.com/crclback** (voting needs a `.edu` email; it takes 10 seconds)

---

## The problem

Every student meets a flood of people: recruiters at the career fair, alumni at a mixer, the person next to you at a hackathon. By the next morning you've lost the name, where you met, the thing you promised ("I'll send my resume"), and the thing they told you ("the role opens in 30 days").

Everyone says to follow up within 48 hours. Nobody does, because **remembering is the hard part, not writing**. The warm connection goes cold.

## What it does

Circle Back lives in iMessage. After you meet someone, send Cubbie a text or a voice note. It does the rest.

| Step | What happens |
|---|---|
| **Capture** | "just met Karen from Anthropic at the career fair, internship opens in 30 days, she loves cats". Type it, say it, or send a photo of their business card. |
| **Remember** | Cubbie saves a profile: who they are, where and when you met, what you talked about, what's coming up, how to reach them. |
| **Remind** | It picks out the dates that matter ("opens in 30 days", "apply in January") and brings the person back up with a real reason to write, not "just checking in." |
| **Follow up** | "write me the follow-up email" gives you a short, warm draft that calls back something specific from the conversation. You send it. |
| **Recall** | Weeks later: "who was that recruiter from the career fair?" or "who do I know at Stripe?" Instant answer from your saved contacts. |
| **Update** | "talked to Karen again, meeting Tuesday at 3" updates her profile and the next reminder. |

## See it

```text
You:     (voice note) just met Karen from Anthropic at the career fair,
         she loves cats, internship opens in 30 days

Cubbie:  Saved Karen from Anthropic: met at today's career fair, loves cats,
         and the internship opens November 23.

You:     write me the follow-up email

Cubbie:  Subject: Great meeting you at the career fair

         Hi Karen,
         It was great meeting you today! Thanks for chatting about Anthropic
         and the upcoming internship... I enjoyed our chat about cats, too!
```

## Try it

1. Text Cubbie this link:
   `https://github.com/JackTYM/circle-back`
2. Cubbie replies that it installed. No app, no account, no extra sign-in.
3. Tell it about someone you just met.

## Why it's different

- **Not a CRM.** No forms, no fields, no app to open. You text like you'd text a friend.
- **Proactive.** It doesn't wait for you to remember. It notices the moment and nudges you.
- **Safe by design.** Cubbie only ever texts *you*. Every message to another person is a draft for you to send, never sent for you.
- **Nothing new to install or break.** It runs on Cubbie's existing abilities: memory, voice transcription, reminders, and Gmail drafts.

## How it works

The Skill is a set of instructions (`SKILL.md`) plus a small contact book script.

```
SKILL.md              When to use it, and the steps Cubbie follows
scripts/contacts.py   The contact book: names, dates and follow-up status
```

**The contact book** (`scripts/contacts.py`) keeps everything exact across conversations: names, dates, who you owe a message to. It needs only Python 3. No packages, no keys, no sign-in.

| Command | What it does |
|---|---|
| `add` | Save someone: name, company, role, where and when you met, notes, and reasons to reconnect (`--hook "reason\|date"`) |
| `due --today <date>` | Who you owe a follow-up or reconnect right now (`--days 14` looks further ahead) |
| `list --company "<co>"` / `list --search "<word>"` | Find people |
| `show --id <id>` | One person in full |
| `done --id <id> --followup` | Mark the follow-up as sent |
| `done --id <id> --hook <n>` | Mark a reconnect as handled |
| `note` / `hook` / `edit` / `remove` | Log a later conversation, add a new reason to reconnect, fix details, delete |

Try it without touching any saved contacts:

```bash
python3 scripts/contacts.py --sample due --today 2026-10-24
```

**Hooks.** Anything a person says about the future ("apply in January", "email me your resume", "I'll be back on campus in spring") becomes a dated reason to reach back out. If there's no hook, Circle Back adds a light check-in about 10 weeks out, worded around something you actually discussed.

**Follow-up drafts.** Three to five sentences, written like a student, not a template. It thanks them for one specific thing, calls back one detail from your conversation, and ends with one small ask or none. It never asks for a job or a referral in the first message. If there's no email address, you get a short LinkedIn connection note instead. If Google is connected, it can save the draft to Gmail. It is never sent for you.

**Weekly check-in (opt-in).** A Sunday-evening rundown of who you owe a message to. If Google is connected, it also scans your calendar for career fairs and info sessions at companies already in your contact book, and suggests a one-line message ("Saw Schwab is at the Nov 12 info session; I'll be there, would be great to say hi"). If nothing needs action, it sends nothing.

## What it won't do

- Send anything to the person you met.
- Invent what someone said, or a company's dates or events.
- Handle emails to your own professors about classes (absences, extensions, grades). Cubbie's built-in professor email skill does that.

## Built for the Cubbie Hackathon

Track 1 asks for a Skill that solves a student problem so well students would miss it if it disappeared. Circle Back goes after the quiet failure behind most missed opportunities: you did the hard part and met the person, then lost them before the follow-up.

**If you'd use this, [vote for Circle Back](https://tinyurl.com/crclback).** `.edu` email needed.
