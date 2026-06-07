## Overview

This design system for React Bits presents a modern, dark-themed aesthetic with a strong emphasis on code-centric content and interactive elements. The visual identity is characterized by a deep, muted purple-gray background, accented with vibrant purples and subtle glows, creating an immersive and sophisticated user experience. Typography relies on the clean, contemporary `Geist` sans-serif for primary content and a distinct `Geist Mono` for code snippets and UI elements, reinforcing the developer-focused nature of the platform. Layouts are structured and spacious, utilizing generous padding and clear visual hierarchy to guide the user through complex information.

The site leverages subtle shadows and rounded corners to provide depth and delineate interactive components, while maintaining a generally flat and minimalist feel. Interactive elements often feature a striking purple accent, drawing attention and indicating interactivity. The overall impression is one of precision, modernity, and a premium feel, tailored for a technical audience.

**Key Characteristics:**
*   **Dark Theme:** Predominantly dark purple-gray and near-black backgrounds.
*   **Vibrant Purple Accents:** Strategic use of bright purple for interactive elements and highlights.
*   **Dual Typeface System:** `Geist` for readability, `Geist Mono` for code and data.
*   **Structured Layouts:** Clear separation of content areas, often with sidebars.
*   **Subtle Depth:** Minimal shadows and inset borders provide a sense of layering.
*   **Rounded Corners:** Consistent application of various border radii for a softer, modern touch.
*   **Code-Focused:** Monospace font and code-like UI elements are prominent.
*   **Spacious Design:** Ample whitespace and padding contribute to a clean, uncluttered look.

## Colors

