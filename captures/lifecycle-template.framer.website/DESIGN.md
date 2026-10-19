## Overview

The Lifecycle website presents a modern, clean, and professional aesthetic characterized by a strong emphasis on spacious layouts, a limited yet impactful color palette, and a distinctive typographic hierarchy. The visual identity balances a sense of corporate reliability with a touch of contemporary flair, utilizing a bright accent color against a largely monochromatic and earthy background. The site feels open and airy, with generous whitespace guiding the user's eye through content.

**Key Characteristics:**
*   **Minimalist Color Palette**: Dominated by `{colors.canvas}` — #f8f8f3 and `{colors.text-primary}` — #000000, with strategic use of `{colors.surface-footer}` — #09342b and `{colors.brand-accent}` — #e5f937.
*   **Distinctive Typography**: Headings employ the unique "Funnel Sans Variable" typeface, providing a modern and slightly unconventional voice, while body text uses a clear sans-serif.
*   **Generous Whitespace**: Ample padding and margins create a breathable and uncluttered user experience, particularly around content blocks and sections.
*   **Subtle Depth**: Absence of explicit shadows, relying on color contrast and layout for visual separation.
*   **Rounded Elements**: Softly rounded corners on cards and potentially pill-shaped elements contribute to a friendly and approachable feel.
*   **Structured Layout**: Content is organized into clear, full-width sections, often with internal grid-like arrangements.
*   **Monochromatic Text**: Text colors are primarily black or white (on dark backgrounds), maintaining high contrast and readability.
*   **Interactive Accent**: A vibrant yellow-green (`{colors.brand-accent}` — #e5f937) is used sparingly to draw attention to key elements.

## Colors

### Brand & Accent
*   **Brand Accent** (`{colors.brand-accent}` — #e5f937): A bright, energetic yellow-green used for highlights and calls to action. Appears as a background color for some interactive elements or decorative accents.
*   **Interactive Link** (`{colors.interactive-link}` — #0000ee): Standard blue for hyperlinks.

### Surface
*   **Canvas** (`{colors.canvas}` — #f8f8f3): The primary background color for most of the page content, providing a clean, light base.
*   **Surface Card** (`{colors.surface-card}` — #f8f8f3): Background for content cards, matching the canvas for a seamless look.
*   **Surface Nav Blurred** (`{colors.surface-nav-blurred}` — rgba(248, 248, 243, 0.3)): A semi-transparent version of the canvas color, used for the navigation bar, suggesting a frosted glass effect.
*   **Surface Footer** (`{colors.surface-footer}` — #09342b): A deep, dark green used for the footer background, providing strong contrast for text.
*   **Surface Dark Alt** (`{colors.surface-dark-alt}` — #21211c): An alternative very dark background color, used sparingly.
*   **Surface Light Alt** (`{colors.surface-light-alt}` — #edede2): An alternative light background color, slightly darker than canvas.

### Hairlines & Borders
*   **Border Default** (`{colors.border-default}` — #000000): Used for general borders and outlines.
*   **Border Muted** (`{colors.border-muted}` — rgba(59, 59, 51, .4)): A semi-transparent dark gray, used for subtle borders or dividers.
*   **Border Subtle** (`{colors.border-subtle}` — rgba(59, 59, 51, .2)): A very light semi-transparent dark gray, for even more subtle visual separation.

### Text
*   **Text Primary** (`{colors.text-primary}` — #000000): The default, high-contrast text color for most content on light backgrounds.
*   **Text Secondary** (`{colors.text-secondary}` — #3b3b33): A dark gray-green used for slightly muted text, often for secondary information.
*   **Text On Dark** (`{colors.text-on-dark}` — #f8f8f3): Used for text that appears on dark backgrounds, such as in the footer or hero sections.
*   **Text Muted** (`{colors.text-muted}` — rgba(59, 59, 51, .7)): A semi-transparent dark gray for less prominent text elements.

## Typography

### Font Family
The primary typeface for headings and prominent display text is "Funnel Sans Variable", paired with "Funnel Sans Placeholder" and a generic `sans-serif` fallback. For specific functional elements, "Geist Mono Variable" is used with a `monospace` fallback. General body text relies on a generic `sans-serif` stack.

### Hierarchy
| Token                 | Font Family                                            | Size   | Weight | Line Height | Letter Spacing | Use                                          |
| :-------------------- | :----------------------------------------------------- | :----- | :----- | :---------- | :------------- | :------------------------------------------- |
| `{typography.body-sm}`  | sans-serif                                             | 12px   | 400    | normal      | normal         | Navigation links, footer text, small body text |
| `{typography.body-mono}`| "Geist Mono Variable", monospace                       | 13px   | 400    | 18.2px      | normal         | Specific interactive elements like buttons   |
| `{typography.body-md}`  | "Funnel Sans Variable", "Funnel Sans Placeholder", sans-serif | 16px   | 400    | 22.4px      | normal         | General body text, larger navigation items   |
| `{typography.body-lg}`  | "Funnel Sans Variable", "Funnel Sans Placeholder", sans-serif | 20px   | 400    | 28px        | normal         | Larger body text, introductory paragraphs    |
| `{typography.display-sm}`| "Funnel Sans Variable", "Funnel Sans Placeholder", sans-serif | 40px   | 400    | 48px        | -0.4px         | H3 headings                                  |
| `{typography.display-md}`| "Funnel Sans Variable", "Funnel Sans Placeholder", sans-serif | 51px   | 400    | 58.65px     | -0.51px        | H2 headings                                  |
| `{typography.display-xl}`| "Funnel Sans Variable", "Funnel Sans Placeholder", sans-serif | 64px   | 400    | 67.2px      | -1.28px        | H1 headings, hero titles                     |

### Principles
The typographic system emphasizes a clear hierarchy through varying font sizes, with "Funnel Sans Variable" providing a distinctive, modern voice for all display text. A consistent `font-weight: 400` across all text styles maintains a light and approachable feel, relying solely on size and line height for differentiation. Letter spacing is subtly tightened for larger display headings to optimize visual density.

## Layout

The layout is characterized by a generous use of whitespace and a modular, section-based structure. Content is primarily contained within full-width sections that stack vertically, often with internal horizontal or vertical stacking of elements.

**Spacing Scale (6px base):**
*   `{spacing.hairline}` — 1px
*   `{spacing.xxs}` — 3px
*   `{spacing.xs}` — 6px
*   `{spacing.sm}` — 12px
*   `{spacing.md}` — 18px
*   `{spacing.lg}` — 24px
*   `{spacing.xl}` — 36px
*   `{spacing.xxl}` — 48px
*   `{spacing.section-sm}` — 72px (common vertical padding for sections)
*   `{spacing.section-md}` — 96px (common vertical padding for sections)
*   `{spacing.section-lg}` — 144px (large vertical padding for sections)
*   `{spacing.10}` — 10px (specific use for gaps)
*   `{spacing.25}` — 25px (specific use for padding)
*   `{spacing.42}` — 42px (specific use for padding)

**Grid & Container Behavior:**
The site appears to use a fluid container model, where content within sections is often constrained by implicit maximum widths or explicit padding on the left and right, typically `{spacing.lg}` — 24px, or sometimes wider for full-bleed elements. Flexbox is heavily utilized for internal arrangement, often with `flex-direction: column` for vertical stacking of major blocks and `gap` properties for consistent spacing between items.

**Whitespace Philosophy:**
Whitespace is a fundamental design element, not merely empty space. It is used to create visual breathing room, separate distinct content blocks, and enhance readability. Large vertical and horizontal gaps between sections and elements contribute to a clean, uncluttered, and premium feel.

## Elevation & Depth

The design system does not utilize explicit shadows (`shadows` array is empty). Visual hierarchy and separation are achieved primarily through color contrast, typography, and generous spacing rather than simulated depth.

## Shapes

The design incorporates subtle rounding, contributing to a softer, more approachable aesthetic.
*   **Extra Small Rounding** (`{rounded.xs}` — 4px): Minor rounding for small elements.
*   **Small Rounding** (`{rounded.sm}` — 6px): Standard rounding for cards and interactive elements.
*   **Pill Small** (`{rounded.pill-sm}` — 60px): Used for pill-shaped buttons or tags.
*   **Pill Medium** (`{rounded.pill-md}` — 80px): Larger pill shapes.
*   **Pill Large** (`{rounded.pill-lg}` — 100px): Even larger pill shapes.
*   **Pill Extra Large** (`{rounded.pill-xl}` — 200px): Very large pill shapes.
*   **Pill XXL** (`{rounded.pill-xxl}` — 600px): Extreme rounding, likely for full-width elements to create a semi-circular or fully rounded effect.

## Components

### `nav-main`
The main navigation bar.
*   **Background**: `{colors.surface-nav-blurred}` — rgba(248, 248, 243, 0.3)
*   **Typography**: `{typography.body-sm}` — 12px, 400, normal, sans-serif
*   **Text Color**: `{colors.text-primary}` — #000000
*   **Padding**: `0px` (internal items have their own spacing)
*   **Structure**: A horizontal flex container with items aligned.

### `footer-main`
The main footer section.
*   **Background**: `{colors.surface-footer}` — #09342b
*   **Typography**: `{typography.body-sm}` — 12px, 400, normal, sans-serif
*   **Text Color**: `{colors.text-on-dark}` — #f8f8f3
*   **Padding**: `{spacing.section-md}` — 96px top, `0px` horizontal, `{spacing.section-sm}` — 72px bottom.
*   **Structure**: A vertical flex container, with internal content often arranged in columns or rows that stack responsively.

### `heading-h1`
Primary page titles and hero headlines.
*   **Typography**: `{typography.display-xl}` — 64px, 400, 67.2px, -1.28px, "Funnel Sans Variable"
*   **Text Color**: `{colors.text-on-dark}` — #f8f8f3 (often used on dark backgrounds)

### `heading-h2`
Secondary section titles.
*   **Typography**: `{typography.display-md}` — 51px, 400, 58.65px, -0.51px, "Funnel Sans Variable"
*   **Text Color**: `{colors.text-primary}` — #000000

### `heading-h3`
Tertiary section titles or prominent subheadings.
*   **Typography**: `{typography.display-sm}` — 40px, 400, 48px, -0.4px, "Funnel Sans Variable"
*   **Text Color**: `{colors.text-primary}` — #000000

### `card-default`
A standard content card.
*   **Background**: `{colors.surface-card}` — #f8f8f3
*   **Border Radius**: `{rounded.sm}` — 6px
*   **Padding**: `{spacing.md}` — 18px horizontal, `{spacing.md}` — 18px top, `{spacing.lg}` — 24px bottom.
*   **Typography**: Inherits body text styles.

## Do's and Don'ts

### Do's
*   **Do** use `{colors.canvas}` — #f8f8f3 as the primary background for most sections to maintain a light and airy feel.
*   **Do** leverage "Funnel Sans Variable" for all headings (`{typography.display-xl}`, `{typography.display-md}`, `{typography.display-sm}`) to maintain brand voice.
*   **Do** apply generous vertical spacing between sections using `{spacing.section-sm}` — 72px, `{spacing.section-md}` — 96px, or `{spacing.section-lg}` — 144px.
*   **Do** use `{colors.brand-accent}` — #e5f937 sparingly for key calls to action or highlights.
*   **Do** ensure high contrast for text, using `{colors.text-primary}` — #000000 on light backgrounds and `{colors.text-on-dark}` — #f8f8f3 on dark backgrounds like `{colors.surface-footer}` — #09342b.
*   **Do** apply `{rounded.sm}` — 6px to interactive elements and cards for a consistent soft aesthetic.
*   **Do** use `flexbox` with `gap` properties for consistent spacing between elements within a container.

### Don'ts
*   **Don't** introduce new font families beyond "Funnel Sans Variable", "Geist Mono Variable", or generic sans-serif.
*   **Don't** use shadows or complex gradients, as the design relies on flat colors and strong contrast.
*   **Don't** use `{colors.brand-accent}` — #e5f937 for large background areas or extensive text; it's intended for accentuation.
*   **Don't** deviate from the established spacing scale; avoid arbitrary pixel values for padding and margins.
*   **Don't** use `font-weight` values other than `400` unless explicitly defined in the typography hierarchy.
*   **Don't** use sharp, unrounded corners for interactive elements or cards; `{rounded.sm}` — 6px is preferred.
*   **Don't** clutter layouts; prioritize generous whitespace and clear visual separation.

## Responsive Behavior

| Breakpoint | Min Width | Touch Targets | Collapse Strategy                                                                                                                                                                     |
| :--------- | :-------- | :------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `mobile`   | 0px       | Standard      | Sections and internal content typically stack vertically (`flex-direction: column`). Horizontal padding may be reduced. Large display typography may scale down.                       |
| `tablet`   | 768px     | Standard      | Content may begin to arrange in multi-column layouts where appropriate. Typography sizes may be slightly adjusted. Navigation might transition from a collapsed state to a horizontal bar. |
| `desktop`  | 1024px    | Standard      | Full desktop layout with multi-column structures and full-size typography.                                                                                                            |

The design is inherently responsive, utilizing `flex-direction: column` for major sections to ensure vertical stacking on smaller screens. Typography scales down to maintain readability and fit within narrower viewports.

## Iteration Guide

1.  **Color Extension**: When introducing new colors, ensure they complement the existing palette and are assigned clear semantic tokens (e.g., `{colors.surface-muted}`, `{colors.text-success}`). Avoid introducing new accent colors that compete with `{colors.brand-accent}` — #e5f937.
2.  **Typography Additions**: New text styles should primarily use "Funnel Sans Variable" or "sans-serif". If a new weight or size is needed, define it as a new token (e.g., `{typography.body-xl}`) and ensure it fits the existing `font-weight: 400` principle.
3.  **Spacing Consistency**: All new spacing values must align with the 6px base scale or be explicitly defined as specific-use tokens. Avoid arbitrary pixel values.
4.  **Component Variants**: When creating new component variants (e.g., `button-secondary`), reuse existing color, typography, spacing, and shape tokens. Document any new tokens required.
5.  **Shadows**: If shadows are introduced, they must be subtle and consistent, defined as `elevation` tokens, and used sparingly to maintain the flat aesthetic.
6.  **Interactive States**: Define `hover`, `focus`, and `active` states for interactive components using existing color tokens (e.g., `{colors.brand-accent-hover}`).

## Known Gaps

*   **Button Component**: While "Buy Lifecycle" text is present, no explicit button component styles (background, padding, border-radius) were extracted, only its specific typography (`{typography.body-mono}`).
*   **Iconography**: No information on icon sets or specific icon styles was available.
*   **Form Elements**: Styles for input fields, text areas, checkboxes, and radio buttons are not present in the extraction.
*   **Interactive States**: Hover, focus, and active states for most components (e.g., navigation links, cards) are not explicitly defined in the provided data.
*   **Specific Grid System**: While `flexbox` is used, a formal, explicit grid system (e.g., 12-column grid) is not detailed.
*   **Accessibility**: Specific accessibility guidelines (e.g., contrast ratios beyond basic color choices, focus indicators) are not covered by the extraction.