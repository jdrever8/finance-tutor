# Finance Tutor — how to use

## Setup (once)
1. Create a new PRIVATE GitHub repository, e.g. `finance-tutor`.
2. Upload the CONTENTS of this folder to the top level of the repo (not the folder itself).
3. In claude.ai/code, select the repo and run the prompt in SETUP-PROMPT.md.
4. Start a new session.

## First session: diagnostic
> Read CLAUDE.md and learner-profile.md. Act as the lead tutor. Use the assessor to run a diagnostic across both tracks, one question at a time, about 15 questions in total. Then have the curriculum-designer adjust both curriculum files and mark the NEXT topic for each. Update learner-profile.md, have the progress-tracker log the session, then commit and push to main.

## Normal sessions
> Read CLAUDE.md, learner-profile.md, review-schedule.md and the latest session-log.md entry. Act as the lead tutor and run a standard session on Track [A or B]: review what's due, teach the NEXT topic, practice questions, teach-back with the challenger, then marking. Have the fact-checker check any new lesson or question set before I rely on it. Finish with the progress-tracker and review-scheduler. Commit and push to main.

## Tips
- Alternate tracks, or do A twice a week and B once.
- Answer in your own words, even if unsure. Wrong answers teach the system what to fix.
- Short and often beats long and rare.
- To add a book or document: upload it to library/, then start a session with "Have the librarian process the new material in library/."
- Keep personal figures rounded or hypothetical, as the repo is on GitHub.
