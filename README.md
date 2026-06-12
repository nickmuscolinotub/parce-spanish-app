# 🇨🇴 PARCE
### Learn Spanish the way a good teacher would actually teach you

> *Inspired by the principles of the Michel Thomas Method — low-stress learning, no rote memorization, guided discovery, constant recall, sentence-building, and confidence through speaking. Original curriculum; no proprietary course material reproduced.*

**Variety:** Colombian Spanish · **Speaking model:** reveal-then-self-rate · **Audio:** AI-generated TTS · **Platform:** cross-platform mobile (React Native + Expo)

Branded in the colors of the Colombian flag — **amarillo, azul, rojo**.

---

## The Core Learning Promise

> *"In your first week, you'll build full Spanish sentences out loud. In 90 days, you'll hold a real conversation with a Colombian — and you will never once have sat down to memorize a vocabulary list."*

### The five laws every feature obeys
1. **No memorization.** Nothing is presented as a list to be drilled. Everything is *built*.
2. **No writing in the core path.** The core lesson is audio-and-speech. Eyes free, mouth working.
3. **Responsibility is the teacher's, not yours.** No "wrong." No failure state. A missed item gets re-taught.
4. **Think, then speak — out loud.** Every prompt is a small puzzle. You pause, assemble, say it, then hear the model.
5. **Build long sentences early.** Confidence comes from capability.

---

## Curriculum Roadmap (Beginner → Intermediate, ~90 days @ 20 min/day → CEFR A2/low-B1)

| Stage | Name | Capability gained | Days | CEFR |
|---|---|---|---|---|
| 1 | *Arranque* (Ignition) | Build sentences instantly with cognates + "engine verbs" (want/can/have to/going to + any verb). Speak in session one. | 1–12 | A0→A1 |
| 2 | *El Presente* | Talk about now: regular & key irregular verbs, questions, negation, "doing it right now." | 13–30 | A1 |
| 3 | *Conexiones* | Link ideas: because/but/so/that/when/if. Object pronouns. | 31–48 | A1→A2 |
| 4 | *El Pasado* | Tell what happened. Past tenses via contrast, not tables. | 49–66 | A2 |
| 5 | *El Futuro y los Deseos* | Future, conditional ("would"), subjunctive as "the mood of doubt and wishing." | 67–82 | A2→B1 |
| 6 | *Conversación Real* | Idioms, Colombian expressions, speed, register, unscripted speaking. | 83–90 | B1 (low) |

**Why this is fast:** "Engine verbs" on Day 1 (*quiero, puedo, tengo que, voy a*) each take an unchanging infinitive — so you express want/ability/obligation/intention across *every verb in the language* before conjugating anything.

---

## The Daily 20 (lesson structure)

```
① WARM RECALL      2 min   3–4 due review prompts (spaced)
② NEW BUILD        8 min   Teacher introduces 1–2 pieces, builds sentences with you
③ SPEAK IT         5 min   Reveal-then-self-rate speaking ladder (the confidence core)
④ LISTEN & CATCH   3 min   Colombian audio at real speed, you decode
⑤ THE CLOSER       2 min   One long "victory sentence" + XP + streak
```

**Intensities** (change cadence, not content): *Tranquilo* (1/day → 90 days) · *Dale* (1.5/day → 60 days) · *A toda* (2/day → 45 days).

---

## Gamification (rewards celebrate effort & recall — never punish absence)

