# Part 4 · AI Video Clip Prompts (B-roll)
### For Higgsfield / Veo / Runway / Kling / Sora — drop these under the HeyGen avatar track

Every clip: **no text baked in** (HeyGen adds the typography), **no dates**, **no readable
faces of real staff**, 16:9 primary + 9:16 reframe. Keep each generation to the stated length —
you only need 2–4 seconds of usable motion per cut.

---

### CLIP 01 — Circuit Ignition (Scene 1 · 4s)
```
Macro shot of thin glowing neon circuit traces igniting and racing inward across a dark deep-indigo to violet gradient surface, converging toward the center of frame where they meet in a soft cyan bloom. Tiny floating dust particles drift through the light. Cinematic, high contrast, volumetric glow, shallow depth of field, seamless loopable motion. Colors strictly deep indigo #0A0B2E, violet #1A0B3D, neon cyan #22D3EE, hints of neon green. No text, no logos, no people. 4 seconds, slow steady camera push-in.
```

### CLIP 02 — Robot Mascot Announces (Scene 1 + 6 · 4s)
```
A friendly glossy white 3D robot character with large glowing cyan eyes and rounded headphone-style ear discs, seated at a modern laptop, looks up at camera and raises one index finger as if making an announcement, then gives a small confident nod. Pixar-style 3D render, soft studio key light with cyan rim light, dark indigo-violet background with faint neon circuit bokeh. Friendly and playful, not menacing. Centered composition, subtle handheld float. 4 seconds. No text, no logos.
```
> *Reuse this exact prompt for Scene 6 but change the action to: "raises both arms up in celebration, confetti glints catching the light."*

### CLIP 03 — The Notification Ripple (Scene 2 · 3s)
```
Dark modern open-plan office at dusk, rows of monitors glowing. A single soft amber notification pulse ripples outward from screen to screen across the room in sequence, each display briefly flaring warm amber. Anamorphic lens flare, deep shadows, moody cinematic teal-and-amber grade, slow dolly-right camera move. People visible only as out-of-focus silhouettes, no recognizable faces. 3 seconds. No text on any screen.
```

### CLIP 04 — Calendar Card Materializes (Scene 3 · 3s)
```
A translucent frosted-glass card with a glowing 1px neon-green border materializes and settles in mid-air against a dark indigo-violet gradient, a soft green checkmark icon pulsing at its left edge. Volumetric light rays behind it, small particles drifting upward, faint circuit-trace pattern in the deep background. Clean premium UI-motion aesthetic, gentle parallax, camera slowly orbits 8 degrees. 3 seconds. Absolutely no text, numbers, dates or characters on the card — leave the card face empty.
```

### CLIP 05 — Tech + Non-Tech Split (Scene 3 · 3s)
```
Split-screen composition. Left half: hands typing fast on a mechanical keyboard, code reflections in glasses, cool cyan lighting. Right half: a person at a whiteboard sketching a workflow diagram with a marker, warm blue lighting. Both halves push toward center and the dividing line dissolves in a soft neon glow as the two scenes merge into one frame. Cinematic, shallow depth of field, dark modern office. Faces out of focus or cropped. 3 seconds. No text.
```

### CLIP 06 — The Three Criteria Icons (Scene 4 · 4s)
```
Three glowing holographic icons float and rotate slowly in a row against a dark indigo-violet void: a neon stopwatch with its hand sweeping backwards, a stylized coin stack dissolving into light particles, and a glowing brain made of circuit pathways firing pulses along its lines. Each icon has a magenta and cyan neon rim glow and casts light onto the atmospheric haze around it. Premium 3D render, soft bloom, slow orbital camera. 4 seconds. No text, no numbers, no currency symbols.
```

### CLIP 07 — Trophy Reveal (Scene 5 · 4s)
```
A polished gold trophy rises slowly out of darkness into a beam of light, rotating gently on its vertical axis as a specular highlight sweeps across its surface. Golden particles and light motes swirl upward around it. Background is a dark indigo-violet gradient with faint neon circuit traces catching gold reflections. Hero product-shot lighting, cinematic bloom, shallow depth of field, 4 seconds. No text, no engraving, no logos on the trophy.
```

### CLIP 08 — The Walk-In (Scene 6 · 4s)
```
Slow-motion wide shot from behind: a diverse group of eight modern office colleagues in business-casual clothing walk together toward a bright glowing doorway of a presentation room, backlit so they read as confident silhouettes with rim light. Laptops and notebooks under their arms. Warm light spills from the doorway into a cool blue corridor with faint neon accent lighting along the floor. Cinematic anamorphic, subtle lens flare, gentle handheld camera following behind. 4 seconds. No faces visible, no text, no signage.
```

### CLIP 09 — Logo Endcard Ambience (Scene 6 · 3s, loopable)
```
Abstract slow-drifting background loop: deep indigo-to-violet gradient with soft radial glow from top-center, thin neon cyan and green circuit traces slowly pulsing light along their paths, fine dot-grid particles floating upward, gentle atmospheric haze. Extremely subtle motion, perfectly loopable, designed as a backplate for a centered logo. 3 seconds. Completely empty center third — no objects, no text.
```

---

### Generation settings that matter

| Setting | Value | Why |
|---|---|---|
| Motion strength | **Low–medium** | These sit *behind* text; heavy motion fights the typography |
| Camera | One move per clip only | Push-in **or** orbit, never both |
| Frame rate | 24 fps (30 if matching HeyGen default) | Cinematic B-roll feel |
| Negative prompt | `text, watermark, logo, letters, numbers, dates, calendar, subtitles, distorted faces, extra fingers` | Stops baked-in typography clashing with HeyGen's |
| Center third | Keep clear on all clips | That's where HeyGen puts the cards |
