# The record (signals layer). Every published call, scored on resolution. Brier score at top once 30 resolve.

Brier score: n/a (0 resolved). Prices via Yahoo chart API, pulled 2026-10-29 ~13:10 UTC (US closes of 28 Oct; Europe/Asia 29 Oct). Polymarket (read 29 Oct): December +25bp 77.5%, no change 20.5%; another hike in 2026 77.5%; midterms Democratic House 92.5%, Senate 67.5%.

| id | made | call | instrument | probability | timeframe | resolves on | exit condition | result | note |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| S01 | 2026-10-21 | BUY | CEG, VST | 70% | 6 months | PJM auction Dec 2026; first 2027 capacity payment | FERC cost-allocation rule pre-auction; hyperscaler capex cut | open | entry 2026-10-21: CEG 270.74 / VST 156.14 |
| S02 | 2026-10-21 | BUY | GEV, ENR | 65% | through 2027 | GEV Q3 2026-10-22; backlog prints | backlog <100 GW; cancelled hyperscaler order | open | entry 2026-10-21: GEV 925.92 / ENR 133.64 EUR |
| S03 | 2026-10-21 | AVOID then CONDITIONAL BUY | CRWV | 75% condition; 60% rebound | 2 months | hyperscaler calls 2026-10-28/30 | any capex trim; CRWV yield >16% after calls | open | entry 2026-10-21: CRWV 61.82 (not entered) |
| S04 | 2026-10-21 | PAIR: short WIT, long TCS/HCL | WIT, TCS, HCLTECH | 65% | 2 quarters | Infosys 2026-10-23 (met); Q3 prints Jan 2027 | Wipro large-deal TCV up two consecutive quarters | open | condition met 2026-10-23 (Infosys FY27 guide cut to 1-2% on pricing pressure); entry marked at 23 Oct close: WIT 2.19 / TCS 2,530 INR; 65% keeps it below the 70% line, scenario-sized |
| S05 | 2026-10-21 | BUY small, dated (ASYMMETRIC) | MP, LYC.AX | 40% lapse (35% at 21 Oct; raised 26 Oct; held 27 Oct); positive EV | to 2026-11-11 | MOFCOM 2026-11-10 | any MOFCOM announcement | open | entry 2026-10-21: MP 39.50 / LYC 11.38 AUD |
| S06 | 2026-10-21 | HOLD, buy weakness | MU, 000660.KS | 55% | 2 quarters | Micron strike settlement | one-off settlement, no formula | open | entry 2026-10-21: MU 913.67 / Hynix 1,216,000 KRW |
| S07 | 2026-10-21 | BUY | SU.PA, PRY.MI, NEX.PA, LR.PA | 70% | 12 months | gigafactory bids 2026-11-12; grid reforms | 7 credible bids with grid dates | open | entry 2026-10-21: SU 249.10 / PRY 108.35 / NEX 122.00 / LR 131.30 EUR |
| S08 | 2026-10-21 | AVOID duration (CONDITIONAL reverse) | UST long, Bunds | 75% no capex cut | until a cut | hyperscaler calls | reverse to BUY on a trim | open | entry 2026-10-21: UST10y 5.15% |
| S09 | 2026-10-21 | BUY | UMG.AS, TRI, REL.L | 60% | 12-18 months | court rulings; licensing deals | SCOTUS/CJEU fair-use ruling; US TDM exception | open | entry 2026-10-21: UMG 16.20 EUR / TRI 115.26 / REL 2973p |
| S10 | 2026-10-21 | AVOID | COUR, UDMY | 60% | 12 months | ISE 2027 survey | misconduct rate falling | open | entry 2026-10-21: COUR 4.97 |
| S11 | 2026-10-21 | BUY after 2026-11-15 | BABA, 0700.HK | 55% | 12 months | MOFCOM comment close | thresholds raised; US-China access deal | open | entry 2026-10-21: BABA 104.41 / 0700 380.60 HKD (not entered) |
| S12 | 2026-10-21 | HOLD | UNH | 55% | 2 quarters | WISeR 2027 list; midterms | contingency cap; Congress acts | open | entry 2026-10-21: UNH 417.00 |

