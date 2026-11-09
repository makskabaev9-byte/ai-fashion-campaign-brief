# Prompt Patterns

## §1 Model Consistency Spec

Write this BEFORE any prompts. It is the contract that keeps one face across all deliverables.

```
MODEL IDENTITY: <name or "Model A">
- Face: <bone structure, eye shape+color, brows, lips, distinguishing marks>
- Skin: <tone, texture level: keep visible pores — no plastic smoothing>
- Hair: <color at roots/ends, texture, default styling>
- Body: <build, height impression, posture>
- Wardrobe logic: <what changes per shot vs what never changes>
- NEVER CHANGE: <3–5 anchors, e.g., "freckle under left eye, short natural nails, no tattoos">
```

Prompt usage: repeat the identity block verbatim at the start of every image prompt; for video, reference the approved still (`--sref`-style character reference or first-frame conditioning depending on the tool).

## §2 Image prompt scaffold

```
[SUBJECT + identity block] , [ACTION/POSE, specific] , [WARDROBE with fabric + fit] ,
[ENVIRONMENT: location, time of day, weather] , [LIGHTING: source, direction, quality] ,
[CAMERA: lens mm, aperture look, framing, angle] , [AESTHETIC: direction + texture/grain] ,
[COLOR SCRIPT: 2–3 dominant colors]
```

Rules: one camera instruction set per prompt; fabrics named ("ribbed knit", "washed satin"), not "nice clothes"; lighting always has direction and quality; end with color script to lock palette across shots.

## §3 Video prompt scaffold

```
[SHOT SIZE + framing] of [SUBJECT + identity block] [MOVEMENT: one clear action] ,
camera [MOVE: push-in/orbit/handheld follow/static] , [ENVIRONMENT + LIGHTING] ,
[MOOD in 2 words] , [DURATION s, 9:16] , motion speed: <slow/natural/fast>
```

Rules: ONE subject movement + ONE camera move per clip (two moves = morphing); 3–8s per generated clip, cut longer edits in post; state the aspect ratio; describe motion speed explicitly or the tool picks for you.

## §4 Negative / avoid library

`extra fingers, fused hands, plastic skin, beauty-filter smoothing, watermark, text artifacts, warped logo, inconsistent eye color, drifting hairline, duplicate limbs, overexposed highlights on product`

Add product-specific negatives per brief (e.g., for glass bottles: `label distortion, refraction artifacts`).

## §5 QA pass before delivery

For every generated asset check: identity anchors intact · hands and product label readable · logo/text uncorrupted (regenerate or fix text in post — never ship baked-in AI text) · skin texture present · palette matches color script.
