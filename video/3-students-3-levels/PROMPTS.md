# 1LIM Academy — "Same Questions. Different English Levels."

Production prompt pack for AI video generators (Veo 3, Sora 2, Kling, Runway, etc.).

- **Format:** vertical 9:16, 1080×1920, 4K source if available, 24–25 fps
- **Estimated runtime:** ~3:00–3:35 total (≈ 1:00–1:10 per question), depending on speaking pace
- **Clips:** 1 intro + 3 question cards + 9 answers + 1 outro = 14 generations (answers split into ≤8 s sub-clips where the tool requires it — see `//` markers)

---

## 0. How to use this pack (read first)

1. **Generate each clip separately.** Paste the **GLOBAL STYLE BLOCK** + the relevant **CHARACTER BLOCK** + the clip prompt. Never ask one generation to do the whole video.
2. **Dialogue length vs. clip length.** Most tools cap a clip at ~8 s (Veo) or ~10–20 s (Sora/Kling). Each answer below is pre-split with `//` at natural sentence breaks so every piece fits in ~8 s. If your tool allows longer clips, merge pieces.
3. **Keep the dialogue exact.** If a generation changes, drops or adds a word, regenerate it — do not keep it. Subtitles must match the supplied text exactly (`subtitles.srt`).
4. **Do NOT let the AI render on-screen text.** AI-generated lettering is unreliable. Generate clean footage, then add titles, level badges and subtitles in your editor (CapCut / Premiere / DaVinci) using the specs in Section 4.
5. **Character consistency.** Use the same character block, word for word, every time. If your tool supports reference images / "character" / "ingredients" features, first generate one approved still portrait of each student and attach it to every clip for that student.
6. **Alternative pipeline (best lip-sync control):** generate silent footage → record or synthesize the voices (e.g. ElevenLabs with three distinct teen voices) → lip-sync with a dedicated tool (HeyGen, Kling Lip-Sync, Sync Labs). Recommended if native audio keeps altering words.

---

## 1. GLOBAL STYLE BLOCK (paste into every prompt)

```
Photorealistic live-action footage, not animation. Vertical 9:16 frame. A modern premium English language academy classroom: light oak desks, white walls, large window on the left with soft natural daylight, a few green potted plants, a sage-green accent wall behind the subject with a subtle, out-of-focus bookshelf. Calm, welcoming academic atmosphere. Premium commercial cinematography, shot on a full-frame cinema camera, 50mm lens, f/2.0, shallow depth of field, soft key light from the window side, gentle fill, natural skin texture, realistic micro-expressions. Locked-off tripod shot, medium close-up from mid-chest up, subject centered, eye-line just off camera-left toward an unseen interviewer. Clean ambient room tone, no music, no on-screen text, no subtitles, no logos, no captions.
```

Negative / avoid (if the tool accepts one):
```
cartoon, 3D render, CGI look, plastic skin, exaggerated acting, over-smiling, unnatural blinking, warped hands, extra fingers, distorted teeth, camera shake, zooms, whip pans, lens flares, text, watermark, subtitles, distorted lettering
```

---

## 2. CHARACTER BLOCKS (use identically every time)

> Adjust ethnicity/appearance to match your real student audience; keep the wording fixed once chosen.

**STUDENT 1 — BEGINNER (A1)**
```
A 14-year-old Central Asian girl with shoulder-length straight black hair held back on one side with a small clip, round friendly face, natural look with no makeup. She wears a white collared shirt under a sage-green knit cardigan. Slightly shy, sits upright with hands resting on the desk, glances down briefly when thinking, small genuine smile. Voice: soft, young female voice, speaks slowly and carefully with short natural pauses between sentences, clear simple pronunciation with a light non-native accent.
```

**STUDENT 2 — ELEMENTARY (A2)**
```
A 15-year-old Central Asian boy with short neat dark hair, clean-shaven, warm brown eyes. He wears a navy crewneck sweater over a white shirt collar. Calm and friendly, relaxed shoulders, occasional small hand gestures, easy smile. Voice: young male teen voice, moderate pace, fairly confident, occasional brief pause to find a word, light non-native accent.
```

**STUDENT 3 — PRE-INTERMEDIATE (B1)**
```
A 16-year-old Central Asian girl with long dark hair in a neat low ponytail, subtle natural look. She wears a beige blazer over a cream top. Confident, open posture, steady eye contact with the interviewer, natural expressive hand gestures, thoughtful nods. Voice: clear young female voice, natural fluent conversational pace, good intonation, light non-native accent.
```

---

## 3. CLIP PROMPTS

### CLIP 00 — INTRO (≈4 s)
```
[GLOBAL STYLE BLOCK]
Three separate locked-off medium close-up shots of three different teenagers, each in the same classroom setting, intended for a vertical three-way split screen (top / middle / bottom). Each student looks into the camera, gives a small natural smile and a slight nod, as if about to start an interview. No dialogue. Soft room tone.
[CHARACTER BLOCK 1] / [CHARACTER BLOCK 2] / [CHARACTER BLOCK 3]
```
Tip: generate each student's 4 s "smile + nod" separately and stack them in the editor — this gives a cleaner split screen than one generation.

### QUESTION CARDS — Q1 / Q2 / Q3 (≈3 s each)
Interviewer is **off-camera** — voice only. Generate the voice (adult, warm, neutral accent) or record it yourself:
- Q1: *"What do you usually do in your free time?"*
- Q2: *"What is your favourite food?"*
- Q3: *"What kind of weather do you like?"*

Visual: a 3 s cutaway of the empty interview chair / desk with a microphone on a small stand, or simply a clean green-branded title card built in the editor.

