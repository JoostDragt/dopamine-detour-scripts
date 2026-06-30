# Episode 2 — Montage Guide & Image Timing (Colorized Doodle)

Visual plan + **exact image timing** for **Episode 2 — The Dopamine Engine**.
Script: [`../../scripts/02-the-dopamine-engine.md`](../../scripts/02-the-dopamine-engine.md) ·
Voiceover: [`VOICEOVER.md`](VOICEOVER.md) (ElevenLabs "Mark", 8 sections).

**Visual style:** Option 1 — **colorized doodle**. Sam keeps his black marker linework; the world
is now in color. Dopamine/energy is always **golden-amber** (channel signature). 16:9, 12 fps,
animated on twos (same hand-drawn stutter as Episode 1).

**Sam reusable Element (Higgsfield):** `aaa7ee1c-4a48-42ae-90df-4d0243ed1763`
— embed `<<<aaa7ee1c-4a48-42ae-90df-4d0243ed1763>>>` in any image prompt to keep Sam consistent.

---

## ⏱️ How the timing works (read this first)

The **Start** column below is on the **voiceover timeline** (the 8 Mark clips laid end-to-end,
≈ 4:40 total raw). The finished video runs longer (~7–9 min) once you hold beats and add
intro/outro music — Episode 1 was also ~4:43 of raw VO inside a ~7–8 min edit.

> ⚠️ **Precision caveat:** these seconds are **computed** from Episode 1's *measured* speaking rate
> (Mark ≈ 156 wpm), because this build environment's egress policy blocks Higgsfield's audio CDN, so
> the real clip lengths can't be read here. Expect **±1–2 s** per cut. **To lock it exactly:** read the
> 8 clip durations in Higgsfield and adjust, **or** just cut on the **VO cue** (the exact words in the
> last column) against the waveform in your editor — that is frame-accurate regardless of the estimate.

---

## 🎬 Image timing table (16 beats)

| # | Start (VO) | VO section | Cut on these words | Image |
|---|-----------|-----------|--------------------|-------|
| 1 | **0:00** | 1 · Hook | *"You sit down to do the one task…"* | Sam slumped at desk, paper "IMPORTANT TASK", hand drifting to glowing phone |
| 2 | **0:12** | 1 · Hook | *"You're not lazy. You're not broken."* | Engine in Sam's chest sputters golden, then dies |
| 3 | **0:23** | 2 · Engine metaphor | *"Imagine your motivation is an engine."* | Cutaway: little car engine in Sam's chest, fuel line to head |
| 4 | **0:34** | 2 · Engine metaphor | *"…the pleasure chemical. That's not quite right."* | "PLEASURE" crossed out, "WANTING" written above |
| 5 | **0:53** | 3 · What dopamine does | *"Every time you do something worth it…"* | Neurotypical synapse: amber coins hop **smoothly**, gauge full |
| 6 | **1:14** | 3 · What dopamine does | *"In a typical brain, this system is pretty steady."* | Pull back: plain figure drives calmly off down straight grey road |
| 7 | **1:27** | 4 · ADHD engine | *"But in the ADHD brain, this engine runs differently."* | ADHD synapse: coral vacuum-pumps yank coins back, gauge near empty |
| 8 | **1:49** | 4 · ADHD engine | *"So the spark fires… and fizzles."* | Sam straining to push a stalled car uphill; plain figure cruises past |
| 9 | **2:15** | 5 · Hunts for stimulation | *"…It goes hunting."* | Sam surrounded by glowing temptations (phone, snack, tabs, TV), reaching |
| 10 | **2:43** | 5 · Hunts for stimulation | *"It's also why novelty feels so good…"* | Split: shiny NEW project bursting vs. same project 3 weeks later, grey |
| 11 | **2:55** | 6 · Interest-based system | *"Here's the part that changes everything…"* | Dashboard: 4 amber buttons NOVELTY/INTEREST/CHALLENGE/URGENCY; dark "because I should" |
| 12 | **3:21** | 6 · Interest-based system | *"That's why you can write the whole essay the night before…"* | Sam at 3 a.m., deadline-clock pumps golden fuel into him |
| 13 | **3:39** | 7 · Reframe | *"Once you see it this way…"* | Sam deliberately feeding sparks: task → game board, clock, friend beside him |
| 14 | **4:02** | 7 · Reframe | *"Because here's the truth: your engine isn't broken."* | Transformed glowing car on winding yellow road to bright horizon/viewpoint |
| 15 | **4:22** | 8 · Outro & CTA | *"If this made your own brain make a bit more sense, subscribe…"* | Sam waves by colorful SUBSCRIBE button; Wed·Fri·Sun marks glow |
| 16 | **4:35** | 8 · Outro & CTA | *"I read every single one."* (end card) | Winding yellow road curves into the channel logo wordmark |

