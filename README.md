# ADG Seguros — Brand Assets

Official logo, icon, and regulatory image files for **ADG Seguros** and the **Expat Protection System (EPS)**.

This repository exists so that the same approved artwork is used everywhere ADG appears — websites, email signatures, forms, landing pages, and partner materials — without files being re-exported, re-compressed, or recreated from memory each time.

> **Este repositorio en español:** archivos oficiales de logotipos, iconos e imágenes regulatorias de **ADG Seguros** y del **Expat Protection System (EPS)**. Su propósito es asegurar que se utilice siempre la misma versión aprobada del material gráfico en sitios web, firmas de correo, formularios y materiales de socios.

---

## Usage rights / Derechos de uso

**This repository is public** so that the images can be linked directly from websites, email signatures, and third-party platforms. Public visibility is intentional — it is not an invitation to reuse the artwork.

- The **ADG Seguros and EPS brand marks** (`ADGLogo.png`, `ADGLogo-Crop.png`, `adg-logo-gold-shine*.gif`, `adg-logo-flare*.gif`, `adg-logo-lens-flare*.gif`, `EPSlogo.png`, `eps-logo-crop.png`) are the property of ADG Seguros and are provided for **authorized use by ADG Seguros, its advisors, and approved partners**. Do not alter their colors, proportions, or composition — request a new variant instead of editing one yourself.
- The ADG Seguros and Expat Protection System names and logos are **trademarks and are not licensed for redistribution, resale, or third-party use**.
- `SSRP.png` is a regulatory graphic that **incorporates** the mark of the **Superintendencia de Seguros y Reaseguros de Panamá**, a government regulator. The SSRP mark itself is **not** ADG property; it is reproduced here, alongside ADG's supervised-status statement, for compliance display only.
- The **social media and contact icons** (Facebook, Instagram, LinkedIn, WhatsApp, etc.) are generic third-party platform icons, not ADG-owned marks. They're hosted here purely for consistency across ADG materials — swap in your own copies of the same icons if preferred, no permission needed from ADG for those specifically.

> **Español:** Este repositorio es público para permitir el enlace directo de las imágenes desde sitios web, firmas de correo y plataformas de terceros. Su visibilidad pública es intencional y no constituye una autorización de uso.
>
> Las marcas de ADG Seguros y EPS (`ADGLogo.png`, `ADGLogo-Crop.png`, `adg-logo-gold-shine*.gif`, `adg-logo-flare*.gif`, `adg-logo-lens-flare*.gif`, `EPSlogo.png`, `eps-logo-crop.png`) son propiedad de ADG Seguros y se proporcionan para uso autorizado de ADG Seguros, sus asesores y socios aprobados. Los nombres y logotipos de ADG Seguros y Expat Protection System son marcas registradas y no se licencian para redistribución, reventa ni uso por terceros. `SSRP.png` es un gráfico regulatorio que incorpora la marca de la Superintendencia de Seguros y Reaseguros de Panamá; dicha marca no es propiedad de ADG. Los íconos de redes sociales y contacto son íconos genéricos de plataformas de terceros, no marcas de ADG; se alojan aquí solo por consistencia.

---

## Contents

### Brand marks

| File | Description |
| --- | --- |
| `ADGLogo.png` | Primary ADG Seguros logo. Default choice for most placements. |
| `ADGLogo-Crop.png` | Tightly cropped ADG logo with minimal surrounding whitespace. Use where vertical space is constrained, such as email signatures. |
| `EPSlogo.png` | Expat Protection System logo. Use for EPS-branded materials aimed at English-speaking expat clients. |
| `eps-logo-crop.png` | Tightly cropped EPS logo (shield + wordmark, minimal whitespace). Use where space is constrained, such as the EPS email-signature banner. |
| `adg-logo-gold-shine.gif` | Animated ADG logo with a gold shine sweep (836×478, 2.5 s loop). Master file — too heavy for email. |
| `adg-logo-gold-shine-email.gif` | Email-optimized version of the animated logo (224×128, ~150 KB, transparent). Display at 112 px wide. First frame is the static logo, so clients that don't animate GIFs (older Outlook desktop) show the normal logo. |
| `adg-logo-flare.gif` | Animated ADG logo with a brief lens-flare glint on the A (836×478; static hold 3.2 s, then a ~1 s flash). Master file — too heavy for email. |
| `adg-logo-flare-email.gif` | Email-optimized version of the lens-flare logo (224×128, ~200 KB, transparent, matted for white backgrounds). Display at 112 px wide. First frame is the static logo. |
| `adg-logo-lens-flare.gif` | Animated ADG logo: a blue-white lens flare travels from the A to the D, with a vertical light ray spanning the full height of the logo (844×486; 1.2 s static hold). Modelled on EJ's own flare GIF. Master file — too heavy for email. |
| `adg-logo-lens-flare-email.gif` | Email-optimized version of the travelling lens flare (224×129, ~240 KB, transparent, matted for white). Display at 112 px wide. First frame is the static logo. |

