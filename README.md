# AI Fashion Campaign Brief — Claude Skill

Turns a client brief or a product link into a production-ready AI fashion, beauty or product
campaign package: creative concept, AI model consistency spec, shot list, image and video
generation prompts, platform cutdowns, a pricing table and AI-content labeling notes.

Made by **Aleksandra Kabaeva**, AI Creative Director · [kabaeva.co](https://kabaeva.co)

## Example

**Input**

> Luxury skincare brand. Three products. Campaign for Instagram.

**Output** (one package, under 3 pages)

1. **Creative concept** — one line a stranger could retell, plus why it fits the brand
2. **Aesthetic direction** — primary and fallback, with lighting and lens vocabulary
3. **AI model consistency spec** — identity anchors, skin and hair, wardrobe logic, do-not-change list
4. **Shot list** — Hook → World → Product → Proof, with timing, framing, motion and on-screen text
5. **Generation prompts** — one image and one video prompt per key shot, model-agnostic
6. **Formats and cutdowns** — 9:16, 4:5 and 1:1 deliverables mapped to Reels, TikTok, paid and e-commerce
7. **Pricing table** — a ready ladder you adjust to your own rate card
8. **Labeling and disclaimers** — AI-content label, client handoff note, "independent concept" line for spec work

See [assets/campaign-brief-template.md](assets/campaign-brief-template.md) for the exact structure.

## Install

**Claude Code**

1. Copy this folder to `~/.claude/skills/ai-fashion-campaign-brief/`
   (or to `.claude/skills/ai-fashion-campaign-brief/` inside a project, for that project only).
2. Check that `SKILL.md` sits directly inside that folder.
3. Start a new Claude Code session and ask: *"What skills are available?"* —
   `ai-fashion-campaign-brief` should be listed.

```bash
git clone https://github.com/makskabaev9-byte/ai-fashion-campaign-brief ~/.claude/skills/ai-fashion-campaign-brief
```

**Claude apps (claude.ai, desktop)**

Download this repository as a ZIP (Code → Download ZIP) and upload it in the Skills
section of your Claude settings. Skills must be enabled for your account.

## Usage

> Create an AI campaign for [product link]

> Here is our brief: [paste]. Make a campaign package with prices.

The skill asks for missing details instead of inventing client constraints.

## Free vs Pro

This free skill plans the campaign. The **Pro Pack** adds 4 production skills that help you
make it: the exact system behind [kabaeva.co](https://kabaeva.co) visuals.

| | Free (this repository) | Pro Pack — $39 |
|---|---|---|
| Campaign brief | ✓ concept, shot list, prompts, pricing, labeling | ✓ works together with the Pro skills |
| AI model consistency | Basic spec format | **ai-model-consistency** — keep one AI model's face identical across 20+ shots |
| Art direction | Aesthetic directions list | **campaign-art-direction** — style guides, color scripts, moodboard anatomy |
| Hooks for Reels/TikTok | Hook frame rule | **ugc-hook-factory** — 20 proven hook formulas for Reels/TikTok scripts |
| Prompts | Image and video scaffolds | **prompt-library** — 28 copy-paste prompt formulas (campaign, editorial, UGC, product) |
| EU AI Act labeling notes | ✓ | ✓ |
| Updates | Public repository | Lifetime updates to v1.x, instant download |
| License | MIT (free to use and modify) | Personal/commercial use by the buyer, no redistribution |

Works with Claude, Claude Code and any agent that supports Agent Skills.

**[Get the Pro Pack →](https://kabaeva.lemonsqueezy.com/checkout/buy/f76ab952-b66b-4bb3-a05a-9df7c65375a7)**

## Notes

- Labeling guidance in [references/compliance.md](references/compliance.md) is practical guidance, not legal advice.
- Prices in the template are examples; replace them with your own rate card.

## License

This repository is released under the [MIT License](LICENSE). The Pro Pack is a separate product
with its own terms and is not covered by this license.
