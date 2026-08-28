# basezero — landing page

Single self-contained HTML landing page for **basezero**, the knowledge-graph technology built by Ascending. Supports an outbound "exploration call" motion aimed at the first 5–10 design partnerships.

## Run it

Open `index.html` in a browser. No build step, no dependencies, no external assets — all CSS, SVG and JS are inline.

## What the page must communicate

Exactly two claims. If a section doesn't visibly advance one of them, it doesn't belong:

1. **Organizing knowledge that is exponentially increasing and already overwhelming** — per person, into something usable instead of scattered.
2. **Breaking silos** — individual knowledge becomes organizational knowledge, with what's sensitive protected along the way, so the company compounds instead of each person drowning separately.

## Structure

1. **Hero** — verbatim positioning copy over an animated knowledge-graph field
2. **The problem: knowledge is exploding** — visual-forward, about the reality of knowledge work only
3. **How it works** — sources → individual knowledge → human approval gate → organizational knowledge, plus the four steps (connect, reach it anywhere, inbox, share center)
4. **Fact-level sharing** — one 60-minute founder call annotated into four audiences (the page's centerpiece)
5. **Technical capabilities** — the five layers: ingestion, retrieval, transparency, curation, control
6. **Where this grows** — expansion vectors, secondary weight
7. **CTA** — design-partnership framing

## Copy rules baked into this page

- **No internal reasoning, GTM strategy, or competitor commentary in visible copy.** The page describes basezero; it does not explain why other approaches fall short, does not quote a "typical pitch", and contains no vs.-competitor comparison block. (The five-layer copy's soft general observations — "Most AI tools search a folder" — are locked as approved; don't add new sentences in that style elsewhere.)
- Hero copy is **verbatim and final**, including the intentional repetition of "exponential". Do not paraphrase.
- The product name here is **basezero**. "graphzero" is a separate working name for a broader value proposition and must not appear.
- The word **"expertise"** is banned.
- The individual → organizational step is **never** described as automatic. A person approves every crossing. (The ingestion layer's "kept current, automatically" describes source-system sync mechanics and is correct as written.)
- Niche back-office integrations (AFAS, Exact, DATEV, Personio) and the "second brain" angle appear only in the ingestion layer and "where this grows" — never the hero or the problem section.

## Design

Light theme on white, vapi.ai-style structure: one accent (`#6E56CF`) reserved for the CTA, the 01–05 numerals, eyebrows, active nav and soft glows behind section headers — never as a large fill. Inter/system sans, 8px spacing base, 1200px container, 16px cards, 8px buttons, sticky blurred nav. Four inline SVG diagrams carry the argument. Fully responsive; the founder-call timeline rotates to a proportional vertical spine below 640px; all motion is CSS/SVG only and respects `prefers-reduced-motion`.

## CTAs

Both CTAs point at `#`. Wire them to a scheduling link or `mailto:` before the page goes anywhere.