### Regulatory

| File | Description |
| --- | --- |
| `SSRP.png` | Regulatory graphic incorporating the mark of the Superintendencia de Seguros y Reaseguros de Panamá (SSRP), Panama's insurance regulator. _(Confirm exact contents/composition — description assumed, not verified against the file.)_ |
| `ADGSSRPdisclaimer.png` | Combined regulatory disclaimer graphic stating ADG Seguros' supervised status under SSRP License PJ 918. Required on client-facing landing pages and marketing materials. |

### Contact icons

Small icons for contact details in email signatures and web footers.

| File | Use |
| --- | --- |
| `mail.png` | Email address |
| `phone.png` | Telephone |
| `whatsapp.png` | WhatsApp |
| `globe.png` | Website |
| `pin.png` | Physical address / location |

### Social media icons

Generic third-party platform icons — not ADG-owned marks. See Usage rights above.

| File | Platform |
| --- | --- |
| `facebook.png` | Facebook |
| `instagram.png` | Instagram |
| `linkedin.png` | LinkedIn |
| `youtube.png` | YouTube |
| `tiktok.png` | TikTok |
| `twitter.png` | X (Twitter) |
| `threads.png` | Threads |
| `pinterest.png` | Pinterest |

---

## Linking to these files

### Recommended — jsDelivr CDN

For email signatures and production websites, link through the jsDelivr CDN. It is faster than GitHub, caches properly, and is far less likely to be blocked or rate-limited by corporate email clients:

```
https://cdn.jsdelivr.net/gh/ejcb-14/adgallassets@main/ADGLogo.png
```

### Direct from GitHub

Acceptable for internal tools, testing, and low-volume use:

```
https://raw.githubusercontent.com/ejcb-14/adgallassets/main/ADGLogo.png
```

Replace the filename at the end of either URL with any file from this repository.

### HTML example

```html
<img src="https://cdn.jsdelivr.net/gh/ejcb-14/adgallassets@main/ADGLogo.png"
     alt="ADG Seguros"
     width="180">
```

Always set a meaningful `alt` attribute — many email clients block images by default, and the alt text is what the recipient sees instead.

> ⚠️ **Do not delete or rename existing files.** They are linked from live websites, email signatures, and forms. Renaming a file silently breaks every place it appears, often without anyone noticing for weeks. If a file is genuinely obsolete, add its replacement first, migrate the references, and only then remove the original.

---

## Adding new assets

1. **Name files descriptively and predictably.** Lowercase, hyphen-separated, no spaces: `adg-logo-white.png`, not `ADG logo FINAL v2 (1).png`. Spaces and parentheses break URLs and have to be percent-encoded.
2. **Never commit an export artifact name.** Filenames such as `-removebg-preview` or a raw download ID from a social platform end up visible in production page source.
3. **Prefer SVG for logos and icons** where a vector version exists. It scales cleanly to any size and is usually smaller than PNG.
4. **Keep PNGs transparent** unless a solid background is specifically required.
5. **Update the tables above** in the same commit that adds the file.

---

## Brand reference

<!-- Fill these in with the official values from the ADG brand guidelines. -->

| | Value |
| --- | --- |
| Primary color | _to be documented_ |
| Secondary color | _to be documented_ |
| Primary typeface | _to be documented_ |
| Minimum logo width | _to be documented_ |

---

## Contact

For asset requests, new variants, or questions about approved usage, contact ADG Seguros (info@adgseguros.com.pa).

**ADG Seguros** — Panama
Regulated and supervised by the Superintendencia de Seguros y Reaseguros de Panamá · License PJ 918

© ADG Seguros. All rights reserved. / Todos los derechos reservados.
