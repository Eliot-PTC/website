---
name: eliot-brand
description: Brand guidelines for John Eliot Elementary School (Needham, MA) and the Eliot PTC, including the Empower Eliot fundraising campaign. Use whenever making flyers, social posts, newsletters, emails, slides, web pages or any other material for Eliot, the Eliot PTC, or Empower Eliot.
---

# John Eliot Elementary School / Eliot PTC brand

Use these rules for anything made for **John Eliot Elementary School** in Needham, MA, the **Eliot PTC** (Parent Teacher Council), or the PTC's annual fundraising campaign, **Empower Eliot**.

The look is bright, friendly and hand-made: deep navy type, sky-blue accents, sunny yellow highlights, a cheerful eagle mascot, hearts, and marker-style brush strokes on a white or pale background. It should feel like a warm note home from school, never like a bank or a corporate ad.

Example flyers are in `examples/`. Look at them before designing anything new.

## Names and usage

| Use | Write it as |
|---|---|
| The school, first mention | John Eliot Elementary School |
| The school, after that | Eliot, the Eliot School, or Eliot Elementary |
| The parent group | the Eliot PTC (PTC = Parent Teacher Council) |
| The fundraising campaign | Empower Eliot (two words, capital E twice) |
| Campaign tagline | People ♥ Programs ♥ Possibilities |
| Families and donors | Eliot families, Eliot supporters |

- Never write "Elliot" or "Elliott". It is **Eliot**, one L, one T.
- The district is Needham Public Schools. Only name it when it actually matters (district policy, district events).
- Do not invent a mascot name, a school motto, or slogans presented as official. If a name is needed, ask.

## Color

Full palette with usage notes and contrast checks: `references/palette.md`. CSS variables: `assets/brand-tokens.css`.

| Name | Hex | Role |
|---|---|---|
| Eliot Navy | `#0B1F4F` | Headlines, body text, "EMPOWER", dark bars |
| Eagle Blue | `#1E4280` | Mascot body, secondary dark fills |
| Bright Blue | `#3A7BC8` | Second headline line, links, highlighted words |
| Eliot Sky | `#6292C8` | "ELIOT" in the wordmark, squiggles, decorative accents |
| Pale Sky | `#D6E8F8` | Card and panel backgrounds, soft washes |
| Sunshine Gold | `#F2C94C` | Hearts, beak and feet, buttons, the heart in "EMPOWER" |
| Butter Yellow | `#F7DE6E` | Brush-stroke highlights behind headlines |
| Cream | `#FBF3D6` | Warm panel backgrounds (quotes, callouts) |
| White | `#FFFFFF` | Page background |

Rules:
- White or Pale Sky backgrounds; navy text. Roughly 60% white/pale, 25% navy and blues, 15% yellow.
- Yellow is for highlights and hearts. Never set text in yellow on white (it fails contrast); put navy text **on** a yellow brush stroke instead.
- Bright Blue and Eliot Sky are for large display text and decoration. Body text stays navy.
- Seasonal pieces (Halloween, winter, spring) may borrow seasonal colors, as the Trunk or Treat flyer does, but keep the eagle and the Eliot name in brand colors.

## Typography

The flyers use three voices. Match them with these free Google Fonts (exact originals are unknown; these are close, freely licensed stand-ins):

| Voice | Font | Use |
|---|---|---|
| Wordmark / bold display | **Montserrat** 800–900, uppercase | "EMPOWER ELIOT", short uppercase labels, big numbers |
| Playful headline | **Fredoka** 600–700 | Event names ("COFFEE DAY!"), friendly headings |
| Handwritten marker | **Kalam** 700 (or Patrick Hand) | Callouts, taglines, "Together, we make Eliot stronger." |
| Body | **Nunito** 400–700 | Paragraphs, details, fine print |

- Headlines are big and short. Use at most two typefaces per element and three per piece.
- Tagline labels ("PEOPLE ♥ PROGRAMS ♥ POSSIBILITIES") are Montserrat 700, all caps, wide letter-spacing (~0.12em), navy, with small gold hearts as separators.
- Minimum body size: 11pt print, 16px web.

