# Eliot brand skill

A Claude skill with the brand guidelines for John Eliot Elementary School (Needham, MA), the Eliot PTC, and the Empower Eliot campaign. Once installed, Claude follows these colors, fonts, mascot rules and voice whenever you ask it for a flyer, post, newsletter, email or web page for Eliot.

## Install

**Claude app (claude.ai or desktop):**
1. Download this `eliot-brand` folder and zip it (the zip should contain the `eliot-brand` folder with `SKILL.md` inside).
2. In Claude, go to Settings → Capabilities → Skills, and upload the zip.

**Claude Code:** copy the `eliot-brand` folder into `~/.claude/skills/` (just for you) or `.claude/skills/` in a project.

## What's inside

| File | What it is |
|---|---|
| `SKILL.md` | The guidelines Claude reads: names, colors, type, wordmark, mascot, voice, layout |
| `references/palette.md` | Full palette with contrast checks and seasonal rules |
| `references/voice-and-copy.md` | Tone, reusable lines and copy rules |
| `assets/brand-tokens.css` | CSS variables and helper classes for web work |
| `assets/empower-eliot-lockup-reference.png` | Reference crop of the Empower Eliot wordmark (not a print-quality logo) |
| `examples/` | Six 2026 PTC flyers showing the style |

## Updating

Colors were sampled from the flyers and fonts are close free stand-ins, since no official style guide exists yet. If you get official logo files or exact colors, add them to `assets/` and update `SKILL.md` and `references/palette.md`.
