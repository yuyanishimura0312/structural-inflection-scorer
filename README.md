# Structural Inflection Point Scorer

Research theme evaluation tool based on Structural Inflection Point theory. Scores themes against 5 academic frameworks to identify optimal investment timing.

## Scoring Axes

1. **Scheffer Critical Transitions** - Are slow variables approaching a fold bifurcation?
2. **Geels MLP** - Is landscape pressure opening a window of opportunity?
3. **Perez Technological Revolutions** - Is this at a turning point between installation and deployment?
4. **North Institutional Economics** - Are transaction costs dropping due to institutional change?
5. **Dixit-Pindyck Real Options** - Is uncertainty collapsing, making the wait-option worthless?

## Setup

1. Open `index.html` in a browser (or deploy to GitHub Pages)
2. Click the gear icon and enter your Anthropic API key
3. Enter a research theme and click "Evaluate"

## Tech Stack

- Single HTML file (no build tools)
- Claude API (browser-side calls)
- Pure SVG radar chart (no dependencies)
- localStorage for history and API key
