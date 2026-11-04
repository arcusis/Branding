# Arcusis Design Language

This file describes how the Arcusis brand looks and how to use it correctly.

## Colors

Green is the Arcusis signature color. Use it for the logo, for primary actions and for
accents. Everything else stays neutral: black, white and the warm off-white.

| Name | HEX | RGB | Use |
| --- | --- | --- | --- |
| **Arcusis Green** | `#59A52C` | 89, 165, 44 | Signature color. The logo, primary buttons, links, highlights |
| Light Green | `#6FCA3A` | 111, 202, 58 | Hover states, gradients together with Arcusis Green, small accents on dark backgrounds |
| Deep Green | `#437D21` | 67, 125, 33 | Pressed states, text on light-green surfaces, the dark end of gradients |
| Black | `#111111` | 17, 17, 17 | Body text, dark backgrounds, the black logo |
| Off-White | `#F9F8EB` | 249, 248, 235 | Warm page and card backgrounds |
| White | `#FFFFFF` | 255, 255, 255 | Plain backgrounds, the white logo, text on green and black |

Swatch: [`Arcusis/Colors/arcusis-colors.png`](Arcusis/Colors/arcusis-colors.png)

Rules of thumb:

- Green is an accent. Large areas are white, off-white or black. Do not fill whole pages in green.
- Text on Arcusis Green must be white. Text on Light Green must be Black or Deep Green.
- Do not introduce a second accent color next to the green. Charts and tags may use
  tints of green and neutral greys.
- Gradients, when needed, run from Light Green (`#6FCA3A`) to Arcusis Green (`#59A52C`)
  or from Arcusis Green to Deep Green (`#437D21`). Never from green to another hue.

## Logo

The Arcusis logo is a stylised "A": a peak with a swoosh. It exists in two versions
and three colors. Formats: SVG, PDF and EPS (vector, preferred), transparent PNG in several
sizes, WEBP, AVIF, flattened JPG, and ICO for the symbol.

### Versions

| Version | Files | When to use |
| --- | --- | --- |
| **Logo** (symbol + wordmark "arcusis") | `Arcusis/Logo/<FORMAT>/arcusis-logo-*` | The default. Website headers, documents, presentations, print, partner pages, anywhere the name must be read |
| **Symbol** (icon only) | `Arcusis/Logo/<FORMAT>/arcusis-symbol-*` (also `ICO/` for favicons and app icons) | Small sizes and square spaces: favicons, app icons, social-media avatars, watermarks, next to the name when it is already written as text |

Use the full logo whenever there is room. Use the symbol only where the full logo would
be too small to read (narrower than about 120 px) or where the format is square.

### Colors

| Color | File suffix | Background |
| --- | --- | --- |
| **Green** `#59A52C` | `-green` | White, off-white or light photos. This is the preferred version |
| **Black** `#111111` | `-black` | Light backgrounds where green would clash (partner logo walls, print in one color, documents) |
| **White** `#FFFFFF` | `-white` | Black, dark grey, dark photos and green surfaces |

Pick the version by contrast: green on light, white on dark, black when color is not
available. The green logo never goes on a green background; use the white one there.

`Arcusis/Logo/PNG/arcusis-symbol-green-gradient-800.png` is the shaded symbol used on
the website's icon. It is a raster only. Use the flat versions for everything else.

### Clear space and minimum size

- Keep clear space around the logo equal to the height of the "a" in "arcusis"
  (about a quarter of the logo height). Nothing else goes inside that space.
- Minimum width: full logo 120 px on screen or 30 mm in print; symbol 24 px or 8 mm.

### Do not

- Do not stretch, rotate, skew or crop the logo.
- Do not recolor it outside the three approved colors, and do not add outlines, shadows or glows.
- Do not place the green logo on busy or green backgrounds.
- Do not separate the swoosh from the peak or rebuild the wordmark in another font.
- Do not combine the logo with other brands' marks so that they look like one logo.

## Typography

The Arcusis website uses **Heebo** for body text and **Rubik** for interface text; both
are free on Google Fonts and support Hebrew and Latin. Headlines on the site use the
licensed display face **Sebenta**, which is not distributed in this repository. When
Sebenta is unavailable, use Heebo Bold.

Hebrew is written right-to-left. Mirror layouts, not the logo: the logo itself is never
flipped.

## Backgrounds

`Arcusis/Backgrounds/arcusis-background-4k.png` (3840×2160) is the dark "falling lines"
background in Arcusis Green on black. Use it for desktop wallpapers, stream overlays,
event screens and video backgrounds. Place the **white** logo on it.

## Other brands in this repository

Gaming Israel, Iron Swords and Modiluxe have their own identities and their own folders.
Use their assets as supplied; the rules above about not altering a logo apply to them too.
