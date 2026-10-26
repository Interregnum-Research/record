# The record (signals layer). Every published call, scored on resolution. Brier score at top once 30 resolve.

Brier score: n/a (0 resolved). Prices via Yahoo chart API, pulled 2026-10-26 ~13:00 UTC (US closes of 23 Oct; Europe/Asia 26 Oct). Polymarket (read 26 Oct): Fed 28 Oct no change 94.4%, +25bp 5.5%; midterms Democratic House 91.5%, Senate 64.5% (December-hike market not in the top-200 list; CME ~76% on 23 Oct).

| id | made | call | instrument | probability | timeframe | resolves on | exit condition | result | note |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| S01 | 2026-10-21 | BUY | CEG, VST | 70% | 6 months | PJM auction Dec 2026; first 2027 capacity payment | FERC cost-allocation rule pre-auction; hyperscaler capex cut | open | entry 2026-10-21: CEG 270.74 / VST 156.14 |
| S02 | 2026-10-21 | BUY | GEV, ENR | 65% | through 2027 | GEV Q3 2026-10-22; backlog prints | backlog <100 GW; cancelled hyperscaler order | open | entry 2026-10-21: GEV 925.92 / ENR 133.64 EUR |
| S03 | 2026-10-21 | AVOID then CONDITIONAL BUY | CRWV | 75% condition; 60% rebound | 2 months | hyperscaler calls 2026-10-28/30 | any capex trim; CRWV yield >16% after calls | open | entry 2026-10-21: CRWV 61.82 (not entered) |
| S04 | 2026-10-21 | PAIR: short WIT, long TCS/HCL | WIT, TCS, HCLTECH | 65% | 2 quarters | Infosys 2026-10-23 (met); Q3 prints Jan 2027 | Wipro large-deal TCV up two consecutive quarters | open | condition met 2026-10-23 (Infosys FY27 guide cut to 1-2% on pricing pressure); entry marked at 23 Oct close: WIT 2.19 / TCS 2,530 INR; 65% keeps it below the 70% line, scenario-sized |
| S05 | 2026-10-21 | BUY small, dated (ASYMMETRIC) | MP, LYC.AX | 40% lapse (35% at 21 Oct; raised 26 Oct); positive EV | to 2026-11-11 | MOFCOM 2026-11-10 | any MOFCOM announcement | open | entry 2026-10-21: MP 39.50 / LYC 11.38 AUD |
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
