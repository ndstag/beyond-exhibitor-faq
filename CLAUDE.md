# Instructions for AI assistants

This repo is a public website. Every push to `main` publishes to https://exhibitors.beyondconference.com/faq within about a minute.

## Rules
1. **Edit only `site/index.html`.** It's one self-contained file with inline CSS and JS. No build step or frameworks; keep it that way. Don't touch `netlify.toml` unless asked.
2. **Pull before editing:** `git pull` first, so you're working on the latest version.
3. **Never push without a clear yes.** Show what changed and ask first. A push is a public release.
4. **One push per batch of edits.** Group changes together and don't push experiments.
5. **Everything here is public,** including this repo. No internal notes, private pricing, personal contact details, or keys.
6. **Keep the page structure** so search, the topic list and Expand all keep working:
   - topic: `<section class="group" id="kebab-id"><h2>Title</h2> … </section>`
   - question: `<details><summary>Question?</summary><div class="a"><p>Answer.</p></div></details>`
   - key dates: `<li>` items in `<ol class="timeline">`
7. **Don't change facts on your own.** Only change dates, rates, deadlines or policies when the person gives you the new information.
8. **Images:** only the existing logo (`.../2026/01/logo.webp`) and icon (`.../2026/02/hexagon.png`) from beyondconference.com. Other images there may show past-year dates or sponsors.
9. **Before committing,** check that opening and closing tags still match (`div`, `section`, `details`, `table`).
10. **Commit messages:** plain English, e.g. "Update shipping deadline to May 14".

## If the site didn't update
Wait a minute and hard-refresh. If it still hasn't changed, tell the person to ask the site owner to check the hosting deploy log.
