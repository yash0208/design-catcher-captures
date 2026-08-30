## Overview

This design system for 99designs presents a professional and clean aesthetic, emphasizing content and user experience. The visual identity is characterized by a strong, modern sans-serif typeface, a limited but effective color palette, and a clear hierarchy established through typography and spacing. The overall impression is one of reliability and focus, with interactive elements subtly highlighted.

**Key Characteristics:**
*   **Primary Typeface:** Graphik, used for both headings and body text, ensuring typographic consistency.
*   **Brand Accent:** A distinct blue (`{colors.brand-primary}` — #1f3ca6) for interactive elements and key information.
*   **Neutral Palette:** Dominated by shades of dark gray (`{colors.text-primary}` — #313030) and off-white (`{colors.canvas}` — #f3f2f0), providing a clean backdrop.
*   **Subtle Depth:** Minimal use of shadows (`{elevation.sm}` — rgba(0, 0, 0, 0.1) 0px 3px 9px 0px) to create a sense of hierarchy and focus.
*   **Structured Layout:** Content is presented within well-defined sections, often with generous horizontal padding, suggesting a grid-based system.
*   **Rounded Corners:** A mix of subtle (`{rounded.sm}` — 3px) to moderate (`{rounded.md}` — 5px, `{rounded.lg}` — 8px) rounded corners provides a friendly, approachable feel.
*   **Clear Information Hierarchy:** Achieved through varying font sizes and weights, making scanning and comprehension easy.

## Colors

### Brand & Accent
*   **Brand Primary** (`{colors.brand-primary}` — #1f3ca6): Used for primary interactive elements, links, and to draw attention to key actions or information. This is the main brand color.

### Surface
*   **Canvas** (`{colors.canvas}` — #f3f2f0): The primary background color for the overall page, providing a soft, off-white base.
*   **Surface Light** (`{colors.surface-light}` — #ffffff): Used for card backgrounds, modal backgrounds, and other elements that require a clean, bright surface.
*   **Surface Light Alt** (`{colors.surface-light-alt}` — #dad9d7): A slightly darker off-white, used for subtle background variations or borders.
*   **Surface Lightest** (`{colors.surface-lightest}` — #eae9e7): An even lighter off-white, likely for very subtle distinctions or borders.
*   **Surface Dark** (`{colors.surface-dark}` — #1c1b1a): A very dark, almost black background, used for specific sections or elements requiring high contrast.

### Hairlines & Borders
*   **Border Primary** (`{colors.border-primary}` — #313030): A dark gray used for strong borders or dividers.
*   **Border Secondary** (`{colors.border-secondary}` — #969694): A medium gray used for less prominent borders, such as around input fields or subtle separators.
*   **Border Tertiary** (`{colors.border-tertiary}` — #b6b5b3): A light gray, used for very subtle outlines or dividers, often on lighter backgrounds.
*   **Border Light** (`{colors.border-light}` — #dad9d7): A light gray border, often paired with light surfaces.
*   **Border Lightest** (`{colors.border-lightest}` — #eae9e7): The lightest border color, for minimal separation.

### Text
*   **Text Primary** (`{colors.text-primary}` — #313030): The dominant dark gray for most body text, headings, and primary labels.
*   **Text Secondary** (`{colors.text-secondary}` — #969694): A medium gray for secondary information, descriptions, or less emphasized text.
*   **Text Tertiary** (`{colors.text-tertiary}` — #b6b5b3): A light gray for tertiary information, footnotes, or disabled states.
*   **Text Muted Dark** (`{colors.text-muted-dark}` — #5b5a58): A slightly darker muted gray, used for specific secondary text elements.
*   **Text On Dark** (`{colors.text-on-dark}` — #ffffff): White text used against darker backgrounds for readability.

## Typography

### Font Family
The primary typeface used across the site is "Graphik", with a variant "Graphik Medium" for emphasis. The fallback stack is `sans-serif`.
*   **Primary:** "Graphik", sans-serif
*   **Emphasized:** "Graphik Medium", sans-serif

### Hierarchy

| Token                 | Font Family       | Size   | Weight | Line Height | Letter Spacing | Use                                          |
| :-------------------- | :---------------- | :----- | :----- | :---------- | :------------- | :------------------------------------------- |
| `{typography.body-lg}`  | Graphik, sans-serif | 19px   | 400    | 30.4px      | normal         | Large body text, section titles              |
| `{typography.body-md}`  | Graphik, sans-serif | 16px   | 400    | 25.6px      | normal         | Standard body text, paragraph text           |
| `{typography.body-sm}`  | Graphik, sans-serif | 14px   | 400    | 22.4px      | normal         | Small body text, captions, metadata          |
| `{typography.heading-xl}` | "Graphik Medium", sans-serif | 24px   | 400    | 30px        | -0.12px        | Primary page titles, main headings           |
| `{typography.heading-lg}` | "Graphik Medium", sans-serif | 24px   | 400    | 31.2px      | normal         | Secondary headings                           |
| `{typography.heading-md}` | "Graphik Medium", sans-serif | 19px   | 400    | 30.4px      | normal         | Section headings, prominent labels           |
| `{typography.heading-sm}` | "Graphik Medium", sans-serif | 16px   | 400    | 20.8px      | normal         | Subheadings, emphasized labels               |
| `{typography.label-md}` | Graphik, sans-serif | 16px   | 400    | 20.8px      | normal         | Labels, navigation items (compact)           |
| `{typography.label-lg}` | Graphik, sans-serif | 16px   | 400    | 28.8px      | normal         | Labels, navigation items (more spacious)     |
| `{typography.button}`   | "Graphik Medium", sans-serif | 16px   | 400    | 25.6px      | normal         | Button text, login links                     |

### Principles
The typographic system relies heavily on the Graphik typeface, using its regular weight for most content and a "Medium" variant for headings and emphasized text. This creates a consistent voice throughout the interface. Line heights are generally generous, promoting readability, especially for body text. Letter spacing is mostly `normal`, with a slight negative tracking (`-0.12px`) applied to the largest heading to improve visual balance. The hierarchy is established primarily through `fontSize` and the subtle distinction between "Graphik" and "Graphik Medium" rather than dramatic `fontWeight` changes.

## Layout

The layout system appears to be based on a flexible grid with a maximum content width, centered on the page.
*   **Base Spacing Unit:** While not strictly adhering to a single base unit, `8px` and `16px` are frequently observed, suggesting a foundational rhythm. Many values are granular, indicating fine-tuned adjustments.
*   **Container Width:** Content is typically constrained within a maximum width, approximately `1240px`, and horizontally centered, providing ample breathing room on larger screens.
*   **Section Padding:** Sections often feature significant horizontal padding, such as `{spacing.section-horizontal}` — 83px, and vertical padding ranging from `{spacing.section-sm}` — 44px to `{spacing.section-lg}` — 150px.
*   **Component Spacing:**
    *   `{spacing.xxs}` — 3px: Very small gaps, often within components.
    *   `{spacing.xs}` — 6px, 7px, 8px, 9px: Small spacing for inline elements or tight groups.
    *   `{spacing.sm}` — 10px, 12px, 13px, 15px, 16px: Standard spacing for elements within a component or small vertical separation.
    *   `{spacing.md}` — 20px, 23px, 25px: Medium spacing, often for vertical separation between related content blocks.
    *   `{spacing.lg}` — 30px: Larger spacing for clear separation of content areas.
    *   `{spacing.xl}` — 45px, 53px: Significant spacing for distinct content blocks or margins.
    *   `{spacing.xxl}` — 60px: Large spacing for major section breaks.
    *   `{spacing.hero-padding}` — 288px: A very large padding value, likely for specific hero sections or full-width elements.
*   **Whitespace Philosophy:** The design embraces generous whitespace, particularly around main content blocks and between sections, contributing to a clean, uncluttered, and professional appearance. This allows content to breathe and improves readability.

## Elevation & Depth

The design uses subtle shadows to indicate elevation and interactive states, rather than strong, multi-layered effects.
*   **Elevation Small** (`{elevation.sm}` — rgba(0, 0, 0, 0.1) 0px 3px 9px 0px): A soft, diffused shadow used to lift elements like cards or modals slightly off the background, providing a sense of depth without being overly prominent. This is applied to interactive elements or content containers to give them focus.

## Shapes

The design incorporates various levels of border-radius, contributing to a modern and approachable aesthetic.
*   **Rounded Small** (`{rounded.sm}` — 3px): A very subtle rounding, used for smaller interactive elements or input fields.
*   **Rounded Medium** (`{rounded.md}` — 5px): A moderate rounding, applied to cards or containers for a softer look.
*   **Rounded Large** (`{rounded.lg}` — 8px): A more pronounced rounding, used for larger components or distinct content blocks.
*   **Rounded Pill** (`{rounded.pill}` — 999px): Used for pill-shaped elements like tags or badges, creating a fully rounded edge.
*   **Rounded Full** (`{rounded.full}` — 50%): Applied to circular elements, such as avatars or icons.

## Components

*   **`button-default`**
    *   **Structure:** Text-based, often without explicit background or border, relying on `color` for distinction.
    *   **Typography:** `{typography.body-md}` — Graphik, sans-serif, 16px, 400, 25.6px, normal.
    *   **Colors:** `color: {colors.text-primary}` — #313030. `background-color: transparent`.
    *   **Padding:** `{spacing.none}` — 0px.
    *   **Radius:** `{rounded.none}` — 0px.
    *   **Usage:** Used for navigation triggers or secondary actions.

*   **`nav-pagination`**
    *   **Structure:** A container for pagination links, typically horizontal.
    *   **Typography:** `{typography.body-md}` — Graphik, sans-serif, 16px, 400, 25.6px, normal.
    *   **Colors:** `color: {colors.text-primary}` — #313030. `background-color: transparent`.
    *   **Padding:** `{spacing.none}` — 0px.
    *   **Radius:** `{rounded.none}` — 0px.
    *   **Usage:** For navigating through paginated content.

*   **`input-select`**
    *   **Structure:** A dropdown select element.
    *   **Typography:** `{typography.body-md}` — Graphik, sans-serif, 16px, 400, 25.6px, normal.
    *   **Colors:** `color: {colors.text-primary}` — #313030. `background-color: transparent`.
    *   **Padding:** `{spacing.xs}` — 6px (top/bottom), `{spacing.xl}` — 45px (right), `{spacing.sm}` — 12px (left).
    *   **Radius:** `{rounded.none}` — 0px.
    *   **Usage:** For filtering or selecting options.

*   **`footer`**
    *   **Structure:** A full-width container for site-wide navigation and information.
    *   **Typography:** `{typography.body-md}` — Graphik, sans-serif, 16px, 400, 25.6px, normal.
    *   **Colors:** `color: {colors.text-primary}` — #313030. `background-color: transparent`.
    *   **Padding:** `{spacing.none}` — 0px.
    *   **Radius:** `{rounded.none}` — 0px.
    *   **Usage:** Standard site footer.

*   **`heading-h1`**
    *   **Structure:** Main page heading.
    *   **Typography:** `{typography.heading-xl}` — "Graphik Medium", sans-serif, 24px, 400, 30px, -0.12px.
    *   **Colors:** `color: {colors.text-primary}` — #313030.
    *   **Padding:** `{spacing.none}` — 0px.
    *   **Radius:** `{rounded.none}` — 0px.
    *   **Usage:** Primary title for a page or main content area.

*   **`section-hero`**
    *   **Structure:** A generic section container, often used for content blocks.
    *   **Typography:** `{typography.body-md}` — Graphik, sans-serif, 16px, 400, 25.6px, normal.
    *   **Colors:** `color: {colors.text-primary}` — #313030. `background-color: transparent`.
    *   **Padding:** `{spacing.none}` — 0px.
    *   **Radius:** `{rounded.none}` — 0px.
    *   **Usage:** Flexible content section, can serve as a hero or general content area.

*   **`card-matrix-item`**
    *   **Structure:** A grid item, likely containing media and text.
    *   **Typography:** `{typography.body-md}` — Graphik, sans-serif, 16px, 400, 25.6px, normal.
    *   **Colors:** `color: {colors.text-primary}` — #313030. `background-color: transparent`.
    *   **Padding:** `{spacing.none}` — 0px (top/bottom), `{spacing.md}` — 22.5px (right).
    *   **Radius:** `{rounded.none}` — 0px.
    *   **Usage:** Displaying individual portfolio items or similar content in a grid.

*   **`card-mediabox`**
    *   **Structure:** A container for media content.
    *   **Typography:** `{typography.body-md}` — Graphik, sans-serif, 16px, 400, 25.6px, normal.
    *   **Colors:** `color: {colors.text-primary}` — #313030. `background-color: transparent`.
    *   **Padding:** `{spacing.none}` — 0px.
    *   **Radius:** `{rounded.none}` — 0px.
    *   **Usage:** General purpose media display.

*   **`card-footer-navigation`**
    *   **Structure:** A group of navigation links within the footer.
    *   **Typography:** `{typography.body-md}` — Graphik, sans-serif, 16px, 400, 25.6px, normal.
    *   **Colors:** `color: {colors.text-primary}` — #313030. `background-color: transparent`.
    *   **Padding:** `{spacing.none}` — 0px (top/bottom), `{spacing.sm}` — 15px (left/right).
    *   **Radius:** `{rounded.none}` — 0px.
    *   **Usage:** Organizing footer links into columns.

## Do's and Don'ts

*   **Do** use `{colors.brand-primary}` — #1f3ca6 exclusively for primary calls to action, active states, and key navigational elements to maintain its impact.
*   **Do** ensure all body text adheres to the `Graphik, sans-serif` font family, using `{typography.body-md}` — Graphik, sans-serif, 16px, 400, 25.6px, normal for standard paragraphs.
*   **Do** apply `{elevation.sm}` — rgba(0, 0, 0, 0.1) 0px 3px 9px 0px sparingly to interactive elements or distinct content cards to provide subtle visual hierarchy.
*   **Do** maintain generous horizontal padding, such as `{spacing.section-horizontal}` — 83px, for main content sections to ensure a clean, breathable layout.
*   **Do** use `{rounded.md}` — 5px for general card and container rounding, and `{rounded.full}` — 50% for circular elements like avatars.
*   **Do** use "Graphik Medium" for headings and emphasized text, specifically `{typography.heading-xl}` — "Graphik Medium", sans-serif, 24px, 400, 30px, -0.12px for main titles.

*   **Don't** introduce new typefaces or weights beyond "Graphik" and "Graphik Medium" to preserve typographic consistency.
*   **Don't** use `{colors.brand-primary}` — #1f3ca6 for large background areas or non-interactive text, as it dilutes its intended purpose.
*   **Don't** use overly strong or multiple shadows; stick to `{elevation.sm}` — rgba(0, 0, 0, 0.1) 0px 3px 9px 0px for subtle depth.
*   **Don't** reduce the whitespace around content blocks; the design relies on ample breathing room for clarity.
*   **Don't** use sharp, unrounded corners for interactive elements or cards; `{rounded.sm}` — 3px should be the minimum.
*   **Don't** use `fontWeight: 700` (bold) as it's not present in the current system; rely on "Graphik Medium" for emphasis.

## Responsive Behavior

| Breakpoint | Min Width | Touch Targets | Collapse Strategy