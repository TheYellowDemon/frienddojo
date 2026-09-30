# Friend Dojo

**Status: draft — not submitted.**

- Builder/contact: Kayfabe_eth · https://x.com/kayfabe_eth · theyellowdemon666@gmail.com
- Categories: Character Spotlight; Token Activity
- Source repository: https://github.com/TheYellowDemon/frienddojo
- Public preview: https://frienddojo.vercel.app
- SDK: FriendSDK v0.1.2

Train your Rare Friend with regenerating Awake (T), then see how intelligence, strength, speed and power perform against eight simulated arena rivals. Compare mock RF supporter options for faster recovery, test the preview clock, and preview the future Friend-vs-Friend roadmap.

The game uses the SDK's selected NFT, original character pixels, verified wallet ownership gate and sandbox. Requires a wallet owning a generation-1-or-higher Rare Friends Generations NFT on Robinhood mainnet (4663). On phone, use a compatible wallet's browser.

Tap or click Training, choose 1 or 5 reps, and train a stat. Combat-stat reps cost 10 T and gain the intelligence bonus; all four stats also gain +2% per level above level 1. Intelligence study costs 10/20/30 T across the 1,000/2,500/3,750 caps. Arena fights cost 10 T and award intelligence-scaled XP: the ladder has eight computer rivals from level 1 Rookie through level 25 Dojo Legend, with higher-level wins worth more XP. Recover 5 T every 15 minutes, or every 10 minutes with supporter status; cap 100. Health starts at 90 HP and gains 2 HP per level; strength does not add health. Reloading resets progress. No real-player matchmaking is claimed.

No actual RF transactions or payouts. A separate 10,000 mock RF balance lets players simulate a 620 RF one-day supporter pass (about $1), a 3,100 RF 30-day supporter pass (about $5), and a proposed refundable 10,000 RF character deposit. The deposit is displayed as an anti-spam proposal; character creation/deletion is not implemented. These prices are tunable proposals. T/stats/XP have no monetary or redemption value. The separate Preview Clock tab tests recovery and expiry without waiting. All formulas, the eight-opponent ladder and the unused SDK compatibility definition are disclosed in game/README.md. Artwork is supplied by Rare Friends through FriendSDK; SDK licensing and artwork notices accompany the source.

Build, strict typecheck, SDK validation, engine tests and desktop/mobile browser interaction checks passed. Owner wallet playtest remains pending. Full results: TEST-RESULTS.md.

Known limits: session-only saves and mock RF, device-clock refill, simulated opponents, no real RF integration or live contracts. A supported authenticated persistence bridge and server would be required for durable progression, cross-device saves and competitive PvP. Real RF memberships would require reviewed contract integration.
