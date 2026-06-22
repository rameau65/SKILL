# VIDEO_STYLE_PRESETS

These presets are shared by VIDEO_ENGINE, SEEDANCE_ENGINE, KLING_ENGINE, FLOW_ENGINE, and all cinematic workflows.

## 1. MEDITATION_CINEMA

### Keywords
- A24
- Terrence Malick
- Slow Cinema
- Dream Ambient

### Purpose
For meditative, introspective, poetic, and emotionally spacious films.

### Visual Direction
- Quiet composition
- Natural light
- Slow camera movement
- Soft film grain
- Minimal gestures
- Spacious silence
- Poetic realism

### Motion Direction
- Slow push-in
- Floating drift
- Subtle parallax
- Gentle wind
- Natural breath-like pacing

### Best Engine
SEEDANCE_ENGINE

### Supporting Engines
HAILUO_ENGINE for subtle still-image animation. KLING_ENGINE only when character motion is needed.

---

## 2. HANMAUM_DOCUMENTARY

### Keywords
- Educational
- Observational
- Humanistic
- Minimal

### Purpose
For Hanmaum philosophy, educational documentaries, institutional films, lectures, interviews, and report-based video content.

### Visual Direction
- Clear composition
- Human-centered framing
- Calm documentary realism
- Minimal visual distraction
- Warm but restrained tone
- Evidence-based storytelling

### Motion Direction
- Static observation
- Slow pan
- Gentle tracking
- Slow push-in during insight moments

### Best Engine
SEEDANCE_ENGINE

### Supporting Engines
FLOW_ENGINE for production planning. INFOGRAPHIC_ENGINE for visual explanation inserts.

---

## 3. AI_POETRY_FILM

### Keywords
- Visual Metaphor
- Memory
- Emotion Landscape
- Inner Journey

### Purpose
For symbolic, dreamlike, AI-art-based films where emotion becomes landscape and thought becomes cinematic metaphor.

### Visual Direction
- Symbolic imagery
- Memory-like atmosphere
- Emotional landscapes
- Surreal but controlled transitions
- Inner world visualization

### Motion Direction
- Morph-like emotional transition
- Floating objects
- Light movement
- Atmospheric particles
- Slow transformation

### Best Engine
SEEDANCE_ENGINE

### Supporting Engines
KLING_ENGINE for symbolic character movement. GROK_VIDEO_ENGINE for experimental native-audio tests.

---

## 4. YOUTUBE_SHORTS_CINEMA

### Keywords
- 5–15 second loops
- Vertical framing
- Fast emotional hook

### Purpose
For short-form cinematic clips, teasers, loops, social media fragments, and YouTube Shorts.

### Visual Direction
- Vertical composition
- Immediate emotional hook
- Strong central subject
- Readable silhouette
- High retention framing

### Motion Direction
- 5–15 second loop
- Single clear motion idea
- Quick atmosphere reveal
- End frame matches or echoes first frame

### Best Engine
SEEDANCE_ENGINE for cinematic loops.

### Supporting Engines
KLING_ENGINE for stronger motion. FLOW_ENGINE for shorts repurposing pipeline.

---

## Default Rule
When no style is specified, use `MEDITATION_CINEMA` for meditation or inner-world content, `HANMAUM_DOCUMENTARY` for educational/institutional content, `AI_POETRY_FILM` for symbolic art films, and `YOUTUBE_SHORTS_CINEMA` for vertical short-form content.