### ANSWER CLIP TEMPLATE
```
[GLOBAL STYLE BLOCK]
[CHARACTER BLOCK N]
The student is being interviewed by someone off-camera and answers naturally, looking slightly off camera-left at the interviewer, with precise lip synchronization. She/He says exactly, word for word, with no added or missing words:
"<DIALOGUE PIECE>"
```

---

### QUESTION 1 — "What do you usually do in your free time?"

**Q1-A1 — Beginner** (~14 s → 2 clips)
> I watch TV and listen to music. I like playing games. // Sometimes I go for a walk with my friends. I also like reading books.

**Q1-A2 — Elementary** (~21 s → 3 clips)
> In my free time, I usually watch films, listen to music and meet my friends. // At weekends, I sometimes go shopping or visit my relatives. I also enjoy reading interesting books because I can learn new things. // My favourite activity is watching films with my family.

**Q1-B1 — Pre-Intermediate** (~28 s → 4 clips)
> I usually spend my free time doing different activities. I enjoy watching films, especially comedies, because they help me relax after a busy day. // I also like meeting my friends and trying new things. // Recently, I've become interested in reading books because I think it's a great way to improve my knowledge. // If I have enough free time, I prefer going somewhere with my friends rather than staying at home.

---

### QUESTION 2 — "What is your favourite food?"

**Q2-A1 — Beginner** (~11 s → 2 clips)
> My favourite food is pizza. I like cheese pizza. // I eat it with my family. I also like ice cream.

**Q2-A2 — Elementary** (~20 s → 3 clips)
> My favourite food is pizza because it is very delicious. I usually eat it at weekends with my family or friends. // I also enjoy trying different types of food. // I don't really like spicy food because it is too hot for me.

**Q2-B1 — Pre-Intermediate** (~27 s → 4 clips)
> If I had to choose my favourite food, I would definitely say pizza. // I enjoy it because there are so many different flavours and toppings to choose from. // I usually eat it when I go out with my friends or when my family orders food at home. // Although I like trying new dishes, I still prefer homemade meals because they are usually healthier and remind me of home.

---

### QUESTION 3 — "What kind of weather do you like?"

**Q3-A1 — Beginner** (~13 s → 2 clips)
> I like sunny weather. It is warm and nice. // I can go outside and play with my friends. I don't like rainy days.

**Q3-A2 — Elementary** (~20 s → 3 clips)
> My favourite weather is sunny and warm. I enjoy going for walks when the sun is shining. // I also like spring because the weather is not too hot or too cold. // Rainy weather is not my favourite because I cannot spend much time outside.

**Q3-B1 — Pre-Intermediate** (~28 s → 4 clips)
> I definitely prefer warm and sunny weather because it makes me feel more energetic and positive. // During sunny days, I enjoy spending time outdoors, going for walks or meeting my friends. // However, I also appreciate rainy weather sometimes because it creates a peaceful atmosphere and gives me a reason to stay at home, read a book or watch a film. // I think every season has something special to offer.

> Note: the third B1 piece in Q3 is ~10 s. On an 8 s tool, split it after "atmosphere" and cut on a subtle blink/nod.

**Performance direction by level** (add to the answer prompt):
- **A1:** "speaks slowly, short pause between each sentence, glances down once while thinking, a slightly shy smile at the end."
- **A2:** "moderate pace, generally confident, one brief natural pause, light hand gesture."
- **B1:** "fluent, natural rhythm and intonation, expressive but restrained hand gestures, relaxed smile, steady eye contact."

---

### CLIP 99 — FINAL SCENE (≈5 s)
```
[GLOBAL STYLE BLOCK — but change framing to:] Medium-wide vertical shot, camera at chest height. The three students from the interviews stand together side by side in front of the sage-green wall of the academy classroom, A1 student on the left, B1 student on the right, A2 student in the middle. They look into the camera and smile naturally; the B1 student gives a small relaxed nod. Very slow subtle push-in. No dialogue, no text.
[CHARACTER BLOCK 1] [CHARACTER BLOCK 2] [CHARACTER BLOCK 3]
```
Leave empty space in the top third of the frame for the end title.

---

## 4. EDITING & GRAPHICS SPEC (add in post)

**Typography:** one clean geometric sans (Montserrat / Inter / Manrope). White text; brand green accent (e.g. `#1F8A5B` or your brand hex). No drop-shadow cartoons — use a subtle 30–40% dark gradient behind text for legibility.

| Moment | On-screen text | Placement |
|---|---|---|
| Intro | **3 STUDENTS. 3 ENGLISH LEVELS.** | Centered over split screen, bold, 2 lines |
| Intro | BEGINNER · ELEMENTARY · PRE-INTERMEDIATE | Small label on each of the three split panels |
| Question cards | **QUESTION 1** + question text | Center, 2.5–3 s, soft fade |
| Every answer | Level badge, e.g. **BEGINNER · A1** | Top-left pill, green background, stays for whole answer |
| Every answer | Subtitles (`subtitles.srt`) | Lower third, max 2 lines, ~28–32 chars/line, safe zone ≥ 250 px above the bottom (TikTok/Reels UI) |
| Final | **YOUR ENGLISH CAN GROW TOO.** then **1LIM ACADEMY** (logo) | Top third, fade in sequentially |

**Cuts:** straight cuts between students; 6–8 frame cross-dissolve or quick fade into each question card. Optional: a thin progress bar showing Q1 / Q2 / Q3.

**Audio:** light, unobtrusive music bed only under the intro, question cards and outro (duck to −25 dB or mute under answers). Normalize dialogue to around −14 LUFS for social.

**Length tip:** At ~3–3.5 min the full cut may exceed Instagram Reels' 3-minute limit, and retention is usually better with a **3-part series** (one question per Reel, ~60 s each), with the same intro and outro on each. Everything here works for both versions.
