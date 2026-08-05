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

---

## Pattern 3: Action Choreography — Wing Chun Street Fight (T2VA, 15s, 5 shots)

A grounded martial-arts fight emphasizing realistic technique, era-specific atmosphere, and progressive combat exhaustion. Shows how to choreograph a one-versus-many fight within the 5-shot budget.

### Key Patterns
- **Era-specific styling**: 1950s New York noir — cobblestone, fire escapes, fedoras, wool overcoats, film grain
- **Technique-specific choreography**: Named Wing Chun techniques (pak sao, tan sao, chain punches) ground the action in realism
- **One-dominant-action-per-shot discipline**: Each shot handles exactly one attacker exchange
- **Progressive exhaustion**: Yi Man calm throughout; attackers accumulate on the ground shot by shot
- **Environmental sound design**: Rain drumming, cobblestone splashes, cloth impacts — no music during combat, score cuts to silence on the final takedown

### Output

```
integrated_multimodal_description: [Shot 1] Cinematic live-action, 1950s film-noir aesthetic with high-contrast chiaroscuro lighting, shallow depth of field, and visible 35mm film grain. A wide static shot establishes a narrow New York back alley at night in heavy rain — wet cobblestone ground reflecting a single overhead streetlamp, brick walls on both sides dripping with water, iron fire escapes climbing the left wall, and a chain-link fence partially visible at the far end. YI MAN, a lean Chinese man in his late thirties with a calm composed expression, short black hair slicked from the rain, wearing a dark charcoal traditional Chinese cotton jacket with cloth buttons, dark trousers, and thin-soled cloth shoes, stands alone in the center of the alley under the streetlamp glow, hands at his sides. Four men in 1950s street clothing — a heavyset man in a brown wool overcoat and fedora, a wiry man in a leather jacket and flat cap, a broad-shouldered man in a dark-grey raincoat, and a younger man in a white undershirt and suspenders — spread out in a semicircle facing him from Screen Right to Screen Left, approximately five meters away. Rain pours steadily. The camera pushes in with small amplitude at slow speed toward Yi Man, isolating him against the dark alley, then holds.
[Shot 2] At 00:03.000, the shot cuts to a medium tracking shot at fast speed moving with Yi Man as he closes the distance toward the wiry man in the leather jacket and flat cap on Screen Right. Yi Man's hands rise into a relaxed Wing Chun guard — elbows tucked, hands open at centerline. The wiry man in the leather jacket throws a wide right hook. Yi Man slips inside the arc with a compact lateral step, his left hand executing a pak sao (slapping block) that deflects the hook outward, and immediately fires a chain of three straight punches into the man's chest and jaw using vertical-fist Wing Chun technique. The impacts are fast, precise, and audible over the rain. The wiry man stumbles backward into the brown-overcoat man behind him. Rain sprays off their shoulders with each impact. The camera shakes slightly during the exchange.
[Shot 3] At 00:06.000, the shot cuts to a low-angle medium shot from ground level, tilted up at Yi Man as the broad-shouldered man in the dark-grey raincoat and the younger man in the white undershirt and suspenders rush him simultaneously from Screen Left. Yi Man pivots on the balls of his feet, his thin-soled cloth shoes gripping the wet cobblestone. He intercepts the younger man's lunging grab with a tan sao (palm-up blocking arm) that redirects the momentum past his right side, then strikes the younger man's solar plexus with a sharp vertical punch. The broad-shouldered man in the raincoat swings a heavy haymaker. Yi Man ducks under it with a slight knee bend and delivers a low Wing Chun front kick to the raincoat man's lead knee, buckling his stance. Both attackers stagger. Water splashes from puddles beneath their feet. The camera arcs right with medium amplitude at fast speed, tracking the redirection of force.
[Shot 4] At 00:09.000, the shot cuts to a close-up handheld shot with strong shake, framing Yi Man from chest to head as the heavyset man in the brown wool overcoat and fedora — the last one standing — grabs Yi Man from behind in a bear hug, locking his arms at his sides. Yi Man's expression stays focused, not panicked. He drops his weight low, stomps his heel onto the heavyset man's instep, and as the grip loosens, throws a sharp backward elbow strike to the man's ribs, followed by a spinning backfist that connects with the heavyset man's jaw. The fedora flies off into the rain. The heavyset man's eyes glaze and he drops to his knees on the wet cobblestone, then falls forward. Rain streaks across the frame. Yi Man's dark charcoal jacket is now darkened with rain across the shoulders and forearms. The camera pulls back with small amplitude to reveal two other men on the ground behind Yi Man and one slumped against the brick wall.
[Shot 5] At 00:12.000, the shot cuts to a wide static shot from the far end of the alley, behind the fallen attackers. All four men lie on the wet cobblestone — two face-down in puddles, one slumped against the brick wall holding his ribs, and the heavyset man in the brown overcoat face-up with his fedora floating in a nearby puddle. Yi Man, the lean Chinese man in his dark charcoal Chinese cotton jacket, stands alone in the center of the alley under the streetlamp, his breathing slightly elevated but his expression composed and still. He lowers his hands slowly to his sides, rolls his shoulders once, and turns to walk toward the far end of the alley into the rain and shadow. The wet cobblestone reflects his retreating silhouette and the dim glow of the streetlamp. Rain continues to fall steadily. The camera holds on the empty alley as the last of the fallen men groans faintly.

overall_soundscape: Heavy rain pours continuously throughout the scene, striking cobblestone, brick walls, metal fire escapes, and puddles with a relentless drumming hiss. Rapid footsteps shuffle and slap on wet stone as fighters reposition. Fists strike cloth and flesh with dull, muffled thuds, and a heavy body hits the wet ground with a wet slap. A faint groan of pain is audible from a fallen attacker in the final shot.

non_diegetic_music: A brooding tension-building score begins with a low sustained double bass drone and sparse, dissonant piano notes that hang in the air during the standoff. As the fighting erupts, a driving rhythmic pulse enters — staccato strings and a muted taiko drum pattern at a fast tempo that accelerates through the combat shots, then cuts abruptly to silence when the last attacker falls, leaving only the rain.
```

