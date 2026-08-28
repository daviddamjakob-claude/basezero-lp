# basezero — landing page

Single self-contained HTML landing page for **basezero**, the knowledge-graph technology built by [Ascending](https://ascending.eu). Used to support an outbound "exploration call" motion aimed at winning the first 5–10 design partnerships.

## Run it

Open `index.html` in a browser. That's it — no build step, no dependencies, no external assets. All CSS, SVG and JS are inline.

## Structure

1. **Hero** — verbatim positioning copy, primary CTA
2. **The difference** — the usual AI-at-work pitch vs. basezero
3. **How it works** — connect / reach it anywhere / inbox / share center, with the human-approval step called out explicitly
4. **Show, don't tell** — one 60-minute founder call split into four fact-level audiences (the page's visual centerpiece)
5. **Technical capabilities** — the five layers: ingestion, retrieval, transparency, curation, control
6. **Where this grows** — expansion vectors, deliberately secondary weight
7. **CTA** — design-partnership framing

## Copy rules baked into this page

- Hero copy is **verbatim and final** — including the intentional repetition of "exponential". Do not paraphrase.
- The name on this page is **basezero**. "graphzero" is a separate working name for a different, broader value proposition and must not appear here.
- The word **"expertise"** is banned — it reads as an overclaim.
- The individual → organizational sharing step is **never** described as automatic. A person approves every move. ("kept current, automatically" in the ingestion layer refers to source-system sync mechanics and is correct as written.)
- No competitor is named in the contrast block.
- Niche back-office integrations (AFAS, Exact, DATEV, Personio) and the "second brain" angle belong in the ingestion layer and the "where this grows" section only — never the hero.

## Design

Dark-first (`#0E0E13`), one accent (violet `#6E5BF6`) used sparingly on CTAs, numbers and section glows. Animated SVG knowledge-graph texture behind the hero, pure CSS/SVG. Fully responsive; respects `prefers-reduced-motion`.

## CTAs

Both CTAs currently point at `#`. Wire them to a scheduling link or `mailto:` before sending the page anywhere.
