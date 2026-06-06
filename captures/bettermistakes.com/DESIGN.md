## Overview

The Better Mistakes website presents a modern, professional, and sophisticated visual identity, primarily characterized by a dark theme and a strong emphasis on typography. The design leverages high-contrast text against deep, muted backgrounds to create a focused and elegant user experience. Generous whitespace and a clear content hierarchy guide the user's eye, while subtle rounded corners add a touch of softness to an otherwise sharp aesthetic. The overall impression is one of a design-forward agency that values clarity and impact.

**Key Characteristics:**
*   Dominant dark background (`{colors.canvas}` — #232323) with high-contrast white text.
*   Two distinct sans-serif typefaces: "Tt Hoves Pro" for display and "Dm Sans" for body.
*   Spacious and airy layouts, utilizing generous vertical and horizontal padding.
*   Fluid typography that scales with the viewport width, ensuring readability across devices.
*   Minimal use of accent colors, reserving them for subtle highlights or brand elements.
*   Softly rounded corners (`{rounded.md}` — 8px, `{rounded.xxl}` — 16px) on interactive elements and media.
*   Clear content segmentation through distinct sections and consistent vertical rhythm.

## Colors

### Surface
*   **Canvas** (`{colors.canvas}` — #232323): The primary dark background color used across most sections of the website, providing a deep, rich foundation.
*   **Canvas Secondary** (`{colors.canvas-secondary}` — #000000): A pure black used for specific background elements, offering a slightly deeper contrast than the main canvas.
*   **Surface Button Primary** (`{colors.surface-button-primary}` — #3d3a3a): The background color for primary call-to-action buttons, a dark gray that complements the canvas.

### Text
*   **On Canvas** (`{colors.on-canvas}` — #ffffff): The primary text color, providing high contrast and readability against the dark canvas backgrounds.
*   **On Canvas Muted** (`{colors.on-canvas-muted}` — `color(srgb 1 1 1 / 0.6)`): A semi-transparent white used for secondary text, captions, or less emphasized information, offering a softer presence.

### Brand & Accent
*   **Accent Gold** (`{colors.accent-gold}` — #ffce0a): A bright, vibrant gold, likely used for subtle brand highlights or interactive elements.
*   **Accent Orange** (`{colors.accent-orange}` — #ea9012): A warm orange, potentially used for specific calls-to-action or decorative elements.
*   **Accent Purple Light** (`{colors.accent-purple-light}` — #caa1fc): A soft, light purple accent.
*   **Accent Blue** (`{colors.accent-blue}` — #064ad2): A royal blue accent.

## Typography

### Font Family
The primary typeface for display and heading elements is "Tt Hoves Pro", a modern sans-serif font, paired with "Dm Sans" (with Arial as a fallback) for body copy and supporting text. This combination provides a clean, contemporary feel with excellent readability.

### Hierarchy
| Token | Font Family | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|---|
| `{typography.display-xl}` | "Tt Hoves Pro", sans-serif | 80px | 400 | 80px | -3.69px | Hero headlines and prominent section titles |
| `{typography.display-lg}` | "Tt Hoves Pro", sans-serif | 80px | 400 | 96px | -3.69px | Large secondary section titles, like "Selected Work" |
| `{typography.heading-h1}` | "Tt Hoves Pro", sans-serif | 40px | 400 | 44px (inferred) | normal (inferred) | Testimonial quotes (`blockquote.heading-style-h4`) |
| `{typography.heading-h2}` | "Tt Hoves Pro", sans-serif | 24px | 400 | 26.4px | -0.24px | Section subheadings and content titles |
| `{typography.heading-h3}` | "Dm Sans", Arial, sans-serif | 32px | 400 | 35.2px | -0.64px | Main body introductions and key descriptive paragraphs |
| `{typography.heading-h4}` | "Dm Sans", Arial, sans-serif | 16px | 500 | 20.8px | -0.32px | Component titles, emphasized text, service labels |
| `{typography.body-lg}` | "Tt Hoves Pro", sans-serif | 16px | 400 | 20.8px | normal | Standard body text and general content |
| `{typography.body-sm}` | "Dm Sans", Arial, sans-serif | 14px | 400 | 18.2px | -0.28px | Smaller descriptive text, sub-labels |
| `{typography.caption}` | "Tt Hoves Pro", sans-serif | 12px | 400 | 13.2px | normal | Captions, labels, meta information, button text |
| `{typography.caption-tight}` | "Tt Hoves Pro", sans-serif | 12px | 400 | 13.2px | -0.12px | Tighter captions, e.g., "Trusted by" label |
| `{typography.caption-loose}` | "Tt Hoves Pro", sans-serif | 12px | 400 | 14.4px | -0.12px | Slightly looser captions, e.g., "Introduction" label |

### Principles
The typographic system emphasizes a clear hierarchy through significant size variations between display, heading, and body text. "Tt Hoves Pro" is used for impact and brand presence, while "Dm Sans" ensures legibility for longer passages. Letter spacing is generally normal for body text but slightly condensed for headings and specific captions, contributing to a modern, refined feel. The fluid `font-size` implementation ensures that text scales appropriately across various viewport sizes, maintaining visual balance and readability.

## Layout

The layout is characterized by a spacious, content-centric approach with a strong vertical rhythm.

**Spacing Scale:** The design appears to follow a base unit of `4px` for its spacing scale.
*   `{spacing.xs}` — 4px
*   `{spacing.sm}` — 8px
*   `{spacing.md}` — 12px
*   `{spacing.lg}` — 16px
*   `{spacing.xl}` — 24px
*   `{spacing.xxl}` — 40px
*   `{spacing.section-gap}` — 48px: Common gap between elements within a section or between minor sections.
*   `{spacing.section-padding-sm}` — 56px
*   `{spacing.section-padding-md}` — 80px
*   `{spacing.section-padding-lg}` — 96px
*   `{spacing.section-padding-xl}` — 106px
*   `{spacing.container-margin-x}` — 147px: Horizontal margin for main content containers.
*   `{spacing.container-padding-x}` — 148px: Horizontal padding for main content containers.

**Grid & Container Behavior:**
Content is typically constrained within a maximum width of `1328px`, as indicated by the `.container--1328` class, and is horizontally centered. Sections often utilize `display: flex` with `flex-direction: column` and a `gap` of `{spacing.section-gap}` — 48px, promoting clear vertical stacking and separation.

**Whitespace Philosophy:**
Whitespace is generously applied, creating ample breathing room around content blocks and between sections. This approach enhances readability, reduces visual clutter, and contributes to the premium, minimalist aesthetic. Large vertical padding values like `{spacing.section-padding-xl}` — 106px are common for section top/bottom spacing.

## Elevation & Depth

The design system does not utilize explicit shadows or complex depth effects. All observed components and elements have `box-shadow: none`, indicating a preference for a flat, clean aesthetic.

## Shapes

The design incorporates subtle rounded corners, primarily for interactive elements and media containers.
*   `{rounded.sm}` — 4px
*   `{rounded.md}` — 8px: Used for primary buttons.
*   `{rounded.lg}` — 10px
*   `{rounded.xl}` — 12px
*   `{rounded.xxl}` — 16px: Used for image wrappers and cards.

## Components

*   **Button Primary** (`{component.button-primary}`)
    *   Structure: `div.btn`
    *   Background: `{colors.surface-button-primary}` — #3d3a3a
    *   Text: `{colors.on-canvas}` — #ffffff, `{typography.caption}` — "Tt Hoves Pro", 12px, 400, 13.2px, normal
    *   Padding: `12px` (top/bottom) `16px` (right) `12px` (left)
    *   Border Radius: `{rounded.md}` — 8px
    *   Border: `none`
    *   Box Shadow: `none`

*   **Heading Display XL** (`{component.heading-display-xl}`)
    *   Structure: `h1.heading-style-h2`
    *   Text: `{colors.on-canvas}` — #ffffff, `{typography.display-xl}` — "Tt Hoves Pro", 80px, 400, 80px, -3.69px
    *   Padding: `0px`
    *   Margin: `0px`

*   **Testimonial Quote** (`{component.testimonial-quote}`)
    *   Structure: `blockquote.heading-style-h4`
    *   Text: `{colors.on-canvas}` — #ffffff, `{typography.heading-h1}` — "Tt Hoves Pro", 40px, 400
    *   Padding: `0px`
    *   Box Shadow: `none`

*   **Card Image Wrapper** (`{component.card-image-wrapper}`)
    *   Structure: `.work--image-wrapper`
    *