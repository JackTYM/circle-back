---
name: circle-back
description: Remembers the people a student meets and helps them circle back, saving a short profile of who each person is, where they met, what they do, and what is coming up for them. Use when the student sends a note or voice memo about someone new (a recruiter, alum, professor, classmate, or friend), gives an update after talking to them again, asks what they know about a person ("who was that recruiter from the career fair?"), asks who they have met or who to reconnect with, asks for help writing a follow-up or preparing for a meeting with someone, or asks to correct or forget what is saved about a person.
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
- "Met 3 people at the mixer: Dev does robotics, Lena's premed, and Sam runs the climbing club."
- "Remind me to wish Coach Dani good luck, her team has playoffs next Friday."
- "Help me follow up with the recruiter I met at the career fair."
- "Who was that guy from the hackathon who worked at Stripe?"
- "Who have I met this month?" / "Who should I reconnect with this week?"
- "I have coffee with Marcus tomorrow, what should I remember?"
- "Actually she's at Google, not Meta." / "Forget what you have on Karen."

Do not use it to build a study plan. Formal email to a professor or TA (an absence, an
extension, office hours, a grade question) belongs to the built-in `email-to-professor`
Skill; see "Professors, TAs and advisors" below for the hand-off.

## What to remember about each person

Use Cubbie's **memory** to keep one short profile per person. Capture only what the student
says; never invent details. A profile holds:

- **Name** and anything that tells them apart ("Priya the AWS recruiter", "Marcus, CS alum '19").
- **Relationship type**: recruiter, alum, professor or TA, classmate, friend, club member, mentor,
  family of a friend. Infer it from context; do not ask.
- **Where and when they met**, and who introduced them if mentioned ("via Marcus").
- **What they do**: role, company or school, major, year, lab, team.
- **What is coming up for them**: events, interviews, games, trips, exams, a launch, a birthday,
  a role opening. Note the date when given.
- **Interests and personal notes**: marathons, a team they coach, a hometown, a shared class.
- **How the student reaches them**: text, email, LinkedIn or Instagram handle, as the student
  gives it. Do not guess contact details.