- **Levels = a journey across Colombia:** Cartagena → Barranquilla → Medellín → Eje Cafetero → Bogotá → Cali → Amazonía. Arriving unlocks an illustrated **postcard** + a regional phrase.
- **XP = ⭐ estrellas:** session +50 · correct recall +5 · speaking drill +10 · victory sentence +25 · on-time review +3 · perfect session +30 bonus.
- **Streaks (humane):** counts days you showed up (even a 2-min review). 2 earned freezes/month. Missing a day → *"¡Tranquilo, parce! Tu racha está a salvo."* No guilt. Milestone streaks trigger flag-color confetti + a *vallenato* accordion riff.
- **Badges = real capabilities:** 🗣️ *Primera Frase* · ☕ *Pedí un Tinto* · ❓ *El Preguntón* · ⏪ *Viajero del Tiempo* · 🌧️ *Sin Miedo* · 🇨🇴 *Parcero de Verdad* · 🔥 *Cien Días*.
- **Unlockables:** Retos (mini speaking adventures: The Taxi, The Date, The Market), regional voice packs (paisa/costeño/rolo), daily surprise *El Tinto del Día*.

---

## Interactive Lesson Formats (guided recall engine)

All built on **the pause** — the moment you produce, not recognize.
1. **The Build** — teach → ask → pause → you speak → model plays.
2. **The Ladder** — a sentence grows one rung at a time; you rebuild the whole thing each rung.
3. **Reveal-then-Self-Rate** — say it aloud → tap *Mostrar* → rate 🟢 *Lo dije* / 🟡 *Casi* / 🔴 *Se me fue* (no penalty; re-taught).
4. **The Trap-Door** — teacher heads off the mistake before you make it.
5. **Catch-the-Word** — real-speed Colombian audio; tap words you caught.
6. **Scramble-Speak** — arrange and *say* the sentence.

### Skill drills
| Skill | Drill | What happens |
|---|---|---|
| Speaking | *Dilo en voz alta* | Reveal-then-self-rate ladder |
| Speaking+ | *Sin Guion* | Speak freely to a situation for 30s, then hear a model |
| Listening | *El Oído* | Colombian TTS at 3 speeds |
| Listening | *¿Qué dijo?* | Hear → choose meaning |
| Translation | *De ida y vuelta* | EN→ES then ES→EN |
| Confidence | *El Reto del Día* | One slightly-too-hard sentence you'll surprise yourself by getting |
| Confidence | *Victory Sentence* | End each session on a long, impressive sentence |

Pronunciation (no ASR in MVP): proactive "mouth tips" + a visual waveform self-compare. Clean upgrade seam for v2 ASR scoring.

---

## Review System (spaced repetition, MT-style)

A "card" is a **prompt to produce** ("Say: I'd like a glass of water, please"), not a flashcard. SM-2 variant:
- 🔴 *Se me fue* (q1) → interval resets to 1 day, ease ↓, **and the teacher re-explains it** next session.
- 🟡 *Casi* (q3) → interval grows modestly.
- 🟢 *Lo dije* (q5) → interval grows by ease factor (1→3→7→16→35d…).
- Items graduate out of active review after ~4 long-interval successes; maintained through use.
- **2-minute floor:** *Solo el repaso* micro-session protects the curve and the streak on busy days.

---

## First 7 Days (example lessons)

`[pause]` = you think and speak aloud; the line after is the model the teacher plays.

### Day 1 — *Arranque*: cognates + *Es*
- Cognates: possible → **posible**, probable → **probable**, important → **importante**. "It is" = **Es**.
- *"It is possible"?* `[pause]` **Es posible.** · *"It is important"?* `[pause]` **Es importante.**
- "Not" = **no** (before the verb). "For me" = **para mí**. "Very" = **muy**.
- *"It is very important for me."* `[pause]` **Es muy importante para mí.**
- **Victory:** *"It is possible, but it is not important for me."* `[pause]` **Es posible, pero no es importante para mí.** → badge 🗣️ *Primera Frase*.

### Day 2 — engine verb *quiero* (I want)
- **quiero** + unchanged verb. hablar / comer / hacer.
- *"I want to speak."* **Quiero hablar.** · *"I want to eat."* **Quiero comer.**
- *"I want to speak Spanish with you."* **Quiero hablar español contigo.**
- **Victory:** *"I want to speak Spanish, but I don't want to eat now."* **Quiero hablar español, pero no quiero comer ahora.**

