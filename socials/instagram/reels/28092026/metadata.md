# Reel 01 — "You opened Instagram to reply to ONE message."
Day code: 28092026 · Brand: Cabo (@cabocardgame) · Status: v6 approved by arab, scheduled 2026-09-29 10:00 IST

## The idea
Pillar: **Change the World** (digital wellness) with a heavy dose of relatable humor.
Human tension: everyone has opened Instagram for one message and surfaced 47 minutes later
with no memory of the original errand. The scroll steals time; nobody chose it.

## The narrative (KEEP THIS — arab's explicit direction)
**Villain vs protagonist. Never preachy.**
- The doomscroll / 47-minute scroll is the VILLAIN. It is the antagonist, not the viewer.
- Cabo / sharpening your memory is the PROTAGONIST — the hero's tool, arriving late.
- Structure that worked: HOOK (0–2s) → VILLAIN (2–6s) → DECISION QUESTION (6–8s) →
  HERO LANDS (8–12s). The 2–3s question beat ("What if 15 minutes made you SHARPER
  instead?") puts the viewer in decision mode; by the time they decide, the hero lands.
- The reel accuses the scroll, not the viewer. ("It didn't want your reply. It wanted
  your evening." — NOT "stop wasting time, play cabo.")

## Final copy (v6)
1. 0–2s: "You opened Instagram / to reply to / ONE message." (ONE in red) + iOS DM
   banner with the genuine Instagram glyph.
2. 2–6s: "THE SCROLL HAD OTHER PLANS." → timer 00:00→00:47 labeled "STOLEN" →
   "47 MINUTES." (slam + screen shake) → "GONE." → "It didn't want your reply. /
   It wanted your evening."
3. 6–8s: "What if 15 minutes / made you SHARPER instead?" (SHARPER 150%, gold)
4. 8–12s: "What if the next 15 minutes challenged your memory instead?" /
   "CABO — your biggest opponent is YOU." + real screenshots, Play Store + App Store
   badges, unambiguous CTA.

## What worked (FOLLOW in future reels)
1. Real Instagram glyph from Wikipedia (`engine/render/assets/logos/instagram_glyph_2016.svg`,
   rasterized with cairosvg) — the hand-drawn version was rejected.
2. Music + SFX designed FOR THE STORY, not pulled from the game. Two-act score:
   dark suspense (villain) → epic uplift (hero), crossfaded at the turn. All SFX
   synthesized (notification blip, whip whoosh, slam booms, riser, bell shimmer).
3. Villain visuals: red/black palette, rotating crimson vortex, "STOLEN" framing —
   color tells the story before the words do.
4. Kinetic typography: expressive scale on key words ("47", "GONE", "SHARPER"),
   sequential word reveals, whip-pan transitions with motion blur, mask reveals,
   every animation hit synced to music downbeats. Craft notes:
   `agent_notes/motion-craft.md`.
5. Audio is baked in — no "add trending audio" step needed for this one.
   Music: "Suspense Cinematic" + "Epic Uplifting" by leberch (Pixabay Content
   License, free commercial use; credit: "Music by leberch from Pixabay").
6. iPhone mockup for every phone (Dynamic Island, iOS status bar). No @handle in
   videos, ever. Product close = 4 full seconds, real undistorted screenshots.

## What to AVOID (learned from v1–v5 rejections)
1. NEVER use real Cabo game BGM/SFX in story reels — the association breaks the
   narrative. Game audio is reserved for actual gameplay/product moments.
2. Never a procedural/approximated Instagram logo — only the genuine asset.
3. Never preachy "stop scrolling, play Cabo" framing.
4. No flat stock-photo collages, no abstract placeholder cards, no plain
   backgrounds, no linear motion.
5. No voiceover needed — text beats must hold long enough to read (words/2.5s rule).

## Quality bar
arab's words: "if you don't want to see it 5 times without getting bored, the video
is boring." v6 passed as "a good start for first draft" — the bar rises from here.

## Tech specs
1080×1920, 30fps, 12.0s, H.264 + AAC 192k, true peak −1.13 dBFS.
Script: `engine/render/cabo_reel_01_v6.py`. Storyboard: `outputs/renders/cabo/reels/2026-09-28/reel-01-storyboard-v6.json`.

## Publishing
- Scheduled: Buffer, 2026-09-29 10:00 IST, @cabocardgame (channel `6aa01817cd8b9c702c2d062e`), type=reel.
- Caption: see `outputs/schedule-brief-reel-2026-09-29.md`.
- Keep branch `social/instagram-carousels-sep28` alive until this reel has published
  (Buffer hotlinks the branch-pinned raw URL).
