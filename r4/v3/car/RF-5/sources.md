# RF-5 v3 sources (text on photo, one woman, one day)

Every quote below is reused from a v2 sources.md, where it was copied from the post text returned by a treg tool call (no quote from memory, no new quotes in v3). Each is under 15 words and shown with name, handle and date, plus "Public post on X. Quoted for context, not an endorsement of Headcount AI."

## Quotes

- Slide 8: "…basically gives every small business a night shift"
  - Greg Isenberg (@gregisenberg), CEO of Late Checkout, on X, 9 Nov 2026
  - https://x.com/gregisenberg/status/2119889516152414518
  - Said of an AI model that "can work 10-12 hours on its own". Verified 23 Nov 2026 with treg (tikhub.x.twitter-web-fetch-tweet-detail); reused from final_v2/carousels/RF-5/sources.md.

## Product facts and real UI

- Product facts: live page https://ecomagents.ai/headcount/ (40 agents in 9 departments plus 2 core, ₹2,999 paid once, 7 bonuses, approvals in Slack or Telegram, "15 minutes to set up", salary table ₹10,20,000 a month for 9 mid-level roles). Fetched headless 24 Nov 2026.
- "About 95% of the work" is the owner's framing (BRIEF-V2.md section 1), written as "about", not a measured statistic.
- Agent message text on phones follows the live showcase runs (https://ecomagents.ai/headcount/assets/data/showcase.json, fetched 24 Nov 2026): ROAS Autopilot (ROAS 3.03 vs target 2.50, ₹5,200 to ₹6,240 a day), Competitor Watch (Kettle & Kin 25% off sitewide, code SLOW25, margin rule caps discounts at 15%), Reddit Buying Signals (3 drafts, 1 venting thread skipped), DM Closer (120 commented, 119 DMs sent, 60 checkout links, 5 bought), AI Visibility Tracker (Claude 19.0%, +8.5 pts), Monday Standup (4 numbers moved, email revenue +45%). Phone text is set 1.18x larger than the site default so it reads on a phone.
- Slide 2 and 7, laptop: the live hero operator dashboard (car_v2/ui/lab_dash.png, the site's own markup and CSS); slide 7 sticker "Agents running 12/42, 21 done today": live hero dashboard capture rf48v2/cap/ds-1.png
- Slide 3 Slack (ROAS Autopilot, move ₹5,200 to ₹6,240 a day, the ₹1,040 a day in the caption), slide 4 Slack (Static Ad Factory), slide 5 Telegram (Competitor Watch): the live site's phone markup and CSS restaged with the live showcase text (lab/build_lab.py, shot headless to ui/)
- Slide 6 Reddit thread: live showcase run of Reddit Buying Signals (rf48v2/cap/mblk/reddit-buying-signals-05.png), fictional brand Brightbin, disclosed replies
- All example runs use the live page's fictional brands and are labelled on the slides. Story captions are fictional narration about a fictional person, not customer results or testimonials.

## Ads shown inside the UI

- slide 4 (radiance, coffee, fuller, cold24): real scroll-stopper ads from our own Winning Statics batches, repo farooqchisty-hub/winning-statics-ads (cloned fresh to car_v3a/ws_ads). Only the example-ad panels with fictional demo brands are used (Lumea, Roasthouse, Rooted, Tundra, Hydra9, Fernwell); crops and source files in car_v3a/ws/crops.json. Tiles with $ prices were left out.

## Generated imagery and the recurring character

- One fictional person, one woman through one day (6:58 AM to 11:02 PM) in one flat. GPT Image 2 (Replicate, openai/gpt-image-2, quality high).
- Character sheet: anchor photo car_v3a/raw/rf5_anchor.png (late 20s, freckles, copper-auburn hair, gold hoops and ring, coral-pink phone case, white flat with monstera and sage-green kitchen tiles). Every scene passes that anchor as the reference image and repeats the same written description, phone case and home, so face, hair, outfit, phone and home stay the same across slides.
- Scenes: rf5_bed, rf5_kitchen_lap, rf5_pov_kitchen, rf5_cafe, rf5_pov_street, rf5_sofa, rf5_desk, rf5_night, rf5_bed_night (prompts in car_v3a/prompts.py). Phone and laptop screens were generated as flat chroma green and keyed; the real UI is mapped onto them (car_v3a/prep.py, build.py).
- Lo-fi by prompt: ordinary phone photo, imperfect framing, grain, real skin texture. No real or famous faces.
