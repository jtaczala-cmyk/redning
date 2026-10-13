# Redning

Free mobile-first browser arcade game by Stop60: an original side-scrolling rescue shooter on a wrapping planet.
Fly left/right, shoot alien landers before their tractor beams lift the little humans away (abducted humans become mutants),
catch falling humans and set them down safely. Radar strip, smart bombs, waves, 3 lives.

- Single self-contained `index.html` (inline JS/CSS, embedded fonts) + `/pl/` and `/en/` entry pages; Norwegian default
- One-finger drag on iPhone (fires while touching), ✸ smart-bomb button; keyboard on desktop
- Opt-in online leaderboard: shared Stop60 Supabase table `public.scores`, `game = 'redning'`, only via the checked RPC `redning_submit` (see `supabase/supabase_redning.sql`)
- Laget med lidenskap – gratis for alle. No ads, no account, no cookies.

© 2026 Stop60 — all rights reserved, see LICENSE. Fonts: see THIRD-PARTY-NOTICES.md.
