# Interregnum Research: the public record

This repository is the timestamped record of every call published by Interregnum Research's signal engine, which studies how artificial intelligence is restructuring the global economy. It exists so that anyone can check, later, that a call was made when we say it was made and has not been edited since.

## What is here

| File | What it holds |
|---|---|
| `calls.json` | Every call: instruments, direction, entry, stop, probability, horizon (event, trend or structural), what resolves it, and its status. |
| `record.md` | The ledger in plain words: each call, its probability, timeframe, exit condition and result. |
| `scorecard.csv` | Every closed call, scored: close price, return, days held, stated probability, result (hit, partial, miss). |
| `book.csv` | A paper model portfolio that follows the calls with fixed sizing and cost rules. Paper only, not real returns. |
| `fingerprints.json` | One SHA-256 hash per day of `calls.json`, `record.md` and `scorecard.csv`, concatenated in that order. |

## How to verify

1. Every weekday the engine commits the day's files here. Git records the commit time, and GitHub shows the full history of every file.
2. To check a day's fingerprint, take that commit's `calls.json`, `record.md` and `scorecard.csv`, join their contents in that order, and compute the SHA-256. It should match that day's entry in `fingerprints.json`.
3. Nothing is deleted or rewritten. A correction is a new commit that says what changed and why.

## What this is not

This is research published for a general audience. It is not personal investment advice, and nothing here is an offer to buy or sell any security. Probabilities are the engine's own estimates and are labelled uncalibrated until 30 calls have closed. The model portfolio is hypothetical.

Interregnum Research is part of Alletta LLC.