---

## Pattern 4: Samurai vs Ninja — Chambara Sword Duel (T2VA, 15s, 5 shots)

A Japanese period-piece duel emphasizing tension-building pacing, stealth choreography, and the chambara film tradition of stylized violence. Shows how to handle a one-on-one fight that ends in assassination rather than victory.

### Key Patterns
- **Chambara aesthetic**: Black-and-yellow moonlit tones, volumetric fog, stone lanterns, temple courtyard
- **Pacing arc**: Frozen tension → rapid exchanges → sudden stealth → intimate kill → cold aftermath
- **Camera-as-character**: Lateral tracking matches dodge rhythm; camera roll matches ninja spin; slow push to impact point for the kill
- **Single turning point**: One taiko drum boom at the tanto draw divides the entire video into suspense and consequence
- **Stylized violence**: Blood appears near-black in moonlight (chambara tradition), one arc spray, not gratuitous
- **Environmental shift**: Fog thickens across shots; rain absent until the kill, then begins lightly — atmospheric punctuation

### Output

```
integrated_multimodal_description: [Shot 1] Cinematic live-action, Japanese chambara film aesthetic with high-contrast black-and-yellow moonlit tones, volumetric fog drifting between dark wooden architecture, shallow depth of field, and fine 35mm film grain. A wide static shot establishes a narrow temple courtyard at night — wet stone tiles reflecting cold moonlight, a stone lantern glowing faintly on the left, wooden temple walls with sliding screen doors on both sides, and low hanging mist clinging to the ground. THE SAMURAI, a tall Japanese man in his forties with a stern weathered face, topknot hairstyle, wearing dark indigo armor plates laced with black silk cord over a layered grey kimono, dark hakama trousers, and straw sandals, stands in the center of the courtyard gripping a katana in a two-handed middle guard, blade raised at eye level pointing forward. Opposite him, ten meters away, THE NINJA — a shorter lean figure wrapped entirely in dark charcoal-black cloth with only a narrow slit for the eyes, black tabi boots, a short ninjato sword strapped across his back — crouches low in a side stance, motionless. Fog drifts between them. The camera holds on this standoff for a beat, then pushes in with small amplitude at slow speed toward the gap between them. Moonlight glints off the samurai's katana blade.
[Shot 2] At 00:03.000, the shot cuts to a medium tracking shot moving at fast speed laterally from Screen Left to Screen Right, following the exchange. The samurai — in his dark indigo armor and topknot — steps forward and swings his katana in a powerful downward diagonal cut. The ninja — wrapped in black cloth, only eyes visible — pivots left, the blade missing his shoulder by inches, moonlight flashing on the steel as it slices through fog. The samurai immediately reverses into a horizontal side cut. The ninja drops low and ducks right, the katana whistling over his head, his black tabi boots sliding on the wet stone tiles. A third overhead strike — the ninja sidesteps left again with fluid precision, each evasion minimal and efficient. Sparks fly where the katana tip grazes a stone tile. The camera tracks the ninja's lateral dodging path, panning left then right then left with medium amplitude at fast speed, matching his evasion rhythm. The samurai's grey kimono sleeves snap with each swing.
[Shot 3] At 00:06.500, the shot cuts to a low-angle close-up from ground level tilted up at the ninja as he executes a sudden spinning side-turn — his body drops almost parallel to the wet stone tiles, black cloth rippling, as he rotates beneath the samurai's reaching guard in a tight spiral. The camera rolls clockwise with small amplitude at fast speed to match the spin, capturing the ninja's body sweeping past the samurai's armored legs in a blur of dark fabric. Wet stone tiles and mist fill the foreground. The ninja's tabi boots push off the ground with a muffled scrape. In a fraction of a second he has passed entirely behind the samurai, who is still mid-recovery from his missed strike, his katana extended forward into empty air. The ninja rises silently behind the samurai's right shoulder, his movement invisible to his opponent.
[Shot 4] At 00:09.000, the shot cuts to a close-up framed on the ninja's hands from behind the samurai's right shoulder. The ninja's right hand, wrapped in black cloth, draws a tanto — a short dagger with a plain dark wooden handle and a thin gleaming steel blade — from a concealed sheath at his lower back in one swift upward pull. The blade catches a sliver of moonlight. In a single fluid motion, the ninja drives the tanto forward into the exposed side of the samurai's neck, just above the indigo armor plates and below the topknot. The blade sinks in to the hilt. The samurai's eyes widen — his stern composure breaks into shock, his mouth opening slightly, his katana grip going slack. His fingers loosen on the katana handle. The camera pushes in with small amplitude at slow speed toward the point of impact, the tanto handle visible against the samurai's grey kimono collar and dark indigo armor lacing.
[Shot 5] At 00:11.500, the shot cuts to a medium shot, slightly low angle, framing both figures from the front as the ninja — still behind the samurai's right shoulder — pulls the tanto blade out in a sharp horizontal draw. Blood sprays from the samurai's neck wound in an arc that catches the cold moonlight, the droplets appearing almost black against the lit stone tiles and mist. The samurai's knees buckle, his dark indigo armor plates clacking as his posture collapses. His katana slips from his fingers and clatters onto the wet stone. The ninja steps back two paces into the fog, tanto held at his side, blood on the blade glinting faintly. The samurai — tall, topknot, grey kimono, indigo armor — sinks to his knees, one hand rising weakly toward his neck, then falls forward onto the wet courtyard tiles. Fog rolls over his fallen body. The camera holds static on the scene as the ninja turns and dissolves into the dark shadow between the temple walls, leaving only the stone lantern glow and the fallen samurai in frame. Rain begins to fall lightly on the blood-spattered stone.

overall_soundscape: A heavy silence dominates the temple courtyard, broken only by the faint scrape of straw sandals and tabi boots shifting on wet stone tiles. The katana cuts through cold air with a sharp metallic whistle on each swing, and stone sparks ping faintly when the blade grazes tile. A muffled cloth rustle signals the tanto being drawn from its hidden sheath, followed by a wet, subdued impact on the neck strike. The katana clatters on stone as it drops, and armor plates clack sharply when the samurai's body collapses. Light rain begins tapping the courtyard in the final seconds.

non_diegetic_music: A single sustained high note on a bamboo flute holds through the standoff and sword exchanges, tense and airy. When the tanto is drawn, a deep taiko drum strikes once — a single boom that resonates and decays through the neck strike. As the samurai falls, a sparse, mournful shamisen pluck enters at a very slow tempo, its dissonant tone hanging unresolved as rain begins to fall and the scene fades.
```

