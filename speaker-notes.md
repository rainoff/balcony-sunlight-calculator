# Speaker notes — "A year of sunlight, inside your balcony" (about 2.5 minutes)

Live app: https://rainoff.github.io/balcony-sunlight-calculator/
Slides: https://rainoff.github.io/balcony-sunlight-calculator/slides.html
Backup if projector internet fails: keep `index.html` open locally in another tab; the QR still points to the public site.

## Slide 1 — how many people have this problem (≈20 s)
- Let the grid finish filling (about 2 s) before you speak; the squares light up as the sun sweeps across them, and the headline number counts up with it.
- "Taiwan has roughly nine million homes. Almost all of them have a balcony."
- "That grid is one square per ten thousand homes. Every one of those squares is someone deciding where to put a pot."
- On the number: say **"about nine million"**. It is an order-of-magnitude figure for Taiwan's housing stock, not an exact count — if anyone asks for a source, point them at the Ministry of the Interior's housing statistics rather than quoting a precise figure from the stage.

## Slide 2 — the question (≈20 s)
- "Everyone with a balcony has asked this: where should the pot go so the plant gets enough direct sun?"
- "Half a metre closer to the railing, or one season later, can change the answer completely."

## Slide 3 — live demo (≈65 s)
Click **Open live demo** (opens in a new tab; use Cmd/Alt+Tab or the browser tab to return to the slides).
1. Point out the one connected picture: the back wall is a whole year of direct-sun hours for the pot, the floor is today's heatmap, and the gold marker is the pot. Default: mint, 20 September, pot mid-floor. Observed: **0.0 h today**, verdict "not enough direct sun".
2. Press **Try a brighter spot**. The pot jumps to the brightest sampled cell near the railing. Observed: **8.2 h today**, which meets mint's 3 h reference. The dashed ring you saw on hover was the preview.
3. Drag the date handle to **22 December**. Observed at that same spot: **0.0 h**, and the note says no sampled cell gets direct sun today — the six-storey building across the alley blocks the low winter sun. The year chart shows where the sunny weeks are.
4. One sentence of honesty: "This is a simplified direct-sun reference — sun geometry plus parapet, awning, side walls and one building across. It is not a promise the plant will grow."
Return to the slides tab.

## Slide 4 — try it (≈35 s)
- "Scan the code, or type the address. Two steps: choose a plant; drag the date or move the pot."
- Leave this slide up while people try it. Mention the source repository link for anyone who wants the model details.

## Do not say
- Do not promise plant growth or quote numbers other than the ones observed on screen during the demo.
- Do not state the nine million as an exact or official count, and do not claim *every* home has a balcony — "almost every one" is the claim on the slide.

## Deck mechanics
- Four slides. Arrow keys / space / Page Up / Down to move; Home and End jump to the ends; the URL hash (`#1`…`#4`) deep-links a slide.
- Slide 1's animation replays every time you return to it, so going back mid-talk is safe.
- Motion respects `prefers-reduced-motion`, and printing the deck renders every slide at its finished state.
