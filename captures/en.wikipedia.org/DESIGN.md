## Overview

This design system, derived from a Wikipedia page, embodies a highly functional, content-first aesthetic. Its primary purpose is to deliver information clearly and efficiently, prioritizing readability and accessibility over decorative elements. The visual identity is characterized by a clean, neutral palette, strong typographic hierarchy, and a structured layout that supports dense information display. The design is utilitarian, leveraging standard browser styles and subtle enhancements to create a familiar and unobtrusive user experience.

**Key Characteristics:**
*   **Content-first**: Emphasis on text readability and information density.
*   **Neutral Palette**: Predominantly grayscale with a distinct blue for links and accents.
*   **Clear Typography**: Uses a sans-serif for body text and a classic serif for prominent headings, ensuring high legibility.
*   **Structured Layout**: Utilizes a multi-column grid for main content and sidebars, optimizing for information presentation.
*   **Minimalist Decoration**: Very few shadows, subtle borders, and small radii contribute to a clean, uncluttered look.
*   **Functional Interactivity**: Links are clearly distinguished by color, with subtle hover states.
*   **System Fonts**: Relies heavily on system sans-serif fonts for broad compatibility and performance.
*   **Subtle Depth**: Shadows are used sparingly, primarily for subtle elevation rather than strong visual separation.

## Colors

