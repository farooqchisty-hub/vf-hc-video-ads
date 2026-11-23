# RF-10 v3 sources (text on photo, one woman, one work week)

Every quote below is reused from a v2 sources.md, where it was copied from the post text returned by a treg tool call (no quote from memory, no new quotes in v3). Each is under 15 words and shown with name, handle and date, plus "Public post on X. Quoted for context, not an endorsement of Headcount AI."

## Quotes

- Slide 8: "Our marketing team is just me and ~40 AI agents."
  - Jacob Bank (@jebank), startup founder, now VP Product, Google Chrome (X bio), on X, 24 May 2025
  - https://x.com/jebank/status/1926330014640877886
  - Quoted whole. Verified by TikHub tweet detail 3de2eef6f44b457e9007b57c83079e8e and profile 4f8ec2e9f5304997ab06d7840c29a95d; reused from final_v2/carousels/CR-3/sources.md.

## Product facts and real UI

- Product facts: live page https://ecomagents.ai/headcount/ (40 agents in 9 departments plus 2 core, ₹2,999 paid once, 7 bonuses, approvals in Slack or Telegram, "15 minutes to set up", salary table ₹10,20,000 a month for 9 mid-level roles). Fetched headless 24 Nov 2026.
- "About 95% of the work" is the owner's framing (BRIEF-V2.md section 1), written as "about", not a measured statistic.
- Agent message text on phones follows the live showcase runs (https://ecomagents.ai/headcount/assets/data/showcase.json, fetched 24 Nov 2026): ROAS Autopilot (ROAS 3.03 vs target 2.50, ₹5,200 to ₹6,240 a day), Competitor Watch (Kettle & Kin 25% off sitewide, code SLOW25, margin rule caps discounts at 15%), Reddit Buying Signals (3 drafts, 1 venting thread skipped), DM Closer (120 commented, 119 DMs sent, 60 checkout links, 5 bought), AI Visibility Tracker (Claude 19.0%, +8.5 pts), Monday Standup (4 numbers moved, email revenue +45%). Phone text is set 1.18x larger than the site default so it reads on a phone.
- Slides 2 and 8 laptop: live hero operator dashboard; slides 3 (Static Ad Factory), 4 (Competitor Watch), 6 (DM Closer): live phone markup restaged with showcase text
- Slide 5 AI share of voice (ChatGPT 20.6% vs rival 26.5%, Claude +8.5 pts): live showcase run of AI Visibility Tracker, fictional brand Trailhen
- All example runs use the live page's fictional brands and are labelled on the slides. Story captions are fictional narration about a fictional person, not customer results or testimonials.

## Ads shown inside the UI

- slide 3 (coffee, cold24, fuller, hydrated): real scroll-stopper ads from our own Winning Statics batches, repo farooqchisty-hub/winning-statics-ads (cloned fresh to car_v3a/ws_ads). Only the example-ad panels with fictional demo brands are used (Lumea, Roasthouse, Rooted, Tundra, Hydra9, Fernwell); crops and source files in car_v3a/ws/crops.json. Tiles with $ prices were left out.

## Generated imagery and the recurring character

- One fictional person, one woman through one work week in one office. GPT Image 2 (Replicate, openai/gpt-image-2, quality high).
- Character sheet: anchor photo car_v3a/raw/rf10_anchor.png (early 30s, short natural coily hair, gold hoops, mustard cardigan over a white t-shirt, gold watch, lilac phone case, plant-filled open office with pegboard). Every scene passes that anchor as the reference image and repeats the same written description, phone case and home, so face, hair, outfit, phone and home stay the same across slides.
- Scenes: rf10_cover, rf10_shoulder, rf10_pov_table, rf10_pov_coffee, rf10_laugh, rf10_pov_lift, rf10_leave, rf10_desk_empty, rf10_arms (prompts in car_v3a/prompts.py). Phone and laptop screens were generated as flat chroma green and keyed; the real UI is mapped onto them (car_v3a/prep.py, build.py).
- Lo-fi by prompt: ordinary phone photo, imperfect framing, grain, real skin texture. No real or famous faces.
