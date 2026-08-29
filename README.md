# basezero — landing page

Single self-contained HTML landing page for **basezero**, the knowledge-graph technology built by Ascending. Supports an outbound "exploration call" motion aimed at the first 5–10 design partnerships.

Live: https://daviddamjakob-claude.github.io/basezero-lp/

## Run it

Open `index.html` in a browser. No build step, no dependencies, no external assets — all CSS, SVG and JS are inline.

## What the page must communicate

Exactly two claims. If a section doesn't visibly advance one of them, it doesn't belong:

1. **Organizing each team member's knowledge work** — data intake has become a core bottleneck and is exponentially increasing; basezero organizes it, per person, into something usable instead of scattered.
2. **Creating an organizational advantage** — dissolving silos without compromising what's sensitive, so exponential data creation becomes a compounding knowledge edge.

## Structure

1. **Hero** — positioning copy over an animated knowledge-graph field
2. **The problem: knowledge is exploding** — visual-forward, about the reality of knowledge work only
3. **How it works · Part one** — organizing one person's knowledge: in one place, viewable rather than a black box, maintained and corrected (naming conflicts surfaced for confirmation), optimized for relevant and reliable AI output
4. **How it works · Part two** — dissolving silos into a compounding edge: the individual → approval gate → organizational pipeline, share and revoke in one platform, sensitivity always kept, agent-to-agent-to-human workflows, the knowledge feed
5. **Fact-level sharing** — one 60-minute founder call annotated into four audiences (the page's centerpiece)
6. **Technical capabilities** — the five layers: ingestion, retrieval, transparency, curation, control
7. **Security & sovereignty** — one knowledge base owned by you, sharing without compromising sensitivity, EU hosting, flexible deployment, no data training, with GDPR / EU AI Act / ISO 27001 marks
8. **CTA** — design-partnership framing

## Copy rules baked into this page

- **No internal reasoning, GTM strategy, or competitor commentary in visible copy.** The page describes basezero; it does not explain why other approaches fall short, does not quote a "typical pitch", and contains no vs.-competitor comparison block. (The five-layer copy's soft general observations — "Most AI tools search a folder" — are locked as approved; don't add new sentences in that style elsewhere.)
- The product name here is **basezero**. "graphzero" is a separate working name for a broader value proposition and must not appear.
- The word **"expertise"** is banned.
- The individual → organizational step is **never** described as automatic. A person approves every crossing. (The ingestion layer's "kept current, automatically" describes source-system sync mechanics and is correct as written.)
- Niche back-office integrations (AFAS, Exact, DATEV, Personio) appear only in the ingestion layer.
- ISO 27001 is stated as **in progress**, not certified. Don't upgrade that claim without evidence.

## Design

Light theme on white, vapi.ai-style structure: one accent (`#6E56CF`) reserved for the CTA, the 01–05 numerals, eyebrows, active nav and soft glows behind section headers — never as a large fill. Inter/system sans, 8px spacing base, 1200px container, 16px cards, 8px buttons, sticky blurred nav. Five inline SVG diagrams carry the argument. Fully responsive; the founder-call timeline rotates to a proportional vertical spine below 640px; all motion is CSS/SVG only and respects `prefers-reduced-motion`.

## CTAs

Both CTAs point at `#`. Wire them to a scheduling link or `mailto:` before the page goes anywhere.
