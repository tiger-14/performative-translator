# Performative Translator
A web app that takes your input and translates it into the dramatic performative voice of LinkedIn, Discord, or Reddit, complete with fake likes, comments, upvotes, and replies. This was created in April 2026.
## Try it
- Open the file directly — see Quick Start below.
## Quick Start
1. Open `finalhackathon.html` in your browser.
2. Type any sentence into the box (e.g. "I lost my keys today").
3. Pick a platform — LinkedIn, Discord, or Reddit.
4. Hit **Translate** and watch your sentence become a full, dramatized fake post.
## Features
- **LinkedIn mode**
- **Discord mode**
- **Reddit mode**
- **Interactive fake engagement** — every generated post has working buttons: like, upvote/downvote, reply, award, and copy-to-clipboard
- **Feed history** — every translation you generate turns into a scrollable feed, so you can compare different versions side by side
## How it works
The entire app is a single self-contained HTML file with inline CSS and JavaScript. When you submit text, `detectIntent()` scans it for keywords to loosely classify it as a failure, success, insight, career, or general story. `applyWordMap()` then swaps in more dramatic word choices. From there, one of three builder functions — `buildLinkedIn()`, `buildDiscord()`, or `buildReddit()` — assembles the final post by randomly selecting from large pools of prewritten hooks, bridges, reflections, usernames, avatars, and hashtag sets, so no two translations look similar. Each rendered post is created with likes, votes, replies, and comments, making the fake post fully clickable and interactive.
## Prompt
Built in response to Hack Club's South Hacks 2026 hackathon prompt: Build something that works, but isn't actually useful — "brilliantly useless." The goal was to make it fun, weird, or entertaining rather than practical.
## Built with
- HTML / CSS / JavaScript (single file, zero dependencies)
## Credits
Built with three other teammates during South Hacks 2026, a Hack Club hackathon hosted by South Forsyth High School, April 25, 2026. Awarded Most Creative Project.