### Day 3 — *puedo* (I can) + questions
- **puedo** + unchanged verb. Questions = same words, rising tone: **¿Puedo…?**
- *"Can I eat now?"* **¿Puedo comer ahora?** · "do it" = **hacerlo**.
- **Victory:** *"Can I do it now, or is it not possible?"* **¿Puedo hacerlo ahora, o no es posible?**

### Day 4 — *tengo que* (I have to) + first Colombian flavor
- **tengo que** + verb. ☕ coffee = **un tinto** (not *café negro*).
- *"I want a tinto, but I have to work."* **Quiero un tinto, pero tengo que trabajar.**
- "Why?" **¿Por qué?** / "because" **porque**.
- **Victory:** *"I can't speak now because I have to work."* **No puedo hablar ahora porque tengo que trabajar.**

### Day 5 — *voy a* (I'm going to)
- **voy a** + verb. tomorrow = **mañana**, today = **hoy**.
- **Victory:** *"Today I have to work, but tomorrow I'm going to speak Spanish with you."* **Hoy tengo que trabajar, pero mañana voy a hablar español contigo.**

### Day 6 — the four engines + "you"
- **¿Quieres…?** / **¿Puedes…?** · 🇨🇴 **¡Qué chévere!** / **Listo.**
- **Victory:** *"Do you want to speak Spanish with me tomorrow? — Listo, ¡qué chévere!"* **¿Quieres hablar español conmigo mañana? — Listo, ¡qué chévere!**

### Day 7 — first conversation + Stage 1 checkpoint
- *Sin Guion* scenario: a *parce* writes *"¡Quiubo! ¿Quieres tomar un tinto hoy?"* — you respond aloud, then hear 3 model replies.
- Reward: arrive in **Cartagena**, earn ☕ *Pedí un Tinto*, unlock the first Reto ("The Café").

---

## Milestones

| | Day 30 | Day 60 | Day 90 |
|---|---|---|---|
| CEFR | A1 | A2 | A2+/low B1 |
| You can… | café & taxi, ask/answer, want/can/have-to/will | past stories, link ideas, pronouns, market/doctor/plans | ~10-min real conversation, future & "would," subjunctive of wishes, register-switching, ~20 Colombian expressions |
| Active vocab | ~300 | ~700 | ~1,200 |
| Region | Medellín | Bogotá | Cali / Amazonía |
| Reward | 🏅 *Conversador* + paisa voice pack | 🏅 *Viajero del Tiempo* + Date/Market retos | 🏆 *Parcero de Verdad* + certificate + 10-min call challenge |

---

## Dashboard & Progress

Calm, yellow-forward home that answers "what do I do right now?" — one giant **EMPEZAR SESIÓN DE HOY** button, a *Solo repaso* shortcut, the Colombia map, a gentle weekly bar, and next-badge teaser.

Progress views: **El Mapa** (journey), **Lo que puedo decir** (capabilities, not word counts — the most motivating screen), **Mi racha** (friendly heatmap), **Insignias**, and tucked-away **Estadísticas**.

---

## What makes it addictive (healthily)
- **Competence** — every session ends on a "wow, I said that" Victory Sentence; the *Lo que puedo decir* screen shows growing power.
- **Simplicity** — one button on open; eyes-free audio core works while walking/driving/dishes → realistic daily habit.
- **Warmth & surprise** — no guilt ever, Colombian delight (slang drops, accent unlocks, *vallenato* milestone sting), anticipation loops (next region/badge/reto always almost in reach), shareable milestone cards.

---

## Build-Ready Product Spec

