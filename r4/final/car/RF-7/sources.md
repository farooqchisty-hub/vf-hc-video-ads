# RF-7 v2 sources (magazine cover)

Every quote below was checked against the original X post through treg (`tikhub.x.twitter-web-fetch-tweet-detail`, status active, 23 Nov 2026) after being found with `treg.x.search.posts`. Each is under 15 words and shown with name, handle and date. No quote is invented; slides say "Public post on X. Quoted for context, not an endorsement of Headcount AI."

## Quotes

- Slide 2: "We’ve moved from AI assistants → AI agents → AI employees." (9 words)
  - Kieran Flanagan (@searchbrat), marketing leader at Zapier and HubSpot (X bio: "CMO, SVP for brands like Zapier, HubSpot"), posted on X 16 Sep 2026
  - https://x.com/searchbrat/status/2100222860962763156
  - Quoted whole, arrows as in the post.
- Slide 3: "The most AI-pilled ones are running 20+ agents" (8 words)
  - Brian Halligan (@bhalligan), co-founder of HubSpot (X bio), posted on X 7 May 2026
  - https://x.com/bhalligan/status/2052498617563566382
  - About the CEOs he interviewed on their personal AI stacks; sentence continues "that basically run their entire day".
- Slide 4: "a wide layer of agents underneath running support, sales, research, marketing, ops" (12 words)
  - Greg Isenberg (@gregisenberg), CEO of Late Checkout, posted on X 9 Aug 2026
  - https://x.com/gregisenberg/status/2086459363842048422
  - From "The new org chart probably looks something like this"; 12 words, shown with a leading ellipsis.
- Slide 8: "Nobody ever wanted software. They wanted the work done." (9 words)
  - David Cancel (@dcancel), founder of Drift, posted on X 16 Nov 2026
  - https://x.com/dcancel/status/2122374380919345413
  - Role checked: https://en.wikipedia.org/wiki/David_Cancel and https://www.linkedin.com/in/dcancel (founder and CEO of Drift).

## Product facts and real UI

- Product facts: live page https://ecomagents.ai/headcount/ (40 agents in 9 departments plus 2 core, ₹2,999 paid once, 7 bonuses, Slack or Telegram approvals, 15 minutes to set up, salary table ₹10,20,000 a month for 9 mid-level roles).
- "About 95% of the work" is the owner's framing (BRIEF-V2.md section 1), written as "about", not a measured statistic.
- Dashboard (slides 5 and 9): live hero dashboard; Telegram approval (slide 6): live hero phone
- Salary table (slide 7): live salary section
- Department names and agent counts (slide 4): assets/data/agents.json on the live site
- All example runs use the fictional brands of the live page (Dewfield, Brightbin, Brindlewood, Fernhollow, Kettle & Kin, Moonbrew) and are labelled on the slides.
- Captures: headless Chromium, element screenshots at 3x to 4x of the live page, desktop and phone width, 23 Nov 2026 (scripts rf48v2/capture*.mjs). Crops are tight so the UI text reads at phone size; nothing in the UI is edited.

## Generated imagery

- GPT Image 2 (Replicate) photos and cut-outs; people are original and general, international casting, no real or famous faces. Prompts: rf48v2/prompts.py.
