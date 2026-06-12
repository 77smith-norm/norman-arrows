# norman-arrows ↕️

Minimal arrow-copy tool. Type a value (LOW, HIGH, or a 2/3-digit number), tap an arrow — the combination hits your clipboard.

Seven arrows: ↑ ↑↑ → ↓ ↓↓ ↗ ↘

## Usage

1. Open `index.html` in any browser
2. Type a value: `LOW`, `HIGH`, or any 2-digit (00–99) or 3-digit (000–999) number
3. Tap an arrow button → copies `value+arrow` (e.g. `167↓↓`)
4. Tap **Copy** next to the input to copy just the value

Or tap an arrow with the input empty to copy just the symbol.

## Tech

- Single static HTML file — no build step, no dependencies
- Responsive: works on Desktop and mobile Safari (iPhone 11 Pro Max included)
- Dark mode support
- Clipboard API with fallback
