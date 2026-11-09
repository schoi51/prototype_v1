# Spending Companion · Prototype v1

A clickable iPhone prototype for a spending companion that helps Erin, a lapsed tracker who pays with several cards and Venmo, keep October on track. Built for IXD 750 (Visual Design & Prototype v1).

## Open it

- **Locally:** download the repo and open `index.html` in a browser. No build step, no dependencies.
- **GitHub Pages:** Settings → Pages → Deploy from branch → `main` / root. The prototype will be live at `https://<your-username>.github.io/<repo-name>/`.

## What's inside

Three task flows, each starting from the same Home, Ledger and Limits screens. Only the AI suggestions differ between flows.

| Flow | What you can try |
|---|---|
| **1 · Smart Ledger** | Confirm a split dinner, name a charge the app couldn't recognize, open any card, change a category by tapping its icon, and move similar charges at once |
| **2 · Heads-up** | Review suggested limits, adjust one, set when heads-ups arrive, open the push, and edit a limit yourself any time |
| **3 · Re-plan** | Spot a one-off payment, pick or edit a re-plan option, approve it, undo it, or handle the case where nothing fits |

The Ledger has a month calendar: today's charges show first, and tapping another October day shows that day's cards.

## Design notes

- **Platform:** iPhone app (375 × 812 frame)
- **Type:** Instrument Sans
- **Color:** blue for actions, orange as a second accent, lavender surfaces
- **AI moments:** thick, pink-tinted glass and a small pink dot. Pink appears nowhere else, and there are no sparkle icons
- Every AI action can be undone, and nothing changes until the user taps

## Tech

- Single self-contained `index.html` (HTML, CSS, vanilla JavaScript)
- Font loaded from Google Fonts
- Designed in Figma (Variables, Text Styles, Effect Styles, Components)
