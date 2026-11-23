# CR-1 v3 sources (spy on your rivals (cobalt editorial))

Every quote below is reused from a v2 sources.md, where it was copied from the post text returned by a treg tool call (no quote from memory, no new quotes in v3). Each is under 15 words and shown with name, handle and date, plus "Public post on X. Quoted for context, not an endorsement of Headcount AI."

## Quotes

- Slide 9: "People will manage teams of agents to do very complex things."
  - Sam Altman (@sama), CEO of OpenAI, on X, 5 Feb 2026
  - https://x.com/sama/status/2019441198734209374
  - Full context: "The companies that succeed in the future are going to make very heavy use of AI. People will manage teams of agents to do very complex things." Verified by TikHub tweet detail 1a818b04c47b4c89b0360cce50dbbee6; reused from final_v2/carousels/CR-3/sources.md.

## Product facts and real UI

- Product facts: live page https://ecomagents.ai/headcount/ (40 agents in 9 departments plus 2 core, ₹2,999 paid once, 7 bonuses, approvals in Slack or Telegram, "15 minutes to set up", salary table ₹10,20,000 a month for 9 mid-level roles). Fetched headless 24 Nov 2026.
- "About 95% of the work" is the owner's framing (BRIEF-V2.md section 1), written as "about", not a measured statistic.
- Agent message text on phones follows the live showcase runs (https://ecomagents.ai/headcount/assets/data/showcase.json, fetched 24 Nov 2026): ROAS Autopilot (ROAS 3.03 vs target 2.50, ₹5,200 to ₹6,240 a day), Competitor Watch (Kettle & Kin 25% off sitewide, code SLOW25, margin rule caps discounts at 15%), Reddit Buying Signals (3 drafts, 1 venting thread skipped), DM Closer (120 commented, 119 DMs sent, 60 checkout links, 5 bought), AI Visibility Tracker (Claude 19.0%, +8.5 pts), Monday Standup (4 numbers moved, email revenue +45%). Phone text is set 1.18x larger than the site default so it reads on a phone.
- Slide 2 dashboard: live hero operator dashboard; slide 3 alerts and slide 5 share of voice: live showcase runs of Competitor Watch (Kettle & Kin, Moonbrew vs Fernhollow) and AI Visibility Tracker (Trailhen); slide 6: Reddit Buying Signals (Brightbin); slide 7 Telegram: live phone markup restaged with the Competitor Watch showcase text
- "4 of them only watch your rivals": Competitor Watch, Winner Remixer ("fresh creative from proven winners, yours and competitors' long-running ads"), AI Visibility Tracker, Reddit Buying Signals, per the live roster (assets/data/agents.json)
- All example runs use the live page's fictional brands and are labelled on the slides. Story captions are fictional narration about a fictional person, not customer results or testimonials.

## Ads shown inside the UI

- slide 4 (sleepshift as "their winner", radiance as "your remix", both breaking-news formats) and slide 8 (hydrated, radiance, coffee, fuller, cold24, obvious): real scroll-stopper ads from our own Winning Statics batches, repo farooqchisty-hub/winning-statics-ads (cloned fresh to car_v3a/ws_ads). Only the example-ad panels with fictional demo brands are used (Lumea, Roasthouse, Rooted, Tundra, Hydra9, Fernwell); crops and source files in car_v3a/ws/crops.json. Tiles with $ prices were left out.

## Generated imagery

- Cover: GPT Image 2 lo-fi on-camera-flash photo of a stakeout gag (car_v3a/raw/cr1_stakeout2.png, prompt in car_v3a/prompts.py). Fictional person, no logos or text.