- **Follow-up owed**: anything the student said they would do ("send her my resume", "intro him
  to Sam"), and anything the person said they would do ("she'll send the application link").
- **Last contact**: the date of this meeting or update.

If the student sends a **voice note**, transcribe it first, then pull these details from it.
If the student sends a **photo** (a business card, a LinkedIn screenshot, a name tag), read it
and save what it shows. Always read back a one-line summary of what you saved so the student
can correct it.

Skip details about a person's health, finances, family trouble or similar unless the student
asks you to keep them. If the student says not to save something, do not save it.

## Saving someone new

1. Pull the details above from the student's message, voice note, or photo.
2. Resolve relative dates ("next Friday", "in 30 days", "end of the semester") against today's
   date in the student's time zone, and show the resolved date in the confirmation. If a weekday
   is given without "next" or "this", take the first one coming up.
3. If one obvious detail is missing and useful (a date for an event they mentioned), ask one
   short question with a default. Otherwise just save it; do not ask for contact details.
4. Save the profile to memory. Confirm in one line: "Saved Priya (AWS recruiter, met at the career fair, runs marathons)."
5. If they mentioned a dated event or a follow-up, set a reminder right away (see "Reminders")
   and mention it in the same confirmation line.

**Several people at once** ("met 3 people at the mixer: ..."): save each as its own profile, and
confirm them in one short message, one line per person.

**No name yet** ("the girl from chem lab with the green jacket"): save the profile under that
description. When the student later gives the name, merge it into the same profile rather than
starting a new one.

**Someone mentioned by someone else** ("Marcus said I should talk to his coworker Sam"): save Sam
as a new profile with "via Marcus," and note the intro as a follow-up for the student.

## Updating someone

When the student talks about a person already saved, find that profile and update it rather
than making a second one. Match on the name, and when the name is not given, on what is saved
(company, event, interest). Merge the new details, refresh "last contact" to today, and resolve
anything that is now done. Confirm what changed in one line.

- **Corrections** ("actually she's at Google, not Meta"): fix the detail, confirm in one line,
  never make a second profile.
- **They reached out first** ("Karen emailed me back", "Marcus texted about Tuesday"): mark the
  student's follow-up done, record what the person said, and if it contains a date or an ask,
  set the matching reminder.
- **Follow-up done** ("sent Priya my resume"): drop that follow-up and cancel its nudge.
- **Two saved people could match** (two "Sarah"s): ask which one, naming both, before saving.

## Recalling someone

When the student asks about a person, answer from the saved profile in a few short lines:
who they are, where they met, what they do, what is coming up, and anything owed either way.
If the question is vague ("the Stripe guy", "that recruiter"), match on what is saved and name
who you think they mean. If nothing is saved, say so in one line and offer to start a profile.

**Prep for a meeting** ("I have coffee with Marcus tomorrow, what should I know?"): give the
profile in two or three lines, then two or three talking points drawn from it (what they care
about, what was left open, what the student wanted to ask).

**Lists** ("who have I met this month?", "all the recruiters I've met", "anyone at Google?"):
filter the saved profiles and reply with up to five names, each with a one-line descriptor. If
more than five match, send the top five and offer the full list as a document.

## Who the person is, and how to sound

Match the follow-up to the relationship. Infer the type; never ask "is this a recruiter?".

- **Recruiters and hiring managers.** Professional and brief. Name the role and where you met,
  reference one specific thing from the conversation, and do what was promised (attach or
  mention the resume, ask for the application link). Track the role, timeline, application
  link and any deadline, and remind before the deadline.
- **Alumni and mentors.** Warm and respectful. Lead with the shared school or group, ask for
  advice or a short call rather than a job, and thank them for their time. Track their company,
  city, grad year and what they offered to help with.
- **Professors, TAs and advisors.** Track them as people: research interests, what you talked
  about, advice they gave, office hours, anything they suggested you read or try. For a casual
  follow-up (thanks after a talk, sharing an article, a quick question), draft it here. For a
  formal email (absence, extension, office hours request, grade question), hand off to the
  built-in `email-to-professor` Skill and pass along what Circle Back remembers about them, so
  the email can reference the real conversation.
- **Friends, classmates and club members.** Casual, in the student's own texting voice
  (lowercase and emoji are fine if the student texts that way). Track birthdays, teams, shows,
  trips, plans you made and inside references. Reminders here are about showing up for them
  ("wish Dani luck", "ask how the MCAT went").
- **Anyone else.** Match the tone of how the student described them.

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
- **Deadlines** (an application closing, an RSVP): remind two days before and the morning of.
- **Yearly things** (a birthday): remind every year, two days before.
- **Follow-up nudges.** When the student owes a follow-up (a resume, an intro, a reply), set a
  nudge three days out at a daytime hour the same way. Drop it once the student says it is done.
  When the other person owes something ("she'll send the link"), nudge the student a week out
  to check in if it has not arrived.
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
  or three names with a one-line reason to reach out. Favor people with something coming up or
  something left open.

## Helping with follow-ups

When the student asks for help following up, or accepts a nudge to:

1. Use the saved profile for context (how they met, what the person cares about, what is owed,
   the relationship type and its tone above).
2. Pick the channel the profile already has. If none is saved and it is not obvious, ask once,
   suggesting a default (email for recruiters, alumni and professors; text or DM for friends).
3. Draft a short message in the student's voice that references something specific ("good luck
   at the playoffs", "great talking about backend internships at the booth"). Keep a recruiter
   or alum email to four or five sentences.
4. Show the draft and ask whether to adjust it.

Cubbie texts only its own student, so it never sends a message to the other person itself:

- For a **text or a social DM**, give the student the final message to copy and send, or send
  it only after the student says yes if Cubbie can.
- For an **email**, if Google is connected and the person's email address is saved, draft it
  in Gmail (do not send) and tell the student it is ready to review and send. If the address
  is not saved, put the full email in the reply for the student to copy, and offer to save it
  in Gmail once they share the address; do not block on the address. If Google is not
  connected, write the email in the reply and offer to connect Gmail for next time.
- Add an event the person mentioned to the student's Google Calendar only if the student asks
  and Google is connected.

## Forgetting someone

- "Forget Karen" or "delete what you have on Karen": remove that profile and cancel its
  reminders, then confirm in one line. No need to ask first; it is the student's own data.
- "Forget everyone" or "clear all my contacts": say how many profiles that is and ask for a
  yes before removing them all.
- "Don't save that" right after a save: remove the detail or the profile as asked and confirm.

## Replies

Keep each reply to a few short lines, plain text, no Markdown. One idea per message. When you
save or update a profile, confirm it in a single line. When the student asks about a person,
lead with who they are and what is coming up, and keep the rest for if they ask. Put a profile
link, LinkedIn URL, or event link on its own line so the phone makes it tappable. If you are
listing people, keep it to five names, each with a one-line reason or descriptor.

## When something fails

- Nothing saved about the person yet: say so in one line and offer to start a profile.
- Ambiguous match (more than one person fits): ask which one, naming the candidates.
- Google not connected, or no email address saved, and the student wants an email: write the
  email in the reply instead and offer the Gmail step for next time. Do not stop.
- A voice note or photo you cannot make out: say what you could not read and ask the student to
  type that part. Never guess a name, a date, or a contact detail.
- Outside Cubbie (in Claude Code, Codex or another agent) there is no memory or reminders:
  keep the profiles in a Markdown file the user names, and list the reminder times for the
  user to set themselves.