Note: S06, S09, S10, S11, S12 sit below the 70% line and are not asymmetric; under the publication rule they stay in the catalyst board as scenarios, not published calls, until probability or evidence rises. Listed here for scoring the engine's early estimates.

## Daily marks and resolutions

### 2026-10-23 (Friday run)
Tracker: S01 at risk (avg -7.8%; CEG 255.21, VST 140.83); S02 at risk (avg -10.4%; GEV 827.42, ENR 120.18 EUR); S07 at risk (avg -7.6%; SU 230.85, PRY 98.14, NEX 113.20, LR 123.00 EUR); S05 on track (-4.1%); S06 on track (-0.6%; MU 856.49, Hynix 1,277,000 KRW); S09 on track (+2.8%); S12 on track (+1.9%; UNH 424.98); S03 waiting (CRWV 55.60); S11 waiting (BABA 101.82, 0700 386.00 HKD); S08 scenario (10y 4.976%); S10 scenario (COUR 5.07). All three at-risk calls moved on 22 Oct, the day the Philadelphia semiconductor index fell 6.7% and Meta fell 7% after reporting capex above operating cash flow; nothing in the three calls' own exit conditions has triggered.
Resolutions: calendar 2026-10-23 Infosys Q2 resolved S04's waiting condition (hit on the repricing thesis: guidance cut on record signings and 10.5% AI revenue; Wipro weakest, TCS strongest); entries marked. Calendar 2026-10-22 Micron Taoyuan strike scored PARTIAL for S06's formula thesis: Taichung signed a quarterly profit-share formula on 21 Oct (exit condition 'one-off settlement, no formula' not triggered), Taoyuan unresolved, talks 27 Oct. Calendar correction: GE Vernova Q3 is 28 Oct, not 22 Oct; Meta reported 21 Oct; the Fed decision is 28 Oct.
Thresholds crossed: T06 US 10-year closed 4.96% on 22 Oct (below the 5% line, on the AI equity selloff, not on a capex cut: S08 scenario stands); T03 CoreWeave 2031 unsecured 15.76% (above 15%); new rows T25 (Meta FCF < 0), T26 (OAT above UST), T27 (PJM 42% phantom load), T28 (Elevance DCP 44.9).
No new call proposed: the two node-candidate signals (Meta Class C; Denmark grid ranking) carry no dated binary and no >=70% branch the engine can state yet.

