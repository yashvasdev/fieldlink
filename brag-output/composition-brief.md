# Hyperframes Composition Brief: FieldLink

## Objective
Create a 20-second launch-style product video for FieldLink that feels like a calm emergency-operations instrument, not a generic AI interface.

## Output
- Composition directory: `brag-output/composition/`
- Rendered video: `brag-output/brag.mp4`
- Format: landscape — 1920x1080
- Duration: 20 seconds

## Source Material
- Project root: `C:/Users/vasde/Projects/fieldlink`
- Primary files: `README.md`, `DEMO.md`, `apps/civilian/web/App.tsx`, `apps/civilian/web/styles.css`, `apps/civilian/src/planner.ts`, `apps/civilian/src/guides.ts`
- Product: FieldLink
- Strongest claim: local models select structured identifiers while stored guidance supplies the actions
- Key UI moment: a disaster description becomes a prioritized, source-attributed offline plan
- Copy that must appear verbatim:
  - `AI prioritized these guides. It did not write the safety steps.`
  - `Designed for infrastructure failure`
  - `No cloud`

## Creative Direction
- Tone preset: polished
- Creative direction: calm emergency-operations product film
- Interpretation: quiet graphite chrome, safety-lime route indicators, map/instrument structure, precise typography, and restrained motion
- Angle: show the system as an auditable local route from input to stored guidance
- Hook: `When the network disappears, guidance shouldn’t.`
- Outro: `Designed for infrastructure failure`
- Avoid:
  - Chatbot bubbles, purple gradients, glowing orbs, glass panels, and generic AI imagery
  - Fabricated metrics, claims, screens, or guide titles
  - Medical instructions beyond existing guide titles and attribution
  - Dense uppercase labels and decorative filler

## Visual Identity
- Background: `#101412`
- Raised surface: `#171C19`
- Hairline: `#303732`
- Text: `#F2F4E9`
- Secondary text: `#A9B2AC`
- Accent: `#D7FF61`
- Warning: `#FF8E63`
- Display/body font: `IBM Plex Sans`
- Metadata font: `IBM Plex Mono`
- Visual references: incident log, paper map grid, local-route indicator, source stamps

## Storyboard
Use `brag-output/brag-plan.md` as the creative contract.

1. Network failure — 3.5s — route nodes and hook
2. Describe the situation — 6s — redesigned feature-faithful intake console
3. Vetted offline plan — 7s — three real source-attributed guide cards and the safety boundary
4. FieldLink — 3.5s — wordmark, infrastructure-failure line, verified local attributes

## Audio
- Audio role: sparse professional support
- Audio arc: steady low bed, precise send click, soft plan reveal, restrained final bell
- Music: `assets/music/happy-beats-business-moves-vol-12-by-ende-dot-app.mp3`
- Music treatment: volume 0.25, 0.5s fade-in, 1s fade-out
- Music cue guidance: bundled preset at 109.96 BPM; strong moments at 8.74s, 13.11s, and 17.47s
- Audio-reactive treatment: none by design
- Audio-coupled moments:
  - Send action — low-risk click at 8.74s
  - First guide card — soft impact at 13.11s
  - Final wordmark — restrained bell at 17.47s
- SFX analysis: use the bundled `sfx-analysis.md`; select low/medium high-frequency-risk files
- Audio files: local assets only

## Hyperframes Instructions
- Use current Hyperframes composition rules and the generated project contract.
- Show a redesigned, feature-faithful presentation of the real FieldLink flow.
- Maintain text readability and 1920×1080 safe margins.
- Use transitions between every scene and entrances on every visible element.
- Do not animate elements out before transitions; only the final scene may fade.
- Use music and three restrained SFX as specified.
- Keep all claims grounded in the project.
- Run `npm run check`, inspect snapshots, and render locally.

