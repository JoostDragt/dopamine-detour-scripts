# Episode 1 — PRODUCTION PACKAGE (Doodle / Stick-Figure Style · 12 fps)

**Working title:** *Your Brain Isn't Broken — It Just Takes a Detour*
**Channel:** Dopamine Detour
**Visual style:** Hand-drawn black-marker **stick-figure doodle** (whiteboard-explainer look) on a white/paper background.
**Frame rate:** **12 fps** for the entire video (animate "on twos" for that charming hand-drawn choppiness).
**Source script (VO):** unchanged from [`01-what-is-adhd-and-add.md`](01-what-is-adhd-and-add.md) — the narration is style-independent; this package re-skins the *visuals* around a recurring character.

> 🔁 **Supersedes** the earlier cinematic/flat-vector visual plan (kept in git history). This doodle version is the active production direction.

> ⚙️ **Fill-in placeholders:** `«VOICE_ID»` (ElevenLabs). Everything else has a concrete default.

---

## 🎨 STYLE BIBLE

**The look:** Rough, friendly black marker lines on white paper, exactly like the reference sheet — oval heads, dot eyes, simple single-line mouths, thin slightly-wobbly limbs, little hands, simple feet. Imperfect on purpose. Think whiteboard animation / Simple-History doodles / sketch-explainer.

**Color rule:** Pure **black-on-white** is the base. **One accent color only — dopamine-gold/yellow** — used sparingly for the things that matter (browser tabs, dopamine sparks, the winding road, the Subscribe button). This keeps the doodle purity while giving the channel a recognizable signature. *(If you want it 100% pure black & white like the reference, just drop the accent — noted per scene where it appears.)*

**Motion & frame rate:**
- Whole film runs at **12 fps**, animated **on twos** (each drawing held ~2 frames) — the deliberate hand-drawn stutter.
- Minimal camera movement. The charm is the *drawing appearing/moving*, not fancy camera work. Where useful: the classic "hand draws it in" whiteboard reveal, simple slides, and squash-and-stretch on the character.
- Backgrounds stay mostly empty white — negative space is part of the style.

---

## 👤 CHARACTER BIBLE

### Sam — the protagonist (the viewer's stand-in)
A simple hand-drawn stick figure: oval head, two dot eyes, expressive single-line mouth, **a small tuft of 2–3 short hair lines on top** (his one consistent identifier so viewers recognize "the same guy" across scenes and across episodes). Thin wobbly marker limbs, little hands, simple feet. Big, readable emotions through pose and mouth-line (smiling, overwhelmed hands-on-head, thinking hand-to-chin, running, slumped).