**Brand & Accent**
*   **Accent Primary** (`{colors.accent-primary}` — #a855f7): Used for primary interactive elements like buttons, active states, and subtle background highlights.
*   **Accent Primary Alt** (`{colors.accent-primary-alt}` — #a955f7): A very similar vibrant purple, used interchangeably with `accent-primary` for backgrounds.
*   **Accent Light** (`{colors.accent-light}` — #d8aeff): Used for text on dark backgrounds, often in conjunction with accent elements.
*   **Accent Muted** (`{colors.accent-muted}` — #b497cf): A softer, muted purple used for less prominent highlights or backgrounds.
*   **Accent Blue** (`{colors.accent-blue}` — #5227ff): A bright blue-purple, used sparingly for specific background elements.
*   **Accent Pink** (`{colors.accent-pink}` — #ff9ffc): A bright pink, used sparingly for specific background elements.

**Surface**
*   **Canvas** (`{colors.canvas}` — #120f17): The primary background color of the page, a very dark, almost black hue.
*   **Surface Default** (`{colors.surface-default}` — #2f293a): A dark purple-gray used for general content containers and background elements.
*   **Surface Card** (`{colors.surface-card}` — #1b1722): A slightly darker purple-gray, specifically used for card backgrounds.
*   **Surface Inset** (`{colors.surface-inset}` — rgba(255, 255, 255, 0.04)): A very subtle translucent white, used for input fields and other interactive surfaces.

**Hairlines & Borders**
*   **Border Default** (`{colors.border-default}` — #27272a): A dark gray used for general borders and dividers.
*   **Border Subtle** (`{colors.border-subtle}` — #2f293a): A dark purple-gray, used for borders on elements with `surface-default` backgrounds.
*   **Border Accent** (`{colors.border-accent}` — rgba(255, 255, 255, 0.08)): A translucent white border, often seen on interactive elements like buttons, providing a subtle glow effect on dark backgrounds.
*   **Border Hairline** (`{colors.border-hairline}` — #000000): A pure black border, used in very specific, minimal contexts.

**Text**
*   **Text Primary** (`{colors.text-primary}` — #ffffff): The main text color for headings and primary content on dark backgrounds.
*   **Text Secondary** (`{colors.text-secondary}` — #aaaaaa): A medium gray, used for secondary information, descriptions, and less emphasized text.
*   **Text Inverted** (`{colors.text-inverted}` — #09090b): A very dark gray, used for text that appears on light backgrounds (though less common on this dark-themed site).

## Typography

### Font Family
The primary typeface for general content and headings is "Geist", a modern sans-serif. For code snippets, UI elements, and data display, the monospaced font "Geist Mono" is used, often with `ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace` as fallbacks.

### Hierarchy

| Token             | Font Family                     | Size      | Weight | Line Height | Letter Spacing | Use                                       |
| :---------------- | :------------------------------ | :-------- | :----- | :---------- | :------------- | :---------------------------------------- |
| `{typography.display-xl}` | Geist, sans-serif               | 56px      | 900    | 56px        | normal         | Main page titles, prominent headlines     |
| `{typography.heading-lg}` | Geist, sans-serif               | 38.4px    | 600    | 42.24px     | -1.152px       | Section headings, large statements        |
| `{typography.heading-md}` | Geist, sans-serif               | 22.4px    | 900    | 33.6px      | normal         | Sub-section titles, prominent labels      |
| `{typography.body-default}` | Geist, sans-serif               | 16px      | 400    | 24px        | normal         | Standard body text, paragraphs            |
| `{typography.body-sm}` | Geist, sans-serif               | 13.6px    | 500    | 20.4px      | normal         | Secondary body text, introductions        |
| `{typography.body-xs}` | Geist, sans-serif               | 13px      | 400    | 19.5px      | normal         | Small body text, descriptions             |
| `{typography.label-lg}` | Geist, sans-serif               | 14px      | 500    | 21px        | -0.5px         | Call-to-action buttons, prominent labels  |
| `{typography.label-md}` | Geist, sans-serif               | 14px      | 500    | 20px        | normal         | Component labels, preview text            |
| `{typography.label-sm}` | Geist, sans-serif               | 13px      | 500    | 19.5px      | normal         | Small labels, feature names               |
| `{typography.label-xs}` | Geist, sans-serif               | 12px      | 600    | 18px        | normal         | Smallest labels, sign-up buttons          |
| `{typography.label-xxs}` | Geist, sans-serif               | 11px      | 600    | 16.5px      | 0.22px         | Micro-labels, "New" tags                  |
| `{typography.mono-lg}` | "Geist Mono", monospace         | 16px      | 400    | 24px        | normal         | Code blocks, navigation links             |
| `{typography.mono-md}` | "Geist Mono", ui-monospace, monospace | 13px      | 500    | 19.5px      | normal         | Input values, search placeholders         |
| `{typography.mono-sm}` | "Geist Mono", monospace         | 13px      | 500    | 19.5px      | 0.52px         | Navigation items, emphasized mono text    |
| `{typography.mono-xs}` | "Geist Mono", ui-monospace, monospace | 12px      | 400    | 18px        | normal         | Small code snippets, input placeholders   |
| `{typography.mono-xxs}` | "Geist Mono", monospace         | 10px      | 600    | 0px         | normal         | Tiny labels, "New" tags (mono)            |

### Principles
The typography establishes a clear hierarchy using a combination of font sizes, weights, and letter spacing. `Geist` is employed for all primary content, with `900` weight for large display text and `400-600` for body and headings, ensuring strong readability. `Geist Mono` is consistently used for all technical or UI-specific text, maintaining a consistent brand voice for code-related content. Letter spacing is generally `normal`, with subtle adjustments (`-0.5px` for large headings, `0.22px` or `0.52px` for small, emphasized mono text) to optimize legibility and visual density. Casing is typically sentence case, with some instances of title case for labels.

## Layout

The layout system is built on a flexible grid, with content primarily constrained within a main column and often accompanied by a persistent sidebar. Spacing is generous, contributing to a clean and breathable interface.

**Spacing Scale (4px base):**
*   `{spacing.xxs}` — 2px: Micro-spacing, often for hairline borders or very small internal padding.
*   `{spacing.xs}` — 4px: Extra small spacing, used for tight element separation.
*   `{spacing.sm}` — 6px: Small spacing, for internal component padding or minor gaps.
*   `{spacing.md}` — 8px: Medium spacing, common for button padding, icon-text separation.
*   `{spacing.lg}` — 10px: Larger medium spacing, for component padding or list item separation.
*   `{spacing.xl}` — 12px: Extra large spacing, for moderate gaps between elements.
*   `{spacing.xxl}` — 14px: Double extra large spacing, for larger component padding or margins.
*   `{spacing.xxxl}` — 16px: Triple extra large spacing, for significant internal padding or margins.
*   `{spacing.xxxxl}` — 20px: Quadruple extra large spacing, for substantial gaps between sections or components.
*   `{spacing.section-sm}` — 24px: Small section spacing, for vertical separation of content blocks.
*   `{spacing.section-md}` — 32px: Medium section spacing, for larger vertical separation.
*   `{spacing.section-lg}` — 92px: Large section spacing, for significant vertical and horizontal content separation.
*   `{spacing.section-xl}` — 96px: Extra large section spacing, for major content block separation.

**Grid & Container Behavior:**
*   The main content area (`.category-wrapper`) appears to have a fixed maximum width or is centered with large horizontal padding, allowing for a consistent reading experience.
*   A persistent left sidebar (`.sidebar`) occupies a fixed width of 162px, providing navigation.
*   A right-hand `aside` panel is present, with a width of 300px, used for supplementary content like promotions.
*   Content is typically left-aligned within its containers.

**Whitespace Philosophy:**
The design embraces ample whitespace, particularly around major content blocks and within components. This creates a sense of calm and order, reducing visual clutter and improving readability, especially given the dark theme. Large horizontal padding on the main content area ensures text lines are not excessively long.

## Elevation & Depth

Depth is subtly introduced through shadows and inset borders, primarily to distinguish interactive elements and cards from the background.

*   **Shadow Default** (`{shadow.default}` — rgba(0, 0, 0, 0.15) 0px 4px 24px 0px): A soft, diffused shadow used for general elevation, likely seen on dropdowns, modals, or floating elements.
*   **Shadow Card** (`{shadow.card}` — rgba(0, 0, 0, 0.2) 0px 2px 16px 0px, rgba(255, 255, 255, 0.06) 0px 0.5px 0px 0px inset): A more pronounced shadow with a subtle white inset border, giving cards a lifted appearance and a slight internal highlight.

## Shapes

The design incorporates various levels of border-radius to soften edges and define component boundaries.

*   **Rounded Hairline** (`{rounded.hairline}` — 1px): Minimal rounding, almost sharp, used for very subtle edge softening.
*   **Rounded XS** (`{rounded.xs}` — 4px): Extra small rounding, for subtle softening of interactive elements.
*   **Rounded SM** (`{rounded.sm}` — 6px): Small rounding, commonly used for input fields and smaller interactive elements.
*   **Rounded MD** (`{rounded.md}` — 8px): Medium rounding, for general component containers and cards.
*   **Rounded LG** (`{rounded.lg}` — 10px): Large rounding, frequently used for buttons and more prominent interactive elements.
*   **Rounded XL** (`{rounded.xl}` — 12px): Extra large rounding, for larger components or distinct containers.
*   **Rounded XXL** (`{rounded.xxl}` — 14px): Double extra large rounding.
*   **Rounded XXXL** (`{rounded.xxxl}` — 16px): Triple extra large rounding.
*   **Rounded Huge** (`{rounded.huge}` — 50px): Very large rounding, used for distinct, often circular or pill-shaped elements.
*   **Rounded Full** (`{rounded.full}` — 999px): Maximum rounding, creating pill-shaped or circular elements.

## Components

*   `button-icon-navbar`:
    *   **Structure**: Small, compact button, often containing an icon or short text.
    *   **Background**: `{colors.surface-inset}` — rgba(18, 15, 23, 0.45)
    *   **Text Color**: `{colors.text-primary}` — rgba(255, 255, 255, 0.6)
    *   **Border**: 1px solid `{colors.border-accent}` — rgba(255, 255, 255, 0.08)
    *   **Padding**: `{spacing.xxl}` — 14px horizontal, vertical padding implied by height.
    *   **Border Radius**: `{rounded.lg}` — 10px
    *   **Typography**: `{typography.mono-md}` — "Geist Mono", monospace, 13px, 500, 19.5px.

*   `input-text`:
    *   **Structure**: Standard single-line text input field.
    *   **Background**: `{colors.surface-inset}` — rgba(255, 255, 255, 0.04)
    *   **Text Color**: `{colors.text-primary}` — rgb(255, 255, 255)
    *   **Border**: 1px solid `{colors.border-subtle}` — rgb(47, 41, 58)
    *   **Padding**: `{spacing.md}` — 8px horizontal, vertical padding implied.
    *   **Border Radius**: `{rounded.sm}` — 6px
    *   **Typography**: `{typography.mono-xs}` — "Geist Mono", ui-monospace, monospace, 12px, 400, 18px.

*   `nav-main`:
    *   **Structure**: Horizontal navigation links.
    *   **Background**: Transparent.
    *   **Text Color**: `{colors.text-primary}` — rgba(255, 255, 255, 0.87)
    *   **Border**: None.
    *   **Padding**: None.
    *   **Border Radius**: `{rounded.none}` — 0px
    *   **Typography**: `{typography.mono-lg}` — "Geist Mono", monospace, 16px, 400, 24px.

*   `card-default`:
    *   **Structure**: A general-purpose container for content, often with a shadow.
    *   **Background**: `{colors.surface-card}` — #1b1722 (inferred from `--bg-card` variable, though sample shows transparent).
    *   **Text Color**: `{colors.text-primary}` — rgba(255, 255, 255, 0.87)
    *   **Border**: None (or subtle, not explicitly defined in sample).
    *   **Padding**: Variable, often `{spacing.xxxxl}` — 20px or more.
    *   **Border Radius**: `{rounded.md}` — 8px (inferred from common usage, sample shows 0px but `chakra-stack` is a generic container).
    *   **Shadow**: `{shadow.card}` — rgba(0, 0, 0, 0.2) 0px 2px 16px 0px, rgba(255, 255, 255, 0.06) 0px 0.5px 0px 0px inset.

## Do's and Don'ts

**Do's:**
*   **Do** use `Geist, sans-serif` for all primary headings and body text to maintain a modern, clean aesthetic.
*   **Do** apply `{colors.accent-primary}` — #a855f7 for key interactive elements like buttons and active states.
*   **Do** utilize `{colors.canvas}` — #120f17 as the page's main background color for a consistent dark theme.
*   **Do** use `{Geist Mono, monospace}` for code examples, input fields, and navigation items to clearly distinguish technical content.
*   **Do** ensure generous `{spacing.section-md}` — 32px or `{spacing.section-lg}` — 92px between major content blocks to enhance readability.
*   **Do** apply `{rounded.lg}` — 10px to primary buttons and `{rounded.sm}` — 6px to input fields for a consistent soft-edged feel.
*   **Do** use `{shadow.card}` for distinct content cards to give them a subtle lifted appearance.

**Don'ts:**
*   **Don't** use light backgrounds for main content areas; stick to the dark theme palette.
*   **Don't** mix `Geist` and `Geist Mono` within the same sentence or short phrase unless it's a specific code inline element.
*   **Don't** use `{colors.text-inverted}` — #09090b on dark backgrounds; it's reserved for light surfaces.
*   **Don't** use excessive or multiple shadows on a single element; maintain subtle depth.
*   **Don't** deviate from the established spacing scale; maintain `{spacing.md}` — 8px for small gaps and `{spacing.xxxl}` — 16px for larger component padding.
*   **Don't** use overly sharp corners; `{rounded.none}` should be rare, with `{rounded.hairline}` as the minimum.

## Responsive Behavior

| Breakpoint | Min Width | Touch Targets                               | Collapse Strategy