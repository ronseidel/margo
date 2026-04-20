# marg0

Test your reading speed across 18 fonts. Find the one your brain reads fastest.

Live at [marg0.app](https://marg0.app).

## What it is

marg0 times you reading short passages in different typefaces, then shows you your reading speed in each. Same content, different font. You might discover your brain reads Charter 15% faster than Inter, or hates Georgia more than you realized.

The corpus is fetched live from Wikipedia, so the text is different every session — you're measuring how fast you read, not how fast you re-read something you've already seen.

## Stack

- Single static HTML file
- 18 fonts loaded from Google Fonts
- Wikipedia API for content (random article, extracted passages)
- Staged prefetching so the next font's passage is ready before you finish the current one
- Font and line-height normalized across tests so comparisons are apples-to-apples
- Results screen shows each font sample rendered in its own typeface, so you can see what you're comparing

## Why

Typography nerds have strong opinions about readability. Most of those opinions are vibes. marg0 turns "which font is easiest to read" into a number you can actually check against your own eyes.

## Part of 0fam

marg0 is part of [0fam](https://0utput.co), a family of small, focused web apps. Every name drops a letter for a zero.

## License

MIT.

## Contact

Built by [Ron Seidel](https://rontheron.com) · [hello@0utput.co](mailto:hello@0utput.co)
