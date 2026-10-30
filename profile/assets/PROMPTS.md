# CompleteTech Security illustration provenance

## profile/assets/banner.jpg (illustration composited by showcase.py org-banner)
- Date: 2026-10-29
- Tool and model: built-in image_gen.imagegen / model ID and version not exposed by this tool (not inferred).
- Seed: not supported
- Reference images: none supplied to the image model. The compositor reads the committed CompleteTech dark master from the skill configuration.
- Prompt: candidates 1–4, verbatim:
```text
[STYLE LOCK — FAMILY]
Clean glossy isometric 3D product illustration, orthographic isometric camera from the front-left. Every scene sits on one rounded-rectangle platform: deep navy (#001F3F) top, ink (#0F172A) sides, a thin glowing sky-blue (#00A7FD) edge line, floating above an empty background with a soft contact shadow. Objects are smooth satin plastic in sky blue (#00A7FD), azure (#0081ED), royal blue (#005ADD) and off-white (#F1F5F9), with small warm-gold (#FFC300) details. Glass parts are frosted translucent blue. Thin gold circuit traces ending in round solder pads link the objects across the platform top. Soft rounded geometry, subtle bevels, bloom on gold details only, key light from the upper left, calm and uncluttered.

[SUBJECT]
A blank shield over rack server units, blank tag cards; one tag card in #E11D48 as the finding.

[OBJECTS]
One shield, two rack server units, two blank tag cards (one off-white, one rose).

[COMPOSITION]
Isolated platform and objects on a perfectly flat, untextured #0F172A background; no floor, grid, gradient or glow touching the edges; 10% empty margin on all sides. Wide 1536x1024.

[PALETTE]
Use only these colors: #0F172A, #001F3F, #00A7FD, #0081ED, #005ADD, #FFC300, #F8FAFC, #F1F5F9, #64748B, #E11D48. Gold #FFC300 is for small details only. Rose #E11D48 appears on the single finding object only.

[EXCLUSIONS]
No text, letters, numbers, symbols, words, labels, signatures, watermarks, logos, brand marks or interface text; every paper, screen and sign surface stays blank. No people, human faces or human hands. No photorealism, no clutter, no extra objects. No skulls, hackers or padlocks with keyholes. No vendor logos or recognizable product designs.
```
- Prompt: candidates 5–8, verbatim:
```text
[STYLE LOCK — FAMILY]
Clean glossy isometric 3D product illustration, orthographic isometric camera from the front-left. Every scene sits on one rounded-rectangle platform: deep navy (#001F3F) top, ink (#0F172A) sides, a thin glowing sky-blue (#00A7FD) edge line, floating above an empty background with a soft contact shadow. Objects are smooth satin plastic in sky blue (#00A7FD), azure (#0081ED), royal blue (#005ADD) and off-white (#F1F5F9), with small warm-gold (#FFC300) details. Glass parts are frosted translucent blue. Thin gold circuit traces ending in round solder pads link the objects across the platform top. Soft rounded geometry, subtle bevels, bloom on gold details only, key light from the upper left, calm and uncluttered.

[SUBJECT]
A blank shield over rack server units, blank tag cards; one tag card in #E11D48 as the finding.

[OBJECTS]
One shield, two rack server units, two blank tag cards (one off-white, one rose).

[COMPOSITION]
Isolated platform and objects on a perfectly flat, untextured #0F172A background; no floor, grid, gradient or glow touching the edges; 10% empty margin on all sides. Wide 1536x1024.

[PALETTE]
Use only these colors: #0F172A, #001F3F, #00A7FD, #0081ED, #005ADD, #FFC300, #F8FAFC, #F1F5F9, #64748B, #E11D48. Gold #FFC300 is for small details only. Rose #E11D48 appears on the single finding object only.

[EXCLUSIONS]
No text, letters, numbers, symbols, words, labels, signatures, watermarks, logos, brand marks or interface text; every paper, screen and sign surface stays blank. No people, human faces or human hands. No photorealism, no clutter, no extra objects. No skulls, hackers or padlocks with keyholes. No vendor logos or recognizable product designs.

[FRAMING PRECISION]
Render exactly 1536x1024 pixels. Pull camera back: the entire platform, all objects AND the entire soft contact shadow must fit strictly inside x=230..1306 and y=154..870. All remaining outer margin must be perfectly flat #0F172A. Keep every visual element INCLUDING shadow well clear of the outer 10% on every side.
```
- Candidates: 8; selected: 5 (reason: first candidate with the complete shield, two servers and two blank tags inside the required margin, a single rose finding, and passing palette and surface review).
- Candidate decisions: 1–4 rejected for foreground/shadow entering the 10% margin; 5–8 pass dimensions, palette and margin checks. Selection follows invocation order, not aesthetic preference.
- Post-processing: showcase.py 1.0.0 (ct-std-v1); custom background extraction in process_art.py follows the skill's CIE76 ΔE ≤ 6 threshold against #0F172A, Gaussian 2 px inward feather and edge decontamination. Canvas retained at 1536×1024, RGBA. No objects drawn or retouched by code.
- Output org-illustration.png: sha256 cdbbc32f2db1f1dcdc5790a4f9a839ad3f5fbca9f03e4c3c5ecafb9fab47121b; 698525 bytes (698.525 KB).
- Output banner.jpg: sha256 641865a1b1daf23333ffa8b5b61f4b8b6f080028242360c6c657319729b72439; 62163 bytes (62.163 KB); 1600×400 RGB JPEG, quality 85, opaque.
- Render command (run from <skill checkout>\target with PYTHONIOENCODING=utf-8 and PYTHONDONTWRITEBYTECODE=1):
```powershell
..\venv\Scripts\python ..\skill\scripts\showcase.py org-banner --org CompleteTech-Security --illustration <work dir>\org-illustration.png --out <work dir>\banner.jpg
```
- QA: 8-colour quantization, each cluster ≥5% within CIEDE2000 ≤12 of the supplied palette; source foreground box [282,188,1265,885] inside the 10% margin. Blank surfaces and absence of people, faces, third-party marks, prohibited security objects and extra scene objects reviewed. Selected illustration inspected using the 200% enlargement. Banner viewed at 1012 px and 390 px, shield/server/tag grouping remains recognizable. Committed brand master is preserved, not redrawn. The illustration contains no text; banner typography is inherited from the committed master.
- Alt text: CompleteTech LLC branding beside a blue shield, two stacked rack servers and two blank tags, one white and one rose, on a navy platform with gold circuit traces.