### Brand & Accent
*   **Brand Accent** (`{colors.brand-accent}` — #3366cc): The primary interactive color, used for links, active states, and other progressive actions. Also defined as `--accent-color-base`.
*   **Link Hover** (`{colors.link-hover}` — #3056a9): A darker shade of the brand accent, indicating interactive elements on hover.
*   **Link Visited** (`{colors.link-visited}` — #6a60b0): A distinct purple hue for visited links, aiding user navigation.

### Surface
*   **Canvas** (`{colors.canvas}` — #ffffff): The main background color for the page, providing a clean white base. Also defined as `--background-color-base`.
*   **Surface Subtle** (`{colors.surface-subtle}` — #f8f9fa): A very light gray used for subtle background distinctions, such as interactive elements in a subtle state. Also defined as `--background-color-interactive-subtle`.
*   **Surface Interactive** (`{colors.surface-interactive}` — #eaecf0): A light gray used for interactive backgrounds or notice areas. Also defined as `--background-color-notice-subtle`.

### Hairlines & Borders
*   **Border Primary** (`{colors.border-primary}` — #202122): A dark gray used for primary borders and outlines, matching the primary text color.
*   **Border Emphasized** (`{colors.border-emphasized}` — #202122): Same as border primary, used for emphasized borders. Also defined as `--border-color-emphasized`.
*   **Border Subtle** (`{colors.border-subtle}` — #72777d): A medium gray used for less prominent borders.
*   **Border Divider** (`{colors.border-divider}` — #a2a9b1): A light gray specifically for dividing elements. Also defined as `--border-color-divider`.

### Text
*   **Text Primary** (`{colors.text-primary}` — #202122): The default dark gray color for most body text. Also defined as `--color-base-fixed`.
*   **Text Black** (`{colors.text-black}` — #000000): Pure black used for some text and borders, often for maximum contrast.
*   **Text Secondary** (`{colors.text-secondary}` — #404244): A slightly lighter dark gray, potentially for secondary information or hover states.
*   **Text Muted** (`{colors.text-muted}` — #54595d): A darker gray for less prominent text. Also defined as `--color-base--subtle`.
*   **Text Emphasized** (`{colors.text-emphasized}` — #101418): A very dark gray, almost black, for emphasized text. Also defined as `--color-emphasized`.
*   **Text Placeholder** (`{colors.text-placeholder}` — #72777d): A medium gray for placeholder text. Also defined as `--color-placeholder`.
*   **Text Disabled** (`{colors.text-disabled}` — #a2a9b1): A light gray for disabled text, matching the divider color. Also defined as `--color-disabled`.

### Semantic
*   **Semantic Error** (`{colors.semantic-error}` — #f54739): A bright red for error messages or states. Also defined as `--background-color-error`.
*   **Semantic Error Active** (`{colors.semantic-error-active}` — #612419): A darker red for active error states. Also defined as `--color-error--active`.
*   **Semantic Warning Subtle** (`{colors.semantic-warning-subtle}` — #fdf2d5): A very light yellow for subtle warning backgrounds. Also defined as `--background-color-warning-subtle`.
*   **Semantic Icon Warning** (`{colors.semantic-icon-warning}` — #ab7f2a): A golden-brown for warning icons. Also defined as `--color-icon-warning`.
*   **Semantic Progressive Subtle** (`{colors.semantic-progressive-subtle}` — #e8eeff): A very light blue for subtle progressive backgrounds. Also defined as `--background-color-progressive-subtle`.

## Typography

### Font Family
The primary body and UI typeface is a generic **sans-serif** stack, likely resolving to system fonts like Arial, Helvetica, or Roboto, ensuring broad compatibility and fast loading. For prominent display headings, a classic serif typeface, **"Linux Libertine", Georgia, Times, "Source Serif 4", serif**, is used to provide a more editorial and authoritative feel. **Arial** is also explicitly used for some smaller UI elements.

### Hierarchy

| Token                 | Font Family                                          | Size       | Weight | Line Height | Letter Spacing | Use                                       |
| :-------------------- | :--------------------------------------------------- | :--------- | :----- | :---------- | :------------- | :---------------------------------------- |
| `{typography.display-xl}` | "Linux Libertine", Georgia, Times, "Source Serif 4", serif | 28.8px     | 400    | 39.6px      | normal         | Main page titles (H1)                     |
| `{typography.heading-1}` | sans-serif                                           | 26px       | 400    | normal      | normal         | Section headings (H2)                     |
| `{typography.heading-2}` | sans-serif                                           | 21px       | 400    | normal      | normal         | Sub-section headings (H3)                 |
| `{typography.body-lg}` | sans-serif                                           | 16px       | 400    | 26px        | normal         | Primary body text, main navigation items  |
| `{typography.body-md}` | sans-serif                                           | 14px       | 400    | normal      | normal         | Most common body text, list items         |
| `{typography.body-md-lh}` | sans-serif                                           | 14px       | 400    | 22px        | normal         | Body text with explicit line height       |
| `{typography.body-md-bold}` | sans-serif                                           | 14px       | 700    | normal      | normal         | Bolded body text, menu labels             |
| `{typography.body-sm}` | Arial                                                | 12px       | 400    | normal      | normal         | Secondary UI text, small labels           |
| `{typography.caption}` | sans-serif                                           | 11.2px     | 700    | normal      | normal         | Small, bold captions or toggle labels     |
| `{typography.input-default}` | Arial                                                | 13.3333px  | 400    | normal      | normal         | Default input text                        |

### Principles
The typographic system prioritizes readability and clear information hierarchy. A sans-serif typeface is used for the majority of the content and UI elements, ensuring a clean and modern feel. Key headings and titles utilize a serif typeface, providing a traditional and authoritative contrast. Weights are generally kept to regular (400) and bold (700), with `normal` letter spacing, to maintain a straightforward and functional appearance. Line heights are carefully chosen to enhance readability for different text sizes, particularly for longer blocks of body text.

## Layout

The layout system is built on a flexible grid structure, primarily defining content areas and sidebars. A base unit of **4px** is used to derive a comprehensive spacing scale, though some values deviate, suggesting a pragmatic approach to spacing.

*   **Spacing Scale (4px base)**:
    *   `{spacing.hairline}` — 1px
    *   `{spacing.xxs}` — 4px
    *   `{spacing.xs}` — 6px
    *   `{spacing.sm}` — 8px
    *   `{spacing.md}` — 12px
    *   `{spacing.lg}` — 16px
    *   `{spacing.xl}` — 20px
    *   `{spacing.xxl}` — 24px
    *   `{spacing.xxxl}` — 32px
    *   `{spacing.xxxxl}` — 44px
    *   `{spacing.xxxxl-plus}` — 45px

*   **Grid & Container Behavior**:
    *   The main content area (`main.mw-body`) employs a two-column grid: `grid-template-columns: 687px 196px;` with a `gap` of `{spacing.xxl}` — 24px. This creates a primary content column and a narrower sidebar column.
    *   The overall page structure includes a header, main content area, and a footer, with additional navigation elements often presented as sidebars or overlays.
    *   Containers generally have a fixed maximum width or are fluid within a defined content area, ensuring content remains readable.

*   **Whitespace Philosophy**:
    *   Whitespace is used generously to separate distinct content blocks and improve readability, but not excessively, maintaining an information-dense presentation.
    *   Padding is consistently applied to elements like footers (`{spacing.md}` — 12px vertical padding) and list items (`{spacing.md}` — 12px left padding for nested items), creating clear visual hierarchy and grouping.
    *   Minimal negative margins are observed in specific contexts, likely for fine-tuning element alignment or overlap.

## Elevation & Depth

Elevation and depth are used sparingly, primarily to indicate interactive elements or subtle separation.

*   **Shadow Medium** (`{shadow.md}` — rgba(0, 0, 0, 0.2) 0px 2px 6px -1px): A subtle, diffused shadow used to give a slight lift to elements, suggesting interactivity or a floating context.
*   **Shadow Inset Hairline** (`{shadow.inset-hairline}` — rgba(0, 0, 0, 0) 0px 0px 0px 1px inset): A very thin, transparent inset shadow, likely used for subtle border effects or focus indicators.
*   **Shadow Border Bottom** (`{shadow.border-bottom}` — rgb(200, 204, 209) 0px 1px 0px 0px): A crisp, single-pixel bottom shadow, effectively acting as a subtle divider or border.

## Shapes

Shapes are predominantly rectangular with minimal rounding, emphasizing a clean and functional aesthetic.

*   **Rounded Small** (`{rounded.sm}` — 2px): A very slight border-radius applied to some interactive elements or containers, providing a touch of softness without compromising the sharp, informational feel.
*   **Rounded Full** (`{rounded.full}` — 50%): Used for perfectly circular elements, such as avatars or small icons that require a circular shape.
*   **Rounded None** (`{rounded.none}` — 0px): The default for most elements, maintaining sharp corners consistent with the functional design.

## Components

*   **`button-default`**
    *   **Structure**: `input.vector-dropdown-checkbox`
    *   **Appearance**: Minimal styling, often transparent background and no explicit border or shadow. Relies on browser defaults or parent container styling for visual cues.
    *   **Typography**: Inherits from parent, often `{typography.input-default}` — Arial, 13.3333px, 400.
    *   **Padding**: `{spacing.none}` — 0px.

*   **`nav-main`**
    *   **Structure**: `nav.vector-main-menu-landmark`
    *   **Appearance**: Transparent background, no explicit borders or shadows.
    *   **Typography**: Inherits from parent, often `{typography.body-lg}` — sans-serif, 16px, 400.
    *   **Padding**: `{spacing.none}` — 0px.

*   **`input-default`**
    *   **Structure**: `input.vector-dropdown-checkbox`
    *   **Appearance**: Transparent background, no explicit borders or shadows.
    *   **Typography**: `{typography.input-default}` — Arial, 13.3333px, 400.
    *   **Padding**: `{spacing.none}` — 0px.

*   **`footer-main`**
    *   **Structure**: `footer.mw-footer`
    *   **Appearance**: Transparent background, no explicit borders or shadows.
    *   **Typography**: Inherits from parent, often `{typography.body-lg}` — sans-serif, 16px, 400.
    *   **Padding**: `{spacing.md}` — 12px vertical, `{spacing.none}` — 0px horizontal.

*   **`heading-page-title`**
    *   **Structure**: `h1.firstHeading`
    *   **Appearance**: No background, border, or shadow.
    *   **Typography**: `{typography.display-xl}` — "Linux Libertine", 28.8px, 400, `{colors.text-emphasized}` — #101418.
    *   **Padding**: `{spacing.none}` — 0px.

*   **`blockquote-quotebox`**
    *   **Structure**: `blockquote.quotebox-quote`
    *   **Appearance**: Transparent background, no explicit borders or shadows.
    *   **Typography**: Inherits from parent, often a slightly smaller body text like `{typography.body-md}` — sans-serif, 14.08px, 400.
    *   **Padding**: `{spacing.none}` — 0px.

*   **`card-menu`**
    *   **Structure**: `.vector-menu`, `.vector-menu-content`, `.mw-portlet`, `.vector-unpinned-container`
    *   **Appearance**: Transparent background, no explicit borders or shadows. Acts as a container for grouped content.
    *   **Typography**: Inherits from parent, typically `{typography.body-md}` — sans-serif, 14px, 400.
    *   **Padding**: `{spacing.none}` — 0px.

*   **`card-toc-item`**
    *   **Structure**: `.vector-toc-list-item`
    *   **Appearance**: Transparent background, no explicit borders or shadows.
    *   **Typography**: Inherits from parent, typically `{typography.body-md}` — sans-serif, 14px, 400.
    *   **Padding**: `{spacing.none}` — 0px top/bottom, `{spacing.md}` — 12px left.

## Do's and Don'ts

*   **Do** use `{colors.brand-accent}` — #3366cc for all primary interactive elements and links.
*   **Do** maintain a clear typographic hierarchy, utilizing `{typography.display-xl}` for main titles and `{typography.body-md}` for general content.
*   **Do** apply `{spacing.md}` — 12px for consistent internal padding within grouped content areas.
*   **Do** keep backgrounds clean with `{colors.canvas}` — #ffffff for the main page and `{colors.surface-subtle}` — #f8f9fa for subtle distinctions.
*   **Do** use `{rounded.sm}` — 2px sparingly for interactive elements to provide a hint of softness.
*   **Do** ensure all text, especially body content, uses the `sans-serif` font family for maximum readability.
*   **Don't** introduce strong, decorative shadows; stick to `{shadow.md}` for subtle elevation.
*   **Don't** use highly saturated or contrasting colors beyond the established brand accent.
*   **Don't** deviate from the established spacing scale; avoid arbitrary pixel values.
*   **Don't** use decorative fonts; maintain the functional sans-serif/serif pairing.
*   **Don't** add excessive borders or background colors to content cards; keep them transparent unless a specific semantic purpose is served.
*   **Don't** use pure black `{colors.text-black}` — #000000 for large blocks of text; reserve it for specific high-contrast elements if necessary.

## Responsive Behavior

| Breakpoint | Min Width | Touch Targets | Collapse Strategy