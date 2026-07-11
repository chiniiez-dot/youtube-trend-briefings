# Production Stack — the faceless toolchain

The pipeline that turns a title into a published video without a face, a studio, or a camera. Each stage has one input and one output that feeds the next. Tool names are current-market suggestions, not requirements — swap freely; the *stage* matters more than the vendor.

## The pipeline

```
Topic → Script → Voiceover → Visual direction → Edit → Package → Upload
```

### 1. Script

- **Do:** write to the [[Script-Template]] and the Brand Bible voice rules. This is the channel's soul — keep it in-house longest, even after you outsource everything else.
- **Tools:** a strong writing setup (a capable LLM as a *drafting partner*, not an autopilot — you edit every line for voice), plus your research notes.
- **Output:** a finished script marked with beat-by-beat visual cues (see step 4).

### 2. Voiceover

- **Do:** generate narration through **one fixed voice profile** — same voice, same pace, every video (Brand Bible rule). The voice is calm, precise, slightly detached: a strategist, not a hype-man.
- **Tools:** ElevenLabs or a comparable AI voice with a saved, locked profile. Test 3–4 voices during Phase 0, pick one, never change it — the voice *is* the brand's audio signature.
- **Output:** a clean narration track, consistent levels, no clipping.

### 3. Visual direction

- **Do:** assign each script beat to a visual. Match the tool to the job (Brand Bible): realistic environments, abstract motion, and static symbol frames each have a different source.
- **Style bible (non-negotiable):** near-black backgrounds, single hard light source, steel-blue `#1B2E40` base, muted gold `#C9A84C` accent, **no red**, subtle grain and rim light. Slow, weighted motion — nothing bounces, no spins/zooms.
- **Tools:** AI image/video generation for the dark cinematic look and the symbol library (chess piece, fox & lion, worn book, chains, mask, throne, puppet strings, spotlight); licensed stock for realistic B-roll; a motion tool for slow pushes.
- **Output:** an ordered set of clips/stills tied to script timestamps.

### 4. Edit

- **Do:** assemble to the channel's motion rules — slow, weighted, minimal. Cuts and slow pushes only. Silence and restraint are on-brand; don't fill every second.
- **Tools:** any capable NLE (DaVinci Resolve is free and excellent; Premiere/Final Cut fine). Licensed music kept low and cold.
- **Output:** the finished cut, color and audio checked.

### 5. Package

- **Do:** run the [[Packaging-Playbook]] — three concepts, score, choose. Build the thumbnail by dropping content into one of the locked A–E templates.
- **Output:** final title (40–55 chars) + thumbnail (legible at 210×118px).

### 6. Upload

- **Do:** complete the upload package — title, description (with affiliate links + product/waitlist link), tags, chapters, end screen, pinned comment, correct playlist/series.
- **Output:** a scheduled or published video, logged in [[Analytics-and-KPIs]].

## Recommended tool set by phase

| Need | Phase 0–1 (lean) | Phase 3+ (scaled) |
|---|---|---|
| Script | LLM + your editing | + a freelance researcher |
| Voice | ElevenLabs starter | ElevenLabs pro, locked profile |
| Visuals | AI gen + free stock | AI gen + paid stock + motion tool |
| Edit | DaVinci Resolve (free), you | Freelance editor to spec |
| Thumbnail | Canva/Figma templates | Same templates, maybe a designer |
| Research/SEO | vidIQ or TubeBuddy free tier | Paid tier |
| Hosting product | free Skool/Patreon shell | paid tier as members grow |

## The consistency rule

The faceless model lives or dies on **sameness**: same voice, same look, same motion, same structure, every upload (Brand Bible rule #6). That sameness is what lets you outsource and scale without the channel drifting — a spec-driven pipeline where any competent editor can produce an on-brand video because the spec, not the person, carries the taste. Write the specs down (this doc + [[Script-Template]] + [[Packaging-Playbook]]) so they survive handoff.

## A note on AI and "reused content"

YouTube demotes and demonetizes mass-produced, low-effort, or templated AI-slop. Your protection is that the **script — the original strategic analysis in a distinct voice — is genuinely yours.** AI assists the voice and visuals; it does not author the ideas. Keep it that way and you stay firmly inside policy (see [[Risk-and-Compliance]]).

---
Related: [[Script-Template]] · [[Publishing-Checklist]] · [[Weekly-Cadence]]