## assets/icon.png
- Date: 2026-10-29
- Tool and model: built-in image_gen.imagegen / model ID and version not exposed by this tool (not inferred).
- Seed: not supported
- Reference images: none
- Prompt: candidates 1–4, verbatim:
```text
[STYLE LOCK — FAMILY]
Clean glossy isometric 3D product illustration, orthographic isometric camera from the front-left. Every scene sits on one rounded-rectangle platform: deep navy (#001F3F) top, ink (#0F172A) sides, a thin glowing sky-blue (#00A7FD) edge line, floating above an empty background with a soft contact shadow. Objects are smooth satin plastic in sky blue (#00A7FD), azure (#0081ED), royal blue (#005ADD) and off-white (#F1F5F9), with small warm-gold (#FFC300) details. Glass parts are frosted translucent blue. Thin gold circuit traces ending in round solder pads link the objects across the platform top. Soft rounded geometry, subtle bevels, bloom on gold details only, key light from the upper left, calm and uncluttered.

[SUBJECT]
A single hero blank shield over one rack server unit, one blank rose #E11D48 tag card as the finding.

[OBJECTS]
One shield, one rack server unit, one blank rose tag card.

[COMPOSITION]
Isolated platform and objects on a perfectly flat, untextured #F8FAFC background; no floor, grid, gradient or glow touching the edges; 10% empty margin on all sides. Square 1024x1024.

[PALETTE]
Use only these colors: #0F172A, #001F3F, #00A7FD, #0081ED, #005ADD, #FFC300, #F8FAFC, #F1F5F9, #64748B, #E11D48. Gold #FFC300 is for small details only. Rose #E11D48 appears on the single finding object only.

[EXCLUSIONS]
No text, letters, numbers, symbols, words, labels, signatures, watermarks, logos, brand marks or interface text; every paper, screen and sign surface stays blank. No people, human faces or human hands. No photorealism, no clutter, no extra objects. No skulls, hackers or padlocks with keyholes. No vendor logos or recognizable product designs.
```
- Prompt: candidates 5–8, verbatim:
```text
[STYLE LOCK — FAMILY]
Clean glossy isometric 3D product illustration, orthographic isometric camera from the front-left. Every scene sits on one rounded-rectangle platform: deep navy (#001F3F) top, ink (#0F172A) sides, a thin glowing sky-blue (#00A7FD) edge line, floating above an empty background with a soft contact shadow. Objects are smooth satin plastic in sky blue (#00A7FD), azure (#0081ED), royal blue (#005ADD) and off-white (#F1F5F9), with small warm-gold (#FFC300) details. Glass parts are frosted translucent blue. Thin gold circuit traces ending in round solder pads link the objects across the platform top. Soft rounded geometry, subtle bevels, bloom on gold details only, key light from the upper left, calm and uncluttered.

[SUBJECT]
A single hero blank shield over one rack server unit, one blank rose #E11D48 tag card as the finding.

[OBJECTS]
One shield, one rack server unit, one blank rose tag card.

[COMPOSITION]
Isolated platform and objects on a perfectly flat, untextured #F8FAFC background; no floor, grid, gradient or glow touching the edges; 10% empty margin on all sides. Square 1024x1024.

[PALETTE]
Use only these colors: #0F172A, #001F3F, #00A7FD, #0081ED, #005ADD, #FFC300, #F8FAFC, #F1F5F9, #64748B, #E11D48. Gold #FFC300 is for small details only. Rose #E11D48 appears on the single finding object only.

[EXCLUSIONS]
No text, letters, numbers, symbols, words, labels, signatures, watermarks, logos, brand marks or interface text; every paper, screen and sign surface stays blank. No people, human faces or human hands. No photorealism, no clutter, no extra objects. No skulls, hackers or padlocks with keyholes. No vendor logos or recognizable product designs.

[FRAMING PRECISION]
Render exactly 1024x1024 pixels. The entire platform and its shadow must be SMALLER in frame, all within the central 70% of the image: bounding rectangle x=154..870, y=154..870. Leave at least 154 pixels of completely blank background on EVERY side. Pull the camera back. The platform must never approach the side edges.
```
- Candidates: 8; selected: 5 (reason: first candidate with the shield, one server and one blank rose tag inside the required margin, passing palette review and the skill's normalized-icon checks).
- Candidate decisions: 1–4 rejected for side-margin intrusion; 2 and 4 also fail the palette check. Candidates 5 and 6 pass source palette and margins; 7 and 8 fail palette. All square source images were returned as 1254×1254 despite requesting 1024×1024; the prescribed icon normalization produces the required final 1024×1024. Source dimensions are recorded rather than claimed to match.
- Post-processing: showcase.py 1.0.0 (ct-std-v1), content icon normalize --ground transparent. The skill detects source ground #F7F9FB, keys CIE76 ΔE ≤6 with 2 px inward feather, trims [208,304,1054,980], fits the 688 px live area on a transparent 1024×1024 canvas, and quantizes to 256 colours for budget. The indexed PNG was decoded to RGBA and losslessly re-saved so the final PNG is true RGBA; content icon check was then rerun on that final file.
- Output icon.png: sha256 ba37626f6fac67f48f6af6f27bb3411730ab04cd8f8c2bf592b30fb6f4c968ad; 138004 bytes (138.004 KB); 1024×1024 RGBA PNG.
- Commands (from the working folder, with PYTHONIOENCODING=utf-8 and PYTHONDONTWRITEBYTECODE=1):
```powershell
<skill workdir>\venv\Scripts\python <skill workdir>\skill\scripts\showcase.py --no-repo-dir --meta out\icon-meta.json content icon normalize --in out\icon5.png --ground transparent --out out\icon.png --preview out\icon-48.png --report out\icon-normalize.json
<skill workdir>\venv\Scripts\python <skill workdir>\skill\scripts\showcase.py --no-repo-dir --meta out\icon-meta.json content icon check --out out\icon.png --art-direction <skill workdir>\skill\references\art-direction.md --report out\icon-check.json
```
- QA: content icon check result pass; source foreground box [207,304,1055,980] inside the 10% margin, 8-colour CIEDE2000 palette check passes. Final live area [168,237,856,787], coverage 18.9%, transparent corners, dominant ink contrast 14.26:1 against #F8FAFC, and not-org-glyph check passes. Blank shield, server surfaces and tag inspected using the 200% enlargement; no letters, numbers, logos, people or prohibited security objects. Final 48 px preview and light-card presentation reviewed.
- Alt text: A blank blue-and-white shield above one rack server beside a blank rose tag, on a navy platform linked by thin gold circuit traces.
