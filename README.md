# The Long View: the record

## What this is

Every call The Long View's engine makes is written here, dated and fingerprinted before its outcome is known. Each day's files are hashed together and the hash is published, so a reader can check that nothing was changed after the fact. Nothing is edited afterwards except by a listed correction, which is added as a new line and never rewrites the old one.

## How to read it

A call is a dated statement that something will happen by a given date, with a probability attached and a condition that would close it early. The probability means what it says: of the calls we make at 70%, about seven in ten should happen. So a miss at 70% is expected about three times in ten, and a single miss or a single hit proves very little on its own. What matters is whether, over many calls, the ones we made at 70% came true about 70% of the time.

A call is scored hit when the stated outcome occurred and the position gained; partial when it occurred in part; miss when neither. The number of closed calls is still small: five have closed as of 18 November 2026, so none of the figures below says much yet about whether the engine is good at this. We publish them anyway, from the start, because a record that begins only once it looks good is not a record.

The paper book is a model portfolio with no real money in it. It is mostly cash by rule, it enters each call at the first price a reader could have traded at after the call was public, and it is kept only to test the calls against a benchmark. It is not a product and not a recommendation. Nothing on this page is investment advice.

## Where things stand

As of 19 November 2026: fourteen calls made since 21 October 2026; six closed (one hit, two partials, three misses); eight open, of which four are entered at full size, one is waiting on a dated condition, and three are scenarios the engine follows at reduced or no size because its own probability fell short of its publication line (one of them, proposed today, enters tomorrow). How close our probabilities were to what happened (the Brier score) is 0.205 on the six closed calls, a figure that becomes meaningful only after thirty.

Branch notes and expectations scored: one (the 7 November issue's expectation on China's rare-earth suspension; the other branch happened on 9 November).

Private-markets calls: one made (13 November), none yet checked. Industry calls: three made (9 and 12 November), all still under embargo, so they appear below only as an id, a date and a fingerprint; none yet checked; three further candidates were tested on 19 November and none passed.

Gap calls: six live, none yet at its check-in date; two candidates tested on 19 November were rejected. Effect predictions on rules: fifteen made, none yet due; the first checks fall on 25 November and 10 December 2026.

The paper book stood at 98.47 at the 18 November close for its US holdings (19 November for Europe and India), from 100 at its start on 26 October 2026, a drawdown of 3.0% from its high; over the same days the S&P 500 index rebased to 100 stood at 95.86 and the equal-weight AI basket at 93.16, so the book is 2.61 points ahead of the S&P 500 and 5.31 points ahead of the AI basket. About 81% of the book is cash, earning the three-month Treasury bill rate. The day's cost was the health-insurance holding closed this morning after a proposed Medicare audit rule took 16% off it in two sessions; the rule hit the revenue the insurer books from diagnoses, not the cost line the trade was watching.

## What we got wrong and what changed

- 19 November 2026: S12 (a health insurer, held on the view that AI would hold its administrative costs down) was stopped out after the Centers for Medicare and Medicaid Services proposed to extrapolate audit findings on diagnosis coding across whole contracts, which took 16% off the stock in two days. The trade watched the cost line; the revenue line, lifted by the same coding tools, was the exposure. No rule in force would have changed the outcome (there was no dated event to size into, and the relative-price exit fired on the same day as the absolute stop), so it is not a process miss. Rule proposed, awaiting the editor's mark: a trade on an insurer carries an exit condition on the revenue base (a Medicare audit or payment action) beside the one on costs.
- 13 November 2026: two dates we carried were wrong (Nvidia reports on 17 November, not 19 or 20; the New Mexico air-permit decision set for 23 November was waived on 3 November). Rule: a dated event enters the calendar only from the company's or the agency's own notice, and the known-binary decision is taken on the run before the confirmed date.
- 9 November 2026: four exits had been recorded at the previous day's close instead of the next morning's open, where a reader could actually have sold. Rule: every exit is restated at the actual next open, and the earlier figure is kept on the call with the correction noted.
- 6 November 2026: two trades (S01, power producers; S06, memory makers) were stopped out on 5 November after the engine held both at full size through the 3 November elections with the odds in hand a week ahead, having read the results as "two-sided". Rule written after the loss: any dated event inside five trading days whose adverse branch we price at 30% or more forces one of three things before the event: halve the position, tighten the stop to the move that branch could produce in a day, or write down in one line why holding is right and what it would cost. "Two-sided" is never a reason to hold. Second rule from the same week: every exit condition names the market move that counts as the condition arriving, not only the rule or event, so a repricing before the rule lands closes the trade.
- 30 October 2026: S08 (a call to avoid long-dated bonds into a dated event) was right on the event and wrong on the channel: yields fell on an equity selloff rather than rising on the event. Scored partial. It became the second half of the exit-condition rule above.

## The month

The first monthly review (6 November 2026): of the nine structural themes the engine follows, five were confirmed by November's evidence, one revised, one admitted provisionally and two remain candidates; the standing negative (that AI makes firms smaller) was again not supported. Gap scorecard: six live, none yet due. Policy effects: thirteen predictions made, none yet due. The learning review needs ten closed calls and has five, so no rule was changed by it.

## Corrections

Every correction is listed, dated, at the end of record.md under "Corrections"; the latest (18 November 2026) record that the PJM grid filings carried as 'not visible' on 16 and 17 November were filed on time (the engine could not read FERC's library), and list the day's secondary-only items and the two price feeds that failed (the Hang Seng Tech index and the S&P health-care index, replaced by an ETF proxy for one test).

## The files

- record.md: the full record in plain text: every call with its date, probability, exit condition and result, the daily marks, the gap, effect, industry, credit and private-markets tables, and the corrections.
- calls.json: the same calls as data, with every leg's entry, last price and status.
- scorecard.csv: one row per closed call and leg, with the entry, exit, return, days held and the scores that produced it.
- book.csv: the paper book, one row per day it was marked, with its value, exposure and the two benchmarks.
- fingerprints.json: the daily hash of calls.json, record.md and scorecard.csv together, so each day's state can be verified.
