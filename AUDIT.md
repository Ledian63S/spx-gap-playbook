# Course audit — Oct 3, 2026

Every rule, quote, table row and quiz answer in `course/index.html` was checked against three sources:
her written lessons (`research/lesson-text/`, with the lesson images), all 29 stream transcripts
(`research/stream-transcripts/`), and about 1,100 of her X posts (Nov 2025 – Oct 2026).

**Verdict:** the core of the course was right: the level math, the OTE zone, Playbooks A–D targets and
stops, the order-block 50% rule, and entering on the next candle. But several rules were taught too
rigidly or wrong, some quotes were misdated, and a few table rows were wrong. All of the fixes below are
now in the course. Where her sources disagree, the course has a new reference page,
"Where her sources disagree".

## Rule corrections

| Topic | Before | Now | Source |
|---|---|---|---|
| Liquidity window | Mixed "15 min", "15–30 min", "by 10:00" | One rule: taken 9:30–10:00 → B, not taken by 10:00 → A | Sep 25: "since July… extend time to 30 minutes" |
| Waiting for 10:00 | "Since July she waits until 10:00"; "watch, don't trade 9:30–10:00" | Waiting only confirms "not taken". B and C can trigger earlier. She entered before 10:00 on about half of the days | Streams; lesson charts enter at 9:44–9:56 |
| 10:00 AM open | Only in the checklist | Taught in step 6: longs only after a 2-minute body close above it, shorts below; a filter, not an entry; not the stop | 10 AM Open lesson; Sep 17 |
| Order block | "The first candle… not the whole run" | The whole run of opposite candles, starting with the first candle that touched the level; use bodies if wicks are long | Order Block lesson; model video |
| Near-miss at 25% | "One tick short = no trade" | Full size only inside the zone; a near-miss with a strong signal is a B setup (half size or skip) | Lesson: "doesn't need perfection"; Sep 16 vs Sep 17 / Oct 2 |
| Gap under 10 | "No trade" | No A/B; Playbook C or an old gap at small size; most of her losses come on no-gap days | Sep 2, Aug 27 |
| Decoupled ES/NQ | "Stay out" | No funded accounts: half size on a practice account; C does not need NQ | Sep 15, Sep 10 |
| Playbook C | Enter on the close; "nine of 10" stated as fact | Enter on the close or on the 70.5% retest; stop depends on gap size; 50% must hold; first profit at ~1R; "nine of 10" is her impression | OTE lesson; Sep 18; Aug 28 |
| Playbook D | No precondition | Needs the higher-timeframe objective still open; flip rule at 25% | Lesson; Aug 26/28 |
| Old gaps | Only for gaps under 10; "70.5% is where the idea is wrong" | Used daily: 25% and OTE give reactions, and their levels are targets | Lesson; X posts |
| Indicator setup | "Invert anchors if reversed"; 4:08 close unexplained | Invert anchors ON; session end 16:08; confirmation timeframe 2 min | Indicator page; Sep 2 |
| Bias from the opens | Above or below = bias | Only after a close beyond the open, with price staying away | PO3 lesson |
| Break-even | Never before a partial | Same, except when NQ clearly turns against the trade | Streams |
| Average R | "Almost never go for 2R" (not found) | 1.3R because she always takes a partial at ~1R on prop accounts | Sep 3 |
| Checklist | NQ and 10 AM open in one box | Split; only a missing NQ check allows half size | 10 AM lesson |

## Fact corrections

- **Sep 24 example:** about +1.4R, not +1.8R ($500 on $350 risk). It was an OTE reaction with no sweep, not "Playbook B". The final exit was at the 9:30 open. Video segment changed to 1:04–2:06.
- **Sep 17 example:** buy 2 was at about 11:41, not 11:11, and she finished around 12:10. Neither entry was inside 25–50% (both were B-grade).
- **Aug 24 loss:** she did not sell "above the 10 AM open". She shorted on a day the model said buy (the low had been swept first).
- **Session table:**
  - Aug 28: +$313 realised (the +$700 was open profit).
  - Sep 3: a gap up, not down.
  - Sep 4: a gap of ~20 that filled at the open, ~+$500.
  - Sep 21: off-model.
  - Sep 22: a Playbook C trade.
  - Sep 25: ~+$500.
  - Sep 30: delayed delivery.
  - Oct 2: +$530 per account.
- **Win rate:** added her own caveats: "less than 70%, more than 65" (Oct 2), "I don't even have 65%" (Sep 17).
- **Removed or replaced quotes** that could not be found in any source: "chop session", "trend day I cannot win", "almost never go for 2R", "Most biggest losses happens on Friday", and "Rule number one. Sometimes you're going to miss the trade".
- **Not the same model:** her "2-minute OHLC" video (71%, fixed 2R) and her 65–68% X stats are for other models. They are kept out of the gap model.

## Site changes

- Phone layout:
  - a fixed Back/Next bar;
  - a theme toggle;
  - diagrams redrawn for narrow screens instead of scrolling sideways;
  - larger tap targets.
- Tap any chart to open it full screen and zoom.
- Theme choice is remembered. Arrow keys move between steps.
- New reference pages: **Cheat sheet** and **Where her sources disagree**.
- New lesson images: the order-block run, order block on candle bodies, Playbook B with both trades, and the Jul 23 overlap gap.
- Proper page title and description, a `noindex` tag (search engines skip it), and a GitHub Pages entry point at the repo root.