### Stack
| Layer | Choice |
|---|---|
| Client | React Native + Expo (TypeScript) |
| Audio playback | `expo-av` (streaming + cached local) |
| Mic capture | `expo-av` Recording (local only in MVP — visual waveform compare) |
| State/local | Zustand + MMKV + SQLite (`expo-sqlite`) for SRS + offline |
| Backend | Supabase (Postgres + Auth + Storage + Edge Functions) |
| TTS | ElevenLabs Colombian voices — **build-time**, stored as files (never live) |
| CDN | Cloudflare / Supabase CDN + aggressive client caching |
| Analytics | PostHog |
| Push | Expo Notifications (gentle, opt-in) |
| Payments | RevenueCat |

### Content model
Lessons and SRS items are **structured JSON**, authored separately, OTA-updatable. See [`content/sample-lesson.json`](content/sample-lesson.json).

### Core schema (Postgres)
```sql
users            (id, email, created_at, intensity, variety='co', tz)
user_progress    (user_id, current_stage, current_day, region, total_xp)
user_streak      (user_id, count, last_active_date, freezes_remaining, freeze_dates[])
srs_state        (user_id, item_id, ease_factor, interval_days, due_date, reps, last_quality)
session_log      (id, user_id, lesson_id, started_at, completed_at, xp_earned, recall_accuracy)
badges           (user_id, badge_id, earned_at)
content_lessons  (id, stage, day, json)
content_items    (id, json)
```

### SRS algorithm (SM-2 variant)
```
on self_rate(item, rating):              // rating ∈ {got_it, close, lost}
  q = {lost:1, close:3, got_it:5}[rating]
  if q < 3:
      interval = 1
      ease     = max(1.3, ease - 0.2)
      flag_for_reteach(item)             // MT touch: re-explain next session
  else:
      if reps == 0:      interval = 1
      elif reps == 1:    interval = 3
      else:              interval = round(interval * ease)
      ease = clamp(ease + (0.1 - (5-q)*(0.08 + (5-q)*0.02)), 1.3, 2.8)
  reps = (q < 3) ? 0 : reps + 1
  due_date = today + interval
  if reps >= 4 and interval > 35: graduate(item)
```

### Screens (MVP)
Onboarding (promise → variety → intensity → notif opt-in → first lesson before account wall) · Home/Dashboard · Lesson Player (audio-first, tap-to-reveal, pause ring, self-rate) · Review · Map/Progress · Badges/Streak · Settings.

### Key analytics events
`onboarding_complete`, `first_victory_sentence` (north-star activation), `session_start/complete`, `speak_self_rate {rating}`, `streak_freeze_used`, `review_completed`, `region_unlocked`, `badge_earned`, `day7_checkpoint`, `paywall_view/convert`. North-star: **% saying first Victory Sentence on Day 1** + **D7 retention**.

### Roadmap
- **MVP:** Stages 1–2 (Days 1–30), reveal-then-self-rate, SRS, streaks/XP/badges, first 3 map regions, 1 Colombian TTS voice, offline caching, paywall after Day 7.
- **v1.1:** Stages 3–4, voice packs, opt-in leagues, shareable cards.
- **v2:** ASR pronunciation scoring (drops behind the existing self-rate UI — no re-architecture).
- **v3:** Stages 5–6, live AI conversation partner, user-generated *Sin Guion* scenarios.

### Branding tokens (Colombian flag, 2:1:1 yellow-dominant)
```js
const palette = {
  amarillo:   '#FCD116', // PRIMARY · surfaces, energy, XP/estrellas
  azul:       '#003893', // STRUCTURE · headers, nav, typography, trust
  rojo:       '#CE1126', // ACCENT · the single primary CTA, streak flame
  crema:      '#FFF8E1', // soft warm surface
  carbon:     '#1A1A2E', // near-black text
  verde_cafe: '#3E7C4F', // Eje Cafetero map region
};
// Yellow dominates surfaces; blue carries structure; red is reserved for the
// single most important action per screen. Typography: warm humanist sans
// (Nunito / Sora). Big, calm, low-density. One decision per screen.
```

---

*Design doc. Not affiliated with or derived from the proprietary Michel Thomas course materials — original curriculum built on the same public pedagogical principles.*
