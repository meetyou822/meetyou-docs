---
title: Privacy Policy
---

> **⚠️ Two things before this can be treated as final.**
>
> 1. **Have a lawyer read it.** This was drafted from the engineering record in
>    `PRIVACY_NOTES.md` — it is accurate about what the software does, which is
>    the hard part, but that is not the same as being legally sound.
> 2. **The SMTP provider that will eventually replace Supabase's built-in
>    mailer isn't chosen yet.** Once it is, it receives every new user's email
>    address and must be added to section 5 as a named sub-processor.
>
> Nothing here checks a user's age — this document still promises the service
> is for people 16 and over, which the app does not enforce. That's a known,
> separately-tracked gap (see `TODO.md` items 5 and 10F), not something this
> revision changes.

**Last updated:** 19 August 2026

## 1. Who is responsible for your data

MeetYou ("the app") is operated by **Ádám Komzsík and Daniel Kolař** ("we",
"us"), who are the joint data controllers for the purposes of the General
Data Protection Regulation.

- **Email:** meetyou.acc1@gmail.com

Every request described in this policy — a copy of your data, a correction, a
deletion, a photo takedown — goes to that email address.

## 2. What we collect

**When you create an account.** Your email address, and a display name and
profile photo. If you sign in with Google, the name and photo come from your
Google account; if you sign up with an email address, the sign-up form asks you
for a display name, and if you don't give one it starts as "MeetYou Member" —
never your email address. You can change both at any time in the app.

**When you use the app.**

- Which events you join or put yourself on the waitlist for, and when.
- Ratings and written feedback you leave after an event.
- Photographs you upload to an event you organize.
- Reports you file about an event, a person or a photo, including anything you
  write in them.
- A request to become an organizer, if you make one, including the optional
  message you write.
- Your notification preferences.

**What we do not collect.** We want to be specific about this, because the
absence is deliberate:

- **No location data.** An event's location is text typed by its organizer. The
  app never asks for or records your device's location.
- **No analytics, no tracking, no advertising identifiers.** There is no
  analytics SDK in the app of any kind.
- **No payment details, no contacts, no calendar, no address book.**

## 3. Why we use it, and on what legal basis

| What | Why | Basis |
|---|---|---|
| Account, display name, photo | To give you an identity other members can recognise | Performance of a contract |
| Event participation | To run the events you sign up for and show organizers who is coming | Performance of a contract |
| Ratings and feedback | To let organizers improve their events | Legitimate interests |
| Event photographs | To show what an event was like | Legitimate interests — see section 6 |
| Reports | To keep the service safe | Legitimate interests |
| Notifications | To tell you about events and changes | Consent, withdrawable in the app at any time |

## 4. Who can see what

Access is enforced by the database itself, not just by what the app chooses to
show you.

| Data | Who can see it |
|---|---|
| Your profile | You, and the operator |
| Your name and photo, as an organizer | Every signed-in member, on the events you run |
| Your name and photo, as a participant | The organizer of the events you joined, and the operator |
| Events, and how many people joined | Every signed-in member |
| Your ratings and written feedback | You, the organizer of that event, and the operator |
| Event photographs | Every signed-in member |
| Reports you file | **The operator only** |
| Your organizer request | You and the operator |
| Anything at all, when signed out | Nothing |

Two things worth stating plainly:

- **The operator can see everything.** That includes your profile, your email
  address, every rating and comment you write, and every report. This is
  necessary to run and moderate the service.
- **Becoming an organizer is public.** If you run events, your display name and
  profile photo are shown to every signed-in member on each event you organize.

**Profile photos you upload require sign-in to view.** They are served through
short-lived, signed web addresses that only work for a signed-in member and
expire after an hour. Two qualifications worth stating plainly: if you sign in
with Google, your profile photo is the one from your Google account, and that
stays hosted on Google's own servers — this app cannot make it private. And a
photo that has recently been viewed can remain briefly reachable at our hosting
provider's network cache for up to an hour after upload, even after this
protection takes effect.

## 5. Who else receives your data

We use four other companies. We do not sell your data to anyone, and none of
these use it for their own purposes.

| Who | What they receive | Why |
|---|---|---|
| **Supabase** | Everything described above | They host the database, the files and the servers |
| **Google** | The fact that you signed in, if you use Google sign-in | To sign you in |
| **OneSignal** | A random identifier for your account, and the text of notifications | To deliver push notifications |
| **Google (Firebase Cloud Messaging)** | Your device's push token and delivery information | Every Android push notification travels through Google |
| **Apple (APNs)** | The same, on iPhones | Every iPhone push notification travels through Apple |

**Your data is stored in the European Union**, in Frankfurt, Germany. This was
chosen deliberately when the service was set up.

The identifier given to OneSignal is a random one generated by our database. It
is not your name or your email address.

The app's fonts are included in the app itself and are not downloaded while you
use it, so no font provider learns anything about you.

## 6. Photographs

This is the most sensitive thing the app holds, so it gets its own section.

Only the organizer of an event can add photographs to it. Once added, they are
visible to every signed-in member — not only to the people who attended.

**A photograph is personal data of everyone in it, not just the person who took
it.** If you appear in a photograph on MeetYou:

- You can report it from inside the app. Every photo has a flag icon; choose
  "I appear in this photo" and it goes straight to the operator.
- Or write to meetyou.acc1@gmail.com.

We will review it and remove the photograph if you ask us to. A reported photo
stays visible until it has been reviewed.

If you would rather not appear in photographs at all, tell the event's organizer
before the event.

## 7. How long we keep it

**Until you delete it.** We do not currently delete anything on a schedule.
Events, ratings, photographs and reports stay until the account or the event
they belong to is deleted.

**When you delete your account** (Settings → Delete Account), we delete your
profile, your event participation, your ratings and comments, your reports, your
profile photo and the photographs you uploaded. If you organized events, **those
events are deleted as well**, along with their photographs and the ratings other
people left on them; anyone who had signed up is notified that the event is
cancelled.

Account deletion is immediate and cannot be undone.

## 8. Your rights

Under the GDPR you have the right to:

- **get a copy** of the data we hold about you;
- **correct** anything that is wrong — most of it you can edit in the app;
- **delete** your account and your data, which you can do yourself at any time;
- **object to** or **restrict** how we use your data;
- **complain** to a data protection authority if you think we have got it wrong.

To exercise any of these, write to meetyou.acc1@gmail.com. We will respond
within one month. There is no automated export in the app yet, so a copy of
your data is assembled by hand when you ask for it.

## 9. Reports and moderation

If you report someone or something, that report goes only to the operator. You
will not be told what was decided, and you cannot read your own report back.
This is deliberate: it stops reports being used to work out who has been
reported. Reports are kept indefinitely, including the fact that you filed them.

Accounts can be disabled by the operator. A disabled account can still sign in
and see that it has been disabled, but cannot join events or take part.

## 10. Age

MeetYou is for people aged **16 and over**. If you are under 16, please do not
create an account.

## 11. Notifications

Push notifications are optional and controlled by two switches in the app. Both
can be turned off at any time, and the setting is applied on our servers when
the recipients are chosen — so turning it off takes effect immediately rather
than at your next launch.

Some notifications are not covered by those switches because they are about your
own account rather than about event traffic: being told that an event you signed
up for has been cancelled, or that your organizer request was approved.

## 12. Changes

If this policy changes, the date at the top changes with it. If a change is
significant, we will say so in the app.

## 13. Contact

Ádám Komzsík and Daniel Kolař
meetyou.acc1@gmail.com
