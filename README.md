# Manufactured Loneliness

**A Strategic Anatomy of Pop Mart's Companion Economy**

*As the world grew lonelier, people began to buy a friend.*

**→ [View project](https://catherinedeng02.github.io/manufactured-loneliness/)**

---

An interactive strategic analysis of Pop Mart International Group (9992.HK), built as a
navigable world rather than a report. Three sections, twelve chapters, twelve interactive
models — each one designed to let the reader test the argument rather than take it on faith.

The project asks a single question in three parts: **can loneliness be industrialised, does
every culture buy the same loneliness, and what does a companion brand do when it starts to
feel incomplete?**

---

## Structure

### S1 — Make It. Millions of It.
*Supply chain and operations · Can loneliness be mass-produced?*

| | Chapter | Interactive |
|---|---|---|
| 1.1 | Why Did It Suddenly Get So Loud? | Margin test — actual vs. demand-shock counterfactual |
| 1.2 | What the Margin Actually Buys | Gross margin vs. overseas revenue mix |
| 1.3 | The More You Make, the Less It's Worth | Output dial with scarcity elasticity |
| 1.4 | What Would You Have Paid in 2020? | Valuation builder with outcome reveal |

**Central finding.** Revenue grew 184.7% in 2025 while gross margin expanded 5.3 points to
72.1%. A genuine demand shock compresses margin through expedited production and air freight.
Margin expanded instead — evidence the supply system was ready before the attention arrived.

### S2 — Arrive, Belong, and Repeat.
*Consumer and retail markets · Does every culture buy the same loneliness?*

| | Chapter | Interactive |
|---|---|---|
| 2.1 | Three Doors Into the Same Room | Four-region channel explorer |
| 2.2 | What a Store Is Actually For | Naive vs. channel-corrected store productivity |
| 2.3 | The Number Nobody Reports | Overseas repeat-purchase sensitivity |
| 2.4 | One Product, Three Businesses | Three-business growth scenario builder |

**Central finding.** China's member repeat purchase rate is disclosed at 55.7%. No repeat rate
is disclosed for any overseas market — including the Americas, which grew 748% with 64% of
revenue arriving online. The absence is itself the finding.

### S3 — Something Is Still Missing.
*Strategic risk and M&A · When a companion brand grows lonely, who does it turn to?*

| | Chapter | Interactive |
|---|---|---|
| 3.1 | The Shape of the Hole | FY2024 vs. FY2025 portfolio concentration |
| 3.2 | Three Futures, Already Lived | Funko, Sanrio, Disney — build, buy, or neither |
| 3.3 | Who Would You Buy? | Weighted acquisition target screen |
| 3.4 | What Money Cannot Buy | FY2025 revenue by IP vintage |

**Central finding.** Hello Kitty is 37% of Sanrio's revenue; THE MONSTERS is 38.1% of Pop
Mart's. Sanrio arrived at that number by descending over a decade; Pop Mart arrived by
ascending in a single year. Meanwhile MOLLY, roughly nine years old, still earned RMB 2.90bn —
more than the entire company earned in 2020. Nothing in the portfolio has gone to zero.

---

## Method

Every figure is drawn from Pop Mart International Group annual and interim results, FY2020–
FY2025, with comparable-company data from Sanrio, Funko and Disney filings. Sources are cited
in a footnote on each chapter page.

Three elements are models rather than disclosure, and each carries a **"Framework, not
forecast"** label on the page:

- the output-versus-value curve in 1.3
- the overseas revenue bridge in 2.3
- the acquisition screen in 3.3

Scoring assumptions in the acquisition screen are stated openly rather than hidden, on the
principle that a screen you cannot argue with is not a screen.

---

## Design notes

Built as a fairy-tale world rather than a deck. Three Pop Mart IP characters anchor the three
sections, selected to match each section's emotional register: SKULLPANDA's industrial
coldness for supply chain, DIMOO's wandering for consumer markets, HIRONO's incompleteness for
strategic risk.

Plain HTML, CSS and vanilla JavaScript. No frameworks, no build step, no dependencies. All
charts are hand-written SVG. Typography is Playfair Display and DM Mono; the palette is a
dark concrete base with one accent colour per section.

---

## Running locally

```bash
python3 -m http.server 5500
```

Then open `http://localhost:5500`. A local server is required — opening the files directly
over `file://` prevents images from loading.

---

*All character images © POP MART. Used for educational portfolio purposes only. This project
is analytical commentary and is not investment advice.*
