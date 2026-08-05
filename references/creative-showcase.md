# H3 Creative Showcase — Advanced Long-Form Prompt Patterns

Quality benchmarks and transferable patterns from the user's advanced H3 prompts. These represent the depth of cinematic thinking the enhancer should bring to every prompt, regardless of mode. Study these to calibrate your creative enhancement quality.

---

## Pattern 1: Long-Form Narrative Storytelling (15s Multi-Shot Montage)

Use for: day-in-the-life, vlog aesthetic, montage, narrative progression across locations.

### Structural Blueprint

A long-form storytelling prompt opens with three explicit aesthetic blocks before the storyboard, then lays out per-shot detail with voiceover integration.

**CAMERA block** — defines the physical camera identity:
```text
CAMERA: Handheld DV 16mm camcorder aesthetic. CHASE records herself throughout every location, mostly holding the camera directly and occasionally setting it down for brief hands-free shots. Preserve natural hand tremors, crooked composition, slow autofocus correction, awkward zooms, accidental face cropping, and moments where the framing briefly loses her. The physical camcorder is never visible.
```

Transferable elements:
- Physical camera type tied to a narrative reason (she's filming herself)
- Named imperfections to preserve: hand tremors, autofocus hunting, exposure shifts, awkward zooms, framing loss
- What's NOT shown (the camera itself is never visible)

**LOOK block** — defines image quality and color science:
```text
LOOK: Authentic soft tape-image texture with mild blur, subtle electronic grain, glowing highlights, small automatic-exposure fluctuations, restrained contrast, and natural skin tones. The lighting changes realistically between locations: warm morning light in the apartment → cooler daylight inside the car → intense colorful lighting backstage and onstage.
```

Transferable elements:
- Texture vocabulary: tape-image, mild blur, electronic grain, glowing highlights
- Named exposure/contrast behavior
- Lighting transitions mapped to each location change with arrow notation

**STYLE block** — defines pacing, energy, and editing rhythm:
```text
STYLE: A fast, energetic day-in-the-life montage with sharp cuts between locations and slightly accelerated transitional movement. Reflective voiceover plays over the footage instead of synchronized dialogue. The pace gradually builds from a quiet sleepy morning into a high-energy performance finale.
```

Transferable elements:
- Pace described as an arc: quiet→energetic, with a named turning point
- Voiceover vs. synchronized audio distinction
- Editing rhythm: sharp cuts, accelerated transitions

### Character Description Pattern

```text
CHASE — an exceptionally beautiful Instagram influencer and rising pop performer in her 20s. Long glossy dark-brown hair, striking symmetrical features, large expressive eyes, flawless glowing skin, and soft pink lips. Slim, toned figure. Her outfit changes with each location: cozy loungewear at home, stylish casual clothing during the ride, and a glamorous performance outfit for the final scene. Each outfit fully covers her arms and torso.
```

Transferable elements:
- Age range + role/occupation for instant identity
- Physical features with specificity (hair color+texture, eye description, skin, lips)
- Wardrobe progression mapped to each location/shot
- Coverage note: "Each outfit fully covers her arms and torso" — always describe the level of coverage explicitly

### Setting Progression

```text
Setting Progression
Stylish apartment bedroom in the morning → luxury van interior during the day → busy backstage area and concert stage at night.
```

Transferable: Arrow notation mapping time + space progression across the full video.

### Per-Shot Storyboard with Voiceover

```text
Storyboard — 15 seconds, 5 cuts

(~3s, bedroom, camera resting on a table, soft morning light) She slowly sits up, stretches, fixes her messy hair, and hurriedly packs a small bag. VOICEOVER (CHASE): "Some mornings begin before I'm even fully awake."

(~3s, van interior, handheld selfie footage, natural window light) She sits beside the window as sunlight moves across her face, casually checking messages on her phone. VOICEOVER (CHASE): "I spend so much time on the road, this place almost feels like home."

(~3s, van interior, macro detail shot) Close-up of her fingers choosing a song from a playlist while passing sunlight flickers across the screen and her hand. No voiceover, only natural road noise.

(~3s, backstage, fast handheld montage) Quick glimpses of makeup brushes, hair styling, costume adjustments, staff rushing past, and her taking one focused breath before going onstage. VOICEOVER (CHASE): "And then everything suddenly starts moving at once."

(~3s, stage, wide shot moving into a close-up, energetic finale) Bright stage lights ignite as she steps through the curtains. The camera catches her silhouette, then a brief confident smile before the image cuts to black. VOICEOVER (CHASE): "This moment is why I keep doing it."
```

Transferable elements:
- Each shot: `(duration, location, camera position, lighting)` header
- ONE dominant action per shot (sits up + packs / checks phone / fingers choosing song / backstage montage / steps through curtains)
- VOICEOVER lines placed at end of shot with attribution
- Silent shots noted explicitly ("No voiceover, only natural road noise")
- Macro/detail shots included for rhythm variety
- Pacing builds: sleepy morning → quiet ride → intimate detail → kinetic backstage → explosive stage finale

---

## Pattern 2: Action Choreography (Ref2VA, 7 Shots, 15s)

Use for: combat, chase, sports, any sequence with spatial movement and character interaction.

### Character Color Lock System

Each character gets a signature color that governs their visual effects, trails, reflections, and environmental impact throughout the entire sequence. This is the single most powerful continuity tool for action prompts.

```text
TSUBAME (Image 1) — Young woman, sharp jawline, shoulder-length brown bob; wearing a glossy purple latex crop-top vest with silver zipper and black leather harness straps; sleek, agile build. Her movement leaves trailing neon-purple afterimages and light streaks.
GARAN (Image 2) — Tall, imposing figure in a metallic teal/seafoam green high-collar jacket over a white ribbed bodysuit; calm but dangerous expression. His heavy impacts generate teal shockwaves and digital distortion ripples.
```

**Color Lock rules:**
- Assign each character a distinct color at definition (Tsubame = Electric Purple/Magenta; Garan = Teal/Cyan)
- That color appears on: movement trails, glints/reflections, impact effects, environmental bounce light
- State the color lock explicitly: `Color Lock: Tsubame = Electric Purple/Magenta (trails, glints); Garan = Teal/Cyan (jacket sheen, shockwaves)`
- The environment reflects the character colors: "purple bounce on walls from her, teal reflections from him"

### Style Block for Action

```text
Style: High-fidelity 3D CGI animation, stylized realism (like Arcane or Spider-Verse). Glossy material rendering (latex/metal), volumetric neon lighting, motion blur on fast objects. Color Lock: Tsubame = Electric Purple/Magenta (trails, glints); Garan = Teal/Cyan (jacket sheen, shockwaves). World: Sleek, futuristic sci-fi corridor with circular archways and reflective floors. Lighting is driven by their suits—purple bounce on walls from her, teal reflections from him. Camera: Dynamic action cam—dolly zooms, whip pans, low angles, speed-ramping.
```

Transferable elements:
- Style reference points (named similar media for instant tonal calibration)
- Material rendering directives: "Glossy material rendering (latex/metal)"
- Lighting source tied to character colors: "Lighting is driven by their suits"
- Camera personality: "Dynamic action cam" with technique list

### Spatial Layout System

For action sequences, explicitly define the geography so movement directions are unambiguous across all shots:

```text
SPATIAL LAYOUT (MAIN VIEW = Corridor Axis): Tsubame starts at the far end (Screen Center-Deep) running toward camera. Garan intercepts from Screen Right. Action flows Deep → Front, then Left → Right.
```

**Action Vectors** — the 2–3 critical motion moments:
```text
ACTION VECTORS:
(V1, SHOT 2) Garan slams fist into floor → Teal shockwave travels Front→Back; Tsubame jumps over the wave.
(V2, SHOT 4) Tsubame slides under Garan's sweeping arm → Purple trail marks the slide path.
(V3, SHOT 6) Close combat lock → Purple glove vs Teal sleeve, sparks fly at contact point.
```

### Progressive Continuity Tracking

State what changes across the sequence so damage and wear accumulate visibly:

```text
Continuity: Tsubame's hair gets messier/windblown progressively. Garan's jacket shows scuff marks/dust after Shot 5.
```

### Per-Shot Choreography Pattern

Each shot in an action sequence needs: shot name + duration + camera + composition + ONE key action + visual effect + emotional beat.

```text
[SHOT 1] · The Stare Down (~2s): Static wide shot, symmetrical composition. Long futuristic corridor with glowing arches. Tsubame stands center-frame, distant, fists clenched, purple vest gleaming under overhead lights. Garan steps into frame from Right foreground, back to camera, teal jacket reflecting the hallway lights. He cracks his knuckles. Tense atmosphere.

[SHOT 2] · The Shockwave (~2s): Low angle, dynamic tracking. Garan stomps forward. A visible teal energy ripple explodes outward from his boot across the reflective floor. Tsubame sprints forward and leaps vertically, clearing the wave. Her purple trails hang in the air like neon ribbons. Debris floats in zero-G for a split second.

[SHOT 3] · The Interception (~2.5s): Handheld shaky cam. Tsubame lands and dashes Screen Left → Screen Right. Garan swings a massive backhand. She ducks under it with fluid grace, her brown bob whipping around. The teal jacket blurs as it passes inches above her head. Speed lines emphasize velocity.

[SHOT 4] · The Slide (~2.5s): Extreme low angle, floor-level. Tsubame goes into a baseball slide across the polished floor, passing directly between Garan's legs. Her purple latex vest reflects the floor lights intensely. Garan tries to stomp down, but she's already past, kicking up a spray of digital sparks (purple/teal mix).

[SHOT 5] · The Wall Run (~1.5s): Vertical pan up. Tsubame runs horizontally along the curved corridor wall (Screen Right), defying gravity. Garan punches the wall where she was a fraction of a second ago—cracks spiderweb out in teal light. She pushes off the wall, launching herself back toward the center.

[SHOT 6] · The Clash (~1s): Extreme close-up, slow-motion impact frame. Tsubame's purple-gloved fist meets Garan's teal-sleeved forearm. The collision point blooms with white-hot light and particle sparks. Their faces are inches apart—her fierce determination vs his stoic focus. Background is a blur of motion streaks.

[SHOT 7] · The Aftermath (~3.5s): Wide shot, camera pulls back rapidly. Tsubame lands in a superhero crouch (Screen Left), sliding to a halt, purple trails fading. Garan stands firm (Screen Right), adjusting his teal collar, unbothered but acknowledging her speed. Dust motes dance in the neon light. The corridor behind them is slightly damaged (cracks, scorch marks). Both breathe heavily. Fade out.
```

Transferable per-shot elements:
- **Named shots**: "The Stare Down", "The Shockwave", "The Clash" — gives each beat a clear identity
- **Camera per shot**: static wide / low angle tracking / handheld shaky / extreme low angle / vertical pan / extreme close-up slow-motion / wide pull-back
- **Color effects in every shot**: purple trails, teal shockwave, teal jacket blur, purple vest reflection, teal spiderweb cracks, white-hot bloom, fading purple trails
- **One key action per shot**: stare → shockwave jump → dodge → slide → wall run → clash → aftermath
- **Emotional contrast**: "her fierce determination vs his stoic focus"

### Environmental Reactivity & Technical Footer

```text
Environmental activity: Holographic ads flicker on walls reacting to their movement. Floor is highly reflective (mirror-like).
Audio: Heavy bass synth track. SFX: Electric hums, heavy thuds, glass-like shattering sounds, neon buzz.
Technical: 15 seconds. 16:9 aspect ratio. No text overlays. Consistent character models (purple vest/black straps for her, teal jacket/white undersuit for him).
```

---

## Transferable Quality Checklist

When enhancing ANY prompt, check if you've applied these patterns where relevant:

- [ ] **Camera identity** — not just "handheld" but WHY handheld and what imperfections to preserve
- [ ] **Visual texture vocabulary** — specific grain/blur/exposure language, not just "cinematic"
- [ ] **Lighting transitions** — if locations change, describe the light shift at each transition
- [ ] **Pacing arc** — named build pattern (quiet→energetic, tense→release) with turning point
- [ ] **Character visual signature** — a recurring color or visual element for instant recognition
- [ ] **Wardrobe progression** — outfits mapped to locations/time with materials described
- [ ] **Spatial geography** — screen directions stated for multi-character or action sequences
- [ ] **Color lock** (action) — each character's effects/trails/reflections have a consistent color
- [ ] **Progressive continuity** — what accumulates (damage, mess, dust, exhaustion) across shots
- [ ] **Environmental reactivity** — the world responds to character action (flicker, crack, reflect)
- [ ] **Named shots** — each shot has a memorable identity beyond "Shot 3"
- [ ] **Emotional beats** — expressions and body language described, not just physical action
- [ ] **Sound design layers** — ambience, physical SFX, diegetic music, non-diegetic score all mapped
- [ ] **Voiceover discipline** — VO clearly marked, lips-closed noted, emotional narration over visuals

---

## Converting Showcase Patterns to H3 Format

The showcase examples above use a creative-brief style (CAMERA/LOOK/STYLE/Storyboard blocks). When converting to actual H3 format output:

1. **Camera identity** → weave into the style opener sentence and each shot's camera motion line
2. **LOOK/visual texture** → style opener + environment/lighting descriptions per shot
3. **STYLE/pacing** → reflected in shot count, timing distribution, and cut rhythm
4. **Character descriptions** → `subject_definitions` entries (Ref2VA) or identity anchors in each shot (Base)
5. **Storyboard shots** → `[Shot N]` entries with timestamps, camera motion, one dominant action each
6. **Color lock** → embedded in character descriptions and per-shot visual effect descriptions
7. **Spatial layout / action vectors** → woven into shot descriptions with screen direction language
8. **Continuity progression** → tracked across shots in the detailed description
9. **Environmental reactivity** → described within relevant shots
10. **Voiceover** → formatted as `"says in an off-screen voiceover"` + `<d>[Language] ...</d>` + lips-closed note
11. **Sound design** → split between `overall_soundscape` (ambience/SFX) and `non_diegetic_music` (score)
