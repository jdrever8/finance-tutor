# Personal Advisor — how to use

Open this repo in claude.ai/code and just ask. The lead advisor reads `CLAUDE.md` automatically.

**Keep this repository PRIVATE** (GitHub → Settings → General → Danger Zone → Change visibility). Use rounded figures only.

## Advise (most of the time)
Just ask your question in plain English, for example:
> Should I put my spare £300 a month into my ISA or extra NHS pension?

> My fixed rate ends in March. What should I do?

> Is this email from "HMRC" a scam?

The advisor checks `my-situation.md`, asks a few quick questions if needed, pulls in specialists, and gives a recommendation with next steps. Big decisions are logged in `decisions-log.md`.

End with "commit and push to main" if you want anything saved.

## First: fill in your situation (one session, ~20 minutes)
> Read CLAUDE.md. Have the fact-finder go through my-situation.md with me, one question at a time, starting with what matters most for retirement planning. Update the file with rounded figures and add any actions to action-list.md. Commit and push to main.

## Review (yearly, at tax-year end, or after a life change)
> Read CLAUDE.md, my-situation.md, decisions-log.md and action-list.md. Run an annual review: update my situation with the fact-finder, check each area with the relevant specialists, have second-opinion check the recommendations, and give me a short prioritised plan. Update action-list.md, have the progress-tracker log the session, then commit and push to main.

## Learn (when you want to understand a topic properly)
> Read CLAUDE.md, learner-profile.md, review-schedule.md and the latest session-log.md entry. Run a Learn session: review what's due, teach the NEXT topic, practice questions, teach-back with the challenger, then marking. Have the fact-checker check any new lesson or question set before I rely on it. Finish with the progress-tracker and review-scheduler. Commit and push to main.

## Tips
- Answer in your own words and say "don't know" freely.
- Short and often beats long and rare.
- To add a document (e.g. a pension statement with personal details removed): upload it to `library/`, then say "Have the librarian process the new material in library/."
- This is AI guidance, not regulated financial advice. For pension transfers, wills, powers of attorney and complex tax, the advisor will tell you who to see.
