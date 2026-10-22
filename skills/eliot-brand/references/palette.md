# Eliot color palette

Colors were sampled from the PTC's 2026 Empower Eliot flyers and rounded to clean values. If the PTC later gets official values from a designer, replace these.

## Core colors

| Name | Hex | RGB | Typical use |
|---|---|---|---|
| Eliot Navy | `#0B1F4F` | 11, 31, 79 | Headlines, body text, "EMPOWER", footer bars, outlines |
| Eagle Blue | `#1E4280` | 30, 66, 128 | Mascot body and wings, darker fills, icons |
| Bright Blue | `#3A7BC8` | 58, 123, 200 | Second headline line, emphasized words, links |
| Eliot Sky | `#6292C8` | 98, 146, 200 | "ELIOT" in the wordmark, squiggles, outlined hearts |
| Pale Sky | `#D6E8F8` | 214, 232, 248 | Panels, cards, background washes |
| Sunshine Gold | `#F2C94C` | 242, 201, 76 | Hearts, buttons, beak and feet, accent marks |
| Butter Yellow | `#F7DE6E` | 247, 222, 110 | Brush-stroke highlights behind text |
| Cream | `#FBF3D6` | 251, 243, 214 | Warm panels for quotes and callouts |
| White | `#FFFFFF` | 255, 255, 255 | Main background |

## Contrast (WCAG)

| Text on background | Ratio | OK for |
|---|---|---|
| Eliot Navy on White | ~15.9:1 | Everything |
| Eliot Navy on Pale Sky | ~12.7:1 | Everything |
| Eliot Navy on Butter Yellow | ~11.8:1 | Everything |
| Eliot Navy on Sunshine Gold | ~10.0:1 | Everything (buttons) |
| White on Eliot Navy | ~15.9:1 | Everything |
| Bright Blue on White | ~4.3:1 | Large text only (18pt+/24px+) |
| Eliot Sky on White | ~3.2:1 | Large display text and decoration only |
| Sunshine Gold on White | ~1.6:1 | Never for text |
| Sunshine Gold on Eliot Navy | ~10.0:1 | Highlighted words on dark bars |

## Proportions

Aim for roughly 60% white or Pale Sky, 25% navy and blues, 15% yellow. Yellow should feel like sunshine sprinkled through, not a yellow page.

## Seasonal palettes

Seasonal events can add theme colors (e.g. Halloween purple, orange and slime green; autumn leaves) as the main background. Keep the Eliot name and the eagle in brand colors so the piece still reads as Eliot.

## The website

The current site in this repo (`index.html`) uses a related but separate set of tokens (navy `#1f3a68`, blue `#3a68ad`, gold `#f0c54a`, Merriweather and Source Sans/Serif). For new web work, prefer the tokens in `assets/brand-tokens.css`.
