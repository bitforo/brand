# BitForo — Brand assets

Official logos and brand assets for **BitForo** ([bitforo.com](https://bitforo.com)), a crypto forum for Spanish speakers.

## Contents

| File | Description |
|---|---|
| `Isotipo BitForo Transparente*.png` | Icon / bug — full color and white, transparent background (9167×9167). |
| `Logotipo BitForo Transparente*.png` | Stacked logo — color, black and white, transparent. |
| `Logotipo Horizontal ... Negro*.png` | Horizontal lockup with dark text — for **light** backgrounds. |
| `Logotipo Horizontal ... Blanco*.png` | Horizontal lockup with white text — for **dark** backgrounds. |
| `Logotipo Horizontal BitForo Transparente_...png` | Horizontal lockup, brand colors (navy + yellow), transparent. |
| `Editable Loogotipo BitForo.ai` | Editable source (PDF-compatible, 11 pages). |
| `Presentación Logotipo BitForo.png` | Brand presentation board. |
| `optimized/` | Web-ready exports (see below). |

### `optimized/`

| File | Use |
|---|---|
| `avatar-460.png` | Profile picture / avatar (isotipo on white, 460×460). |
| `isotipo-512.png` | Icon, transparent, 512×512. |
| `logo-light.png` | Horizontal logo, dark text — README on **light** themes. |
| `logo-dark.png` | Horizontal logo, white text — README on **dark** themes. |
| `logo-color.png` | Horizontal logo, brand colors. |
| `og-1200x630.png` | Open Graph image (white background). |
| `og-1200x630-dark.png` | Open Graph image (navy background). |
| `apple-touch-180.png` | Apple touch icon, 180×180. |

## Colors

| Color | Hex |
|---|---|
| Yellow | `#FFBC00` |
| Navy | `#1F333B` |
| White | `#FFFFFF` |
| Light gray | `#D1D5D7` |

## Usage

```html
<!-- README, light/dark aware -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="optimized/logo-dark.png">
  <img alt="BitForo — Comunidad Cripto" src="optimized/logo-light.png" width="520">
</picture>
```

---

<sub>BitForo is not financial advice. Do your own research (DYOR).</sub>