## The Empower Eliot wordmark

Reference image: `assets/empower-eliot-lockup-reference.png` (cropped from a flyer, for reference only; ask the PTC for an original file before printing large).

- "EMPOWER" in Eliot Navy, the **O replaced by a Sunshine Gold heart**.
- "ELIOT" below in Eliot Sky, same width or slightly narrower.
- Tagline underneath: PEOPLE ♥ PROGRAMS ♥ POSSIBILITIES.
- Put it top-left or top-center. Leave clear space around it at least the height of the "E".
- Don't stretch, recolor, outline, rotate, or put it on a busy photo. On navy, switch "EMPOWER" to white and keep "ELIOT" Sky.
- If you cannot reproduce it faithfully (e.g. in plain HTML), set it as live text with the rules above rather than drawing something approximate.

## Mascot: the Eliot eagle

A friendly cartoon bald eagle, drawn chunky and cute (big head, big eyes, small body):
- White head with rounded feathers, big dark eyes with highlights, open smiling yellow beak.
- **Navy/Eagle Blue body and wings with a Sunshine Gold heart on the chest** (the current Empower Eliot version).
- Yellow feet, thick navy outlines, flat colors with light shading.
- Poses: waving, wings spread wide in celebration, standing proudly, hugging a heart.

Older pieces show a brown-bodied eagle, sometimes in a blue "E" sweater. That is fine for general school events; use the **navy eagle with the gold heart for anything Empower Eliot**. Don't mix both versions in one piece.

The mascot should always look happy and kind. No angry, fierce, or realistic eagles. Don't put the mascot next to another organization's mascot or logo.

## Graphic elements

- **Brush strokes:** loose, dry-brush swipes of Butter Yellow or Pale Sky behind headlines and key phrases.
- **Hearts:** filled gold hearts and outlined blue or gold hearts, scattered loosely; a heart replaces an O or a bullet where it fits.
- **Burst lines:** short marker dashes radiating from the mascot or a headline for excitement.
- **Squiggles:** zigzag scribbles in Eliot Sky in corners.
- **Rounded cards:** soft-cornered panels in Pale Sky or Cream for grouped info, each with a simple navy line icon.
- **Underlines:** hand-drawn yellow underline under one key word.
- Keep plenty of white space. Decoration frames content; it never sits behind body text.

## Voice and tone

Full guide with sample lines: `references/voice-and-copy.md`.

Warm, grateful, upbeat, community-first. Write like a friendly parent volunteer, not a fundraising office.
- Use "we", "our", "together". Thank people often and sincerely.
- Short, punchy lines. Exclamation points in headlines are on-brand; keep body copy calmer.
- Make the ask concrete: what happens, when, where, how to give or sign up.
- Show impact with real numbers and real stories (only ones the PTC has provided; never invent figures, quotes or teacher names).
- Rule of three works well: "A little coffee. A lot of appreciation. A stronger Eliot."
- Never guilt, shame, or pressure. No "only X families have given". No comparing classes or families.

## Layout checklist

Every piece should have:
1. The Eliot name or Empower Eliot wordmark near the top.
2. One big headline (2–5 words) on a brush stroke or in big navy display type.
3. The mascot (when there's room) in a pose matching the message.
4. The essentials: what, when (day, date, time), where, how (link, QR code, or contact).
5. One closing line in the handwritten voice.

Before finishing, check: spelling of "Eliot", dates and times match the day of the week, text contrast is readable, no yellow text on white, and nothing is invented.

## Formats

- Instagram / Facebook post: 1080×1080 (square) or 1080×1350 (portrait).
- Story: 1080×1920. Keep text out of the top and bottom 250px.
- Email / web banner: 1200×630 or 1600×800.
- Printed flyer: US Letter 8.5×11 in, 0.5 in margins.
- Web: use `assets/brand-tokens.css`.