### 2026-10-26 (Monday run)
Tracker: S01 at risk (avg -8.3%; CEG 253.45, VST 140.16, 23 Oct close; 3.7% to stop); S02 at risk (avg -9.9%; GEV 815.00 -12.0%, ENR 123.24 EUR -7.8%; 5.1% to stop); S07 back on track (avg -4.5%; SU 235.35, PRY 102.75, NEX 117.20, LR 126.85 EUR); S04 on track (+1.9%; WIT 2.11 short, TCS 2,535); S05 on track (-2.0%; MP 38.30, LYC 11.27 AUD); S06 on track (+0.5%; MU 877.55, Hynix 1,275,000 KRW); S09 on track (+2.0%); S12 on track (+0.3%; UNH 418.09); S03 waiting (CRWV 54.24); S11 waiting (BABA 99.64, 0700 386.40 HKD); S08 scenario (10y 4.99%); S10 scenario (COUR 5.08). No stop hit, no exit condition met, no call closed.
Resolutions: none due. Calendar 23 Oct Moody's France: Aa3 negative held (no call). Probability change: S05 lapse probability raised 35% to 40% on the absence of any extension instrument with 15 days left and a leaders' meeting scheduled after the lapse (engine estimate, uncalibrated; history kept on the call).
Thresholds: T06 US 10-year back at the 5% line (5.00% on 23 Oct, 4.99% on 26 Oct); T26 reversed (OAT 4.976% below UST 4.99% on 26 Oct, on the Moody's hold); T23 no extension gazetted (checked 26 Oct); new rows T29 (S&P: 146 US data-centre projects delayed or cancelled) and T30 (MOFCOM No. 48 AI export catalogue).
Paper book opened: value 100 on 26 Oct, 18 legs across 8 entered calls, gross exposure 35.6%, net 30.6%; US legs entered at the 23 Oct close as a proxy because the 26 Oct open had not printed at run time.
No new call proposed: the strongest new signals (MOFCOM No. 48; both stays unextended; SpaceX GPU SPV; NextEra federal hubs; China State Council pacing) carry no dated binary the engine can state at >=70%.

### 2026-10-27 (Tuesday run)
Tracker: S01 at risk (avg -8.0%; CEG 252.48, VST 141.73, 26 Oct close; 4.0% to stop); S02 back on track (avg -6.1%; GEV 855.12 after +4.9% on 26 Oct, ENR 127.62 EUR; inside half the stop); S07 on track (avg -2.3%; SU 241.35, PRY 105.60, NEX 120.50, LR 128.25 EUR); S04 on track (+1.6%; WIT 2.09 short, TCS 2,496.9 INR); S05 on track (-1.3%; MP 37.47, LYC 11.66 AUD); S06 on track (+4.6%; MU 903.70, Hynix 1,341,000 KRW); S09 on track (+2.3%); S12 on track (-1.5%; UNH 410.70); S03 waiting (CRWV 55.19); S11 waiting (BABA 100.25, 0700 385.20 HKD); S08 scenario (10y 4.99%); S10 scenario (COUR 4.97). No stop hit, no exit condition met, no call closed, no probability changed.
Resolutions: none due. Calendar 27 Oct: HCA and Centene reported (S12 context: Centene employees -9.9% in a quarter with a flat benefit ratio); Micron Taoyuan talks ended without agreement, third round 6 Nov (S06: no scoring change; the next third waits). SpaceX and Apollo (26 Oct) disclosed the $40bn as a master finance lease commitment with no rate set and no close before year-end: S03's public trigger now compares against a private price.
Thresholds: T06 10-year 4.99% at the line into the Fed; T11 GE Vernova 125 GW line tested 28 Oct; T15 and T27 annotated; new rows T31 (US local moratoria 925), T32 (Japanese bank NBFI exposure 126 trillion yen, BoJ FSR), T33 (Microsoft voluntary exit uptake), T34 (SpaceX lease rate and close).
Paper book: value 100.65 (+0.47% on the day, +0.65% since 26 Oct), drawdown 0.0%, 18 legs, gross 35.6%, net 30.6%; no entries or exits.
No new call proposed: the strongest new signals (BoJ NBFI channel; SpaceX lease; Microsoft voluntary exit; INNIO engines; US moratoria into zoning code) carry no dated binary the engine can state at >=70% or as a small asymmetric; INNIO (behind-the-meter engines) is logged as a trend scenario for the monthly issue.

### 2026-10-28 (Wednesday run)
Tracker: S01 back on track (avg -5.2%; CEG 258.98, VST 146.66, 27 Oct close; inside half the stop; recovery waits for the monthly issue, no alert); S02 on track (avg -1.7%; GEV 895.08, ENR 133.54 EUR at entry); S07 on track (avg +0.5%; SU 247.15, PRY 108.85, NEX 123.80, LR 132.50 EUR, first positive mark); S04 on track (+2.0%; WIT 2.04 short, TCS 2,460 INR); S05 on track (+6.7%; MP 40.87, LYC 12.51 AUD); S06 on track (+12.0%; MU 928.76, Hynix 1,487,000 KRW after the Q3 print); S09 on track (-0.5%; TRI 116.41, REL 2,909p, UMG 16.16 EUR); S12 on track (-1.6%; UNH 410.39); S03 waiting (CRWV 59.57); S11 waiting (BABA 100.24, 0700 387.60 HKD); S08 scenario (10y 5.00%); S10 scenario (COUR 4.75). No stop hit, no exit condition met, no call closed, no probability changed. Every entered call is on track for the first time since 22 Oct.
Resolutions: none due (S03 and S08 resolve on the Amazon call, 30 Oct; the Fed decides at 18:00 UTC today, after the run). Calendar 28 Oct: GE Vernova Q3 tested S02's backlog line: 122 GW under contract or reserved against the 125 GW guide, raised to 130 GW; the slot-reservation book fell for the first time (63 to 58 GW) and gross new signings halved to 11 GW; no scoring change (resolves 2027). SK hynix Q3 (80% operating margin; KRW 10tn of the buyback to employees under the written profit-share formula) supports S06's formula thesis; Micron's Taoyuan refusal to run a calculation (27 Oct) keeps the Taiwan leg unresolved to 6 Nov.
Thresholds: T06 10-year 5.00% at the line into the Fed; T11 updated to 122 GW with reservations falling; T25 Meta equity leg confirmed ($25bn forward sale plus $12.5bn 6.50% mandatory convertible, 26 Oct); T31 annotated with the Ohio Supreme Court shield for moratoria; new rows T35 (GE Vernova gross new signings per quarter, line 13 GW) and T36 (Nvidia CDS above Meta's, crossed 26 Oct).
Paper book: value 101.49 (+0.84% on the day, +1.49% since 26 Oct), drawdown 0.0%, 18 legs, gross 35.6%, net 30.6%; no entries or exits; sleeves events +0.07%, trends +0.65%, structural +0.77%.
No new call proposed: the strongest new signals (Meta's forward sale and preferred; GE Vernova's falling reservation book; the WISeR fade; New York's sycophancy statute; the Dutch 25,000 target) carry no dated binary the engine can state at >=70% or as a small asymmetric; Samsung's 30 Oct print and the hyperscaler calls tonight may change that.

### 2026-10-29 (Thursday run)
Tracker: every entered trade on track. S01 (avg +1.5%; CEG 258.08, VST 142.72, 28 Oct close; DOE $5bn conditional loan for Constellation uprates); S02 (avg +9.6%; GEV 878.03, ENR 135.36 EUR; the GE Vernova Q&A: new reservations 8 GW against 19 and 18 GW in Q1 and Q2, +50% per kW, no cancellations); S04 (+1.0%; WIT 2.06 short, TCS 2,478 INR); S05 (+13.4%; MP 41.06, LYC 13.03 AUD; Lynas built ~1,200 t of inventory at a record price); S06 (+14.9%; MU 983.23, Hynix 1,526,000 KRW; the KRW 10tn employee tranche sized at ~206 shares a head); S07 (+10.7%; SU 248.40, PRY 114.80, NEX 128.50, LR 134.40 EUR); S09 (-3.2%; UMG 15.83 EUR, TRI 116.09, REL 2,911p); S12 (-2.8%; UNH 407.10); S03 waiting (CRWV 63.93, -6% pre-market after Microsoft's third-party delivery slip); S11 waiting (BABA 100.96, 0700 377.60 HKD); S08 scenario (10y 5.04% close, 5.01% morning; Fed held 10-2 with two hike dissents); S10 scenario (COUR 4.70). No stop hit, no exit condition met, no trade closed, no probability changed.
Resolutions: none due; S03 and S08 resolve on the Amazon call (30 Oct, after the close). Calendar 28 Oct: Microsoft (capex $45.2bn, third-party deliveries slipped to H2, calendar ~$170bn, leasing not bonds, no Copilot seat count) and Alphabet (FCF -$9.1bn, $924bn purchase commitments, 2027 capex 'significantly' higher): no capex cut, so S08 stands and S03's second condition (a >16% unsecured print) is unverified; UK Budget delivered with a Data Centre Covenant and a draft National Policy Statement for data centres (consultation to 8 Jan 2027).
Thresholds: T06 10-year crossed above 5% (5.04% close); T25 two of four hyperscalers FCF-negative; T31 corrected to the National League of Cities count (at least 76 localities; the '925' withdrawn) with San Diego added; T35 new reservations 8 GW; new rows T37 (hyperscalers with negative FCF, 2 of 4, line 3), T38 (Microsoft Copilot seats withdrawn), T39 (data-centre CMBS AAA spread versus other property, +60bp year to date).
Options: live chains read at ~13:50 UTC after the feed returned no bid or ask before 13:45; Constellation's option and spread opened today (ask $16.60; spread $10.70); the Wipro put is too thin (shares only).
Paper book: value 101.66 (+0.31% on the day, +1.66% since 26 Oct), drawdown 0.0%, 18 legs, gross 35.6%, net 30.6%; sleeves events +0.08, trends +0.70, structural +0.84 points; S&P 500 101.37 and the AI basket 103.65 rebased to the 26 Oct open; trades only +4.57% on capital deployed; cash 66.9% at 4.00%.
Gaps: G-2026-10-03 (tenant commitment risk in data-centre credit, Open, 50%) and G-2026-10-04 (coding-drift audit for AI-documented encounters, Stirring, 45%) named; G-02 logged its first incumbent move (k-ID Kai, 27 Oct) and stays at Stirring; G-01 stays Open. Policy: two effect predictions added (E-09 rare-earth front-loading, E-10 PJM registry versus forecast); rules R21 to R23 added (Pennsylvania curtail-first, Ofgem self-build, Treasury COINS); the UK draft NPS opened a window to 8 Jan 2027.
No new trade proposed: the strongest new signals (Alphabet's $1.08tn of commitments; the Fed's split; the DOE as lender; the SK hynix employee bloc; GE Vernova's price-cleared queue) carry no dated binary the engine can state at >=70% or as a small asymmetric; Amazon tonight and Samsung tomorrow are the next tests.

## Gap calls

Rebuilt every run from the gap record; fingerprinted with the trades.

| id | named | gap | stage | probability | check-in | status at check-in | time to fill | result |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| G-2026-10-01 | 2026-10-28 | Verifying data-centre power requests | Open | 45% | 2027-04-28 |  |  | live |
| G-2026-10-02 | 2026-10-28 | Chatbot child-safety compliance | Stirring | 50% | 2027-04-28 |  |  | live |
| R-2026-10-01 | 2026-10-28 | Provider tools for Medicare WISeR prior authorisation |  |  |  |  |  | rejected |
| G-2026-10-03 | 2026-10-29 | Tenant commitment risk in data-centre credit | Open | 50% | 2027-04-29 |  |  | live |
| G-2026-10-04 | 2026-10-29 | Coding-drift audit for AI-documented encounters | Stirring | 45% | 2027-04-29 |  |  | live |

## Effect predictions

Rebuilt every run from the effect record. Each says what a rule will cause, never whether it is adopted.

| id | rule | made | effect | check date | probability | result |
| --- | --- | --- | --- | --- | --- | --- |
| E-2026-10-01 | PJM large-load adjustment | 2026-10-28 | PJM's final 2030/31 large-load adjustment is at least 15% below the utilities' 29 Sep submissions | 2026-12-31 | 60% | open |
| E-2026-10-02 | ERCOT Batch Zero verification | 2026-10-28 | The 10 Dec report disqualifies or lists as non-responding at least 10% of conditionally included, not-yet-energised large-load megawatts | 2026-12-17 | 55% | open |
| E-2026-10-03 | Texas 75 MW threshold (SB 6, Project 58481) | 2026-10-28 | ERCOT's count of 25-75 MW data-centre and crypto loads exceeds 157 by at least 20% | 2026-12-10 | 50% | open |
| E-2026-10-04 | New York minors' AI companion law | 2026-10-28 | At least two of ChatGPT, Gemini, Meta AI, Character.AI and Replika require age assurance beyond self-declaration for New York users' memory or persona features | 2027-06-30 | 55% | open |
| E-2026-10-05 | California SB 243 reporting | 2026-10-28 | The Office of Suicide Prevention publishes data for at least 3 named operators, with over 100,000 crisis-referral notifications for 2026-27 | 2027-12-31 | 40% | open |
| E-2026-10-06 | Colorado AI Act and chatbot rules | 2026-10-28 | Two or fewer Attorney General enforcement actions under SB 26-189 or HB 26-1263 by end-2027 | 2027-12-31 | 80% | open |
| E-2026-10-07 | Medicare WISeR pilot | 2026-10-28 | The first evaluation shows at least a 15% fall in listed services against comparison states, and at least a 5% rise in adjacent unlisted services | 2028-03-31 | 35% | open |
| E-2026-10-08 | PJM interim and non-firm large-load services | 2026-10-28 | More than half of new large-load megawatts signing in the first 12 months choose non-firm or interim service | 2028-06-30 | 45% | open |
| E-2026-10-09 | MOFCOM Announcement 70/2025 (rare-earth suspension, fixed expiry 10 Nov 2026) | 2026-10-29 | China's October 2026 exports of rare-earth permanent magnets (HS 8505.11) exceed the January-September 2026 monthly average by at least 10% as buyers front-load before the expiry | 2026-11-25 | 55% | open |
| E-2026-10-10 | FERC order of 9 Oct 2026 in ER26-3515 (PJM Large Load definition and Registry) | 2026-10-29 | The first published registry total of large-load megawatts with executed agreements comes in at least 30% below the utility-submitted large-load additions in PJM's 2027 Long-Term Load Forecast for 2030/31 | 2027-06-30 | 50% | open |

Comments filed: none yet.

## Corrections

A correction never rewrites an earlier entry.

- 2026-10-29: T31 "925 US local moratoria" is not verified; the National League of Cities tracker counts at least 76 localities as of Aug 2026 (https://www.route-fifty.com/artificial-intelligence/2026/08/many-localities-have-tried-data-center-moratoriums-tracker-finds/415696/)
- 2026-10-29: The "Ohio Supreme Court shield for moratoria" (T31 annotation, 28 Oct) is not verified as stated: the court let the Ashville referendum proceed in Aug 2026, and the Lordstown case was still pending in Jun 2026 (https://www.mariettatimes.com/uncategorized/2026/08/ohio-supreme-court-allows-ashville-referendum-against-data-center-project-to-move-forward/)
- 2026-10-29: T27 "PJM 42% phantom load": the figure is the share of PJM's assumed data-centre growth that was cancelled or delayed (PJM market monitor), not load flagged as speculative (https://techradar.com/pro/how-do-you-know-whats-real-us-utilities-are-making-ai-data-centers-prove-they-exist-before-handing-over-power-connections-as-50-percent-of-planned-buildouts-are-currently-being-delayed-stalled-or-canceled)
- 2026-10-29: S12 "WISeR 2027 list" and "contingency cap": neither appears in CMS's WISeR FAQ (updated 22 Sep 2026) or participant guide; treat both as unverified (https://www.cms.gov/priorities/innovation/files/document/wiser-model-frequently-asked-questions)
- 2026-10-29: "New York's sycophancy statute" (28 Oct run) is S9051B/A10379C, a minors' companion-chatbot law signed 28 Oct 2026, effective 1 Jan 2027; flattery is one of 12 banned features (https://iapp.org/news/a/new-york-s-governor-signs-youth-ai-chatbot-safety-bill)
