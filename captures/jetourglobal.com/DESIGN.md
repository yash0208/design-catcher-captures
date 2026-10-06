## Overview

The JETOUR G700 website presents a modern, sleek, and performance-oriented visual identity, heavily relying on a dark mode aesthetic with stark white typography. The design emphasizes large, immersive imagery and video content, particularly within hero sections and carousels, creating a dynamic and engaging user experience. Typography plays a crucial role in conveying both technical specifications and brand messaging, utilizing a clean sans-serif for body text and a distinctive, slightly futuristic serif-like font for prominent headings. The overall impression is one of sophistication and robust engineering, with a focus on visual impact over intricate decorative elements.

**Key Characteristics:**
*   Dominant use of `{colors.canvas}` — #ffffff and `{colors.text-primary}` — #000000 for high contrast.
*   Extensive use of large, full-bleed imagery and video backgrounds.
*   Minimalist UI elements, often transparent or subtly outlined.
*   Two distinct font families: "HarmonyOS Sans" for readability and "Goldman" for impact.
*   Generous vertical spacing, especially in hero and section layouts.
*   Sharp, unrounded corners across all UI elements.
*   Responsive design with significant padding adjustments for smaller viewports.
*   Interactive carousels and animated elements for dynamic content presentation.

## Colors

### Brand & Accent
*   **Swiper Theme** (`{colors.brand-swiper}` — #007aff): Used specifically for the Swiper carousel theme color, indicating interactive elements.

### Surface
*   **Canvas** (`{colors.canvas}` — #ffffff): Primary background color for light-themed sections, such as the footer. Also used as text color on dark backgrounds.
*   **Surface Light** (`{colors.surface-light}` — #f3f3f3): A very light grey background, used for subtle differentiation.
*   **Surface Medium** (`{colors.surface-medium}` — #d9d9d9): A light grey background, explicitly defined by `--background-1`.
*   **Surface Muted** (`{colors.surface-muted}` — #afafaf): A medium grey background, likely for less prominent sections or elements.

### Hairlines & Borders
*   **Hairline Light** (`{colors.hairline-light}` — #e5e5e5): The most common border color, providing subtle separation on light backgrounds. Explicitly defined by `--border`.
*   **Hairline Lighter** (`{colors.hairline-lighter}` — #eeeeee): A slightly lighter border color.
*   **Border Dark** (`{colors.border-dark}` — oklch(0.279 0.041 260.031)): A dark, desaturated blue-purple used for borders, likely on dark surfaces.
*   **Border Muted UI** (`{colors.border-muted-ui}` — oklch(37.2% 0.044 257.287)): A dark grey border color, defined by `--ui-border-muted`.

### Text
*   **Text Primary** (`{colors.text-primary}` — #000000): Default text color, used extensively on light backgrounds.
*   **On Dark** (`{colors.on-dark}` — #ffffff): Text color used on dark backgrounds, such as the header and hero sections.
*   **Text Muted** (`{colors.text-muted}` — #999999): Used for secondary or less prominent text.
*   **Text Muted UI** (`{colors.text-muted-ui}` — oklch(70.4% 0.04 256.788)): A light grey text color, defined by `--ui-text-muted`.
*   **Text Dimmed UI** (`{colors.text-dimmed-ui}` — oklch(55.4% 0.046 257.417)): A darker grey text color, defined by `--ui-text-dimmed`.

### Semantic Overlays
*   **Overlay Light 10** (`{colors.overlay-light-10}` — oklab(0.999994 0.0000455678 0.0000200868 / 0.1)): A white overlay with 10% opacity.
*   **Overlay Light 20** (`{colors.overlay-light-20}` — oklab(0.999994 0.0000455678 0.0000200868 / 0.2)): A white overlay with 20% opacity.
*   **Overlay Light 50** (`{colors.overlay-light-50}` — oklab(0.999994 0.0000455678 0.0000200868 / 0.5)): A white overlay with 50% opacity.
*   **Overlay Dark 05** (`{colors.overlay-dark-05}` — oklab(0 0 0 / 0.05)): A black overlay with 5% opacity.
*   **Overlay Dark 10** (`{colors.overlay-dark-10}` — oklab(0 0 0 / 0.1)): A black overlay with 10% opacity.
*   **Overlay Dark 20** (`{colors.overlay-dark-20}` — oklab(0 0 0 / 0.2)): A black overlay with 20% opacity.

## Typography

### Font Family
The primary sans-serif typeface is **"HarmonyOS Sans"**, with `微软雅黑`, `Alibaba-PuHuiTi`, `Geist Sans`, and `Arial` as fallbacks, ensuring broad compatibility. This family is used for all body text, navigation, and most headings. For prominent display headings, the distinctive, tech-inspired serif-like typeface **"Goldman"** is used, providing a strong visual accent.

### Hierarchy

| Token                      | Font Family                                                              | Size         | Weight | Line Height | Letter Spacing | Use                                          |
| :------------------------- | :----------------------------------------------------------------------- | :----------- | :----- | :---------- | :------------- | :------------------------------------------- |
| `{typography.caption-xs}`  | "HarmonyOS Sans", 微软雅黑, Alibaba-PuHuiTi, "Geist Sans", Arial, sans-serif | 7.70625px    | 400    | 0px         | normal         | Smallest auxiliary text, e.g., plus signs    |
| `{typography.caption-xs-medium}` | "HarmonyOS Sans", 微软雅黑, Alibaba-PuHuiTi, "Geist Sans", Arial, sans-serif | 7.70625px    | 500    | 0px         | normal         | Smallest auxiliary text, medium weight       |
| `{typography.body-sm}`     | "HarmonyOS Sans", 微软雅黑, Alibaba-PuHuiTi, "Geist Sans", Arial, sans-serif | 10.275px     | 400    | 15.4125px   | normal         | Default body text, navigation links          |
| `{typography.body-sm-medium}` | "HarmonyOS Sans", 微软雅黑, Alibaba-PuHuiTi, "Geist Sans", Arial, sans-serif | 10.275px     | 500    | 15.4125px   | normal         | Navigation links, medium weight              |
| `{typography.body-sm-semibold}` | "HarmonyOS Sans", 微软雅黑, Alibaba-PuHuiTi, "Geist Sans\", Arial, sans-serif | 10.275px     | 600    | 15.4125px   | normal         | Specific UI elements, semibold               |
| `{typography.body-sm-bold}` | "HarmonyOS Sans", 微软雅黑, Alibaba-PuHuiTi, "Geist Sans", Arial, sans-serif | 10.275px     | 700    | 15.4125px   | normal         | Specific UI elements, bold                   |
| `{typography.body-md}`     | "HarmonyOS Sans", 微软雅黑, Alibaba-PuHuiTi, "Geist Sans", Arial, sans-serif | 11.5594px    | 400    | 17.9813px   | normal         | Button text, language selector               |
| `{typography.body-lg}`     | "HarmonyOS Sans", 微软雅黑, Alibaba-PuHuiTi, "Geist Sans", Arial, sans-serif | 15.4125px    | 400    | 23.1187px   | normal         | Feature descriptions                         |
| `{typography.heading-sm}`  | "HarmonyOS Sans", 微软雅黑, Alibaba-PuHuiTi, "Geist Sans", Arial, sans-serif | 16.6969px    | 400    | 22.2624px   | normal         | Sub-headings, feature titles                 |
| `{typography.heading-sm-relaxed}` | "HarmonyOS Sans", 微软雅黑, Alibaba-PuHuiTi, "Geist Sans", Arial, sans-serif | 16.6969px    | 400    | 25.0453px   | normal         | Feature descriptions with more line height   |
| `{typography.heading-sm-medium}` | "HarmonyOS Sans", 微软雅黑, Alibaba-PuHuiTi, "Geist Sans", Arial, sans-serif | 16.6969px    | 500    | 22.2624px   | normal         | Section titles, medium weight                |
| `{typography.heading-sm-semibold}` | "HarmonyOS Sans", 微软雅黑, Alibaba-PuHuiTi, "Geist Sans", Arial, sans-serif | 16.6969px    | 600    | 22.2624px   | normal         | Section titles, semibold                     |
| `{typography.heading-md}`  | "HarmonyOS Sans", 微软雅黑, Alibaba-PuHuiTi, "Geist Sans", Arial, sans-serif | 20.55px      | 400    | 24.66px     | normal         | Larger sub-headings                          |
| `{typography.heading-lg}`  | "HarmonyOS Sans", 微软雅黑, Alibaba-PuHuiTi, "Geist Sans", Arial, sans-serif | 32.1094px    | 500    | 32.1094px   | normal         | Key specifications, large numbers            |
| `{typography.display-md}`  | Goldman, "HarmonyOS Sans", ...                                           | 38.5312px    | 500    | 38.5312px   | normal         | Primary display headings, short lines        |
| `{typography.display-md-relaxed}` | Goldman, "HarmonyOS Sans", ...                                           | 38.5312px    | 500    | 57.7969px   | normal         | Primary display headings, multi-line         |

### Principles
The typographic system employs a clear hierarchy with a strong emphasis on readability for body text using "HarmonyOS Sans". Key information and brand statements are highlighted with the distinctive "Goldman" typeface, often in larger sizes and medium weights, to create visual impact. Line heights are generally generous for body text, aiding legibility, while display headings tend to have tighter line heights for a compact, powerful look. Letter spacing remains `normal` across the board, maintaining a clean and uncluttered appearance.

## Layout

The layout is characterized by a full-width, immersive design, heavily utilizing the entire viewport for imagery and content. A flexible spacing system is observed, with a tendency towards larger values for vertical separation.

*   **Spacing Scale**: While not strictly adhering to a single base unit, common spacing values are tokenized for consistency:
    *   `{spacing.xxs}` — 3px: Smallest internal padding or gap.
    *   `{spacing.xs}` — 8px: Small padding or gap, often for inline elements.
    *   `{spacing.sm}` — 13px: Standard small padding or gap.
    *   `{spacing.md}` — 26px: Medium padding or gap, common for component separation.
    *   `{spacing.lg}` — 32px: Large internal padding, e.g., within content blocks.
    *   `{spacing.xl}` — 39px: Extra large padding.
    *   `{spacing.xxl}` — 45px: Very large padding.
    *   `{spacing.section-gap}` — 68px: Vertical spacing between major content sections.
    *   `{spacing.hero-padding-top}` — 276px: Significant top padding for hero sections, adjusted responsively.

*   **Container Behavior**: Content is often full-width, but some sections, particularly in the footer and for specific text blocks, appear to be contained within an implicit maximum width, centered on the page. The navigation uses explicit horizontal padding (`{spacing.xxl}` — 45px on desktop, reducing to `0.7rem` or `11.2px` on smaller screens).

*   **Whitespace Philosophy**: The design embraces ample whitespace, particularly vertical spacing, to create a sense of openness and allow content, especially large visuals, to breathe. This contributes to the premium and uncluttered aesthetic.

## Elevation & Depth

No explicit shadow tokens or elevation styles were found in the provided data. The design primarily relies on flat surfaces and high-contrast imagery for visual hierarchy rather than simulated depth.

## Shapes

The design consistently uses sharp, unrounded corners across all elements.
*   **None** (`{rounded.none}` — 0px): All interactive elements, cards, and containers feature sharp, 90-degree corners. The large `1.67772e+07px` radius found in the data is interpreted as effectively no rounding for practical design purposes.

## Components

*   **Button Text** (`{component.button-text}`):
    *   **Structure**: Inline-flex container with text and an optional icon.
    *   **Background**: Transparent (`rgba(0, 0, 0, 0)`).
    *   **Text Color**: `{colors.on-dark}` — #ffffff.
    *   **Typography**: `{typography.body-md}` — "HarmonyOS Sans", 11.5594px, 400, 17.9813px.
    *   **Padding**: `0px`.
    *   **Border**: None.
    *   **Radius**: `{rounded.none}` — 0px.
    *   **Usage**: Navigation links, language selectors.

*   **Nav Main** (`{component.nav-main}`):
    *   **Structure**: Fixed header, full-width, containing navigation links and branding.
    *   **Background**: Transparent (`rgba(0, 0, 0, 0)`).
    *   **Text Color**: `{colors.on-dark}` — #ffffff.
    *   **Typography**: `{typography.body-sm}` — "HarmonyOS Sans", 10.275px, 400, 15.4125px.
    *   **Padding**: Horizontal: `{spacing.xxl}` — 45px (desktop), `11.2px` (mobile). Vertical: `0px`.
    *   **Radius**: `{rounded.none}` — 0px.
    *   **Height**: `48px`.

*   **Footer Default** (`{component.footer-default}`):
    *   **Structure**: Full-width footer with multiple columns for links and social media.
    *   **Background**: `{colors.canvas}` — #ffffff.
    *   **Text Color**: `{colors.text-primary}` — #000000.
    *   **Typography**: Primarily `{typography.body-sm}` — "HarmonyOS Sans", 10.275px, 400, 15.4125px for links, with `{typography.body-sm-bold}`