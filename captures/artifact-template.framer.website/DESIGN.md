## Overview

This website presents a clean, modern, and professional aesthetic, emphasizing clarity and direct communication. The design utilizes a minimalist color palette dominated by black and white, with a subtle off-white accent and a distinct blue for interactive elements. Typography plays a crucial role, employing the contemporary "Geist Variable" typeface for headlines and key information, paired with a standard sans-serif for general body text, creating a strong visual hierarchy. Layouts are structured with generous vertical spacing and a clear focus on content, often using full-width sections that stack vertically. Subtle elevation through shadows is applied to interactive elements like cards, adding a touch of depth without distracting from the flat design.

**Key Characteristics:**
*   **Monochromatic Base:** Primarily black (`{colors.text-primary}` — #000000) and white (`{colors.canvas}` — #ffffff).
*   **Modern Typography:** "Geist Variable" for display, `sans-serif` for body.
*   **Generous Whitespace:** Ample vertical and horizontal padding, especially between sections.
*   **Subtle Depth:** Minimal shadows (`{elevation.card}` — rgba(0, 0, 0, 0.06) 0px 2px 6px 0px) for cards.
*   **Structured Layout:** Content is organized into distinct, often full-width, vertical sections.
*   **Functional Accent:** A clear blue (`{colors.link-primary}` — #0000ee) for links and interactive elements.
*   **Rounded Corners:** Gentle `6px` radius (`{rounded.md}` — 6px) on cards.
*   **Consistent Spacing Scale:** Based on a `6px` unit, providing a harmonious rhythm.

## Colors

**Brand & Accent**
*   **Primary Link** (`{colors.link-primary}` — #0000ee): Used for interactive text elements like navigation links and calls to action. This bright blue provides a clear visual cue for clickable items against the predominantly monochrome background.

**Surface**
*   **Canvas** (`{colors.canvas}` — #ffffff): The primary background color for most of the page content and cards, providing a bright, clean foundation.
*   **Surface Secondary** (`{colors.surface-secondary}` — #f6f4f1): A light, off-white background color used for specific sections, offering a subtle visual break from the main canvas.
*   **Surface Footer** (`{colors.surface-footer}` — #000000): Used as the background for the footer, creating a strong, dark contrast at the bottom of the page.

**Text**
*   **Text Primary** (`{colors.text-primary}` — #000000): The dominant color for all headings, body text, and general content, ensuring high readability against light backgrounds.

## Typography

### Font Family
The primary typeface for display and most body text is **"Geist Variable"** with a fallback to **"Geist Placeholder"** and generic `sans-serif`. For general utility and smaller text, a generic `sans-serif` is used.

### Hierarchy

| Token          | Font Family                               | Size  | Weight | Line Height | Letter Spacing | Use                                       |
| :------------- | :---------------------------------------- | :---- | :----- | :---------- | :------------- | :---------------------------------------- |
| `{typography.body-xs}` | `sans-serif`                              | 12px  | 400    | normal      | normal         | Default body text, navigation links, utility text |
| `{typography.body-sm}` | `"Geist Variable", "Geist Placeholder", sans-serif` | 14px  | 400    | 19.6px      | normal         | Navigation items, smaller body text       |
| `{typography.body-md}` | `"Geist Variable", "Geist Placeholder", sans-serif` | 17px  | 400    | 23.8px      | normal         | Standard body text, descriptive paragraphs |
| `{typography.body-lg}` | `"Geist Variable", "Geist Placeholder", sans-serif` | 20px  | 400    | 26px        | normal         | Emphasized body text, sub-headings        |
| `{typography.display-md}` | `"Geist Variable", "Geist Placeholder", sans-serif` | 28px  | 400    | 33.6px      | normal         | Section titles, prominent quotes          |
| `{typography.display-lg}` | `"Geist Variable", "Geist Placeholder", sans-serif` | 40px  | 400    | 46px        | -0.8px         | Large headings, section introductions     |
| `{typography.display-xl}` | `"Geist Variable", "Geist Placeholder", sans-serif` | 56px  | 400    | 61.6px      | -1.12px        | Primary page titles, hero headlines       |

### Principles
The typographic system establishes a clear hierarchy using varying font sizes and line heights, primarily relying on the "Geist Variable" typeface for visual impact. Most text uses a regular `400` weight, maintaining a light and airy feel. Display headings (`{typography.display-lg}` — 40px, `{typography.display-xl}` — 56px) employ subtle negative letter spacing to optimize visual density and readability at larger sizes. Body text maintains `normal` letter spacing for comfortable reading.

## Layout

The layout is built on a `6px` spacing unit, creating a consistent vertical and horizontal rhythm.

*   **Spacing Scale:**
    *   `{spacing.xxs}` — 3px
    *   `{spacing.xs}` — 6px
    *   `{spacing.sm}` — 9px
    *   `{spacing.md}` — 10px
    *   `{spacing.lg}` — 12px
    *   `{spacing.xl}` — 18px
    *   `{spacing.xxl}` — 24px
    *   `{spacing.section-sm}` — 36px
    *   `{spacing.section-md}` — 48px
    *   `{spacing.section-lg}` — 72px
    *   `{spacing.section-xl}` — 96px

*   **Grid & Container Behavior:** Content is typically presented in full-width sections, with internal elements often centered or aligned within a maximum content width (implied around 1200px based on `bbox` widths, though not explicitly defined as a container token). Sections frequently utilize `flex` display with `flex-direction: column` to stack content vertically, especially on smaller viewports. Gaps between elements within these sections are consistently applied using the spacing scale (e.g., `{spacing.md}` — 10px, `{spacing.lg}` — 12px, `{spacing.xxl}` — 24px).

*   **Whitespace Philosophy:** The design embraces generous whitespace, particularly vertical spacing between sections (`{spacing.section-lg}` — 72px, `{spacing.section-xl}` — 96px). This creates a breathable, uncluttered experience, allowing content to stand out and improving readability. Internal padding within components like cards (`{spacing.xxl}` — 24px, `{spacing.xl}` — 18px) also contributes to this open feel.

## Elevation & Depth

The design uses subtle shadows to create a sense of depth and highlight interactive elements, adhering to a generally flat aesthetic.

*   **Card Shadow** (`{elevation.card}` — rgba(0, 0, 0, 0.06) 0px 2px 6px 0px): A soft, diffused shadow applied to cards to lift them slightly from the background, indicating they are distinct, interactive content blocks.

## Shapes

The design incorporates a few distinct border radii to soften edges and define component boundaries.

*   **Rounded Small** (`{rounded.sm}` — 4px): A subtle rounding, likely used for smaller interactive elements or input fields (not explicitly found in components, but present in radius data).
*   **Rounded Medium** (`{rounded.md}` — 6px): The most common radius, applied to cards (`{component.card-primary}`), providing a gentle, friendly curve.
*   **Rounded Large** (`{rounded.lg}` — 200px): A very large radius, suggesting use for pill-shaped buttons or tags, though no specific component uses this in the provided data.
*   **Rounded Full** (`{rounded.full}` — 100%): Used for perfectly circular elements, such as avatars or badges.

## Components

*   **Navigation Bar** (`{component.nav}`):
    *   **Structure:** A horizontal bar at the top of the page.
    *   **Background:** Transparent (`rgba(0, 0, 0, 0)`).
    *   **Text Color:** `{colors.text-primary}` — #000000.
    *   **Typography:** `{typography.body-xs}` — 12px `sans-serif`.
    *   **Padding:** `{spacing.none}` — 0px.
    *   **Layout:** Uses `flex` display with a `gap` of `{spacing.md}` — 10px between items.

*   **Footer** (`{component.footer}`):
    *   **Structure:** A full-width section at the bottom of the page.
    *   **Background:** `{colors.surface-footer}` — #000000.
    *   **Text Color:** `{colors.text-primary}` — #000000 (likely overridden by child elements for contrast, but the component itself has this default).
    *   **Typography:** `{typography.body-xs}` — 12px `sans-serif`.
    *   **Padding:** `{spacing.section-xl}` — 96px vertical padding, `{spacing.none}` — 0px horizontal.

*   **Hero Section** (`{component.hero}`):
    *   **Structure:** A prominent section at the top of the page, often containing a headline and introductory text.
    *   **Background:** `{colors.canvas}` — #ffffff.
    *   **Padding:** `{spacing.xl}` — 18px top padding, `{spacing.none}` — 0px horizontal/bottom.

*   **Card Primary** (`{component.card-primary}`):
    *   **Structure:** A rectangular container for content, often used for pricing plans or testimonials.
    *   **Background:** `{colors.surface-card}` — #ffffff.
    *   **Border Radius:** `{rounded.md}` — 6px.
    *   **Shadow:** `{elevation.card}` — rgba(0, 0, 0, 0.06) 0px 2px 6px 0px.
    *   **Padding:** `{spacing.xxl}` — 24px.
    *   **Typography:** Inherits from parent, but internal text often uses `{typography.body-md}` — 17px or `{typography.body-lg}` — 20px.

*   **Card Secondary** (`{component.card-secondary}`):
    *   **Structure:** Similar to `card-primary` but with slightly less padding.
    *   **Background:** `{colors.surface-card}` — #ffffff.
    *   **Border Radius:** `{rounded.md}` — 6px.
    *   **Shadow:** `{elevation.card}` — rgba(0, 0, 0, 0.06) 0px 2px 6px 0px.
    *   **Padding:** `{spacing.xl}` — 18px.
    *   **Typography:** Inherits from parent.

## Do's and Don'ts

**Do's:**
*   **Do** use "Geist Variable" for all display text (`{typography.display-xl}` — 56px, `{typography.display-lg}` — 40px, `{typography.display-md}` — 28px, `{typography.body-lg}` — 20px, `{typography.body-md}` — 17px, `{typography.body-sm}` — 14px) to maintain brand voice.
*   **Do** apply `{colors.text-primary}` — #000000 for all primary text content against light backgrounds.
*   **Do** ensure interactive elements like links use `{colors.link-primary}` — #0000ee for clear affordance.
*   **Do** utilize `{spacing.section-xl}` — 96px or `{spacing.section-lg}` — 72px for vertical separation between major content sections.
*   **Do** apply `{rounded.md}` — 6px to all card-like elements for consistent visual softness.
*   **Do** use `{elevation.card}` — rgba(0, 0, 0, 0.06) 0px 2px 6px 0px for any elevated content blocks to maintain subtle depth.
*   **Do** use `{colors.canvas}` — #ffffff as the default background for most content areas.

**Don'ts:**
*   **Don't** introduce new font families; stick to "Geist Variable" and `sans-serif`.
*   **Don't** use strong, saturated colors for backgrounds or large text areas, as the palette is intentionally restrained.
*   **Don't** deviate from the established spacing scale; all padding and margins should derive from `{spacing.xxs}` — 3px to `{spacing.section-xl}` — 96px.
*   **Don't** use harsh or deep shadows; maintain the subtle effect of `{elevation.card}`.
*   **Don't** use sharp, unrounded corners on interactive or card-like elements; `{rounded.md}` — 6px is preferred.
*   **Don't** use `sans-serif` for prominent headings; reserve it for utility text and default body (`{typography.body-xs}` — 12px).

## Responsive Behavior

| Breakpoint | Min Width | Touch Targets | Collapse Strategy                                                                                             |
| :--------- | :-------- | :------------ | :------------------------------------------------------------------------------------------------------------ |
| `mobile`   | 0px       | Standard      | Sections stack vertically (`flex-direction: column`). Horizontal padding may reduce. Navigation likely collapses to a hamburger menu. |
| `tablet`   | 768px     | Standard      | Content remains stacked, but with more horizontal space. Cards or multi-column layouts may begin to appear.   |
| `desktop`  | 1024px    | Standard      | Full multi-column layouts and wider content containers are utilized.                                          |
| `wide`     | 1440px    | Standard      | Provides additional horizontal space for content, potentially wider content areas or more generous side margins. |

The design primarily uses `flex-direction: column` for `pageSections`, indicating a mobile-first or mobile-friendly stacking approach. As screen width increases, these columns likely adapt to multi-column layouts, maximizing horizontal space while maintaining readability. Touch targets are assumed to be standard and accessible across all breakpoints.

## Iteration Guide

1.  **Extend Spacing:** When new spacing values are needed, always derive them as multiples or fractions of the `{spacing.xs}` — 6px unit. For example, `spacing.xxxs` could be `2px` or `3px`.
2.  **Color Variants:** If new colors are required, introduce them as semantic tokens (e.g., `colors.text-muted`, `colors.surface-accent`) and ensure they harmonize with the existing monochrome and blue palette. Avoid introducing highly saturated or clashing hues.
3.  **Typography Additions:** For new text styles, first attempt to fit them within the existing hierarchy. If a new size or weight is essential, define it using "Geist Variable" and ensure it maintains the overall light weight and clean aesthetic.
4.  **Component States:** When developing interactive components, define `hover`, `focus`, and `active` states using existing color tokens or subtle variations (e.g., slight darkening of `{colors.link-primary}` — #0000ee).
5.  **New Components:** When creating new components, prioritize re-using existing tokens for colors, typography, spacing, and shapes. If a new token is absolutely necessary (e.g., a unique border radius), add it to the system with a clear semantic name.

## Known Gaps

*   **Interactive States (Hover/Focus/Active):** The provided data does not include styles for interactive states beyond the default. These would need to be defined for a complete design system.
*   **Specific Button Styles:** While `link-primary` implies interactive elements, explicit button component styles (e.g., `button-primary`, `button-secondary`) with defined padding, background, and text color are not present.
*   **Form Element Styles:** Input fields, text areas, checkboxes, and radio buttons are not explicitly defined, including their default, focus, and error states.
*   **Iconography:** No information on icon sets, sizes, or colors is available.
*   **Content Widths:** While sections appear to have implied content maximums, a specific container width token (e.g., `layout.container-lg`) is not explicitly defined.
*   **Hairline/Border Colors:** No specific border colors are identified beyond the default black.