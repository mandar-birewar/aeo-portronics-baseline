# aeo-portronics-baseline

# Do AI answers mention Portronics? A 7-day baseline test (Nov 2026)

A small, reproducible test of whether ChatGPT, Perplexity and Google AI Overviews mention the consumer-electronics brand **Portronics** (India), and what happened over a week of third-party content work.

**Disclosure:** I'm an engineering student in Nagpur. I own a Portronics Bluetooth mouse and used Portronics speakers until recently. I have no affiliation with, or payment from, Portronics or any competitor. This repo documents a student research exercise. The write-up was drafted with AI assistance, and the numbers come from my own captured answers.

## What's here
- `queries.md`: the five fixed queries and the capture dates
- `results.csv`: 15 answers (5 queries x 3 engines), baseline vs Day 7
- `LIMITATIONS.md`: what this test cannot show

## Result in one table

| | Baseline | Day 7 |
|---|---|---|
| Portronics present | 8 | 11 |
| Inconsistent | 1 | 0 |
| Absent | 6 | 4 |

On category queries only (Q1, Q3, Q5; 9 answers), Portronics appeared in 2 (3 counting an inconsistent run) at baseline and 5 on Day 7. boAt appeared in 7 of 9 at baseline and 8 of 9 on Day 7.

## Findings
1. **The gap is by category, not engine.** Portronics appeared for power banks and for queries that name it, but not for neckbands on any engine. Speakers appeared only on Day 7.
2. **Product fit doesn't explain the neckband gap.** Portronics Harmonics Z3 lists IPX5, equal to the boAt Rockerz 330 that ChatGPT listed at baseline, at a lower price on the listings I read.
3. **I can't attribute the Day 7 changes to my pages.** My pages were not indexed, none appeared in the visible sources, and a third-party listing dated 7 Nov that includes the Portronics Fynix appears in the Google results.
4. **Answers vary run to run.** Different Portronics models appeared for Q1 on two engines.
5. **Claims about reliability rest on forum sentiment and thin review pages.** The Trustpilot page I found for portronics.com has 11 reviews, and one answer states a founding year (2010) while a company profile says 2008.

## Published pages (the experiments)
- Best power bank under ₹2,000: https://medium.com/@mandarbirewar/best-power-bank-under-2-000-in-india-2026-portronics-vs-ambrane-vs-xiaomi-5ef81069d509
- Best Bluetooth speaker under ₹3,000: https://medium.com/@mandarbirewar/best-bluetooth-speaker-under-3-000-in-india-2026-portronics-fynix-vs-tribit-xsound-go-vs-boat-ed6c89bd49da
- Best wireless neckband under ₹1,500 for the gym: https://medium.com/@mandarbirewar/best-wireless-neckband-under-1-500-in-india-for-the-gym-2026-portronics-harmonics-vs-boat-b58258be4d63
- Portronics vs Ambrane power bank: https://medium.com/@mandarbirewar/last-updated-5-november-2026-prices-change-with-sales-so-check-the-current-price-before-buying-cf99f9c21426
- Is Portronics worth buying in India? https://portronicsbuyernotes.blogspot.com/2026/11/is-portronics-worth-buying-india.html
- Explainer video: https://youtu.be/V44kygkMzpo

## How to reproduce
1. Use the five queries in `queries.md`, with exact wording.
2. Run each on ChatGPT (search on), Perplexity and Google AI Overview, in a fresh chat or incognito window.
3. Screenshot the answer and note whether the brand appears, which competitors appear, and which sources are cited.
4. Repeat each query at least twice, because answers change between runs.
5. Compare with your baseline in a table like `results.csv`.
