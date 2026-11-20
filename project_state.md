# ai-revolution — screenplay-style visual essay

Goal: portfolio piece in the nenioch "screenplay" format (wait-but-why
ai-revolution page): one self-contained HTML, 16 scenes x 12 s, live canvas,
Web Audio synth score, no deps, no build step.

## LIVE (2026-11-20)
- Repo:  https://github.com/psvanzyl/ai-revolution (public, main)
- Site:  https://ai-revolution.laserraptorai.duckdns.org
- Coolify app uuid 7uplowa5sxiekuhsmvbzibl1, project uzi10a2aty74qzuoyoczsyvl,
  dockerfile pack (nginx:1.27-alpine, COPY index.html), port 80, CT310.
- Redeploy: POST :8000/api/v1/deploy?uuid=... (token ~/.config/coolify.token)

## Content
- Own English summary of Tim Urban, The AI Revolution (WBW 2015 + sequel).
  NOT a copy of nenioch Dutch text; engine architecture learned from it,
  all code/art/score original.
- 16 scenes: traveler, accelerating returns, knee, ANI/AGI/ASI, narrow AI,
  Moravec, compute, three roads, silicon edge, staircase, explosion, beam,
  when?, camps, Turry, you-are-here. Scene 13 shows today from system clock.

## QA record
- Headless chromium (?t=<sec>&paused) screenshots of all 16 scenes.
- Vision-analyzed 8+ frames; 2 fix iterations: chart margins vs text panel,
  sc3 figure overlap, sc0 flash overexposure, sc9 camera + sun in frame,
  sc11 branch paths earlier + star. Final check on live URL passed.

## Conventions
- ponytail plugin active (smallest complete change) since 2026-11-20.
