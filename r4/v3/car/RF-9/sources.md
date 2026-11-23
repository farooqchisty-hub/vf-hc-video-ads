# RF-9 v3 sources (text on photo, one man, one week)

Every quote below is reused from a v2 sources.md, where it was copied from the post text returned by a treg tool call (no quote from memory, no new quotes in v3). Each is under 15 words and shown with name, handle and date, plus "Public post on X. Quoted for context, not an endorsement of Headcount AI."

## Quotes

- Slide 8: "…a marketer that can do as much as an agency did before now with agents."
  - Aaron Levie (@levie), CEO of Box, on X, 23 May 2026
  - https://x.com/levie/status/2058223867815227756
  - Full sentence: "The small business that couldn't afford a full marketing agency can hire or contract out to a marketer that can do as much as an agency did before now with agents." Verified by TikHub tweet detail 2c10e537e68748a3bca0ebeb27e9baee; reused from final_v2/carousels/CR-1/sources.md.

## Product facts and real UI

- Product facts: live page https://ecomagents.ai/headcount/ (40 agents in 9 departments plus 2 core, ₹2,999 paid once, 7 bonuses, approvals in Slack or Telegram, "15 minutes to set up", salary table ₹10,20,000 a month for 9 mid-level roles). Fetched headless 24 Nov 2026.
- "About 95% of the work" is the owner's framing (BRIEF-V2.md section 1), written as "about", not a measured statistic.
- Agent message text on phones follows the live showcase runs (https://ecomagents.ai/headcount/assets/data/showcase.json, fetched 24 Nov 2026): ROAS Autopilot (ROAS 3.03 vs target 2.50, ₹5,200 to ₹6,240 a day), Competitor Watch (Kettle & Kin 25% off sitewide, code SLOW25, margin rule caps discounts at 15%), Reddit Buying Signals (3 drafts, 1 venting thread skipped), DM Closer (120 commented, 119 DMs sent, 60 checkout links, 5 bought), AI Visibility Tracker (Claude 19.0%, +8.5 pts), Monday Standup (4 numbers moved, email revenue +45%). Phone text is set 1.18x larger than the site default so it reads on a phone.
- Slide 2 laptop: live hero operator dashboard; slides 3 (Static Ad Factory), 4 (Competitor Watch, Telegram), 6 (ROAS Autopilot), 7 (Monday Standup): live phone markup restaged with showcase text
- Slide 5 funnel (120 commented, 119 DMs sent, 5 bought): live showcase run of DM Closer, fictional brand Brindlewood (rf48v2/cap/mblk/dm-closer-05.png)
- All example runs use the live page's fictional brands and are labelled on the slides. Story captions are fictional narration about a fictional person, not customer results or testimonials.

## Ads shown inside the UI

- slide 3 (hydrated, obvious, sleepshift, radiance): real scroll-stopper ads from our own Winning Statics batches, repo farooqchisty-hub/winning-statics-ads (cloned fresh to car_v3a/ws_ads). Only the example-ad panels with fictional demo brands are used (Lumea, Roasthouse, Rooted, Tundra, Hydra9, Fernwell); crops and source files in car_v3a/ws/crops.json. Tiles with $ prices were left out.

## Generated imagery and the recurring character

- One fictional person, one man through one week (Monday to the next Monday) in one loft. GPT Image 2 (Replicate, openai/gpt-image-2, quality high).
- Character sheet: anchor photo car_v3a/raw/rf9_anchor.png (early 30s, curly hair, short beard, round tortoiseshell glasses, faded navy hoodie, black watch, olive-green phone case, brick-wall loft). Every scene passes that anchor as the reference image and repeats the same written description, phone case and home, so face, hair, outfit, phone and home stay the same across slides.
- Scenes: rf9_call, rf9_sofa_lap, rf9_pov_desk, rf9_kitchen, rf9_sofa_night, rf9_hike, rf9_pov_bed, rf9_feet (prompts in car_v3a/prompts.py). Phone and laptop screens were generated as flat chroma green and keyed; the real UI is mapped onto them (car_v3a/prep.py, build.py).
- Lo-fi by prompt: ordinary phone photo, imperfect framing, grain, real skin texture. No real or famous faces.
