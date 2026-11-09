---
name: ai-fashion-campaign-brief
description: Turns a client brief or product link into a production-ready AI fashion/beauty/product campaign package — creative concept, AI model consistency spec, shot list, generation prompts for image and video, platform cutdowns, and EU AI Act labeling notes. Use when asked to plan, scope, concept, or estimate an AI-generated campaign, AI fashion video, AI product commercial, or AI model imagery for a brand; when a user shares a product page, brand URL, or rough brief and wants a campaign concept; or when pricing/packaging an AI creative deliverable for fashion, beauty, or product clients.
---

# AI Fashion Campaign Brief

Convert any client input (brief, product URL, moodboard description, or one-line idea) into a complete, sellable campaign package. The output must be concrete enough to produce from and to quote a price on.

## Workflow

1. **Parse the brief.** Extract: product + category, target audience, platform mix (IG Reels/TikTok/Paid/E-com), must-haves, restrictions, budget signal, deadline. If the input is a URL, infer brand aesthetics from the site. If 3+ critical fields are missing, ask — do not invent client constraints.
2. **Choose the aesthetic direction.** Pick 1 primary + 1 fallback direction using [references/aesthetics.md](references/aesthetics.md). Justify the choice in one line tied to the brand, never "because it looks cool".
3. **Define the AI model(s).** Write a Model Consistency Spec (identity anchors, skin/hair, wardrobe logic, do-not-change list) following [references/prompt-patterns.md](references/prompt-patterns.md) §1. One face across all deliverables is a hard requirement unless the brief says otherwise.
4. **Build the shot list.** Follow the Hook → World → Product → Proof arc; always open with a scroll-stopping hook frame. Format: shot ID, duration, framing, motion, on-screen text.
5. **Write generation prompts.** One image prompt + one video prompt per key shot, using the scaffolds in [references/prompt-patterns.md](references/prompt-patterns.md) §2–3. Keep prompts model-agnostic (work across Midjourney/Flux/Veo/Kling/Runway); add model-specific parameters only if the user names a tool.
6. **Plan cutdowns and formats.** Map every deliverable to platform specs (9:16, 1:1, 4:5; durations 7–15s for organic hooks, up to 60s for explainers).
7. **Package for sale.** Fill the deliverable table and pricing from [assets/campaign-brief-template.md](assets/campaign-brief-template.md). Standard ladder: single video €200 / commercial €250 / model set €350 / campaign pack €790 / monthly €490 — adjust to the user's own rate card if they state one.
8. **Add compliance.** Every concept ships with the labeling note from [references/compliance.md](references/compliance.md). If any real brand is referenced for a spec or demo, mark it "independent concept, not affiliated".

## Rules

- Never present generated imagery of a real brand as real client work; always mark concept/spec work.
- No fabricated results: do not claim engagement, sales, or "viral" outcomes in the package.
- Hook frames get the most effort: the first frame decides distribution.
- Keep the whole package under 3 pages unless the user asks for a full treatment.
- Output language: match the client's language (default English).

## Bundled resources

- [references/aesthetics.md](references/aesthetics.md) — aesthetic directions, lighting/lens vocabulary, 2026 trend aesthetics; read at step 2
- [references/prompt-patterns.md](references/prompt-patterns.md) — model consistency spec format, image/video prompt scaffolds, negative-prompt library; read at steps 3 and 5
- [references/compliance.md](references/compliance.md) — EU AI Act Article 50 labeling checklist and disclosure snippets; read at step 8
- [assets/campaign-brief-template.md](assets/campaign-brief-template.md) — the deliverable package template; copy and fill at step 7
