---
name: circle-back
description: Remembers the people a student meets and helps them circle back, saving a short profile of who each person is, where they met, what they do, and what is coming up for them. Use when the student sends a note or voice memo about someone new (an alum, recruiter, classmate, or friend), gives an update after talking to them again, asks to be reminded about someone's event, asks for help writing or sending a follow-up, or asks what they know about a person ("who was that recruiter from the career fair?").
---

# Circle Back

A personal relationship tracker. The student meets a lot of people, especially while
networking, and forgets the details. After each meeting the student sends a quick text or
voice note about who they met; this Skill saves it, keeps it updated, reminds the student
about what matters to those people, and helps the student follow up.

This Skill uses only Cubbie's built-in abilities (memory, voice-note transcription,
reminders and check-ins, and drafting messages). It has no scripts and needs no sign-in.

## When to use

- "Just met Priya at the AWS booth, she's a recruiter there, wants a backend intern, mentioned she runs marathons."
- A voice note: "so I grabbed coffee with Marcus the alum again, he just moved to the Austin office..."
- "Remind me to wish Coach Dani good luck, her team has playoffs next Friday."
- "Help me follow up with the recruiter I met at the career fair."
- "Who was that guy from the hackathon who worked at Stripe?"
- "Who should I reconnect with this week?"

Do not use it for emailing a professor (that is `email-to-professor`) or for building a
study plan. This Skill is about people the student meets and staying in touch with them.

## What to remember about each person

Use Cubbie's **memory** to keep one short profile per person. Capture only what the student
says; never invent details. A profile holds:

- **Name** and anything that tells them apart ("Priya the AWS recruiter", "Marcus, CS alum '19").
- **Where and when they met**, and who introduced them if mentioned.
- **What they do**: role, company or school, major, year.
- **What is coming up for them**: events, interviews, games, trips, exams, a launch, a birthday. Note the date when given.
- **Interests and personal notes**: marathons, a team they coach, a hometown, a shared class.
- **How the student reaches them**: text, email, LinkedIn or Instagram handle, as the student gives it. Do not guess contact details.
- **Follow-up owed**: anything the student said they would do ("send her my resume", "intro him to Sam").
- **Last contact**: the date of this meeting or update.

If the student sends a **voice note**, transcribe it first, then pull these details from it.
If the student sends a **photo** (a business card, a LinkedIn screenshot), read it and offer
to save what it shows. Always read back a one-line summary of what you saved so the student
can correct it.

## Saving someone new

1. Pull the details above from the student's message, voice note, or photo.
2. If an obvious detail is missing and useful (how to reach them, or a date for an event they
   mentioned), ask one short question, suggesting a default. Otherwise just save it.
3. Save the profile to memory. Confirm in one line: "Saved Priya (AWS recruiter, met at the career fair, runs marathons)."
4. If they mentioned a dated event or a follow-up, set a reminder right away (see "Reminders")
   and mention it in the same confirmation line.

## Updating someone

When the student talks about a person already saved, find that profile and update it rather
than making a second one. Merge the new details, refresh "last contact" to today, and resolve
anything that is now done (drop a follow-up once it is sent). Confirm what changed in one line.
If two saved people could match (two "Sarah"s), ask which one before saving.

## Recalling someone

When the student asks about a person, answer from the saved profile in a few short lines:
who they are, where they met, what they do, what is coming up, and anything owed. If nothing
is saved, say so and offer to start a profile. If the question is vague ("the Stripe guy"),
match on what is saved (company, event, interest) and name who you think they mean.

## Reminders

This Skill's value is in Cubbie noticing the moment to reach out, so set one-off reminders for
the student instead of asking first. A reminder only ever texts the student, so it needs no
yes. Do not ask what time they want it; pick a time that fits the event, as below, and let
them change it. Never force a fixed hour.

- **Something the student attends at a set time** (a meeting, an interview, a coffee chat, a
  game): remind them the evening before so they can prepare, and again about an hour before so
  they show up. If it is tomorrow, skip the evening-before one.
- **Something dated without a time** (an application opening, a birthday, a trip, a launch):
  remind them two days before, at a daytime hour when they are not in class (Cubbie knows the
  student's schedule). If two days before has passed, use the day before; if that has passed
  too, say the event is close instead of setting a reminder.
- **Follow-up nudges.** When the student owes a follow-up (a resume, an intro, a reply), set a
  nudge three days out at a daytime hour the same way. Drop it once the student says it is done.
- **Time zones.** Use the student's time zone. Assume a time the student gives is in their own
  time zone unless they say otherwise; do not ask.
- **Tell the student, do not ask.** Fold the reminder into the confirmation in one line
  ("Noted Karen's meeting Tue Oct 27, 3 pm. I'll remind you Monday evening and an hour before;
  say the word to move or cancel."). Change or cancel it right away if they ask.
- **Word each reminder so it still makes sense days later**: name the Skill, the person, and
  what to do ("circle-back: Coach Dani's playoffs are tomorrow, want to wish her luck?").
- **Reconnect check-in (recurring, opt-in).** A weekly check-in that surfaces a few people the
  student has not contacted in a while is a standing schedule, so offer this one and create it
  only after the student agrees, letting them pick the day and time. Keep each check-in to two
  or three names with a one-line reason to reach out.

## Helping with follow-ups

When the student asks for help following up, or accepts a nudge to:

1. Use the saved profile for context (how they met, what the person cares about, what is owed).
2. Ask which channel if it is not obvious (text, email, LinkedIn or Instagram message), and
   suggest the one the profile already has.
3. Draft a short, warm message in the student's voice that references something specific
   ("good luck at the playoffs", "great talking about backend internships at the booth").
4. Show the draft and ask whether to adjust it.

Cubbie texts only its own student, so it never sends a message to the other person itself:

- For a **text or a social DM**, give the student the final message to copy and send, or send
  it only after the student says yes if Cubbie can.
- For an **email**, if Google is connected, draft it in Gmail (do not send) and tell the
  student it is ready to review and send. If Google is not connected, write the email in the
  reply for the student to copy, and offer to connect Gmail for next time.
- Add an event the person mentioned to the student's Google Calendar only if the student asks
  and Google is connected.

## Replies

Keep each reply to a few short lines, plain text, no Markdown. One idea per message. When you
save or update a profile, confirm it in a single line. When the student asks about a person,
lead with who they are and what is coming up, and keep the rest for if they ask. Put a profile
link, LinkedIn URL, or event link on its own line so the phone makes it tappable. If you are
listing people to reconnect with, keep it to three names, each with a one-line reason.

## When something fails

- Nothing saved about the person yet: say so in one line and offer to start a profile.
- Ambiguous match (more than one person fits): ask which one, naming the candidates.
- Google not connected and the student wants an email drafted in Gmail: write the email in the
  reply instead and offer to connect Gmail next time. Do not stop.
- A voice note or photo you cannot make out: say what you could not read and ask the student to
  type that part. Never guess a name, a date, or a contact detail.
