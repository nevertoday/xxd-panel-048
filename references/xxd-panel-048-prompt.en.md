# XXD Panel 048 | Transparent Structural Blueprint Production Prompt

## Runtime complete-canvas contract — highest priority

- `TOP_BOTTOM` and `LEFT_RIGHT` default to one complete finished generation using the current source as a high-fidelity edit/reference input. Do not pre-split the job into photographic and design halves.
- Top-bottom keeps the faithful source in approximately the upper 50% and performs this style transformation below; left-right uses the faithful source in approximately the left 50% and the transformation on the right. Unify both regions through colour, light, rhythm, typography, and meaning.
- `DESIGN_ONLY` and `WALLPAPER_PACK` use the complete canvas while the source remains an invisible identity/content reference. Recompose every wallpaper separately for its device.
- `FINAL CANVAS` means the ratio/pixels of the whole finished artwork and must be explicitly resolved before generation; never apply source dimensions silently. `DESIGN FRAME` is used only if a failed complete-canvas retry triggers deterministic composition fallback.
- Retry a failed complete canvas once against the failed constraint only. Scripted composition is allowed only after that retry still fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless pixel calibration.

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is available through the current built-in image tool or a configured compatible route, use it first for the high-fidelity reference/edit and complete-canvas generation required by this prompt.
- Also support Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model only when the actual route can preserve the source, realise the whole finished canvas, render the target-language text, and accept the multiple references needed by a linked wallpaper pack.
- An alternative model changes only the generation route. It must not change this prompt's modes, canvas, source visibility, copy, locale, wallpaper relationship, or complete-canvas-first / composition-fallback-only logic. Do not silently downgrade a hard requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task, but never echo, display, log, or expose their value in chat, prompts, or diagnostics. Do not persist them or modify global route configuration unless explicitly requested.
- Judge availability by actual image capability, not by a provider name or one missing environment variable.

Process only the source photograph explicitly supplied for this fresh task. Privately lock identity, outer contour, proportion, pose, direction, action, function, spatial relation, material, and source colour. Preserve at least three source-specific cues and never borrow from another input, old output, or sample.

## Aesthetic transformation

Rebuild the recognisable subject as a transparent structural blueprint between engineering drawing, X-ray transparency, scientific illustration, and a future archive. Keep the outer contour immediately identifiable and decide what “inside” means from the subject itself: components and joints for objects, spaces and construction for architecture, propulsion and load-bearing structure for vehicles, veins and growth for plants, or pose skeleton, motion path, and clothing layers for people and animals. Never invent arbitrary machinery or use flesh-like anatomy.

Use this causal sequence: lock identity, contour, pose, and narrative relation → preserve three cues → identify the subject's meaningful internal logic → reveal selective transparent layers, cuts, and connections → organise magnification, exploded detail, axes, dimensions, nodes, and leaders into one reading path → derive one lucid monochrome system from the source → maintain generous clean space → bind technical copy to the exact structure it explains.

## Hard visual requirements

- Keep silhouette, proportion, direction, and key relations recognisable. Every revealed structure must be object-specific, not a generic pile of parts.
- Use transparency, cutaways, layer ghosting, perspective, magnified details, and exploded fragments only to explain meaningful structures. Establish hierarchy through line weight, opacity, density, and focus.
- Fine axes, dimension lines, numbered nodes, local frames, mini-diagrams, and leaders orbit the subject and never become a full-screen technology UI.
- Keep one visual centre, one legible reading path, and generous blank space. Reject ordinary tracing, CAD-screenshot literalism, and cheap HUD decoration.
- Derive a light ground, one principal line colour, and a few tonal steps from the source's most characteristic spirited colour. Blue, green, red, orange, violet, or neutral may be right; never silently default to blue, muddy grey, darkness, neon, or complex multicolour.

## Copy and locale

Obey the resolved automatic, exact-user, or text-free mode and target locale. Automatic copy uses one concise title derived from identity, function, state, action, or symbolic meaning plus only essential component names, state words, directions, dimensions, numbers, or micro-notes. Every text element must connect through a real leader, scale, node, section, or edge to what it explains. Do not introduce a year or long explanatory copy. Preserve exact user wording verbatim. Text-free output contains no characters, numbers, labels, or pseudo-text.

## Mode and acceptance


Reject ordinary line art, generic blueprints, fixed blue, arbitrary machinery, anatomical gore, complex technology UI, dense annotation, neon cyberpunk, multicolour dashboards, unreadable pseudo-technical text, logos, watermarks, swatches, device mockups, and unsupported facts.

If any hard condition fails, correct the generated bitmap. Never fake the artwork with programmatic drawing, SVG, HTML, Canvas, 3D code, or post-composited type.