---

## Pattern 5: Anime Fight — SeeDance to H3 Conversion (T2VA, 15s, 5 shots)

A 2D anime-style fight converted from a SeeDance-format prompt. Shows how to consolidate 7 timestamped segments into the H3 5-shot budget without losing any choreography beat, and how to convert external prompt formats into H3 structure.

### Key Patterns
- **Segment consolidation**: 7 SeeDance segments → 5 H3 shots by merging the orbit-into-clinch and snap-impact sequences
- **Character color lock**: BULLDOG = burnt orange/rust/gold; VIPER = olive green/black/white tape — each character's palette consistent across every shot
- **Anime aesthetic specification**: 2D semi-realistic concept art, cel shading, clean lineart, 24fps motion feel, subtle film grain
- **Camera style preservation**: Alternating low-angle wides with violent snap-in extreme close-ups, whip pans, handheld energy — no smooth glides
- **Slow-motion beat**: Brief slow-mo at the apex of the dual lunge, then hard snap back to full speed
- **Audio architecture**: Percussive drums building intensity synced to strikes, bass drop on final impact, then cut to near-silence with only breathing

### Output

```
integrated_multimodal_description: [Shot 1] 2D semi-realistic anime concept art, clean confident lineart, painterly cel shading with soft gradients, subtle film grain, 24fps motion feel. A muted palette of burnt orange, olive green, warm gray concrete, and dusty sunset gold. A low-angle wide full shot frames a gritty back-street lot at sunset — cracked concrete ground, chain-link fence topped with razor wire, graffiti-covered walls, palm trees, and parked cars. Warm orange dusk light casts long hard shadows across the lot. BULLDOG — a heavyset, powerful woman with broad shoulders, deep tan skin, buzzed rust-orange fade hair, gold hoop earrings, a nose ring, wearing a burnt-orange cropped tank top, a thin gold chain, baggy gray sashed pants, blood-stained white hand wraps, gold knuckle rings, and gray high-top sneakers — and VIPER — a lean, athletic woman with deep tan skin, long black ponytail with blunt bangs, green eyes, a small black shoulder tattoo, wearing an olive sports bra, black shorts, black fingerless gloves over white taped wrists, tan ankle braces, and white sneakers — face each other at mid-distance in profile, guards raised, circling clockwise. Sneakers scuff on gravel. The camera tracks right at slow speed, orbiting with their circle, keeping both fighters fully in frame against the hazy sunset backdrop.
[Shot 2] At 00:03.000, the shot cuts to a tight over-the-shoulder shot from behind BULLDOG, still in her burnt-orange tank top and gold knuckle rings, looking past her wrapped fist toward VIPER. BULLDOG fires a heavy straight punch — her blood-stained white hand wrap and gold knuckle ring passing close by the lens in motion blur. VIPER, her green eyes tracking the fist, slips it with a sharp head snap to the side, her long black ponytail whipping across the frame. The punch misses by inches. The camera shakes slightly with handheld energy, emphasizing the miss. Dust motes float in the warm sunset light between them.
[Shot 3] At 00:06.000, the shot whip-pans to a medium full shot from the opposite side. VIPER counters immediately — her white-taped wrists and black fingerless gloves firing a fast one-two straight combination into BULLDOG's guard, followed by a sharp rising knee. BULLDOG, in her burnt-orange tank top and gold chain, absorbs the strikes on crossed forearms, her heavyset frame driven back two heavy steps, gray high-top sneakers scraping cracked concrete, dust kicking up from the impact. The camera tracks backward at fast speed with them, low horizon line, both fighters' bodies fully visible, long sunset shadows stretching behind them. BULLDOG's rust-orange fade and gold hoop earrings catch the warm light as she steadies.
[Shot 4] At 00:09.000, the shot cuts to a dynamic low wide shot. Both fighters — BULLDOG in burnt-orange and gray, VIPER in olive and black — lunge at each other simultaneously, bodies stretched long, one foot off the ground each, silhouetted against the bright hazy sunset sky. At the apex of the lunge the motion shifts to brief slow motion, sunset light rim-lighting both figures, then snaps hard back to full speed as their fists collide against each other's guards. The impact sends dust and gravel spraying. The camera then orbits tightly around the resulting clinch — chain-link fence and graffiti wall sweeping through the background as BULLDOG and VIPER trade short hooks and elbows at close range, shoulders grinding, feet shuffling on cracked concrete, ponytail and rust-orange fade visible in the tight orbit.
[Shot 5] At 00:11.500, the shot cuts to an extreme close-up as VIPER's taped fist — white tape over black fingerless glove — drives directly toward the lens, filling the frame in heavy motion blur. The punch lands. The camera snaps instantly to BULLDOG's face in extreme close-up — her head torquing violently sideways, sweat flying from her buzzed rust-orange fade, gold hoop earring swinging, eyes squeezed shut, the frame shaking hard on contact. At 00:13.500 the camera pulls back fast to a low-angle wide shot. BULLDOG drops to one knee on the cracked pavement, head down, shoulders heaving in her burnt-orange tank top, gold chain dangling. VIPER stands a few paces away in her olive sports bra and black shorts, guard lowering, chest rising and falling, black ponytail settling against her back. Both fighters are backlit against the glowing sunset haze. The camera slows to a held final frame on this aftermath.

overall_soundscape: Sneakers scuff and grind on gravel and cracked concrete throughout, with dust-shifting crunches on every heavy step. Fists strike guards and flesh with sharp percussive thwacks, and fabric rustles sharply during each exchange. Heavy breathing from both fighters grows more labored as the fight progresses. Distant city traffic hum provides a low ambient bed beneath the action.

non_diegetic_music: Gritty low percussive drums build steadily in intensity from the opening standoff, layering in sharper hi-hat patterns and deeper kick hits that sync to each landed strike. The rhythm tightens and accelerates through the clinch, peaks with a heavy bass drop on the final punch impact, then cuts abruptly to near-silence — leaving only the fighters' breathing over the final held frame.
```
