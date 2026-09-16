# Threshold — prototype

A quiet, human-backed platform for people in the West who feel there must be a God, for those at the threshold of Islam, and for new Muslims taking their first steps.

This is a **clickable prototype** for review by the companions (du'at). Nothing here is final; the aim is to test the shape of the experience, not the content.

## What's in it
- **Start** — five statements; each opens a short reading path. "God is near" is fully written; the other four are drafts.
- **Questions** — a searchable library (on-device search, no server) plus a "didn't find it" box that goes to a human companion.
- **First steps** — a gradual lessons list for new Muslims; later steps unlock when the companion opens them.
- **Qur'an** — Arabic + plain rendering + one line of context. Al-Fatihah, al-Ikhlas, and al-Furqan 63–64 as samples.
- **Companion** — the human behind every account.
- **Companion dashboard** (open from the Companion tab → “Team view”) — a working prototype: your people with stage, last contact and open questions; a “needs attention” list (quiet for 7+ days, open questions, overdue next step); add a person (they get an invite code); a page per person with stage stepper, next step, contact log, questions (answer / suggest for library), stage-specific needs checklist, milestones, which first-steps lessons they can see, private notes and a timeline; and a Team & admin view with companions, unanswered questions across the team, questions people couldn’t find, and stage counts. Sample data is stored on this device only; “Reset sample data” restores it.

## Design decisions already made
- English first; content lives in one object per language (`CONTENT.en`) — a new language is a copy, translated, with `dir` set.
- Companions are a closed group added by the administrator only; people join with an invite code from their companion.
- No paid AI inside the product. Search, guided question trees, and a human companion replace it.
- Progress is stored on the device only in this prototype.

## Run it
Open `index.html` in a browser, or serve the folder (any static host).

## Feedback we're asking companions for
1. Do the five opening statements match the people you actually meet?
2. What would you cut from "God is near"? What's missing?
3. Which recurring questions should be in the library from day one?
4. What do you need on the dashboard that isn't there?