### Supporting cast (all same doodle style)
- **The Expert** — a stick figure with **round glasses** (like the reference's top-right figure). Pops in to bust myths and explain the science. Calm, pointing-finger "aha" poses.
- **The Crowd** — generic stick figures: the neat row of people walking the "straight highway," a friend for the handshake/body-doubling beat, etc.
- **Brain-Buddy** — a little hand-drawn brain with a face (dot eyes + mouth). Sam's "co-pilot," used for the dopamine/executive-function beats. Optional but charming and very on-brand.

### Prop doodles (same hand style)
Browser tabs (little rectangles), dopamine = small coins/sparks/⚡, a swinging spotlight, an air-traffic control tower, three doors, a synapse (two blobs with a gap), a filing cabinet, the straight road vs. the winding road.

---

## 🎯 STEP 1 — VIDEO BRIEF

| Field | Value |
|---|---|
| **Topic** | What ADHD (and the outdated "ADD") actually is — a different route, not a broken one |
| **Length** | 7–8 min (~1,250–1,350 words) |
| **Style** | Hand-drawn stick-figure doodle / whiteboard explainer, B&W + single gold accent |
| **Frame rate** | **12 fps**, animated on twos |
| **Aspect ratio** | 16:9 (1080p source is fine for this style; 4K optional) |
| **Tone** | Confident, direct, warm, contractions. Sam makes it personal. |
| **Recurring motif** | Sam at a fork: straight road vs. winding road. Opens & closes the film. |

---

## ✍️ STEP 2 — SCRIPT (VOICEOVER)

> Narration is identical to the polished `[HOOK] / [MAIN CONTENT] / [ENDING]` version. It does not change for the doodle style — what changes is what Sam is *doing* on screen (Step 3). Full VO text lives in the source script; key emotional cues repeated in Step 4.

---

## 🎥 STEP 3 — SCENE-BY-SCENE (DOODLE + 12 FPS)

**Global Higgsfield/image style tag to append to every prompt:**
> *"hand-drawn black marker stick figure doodle, rough sketchy uneven lines, simple, on plain white paper background, whiteboard-explainer style, minimal, lots of empty white space, black ink only [+ small yellow accent where noted], 2D, flat, no shading"* — `--ar 16:9`

> ⚠️ **Consistency tip:** generate Sam once (the character sheet below), then pass that image as a **reference** for every scene so his proportions/hair-tuft stay constant. For true line-art consistency, the most reliable pipeline is **doodle stills → animate in your editor at 12 fps** (or a whiteboard tool like VideoScribe/Doodly), because AI *video* tends to wobble line art.

### SCENE 0 — CHARACTER SHEET (make this first)
- **Prompt:** *"Character reference sheet of a simple hand-drawn stick figure named Sam: oval head, two dot eyes, small friendly single-line smile, a small tuft of 2-3 short hair lines on top of his head, thin wobbly marker limbs, little hands, simple feet. Several poses: standing waving, thinking hand on chin, arms up overwhelmed, running. [global style tag]"*
- Use the resulting image as the reference for all scenes below.

### SCENE 1 — Tab avalanche (0:00–0:10) · *"how many tabs…"*
- **Action:** Sam sits cross-legged, calm for a beat — then dozens of little hand-drawn browser-tab rectangles (yellow-accent glow) pop and pile up over his head until he's buried, eyes wide.
- **Prompt:** *"A stick figure named Sam sitting, looking up overwhelmed as dozens of small hand-drawn browser-tab rectangles and notification dots pile up and swirl above his head, a few tabs glowing soft yellow, chaotic, [global style tag]."*
- **Camera/motion:** Locked. Tabs draw-in fast, one every couple of frames (12 fps stutter sells the chaos).

### SCENE 2 — "Isn't broken" (0:10–0:18)
- **Action:** All the tabs get swept off-screen by an unseen hand; Sam stands, dusts himself off, gives a small reassured smile. A single yellow line is drawn under him that will become the road.
- **Prompt:** *"A stick figure Sam standing and dusting himself off with a small relieved smile, all the clutter wiped away, a single clean yellow line drawn on the ground beneath him, lots of empty white space, [global style tag]."*
- **Motion:** Whiteboard "wipe" of the tabs; the yellow line draws in.

### SCENE 3 — Highway vs. winding road (0:18–0:30) · *"different route"*
- **Action:** Split. Top: a straight ruled road with a neat row of identical stick figures marching. Bottom: a wobbly **yellow winding road** with Sam strolling, curious, looking around.
- **Prompt:** *"Split composition: top half a perfectly straight ruled road with a tidy row of identical stick figures walking in line; bottom half a wobbly winding yellow hand-drawn road with stick figure Sam strolling and looking around curiously, [global style tag]."*
- **Motion:** Both roads draw in left-to-right; figures bob on twos.

### SCENE 4 — The lying acronym (0:30–0:48) · *"that name lies"*
- **Action:** The Expert (glasses) writes "ATTENTION DEFICIT" in marker, then crosses out "DEFICIT" with a big scribble.
- **Prompt:** *"A stick figure with round glasses (the Expert) standing next to hand-written marker words 'ATTENTION DEFICIT', scribbling out the word 'DEFICIT' with a rough cross-out, [global style tag]."*
- **Motion:** Hand-drawn text reveal; cross-out scratches on in 2–3 frames.

### SCENE 5 — Runaway spotlight (0:48–1:05) · *"hand has a mind of its own"*
- **Action:** Sam tries to read a book; a doodled spotlight circle keeps sliding off the page onto a clock, a snack, his phone. Sam's eyes follow helplessly.
- **Prompt:** *"Stick figure Sam trying to read a book while a hand-drawn spotlight circle (faint yellow) keeps sliding away onto a doodled clock, a snack, and a phone, Sam's dot-eyes following it, [global style tag]."*
- **Motion:** Spotlight jitters around — 12 fps makes it feel twitchy and uncontrollable.

### SCENE 6 — Wired differently (1:05–1:25) · *"neurodevelopmental"*
- **Action:** Sam's oval head opens like a lid; inside, Brain-Buddy waves. A wobbly path of dots routes the long, scenic way instead of straight across.
- **Prompt:** *"Stick figure Sam with the top of his head opened like a lid, a small cartoon brain with a face (Brain-Buddy) inside waving, a dotted line winding the long scenic way across the brain instead of a straight line, [global style tag]."*
- **Motion:** Lid flips open; dotted path draws along the winding route.

### SCENE 7 — Everywhere (1:25–1:40) · *"every country, every culture"*
- **Action:** A doodled globe; lots of tiny stick figures pop up all around it, a few with the hair-tuft like Sam, a few with glasses — variety.
- **Prompt:** *"A simple hand-drawn globe with many tiny diverse stick figures popping up around its edge (some with a hair tuft, some with glasses), friendly, [global style tag]."*
- **Motion:** Figures pop in around the globe, one every couple frames.

### SCENE 8 — Dusty "ADD" cabinet (1:40–2:05) · *"what about ADD?"*
- **Action:** The Expert opens a doodled filing-cabinet drawer labeled "ADD"; little dust-puff marks rise.
- **Prompt:** *"The Expert stick figure pulling open a hand-drawn filing cabinet drawer labelled 'ADD', small doodled dust puffs rising, [global style tag]."*
- **Motion:** Drawer slides; dust puffs drawn on twos.

### SCENE 9 — Relabeled (2:05–2:20) · *"it's all called ADHD now"*
- **Action:** Expert peels the "ADD" label and slaps on a fresh "ADHD" label. Thumbs-up.
- **Prompt:** *"The Expert stick figure peeling an 'ADD' paper label off and sticking a new 'ADHD' label on, giving a thumbs up, [global style tag]."*
- **Motion:** Label swap; small "tada" sparkle (yellow).

### SCENE 10 — Three doors (2:20–2:35) · *"three flavors"*
- **Action:** Three hand-drawn doors. Sam stands in front, scratching his head, looking at all three.
- **Prompt:** *"Three simple hand-drawn doors in a row, stick figure Sam standing in front scratching his head looking at them, [global style tag]."*

### SCENE 11 — Door 1: daydreamer (2:35–2:50) · *"inattentive"*
- **Action:** Door 1 opens: a Sam-like figure stares off, little dreamy thought-bubbles (a few yellow tabs) floating up.
- **Prompt:** *"An open door revealing a stick figure gazing away dreamily with floating doodled thought-bubbles and a few small yellow tabs drifting up, [global style tag]."*

### SCENE 12 — Door 2: restless (2:50–3:08) · *"hyperactive-impulsive"*
- **Action:** Door 2 opens: a stick figure vibrating with motion-lines, foot mid-tap, scribbled energy around it.
- **Prompt:** *"An open door revealing a stick figure bouncing with hand-drawn motion lines and scribbled energy around it, foot tapping, restless, [global style tag]."*
- **Motion:** Buzz/vibrate on twos — extra jittery at 12 fps.

### SCENE 13 — Door 3: combined (3:08–3:25) · *"combined"*
- **Action:** Door 3 opens: a stick figure that's both dreamy AND buzzing — thought-bubbles above, motion-lines below.
- **Prompt:** *"An open door revealing a stick figure that is both daydreaming (thought bubbles above) and restless (motion lines below) at once, [global style tag]."*

### SCENE 14 — Air-traffic control (3:25–3:55) · *"prefrontal cortex"*
- **Action:** Sam in a tiny doodled control tower waving paddles at little paper planes ("tasks"); some land, some loop, one drifts off as a dotted line. Brain-Buddy beside him sweating.
- **Prompt:** *"Stick figure Sam in a small hand-drawn air-traffic control tower waving signal paddles at little doodled paper planes; some planes land, some circle, one drifts off along a dotted line; Brain-Buddy nearby looking stressed, [global style tag]."*

### SCENE 15 — Dopamine across the synapse (3:55–4:25) · *"dopamine & norepinephrine"*
- **Action:** Two big blobs (neurons) with a gap; little **yellow dopamine coins/⚡** try to leap the gap — some make it, some get yanked back and vanish.
- **Prompt:** *"Two large hand-drawn blob shapes with a gap between them, small yellow doodled coins and lightning sparks leaping across the gap, a few getting pulled back and disappearing, [global style tag]."*
- **Motion:** Sparks hop the gap — the 12 fps stutter makes the misfires read clearly.

### SCENE 16 — Laser focus vs. quiet signal (4:25–4:55) · *"fires unevenly"*
- **Action:** Left: Sam locked in, a bold yellow beam of focus, tongue-out concentration. Right: same Sam slumped, the beam a weak flicker, a boring form in front of him.
- **Prompt:** *"Split: left, stick figure Sam intensely focused with a bold yellow beam of concentration; right, the same Sam slumped and bored at a desk with only a faint flickering line of energy, [global style tag]."*

### SCENE 17 — The winding road, walked (4:55–5:25) · *"that's the detour"*
- **Action:** Sam happily walks the **yellow winding road**, passing a doodled viewpoint, a little waterfall, a shortcut sign — things the straight-road marchers miss.
- **Prompt:** *"Stick figure Sam cheerfully walking along a wobbly yellow winding road, passing a doodled scenic viewpoint, a small waterfall, and a 'shortcut' sign, [global style tag]."*

### SCENE 18 — Strengths montage (5:25–6:05) · *"hyperfocus… ideas… calm…"*
- **Action:** Quick doodle beats: Sam up at 3am (doodled moon) deep in creative work; Sam connecting floating idea-dots into a constellation; Sam standing calm while scribbled chaos whirls around him; Sam and a friend shaking hands (the handshake pose from your reference) = support.
- **Prompt (montage, generate as separate stills):** *"Stick figure Sam working happily at night under a doodled moon / Sam drawing lines connecting floating idea dots into a constellation / Sam calm while scribbled chaos swirls around him / Sam shaking hands warmly with another stick figure, [global style tag]."*
- **Motion:** Fast hard cuts between the four beats.

### SCENE 19 — Two roads, same place (6:05–6:30) · *"a different route"*
- **Action:** The straight road and Sam's winding yellow road both arrive at the same doodled little town at the same time. Sam waves to the marchers.
- **Prompt:** *"A straight road and a winding yellow road both arriving at the same small hand-drawn town from opposite sides at once, stick figure Sam waving to the row of marchers, [global style tag]."*

### SCENE 20 — Logo from the road (6:30–7:00) · *"it's just yours"*
- **Action:** Pull back: Sam's winding yellow road curves to form the channel wordmark; Sam waves goodbye next to a doodled Subscribe button (yellow).
- **Prompt:** *"A wobbly yellow winding road curving to spell out a logo wordmark, stick figure Sam waving beside a hand-drawn 'Subscribe' button highlighted in yellow, lots of white space, [global style tag]."*

---

## 🎙️ STEP 4 — VOICE (ELEVENLABS)

- **Voice ID:** `«VOICE_ID»`
- **Type:** Warm British male, documentary-friend tone. (Defaults to audition: "George" / "Daniel".)
- **Settings:** Stability **45%**, Similarity **80%**, Style **30%**, Speed **0.95×**.
- **Key emotional cues:** "how many tabs…" knowing smile · "Your brain isn't broken." slow, sincere · "Not won't. Can't — without a battle." firm · "It's medical… genuinely harder." grounded · "the road's not broken / it's just yours." near-whisper, big pause.

The plain doodle visuals lean hard on the VO — keep the voice intimate and unhurried; let the simple drawings breathe.

---

## 🔊 STEP 5 — SOUND DESIGN

- **Music:** Light, playful-but-warm — soft marimba/ukulele/piano under explainer beats, dropping to near-silence for "Your brain isn't broken" and the ending. Whiteboard-doodle energy, never sterile.
- **SFX:** Marker "scribble/squeak" sounds as drawings appear (signature of this style) · soft pops for tabs · a little "boing" on Sam's overwhelmed reaction · gentle "ding/tada" on the ADHD relabel · spark "tick" on the dopamine hops.
- **Rises:** under the air-traffic-control and strengths montage. **Drops:** before the two thesis lines.

---

## ✂️ STEP 6 — EDITING PLAN (12 FPS)

- **Project & export frame rate: 12 fps.** Animate on twos. If you generate AI video clips at 24/30 fps, **conform/retime them to 12 fps** in the editor and **turn OFF frame-blending / optical-flow** so the choppy hand-drawn charm survives (don't let the editor smooth it).
- **Reveals:** lean on the classic whiteboard "hand draws it in" effect (VideoScribe/Doodly do this natively; in After Effects use write-on/trim-paths).
- **Cuts:** average 3–5 s; hook faster (1.5–2.5 s). Pattern interrupt every ~30–40 s.
- **Transitions:** mostly hard cuts + marker-wipe transitions. No glossy effects — keep it papery.
- **Text overlays (hand-marker font):** "It's not a broken brain." · "wired differently" · "ADD → now a type of ADHD" · "Inattentive · Hyperactive · Combined" · "Dopamine · Norepinephrine" · "Interest runs the engine — not effort." · "Next: The Dopamine Engine →" · "The road's not broken. It's just yours."
- **Captions:** on by default, hand-drawn/marker style, key words in yellow.

---

## 📈 STEP 7 — THUMBNAILS (doodle style, 1280×720)

3 variations — generate with Nano Banana, same doodle style tag.

- **A — "BROKEN?":** Sam's oval head, half tidy lines / half a wild scribble, big marker text **"YOUR BRAIN ISN'T BROKEN"** with "BROKEN" crossed out in red. White background.
- **B — "100 TABS":** Sam buried under a pile of yellow doodled browser tabs, wide-eyed, marker text **"WHY YOUR BRAIN HAS 100 TABS"**.
- **C — "TWO ROADS":** Sam at the fork — straight ruled road vs. wobbly yellow winding road — marker text **"ADHD, EXPLAINED"** + "the detour" in yellow.

> All thumbnails: black marker on white + one red/yellow accent, huge readable text, Sam's hair-tuft visible for brand recognition.

---

## 🛠️ RECOMMENDED PRODUCTION METHOD (honest)

This exact look is the classic **whiteboard-doodle** aesthetic. Two reliable pipelines:

1. **Doodle stills + editor (best consistency, cheapest):** generate each scene as a still in the doodle style (reuse Sam's character sheet as reference), then animate/reveal them at **12 fps** in CapCut / DaVinci / After Effects. Line art stays consistent because you control it frame-by-frame.
2. **Whiteboard-animation tool:** VideoScribe or Doodly draw the figures on for you at a set fps — purpose-built for this style, flat monthly fee, no per-clip AI cost.

AI *video* (Kling/Higgsfield) can do short stick-figure motion but tends to wobble the line art across frames — fine for a few hero beats, risky for a whole episode. So: **stills + editor (or a whiteboard tool) for most of it; AI video only for select hero shots.**

> ⚠️ Description disclaimer: *"Educational content, not medical advice. If you think you have ADHD, talk to a qualified professional."*
