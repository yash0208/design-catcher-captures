## DESIGN.md

## Overview

Airmee's visual design is characterized by a modern, clean, and highly typographic aesthetic, emphasizing clarity and efficiency, much like its logistics service. The brand leverages a minimalist color palette, primarily black and white, punctuated by a vibrant, energetic yellow accent. Typography plays a central role, utilizing a distinctive sans-serif typeface, "Unica77 LL TT", to establish a strong, professional, yet approachable voice. Layouts are spacious and organized, employing generous whitespace and a clear content hierarchy to guide the user's eye. The overall impression is one of reliability, innovation, and user-friendliness.

**Key Characteristics:**
*   **Monochromatic Base:** Predominantly black and white with minimal grayscale variations.
*   **Vibrant Accent:** A bright yellow (`{colors.brand-accent}` — #fff066) provides a distinct brand signal and highlights interactive elements.
*   **Strong Typography:** Relies heavily on the "Unica77 LL TT" typeface for both headlines and body text, creating a consistent and modern feel.
*   **Generous Whitespace:** Ample padding and margins contribute to a clean, uncluttered interface.
*   **Pill-shaped Buttons:** Interactive elements often feature highly rounded corners, softening the geometric typography.
*   **Clear Information Hierarchy:** Large, bold headlines and structured content sections facilitate easy scanning and comprehension.
*   **Subtle Depth:** Absence of explicit shadows maintains a flat, contemporary design, with depth implied through background color changes.

## Colors

*   **Canvas** (`{colors.canvas}` — #ffffff): The primary background color for most content areas, providing a clean, bright foundation.
*   **On Canvas** (`{colors.on-canvas}` — #000000): The main text color, offering high contrast against the canvas background. Also used for borders and some background elements.
*   **Brand Accent** (`{colors.brand-accent}` — #fff066): A vibrant yellow used sparingly to highlight interactive elements like buttons (e.g., in the cookie banner) and draw attention.
*   **Surface Muted** (`{colors.surface-muted}` — #bfc0d2): A light, cool gray used as a background for certain sections, such as the hero area, to subtly differentiate content blocks.
*   **Surface Card** (`{colors.surface-card}` — #e1e1e1): A slightly darker light gray used for background of cards, providing a subtle lift from the canvas.
*   **Surface Light** (`{colors.surface-light}` — #ebebeb): Another light gray background, similar to `surface-card`.
*   **Surface Hairline** (`{colors.surface-hairline}` — #e8e8e8): A very light gray, likely used for subtle dividers or backgrounds.
*   **Text Muted** (`{colors.text-muted}` — rgba(0, 0, 0, 0.4)): A semi-transparent black used for secondary text or descriptive content, providing a softer contrast than primary text.

## Typography

### Font Family
The primary typeface is **"Unica77 LL TT"**, a modern sans-serif, used extensively for all headings, body text, and UI elements. It provides a clean, geometric, and highly legible appearance. For specific, perhaps more technical or branding-related contexts, **"Unica77 Mono"** is introduced, offering a monospaced alternative while maintaining brand consistency. The full fallback stack for both is `system-ui, -apple-system, sans-serif`.

### Hierarchy
| Token                 | Font Family                                     | Size         | Weight | Line Height | Letter Spacing | Use                                                              |
| :-------------------- | :---------------------------------------------- | :----------- | :----- | :---------- | :------------- | :--------------------------------------------------------------- |
| `{typography.display-xl}` | "Unica77 LL TT", system-ui, -apple-system, sans-serif | 102.75px     | 400    | 113.025px   | -2.055px       | Large numerical displays (e.g., ratings)                         |
| `{typography.display-lg}` | "Unica77 LL TT", system-ui, -apple-system, sans-serif | 51.375px     | 400    | 61.65px     | -1.0275px      | Large section titles (e.g., "Boost your business")               |
| `{typography.display-md}` | "Unica77 LL TT", system-ui, -apple-system, sans-serif | 41.1px       | 400    | 49.32px     | -0.822px       | Main app/feature titles (e.g., "The best way to experience Airmee") |
| `{typography.heading-xl}` | "Unica77 LL TT", system-ui, -apple-system, sans-serif | 35.9625px    | 400    | 43.155px    | -0.71925px     | Section headlines (e.g., "The new standard in last mile delivery") |
| `{typography.heading-lg}` | "Unica77 LL TT", system-ui, -apple-system, sans-serif | 30.825px     | 400    | 36.99px     | -0.6165px      | Prominent call-to-action text, sub-headlines                     |
| `{typography.heading-md}` | "Unica77 LL TT", system-ui, -apple-system, sans-serif | 20.55px      | 400    | 24.66px     | normal         | Service titles, card body text                                   |
| `{typography.body-lg}`    | "Unica77 LL TT", system-ui, -apple-system, sans-serif | 15.4125px    | 400    | 18.495px    | normal         | Key statistics descriptions                                      |
| `{typography.body-md}`    | "Unica77 LL TT", system-ui, -apple-system, sans-serif | 13.7px       | 400    | 16.44px     | normal         | Standard body text, navigation links, footer text                |
| `{typography.body-sm}`    | "Unica77 LL TT", system-ui, -apple-system, sans-serif | 11.9875px    | 400    | 15.4639px   | normal         | Smaller body text, secondary navigation                          |
| `{typography.caption-mono}` | "Unica77 Mono", system-ui, -apple-system, sans-serif | 11.9875px    | 400    | 14.385px    | 0.359625px     | Eyebrow text, specific branding elements (e.g., "The Airmee App") |

### Principles
The typographic system relies on a single font family, "Unica77 LL TT", across a wide range of sizes to establish hierarchy, with "Unica77 Mono" reserved for specific, distinctive labels. All text maintains a `font-weight` of 400 (regular), with hierarchy primarily achieved through `font-size` and `line-height` variations. Letter spacing is generally `normal` for readability, with a slightly positive `letter-spacing` for the mono typeface to enhance its distinctiveness. Headings often feature negative letter spacing for a tighter, more impactful appearance.

## Layout

The layout adheres to a spacious, grid-like structure with content typically centered within a maximum width, often with a consistent horizontal padding. A base unit of approximately `17px` is observed, with a derived scale for various spacing needs.

*   **Spacing Scale (Base: ~17px)**:
    *   `{spacing.xxs}` — 4px: Minimal spacing, small gaps.
    *   `{spacing.xs}` — 9px: Small spacing, between inline elements or tight groups.
    *   `{spacing.sm}` — 17px: Standard small spacing, padding within components.
    *   `{spacing.md}` — 26px: Medium spacing, between related content blocks.
    *   `{spacing.lg}` — 34px: Larger spacing, between distinct elements.
    *   `{spacing.xl}` — 69px: Generous spacing, often used for section padding or large component separation.
    *   `{spacing.xxl}` — 86px: Very large spacing, between major sections.
    *   `{spacing.section}` — 103px: Significant vertical spacing between main page sections.
    *   `{spacing.container-offset}` — 322px: Large offset for specific content alignment.

*   **Container Behavior**: Most primary content is constrained to a maximum width, approximately `1081px` (e.g., `app__eyebrow`, `partnerships__eyebrow`) or `1218px` for full-width sections, and is horizontally centered. A common horizontal padding of `{spacing.xl}` — 69px is applied to content within these containers.
*   **Whitespace Philosophy**: The design embraces generous whitespace, particularly vertical spacing, to create a sense of openness and reduce visual clutter. This allows content to breathe and improves readability.

## Elevation & Depth

The design primarily favors a flat aesthetic with no explicit `box-shadow` properties observed in the provided data. Depth is implicitly conveyed through changes in background colors between sections (e.g., `{colors.canvas}` — #ffffff, `{colors.surface-muted}` — #bfc0d2, `{colors.surface-card}` — #e1e1e1).

## Shapes

The design incorporates distinct rounded corners, ranging from subtle to fully pill-shaped, softening the overall geometric feel.

*   **Rounded Small** (`{rounded.sm}` — 17.125px): Used for subtle rounding on elements, potentially cards or smaller containers.
*   **Rounded Medium** (`{rounded.md}` — 119.875px): Applied to interactive elements like buttons, giving them a distinct pill-like shape.
*   **Rounded Large** (`{rounded.lg}` — 137px): Larger radius, likely for specific UI elements or imagery.
*   **Rounded Full** (`{rounded.full}` — 154.125px): The largest radius, suggesting use for circular elements or extremely rounded containers.

## Components

*   **`button-primary`**
    *   **Structure**: A prominent, pill-shaped button.
    *   **Background**: `{colors.canvas}` — #ffffff
    *   **Text Color**: `{colors.on-canvas}` — #000000
    *   **Typography**: `{typography.heading-lg}` — "Unica77 LL TT", 30.825px, 400, 36.99px, -0.6165px
    *   **Padding**: `55.6562px` vertical, `77.0625px` horizontal.
    *   **Border Radius**: `{rounded.md}` — 119.875px
    *   **Border**: None.

*   **`nav-footer`**
    *   **Structure**: Standard navigation links within the footer.
    *   **Background**: Transparent.
    *   **Text Color**: `{colors.on-canvas}` — #000000
    *   **Typography**: `{typography.body-md}` — "Unica77 LL TT", 13.7px, 400, 16.44px, normal
    *   **Padding**: 0px.
    *   **Border Radius**: `{rounded.none}` — 0px.

*   **`input-select`**
    *   **Structure**: A dropdown select input, likely for language selection.
    *   **Background**: Transparent.
    *   **Text Color**: `{colors.on-canvas}` — #000000
    *   **Typography**: `{typography.body-md}` — "Unica77 LL TT", 13.7px, 400, 16.44px, normal
    *   **Padding**: `4.28125px`.
    *   **Border Radius**: `{rounded.none}` — 0px.
    *   **Border**: None.

*   **`footer`**
    *   **Structure**: The page footer containing navigation and copyright.
    *   **Background**: Transparent.
    *   **Text Color**: `{colors.on-canvas}` — #000000
    *   **Typography**: `{typography.body-md}` — "Unica77 LL TT", 13.7px, 400, 16.44px, normal
    *   **Padding**: `25.6875px` vertical, `68.5px` horizontal.
    *   **Border Radius**: `{rounded.none}` — 0px.

*   **`card-service`**
    *   **Structure**: A content card used to describe services.
    *   **Outer Background**: `{colors.surface-card}` — #e1e1e1
    *   **Inner Padding**: `{spacing.xl}` — 68.5px
    *   **Text Color**: `{colors.text-muted}` — rgba(0, 0, 0, 0.4)
    *   **Typography (Body)**: `{typography.heading-md}` — "Unica77 LL TT", 20.55px, 400, 24.66px, normal
    *   **Border Radius**: `{rounded.none}` — 0px
    *   **Border**: None.

## Do's and Don'ts

**Do's:**
*   **Do** use "Unica77 LL TT" for all primary text content, including headings and body.
*   **Do** maintain generous vertical spacing between content blocks, using tokens like `{spacing.xl}` — 69px and `{spacing.section}` — 103px.
*   **Do** use `{colors.brand-accent}` — #fff066 exclusively for key interactive elements or critical highlights.
*   **Do** ensure all interactive buttons, especially primary CTAs, are pill-shaped using `{rounded.md}` — 119.875px.
*   **Do** apply `{colors.on-canvas}` — #000000 for primary text on light backgrounds to maintain high contrast.
*   **Do** use `{colors.text-muted}` — rgba(0, 0, 0, 0.4) for secondary or descriptive text to create visual hierarchy.
*   **Do** center main content horizontally within a defined maximum width, typically with `{spacing.xl}` — 69px side padding.

**Don'ts:**
*   **Don't** introduce new typefaces outside of "Unica77 LL TT" and "Unica77 Mono".
*   **Don't** use `font-weight` other than 400 (regular) for any text, as hierarchy is managed by size.
*   **Don't** add `box-shadow` to elements; the design relies on flat surfaces and background color changes for depth.
*   **Don't** use `{colors.brand-accent}` — #fff066 for decorative purposes or large background areas.
*   **Don't** use inconsistent spacing; adhere to the established spacing scale.
*   **Don't** use sharp, unrounded corners for primary interactive elements.

## Responsive Behavior

| Breakpoint | Min Width | Touch Targets | Collapse Strategy