> **Density note:** these 16 are the *hero* beats. For the "lots of pictures, more color" feel, drop
> small connective doodles (an icon, an arrow, a Sam reaction) every 3–5 s **between** these — target
> 60–90 images across the finished video.

---

## 🎨 Reusable style preamble (paste atop every prompt)

> Hand-drawn black marker doodle of stick figure `<<<aaa7ee1c-4a48-42ae-90df-4d0243ed1763>>>` (Sam —
> oval head, two dot eyes, small friendly smile, small hair tuft), keep him identical. Whiteboard-explainer
> style, **colorized**: black outlines kept, filled with a warm cheerful flat palette. **Dopamine / energy
> is always golden-amber.** Backgrounds are soft colored washes (warm cream, sky teal) not empty white.
> Coral = stress/friction, mint accents. Light paper texture, simple flat 2D shapes, gentle soft shading,
> friendly. 16:9.

**Model:** `nano_banana_2` (Nano Banana) with the Sam element. **Palette lock:** amber = dopamine ·
teal = calm/background · coral = stress · cream = paper.

---

## 🖼️ Per-image prompts

1. **Desk + phone** — Sam slumped at a small desk, a sheet reading 'IMPORTANT TASK', staring; one hand drifting toward a glowing golden phone. Coral stress-squiggles above. Cream background, teal desk.
2. **Engine sputters** — Cutaway of Sam standing; the little car engine in his chest flickers golden then sputters and dies, faint grey smoke puffs. Cream background.
3. **Engine cutaway** — Sam with a little hand-drawn car engine glowing amber inside his chest, a fuel line running up into his head. Teal background.
4. **Pleasure → Wanting** — The word 'PLEASURE' beside the engine, crossed out with a marker line; 'WANTING' written golden above it. Cream background.
5. **Neurotypical synapse** — Two friendly neuron-blobs with a small gap; golden coins hop **smoothly** across and land; a fuel gauge beside them sits steady at full. Teal background.
6. **Plain figure drives off** — A plain stick figure climbs into a tiny car and drives calmly down a straight grey road, gauge full, no drama. Cream/teal.
7. **ADHD synapse (drain)** — Same two neuron-blobs; golden coins leap toward the gap but coral vacuum-pumps yank most back before landing; only one crosses; gauge near empty.
8. **Stalled car uphill** — Sam straining to push a stalled little car uphill, sweating coral drops, while a plain stick figure cruises effortlessly past on a smooth straight road. Amber sun, teal sky.
9. **Temptation swarm** — Sam in the center surrounded by tempting objects each radiating golden sparks (phone, snack, floating browser tabs, TV); he reaches for the brightest. Busy, cheerful.
10. **New vs. old project** — Split panel. Left: a shiny 'NEW' project box bursting with golden sparks, Sam thrilled. Right: the same box 3 weeks later, dull and greyed-out, Sam slumped, gauge empty.
11. **Interest dashboard** — A doodled control panel with four big glowing amber buttons: 'NOVELTY' 'INTEREST' 'CHALLENGE' 'URGENCY'; Sam pressing them, his engine roaring with golden sparks; a small grey unlit button 'because I should' off to the side. Teal background.
12. **3 a.m. deadline** — Sam at 3 a.m. under a doodled moon, writing furiously, a big glowing deadline-clock pumping golden fuel into him. Dark teal night, amber glow.
13. **Feeding the engine** — Sam deliberately feeding his engine golden sparks: turning a grey boring task into a little game board, sticking a clock on it, pulling up a chair so a friend sits beside him. Warm cream.
14. **Transformed road** — Sam's once-stalled car, now transformed and glowing amber, driving happily along a wobbly yellow winding road toward a bright colorful horizon and a scenic viewpoint the straight grey highway missed. Amber+teal+coral sunset.
15. **Subscribe** — Sam waving cheerfully next to a colorful hand-drawn 'SUBSCRIBE' button; three little calendar marks 'Wed · Fri · Sun' glow amber beside him. Cream background.
16. **Logo outro** — A wobbly yellow winding road curving off to the horizon and forming the channel logo wordmark 'Dopamine Detour'. Lots of warm space.

---

## 📦 Generated assets

- **Sam element:** `aaa7ee1c-4a48-42ae-90df-4d0243ed1763`
- **Proof images (colorized look test):** _pending review — links added once approved._
- Full 16-image links + thumbnails to be appended after the batch is generated and approved.

> Description disclaimer: *"Educational content, not medical advice. If you think you have ADHD, talk to a qualified professional."*
