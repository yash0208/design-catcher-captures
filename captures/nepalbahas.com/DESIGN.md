## Overview

Nepal Bahas presents a news publication design characterized by a clean, structured layout with a strong emphasis on readability and clear content hierarchy. The visual identity is anchored by a vibrant red, signaling urgency and importance, often contrasted with a neutral palette of grays and whites. Typography plays a crucial role, utilizing a distinct display font for headlines to create visual impact, paired with a highly legible sans-serif for body text. The overall aesthetic is professional and content-focused, with subtle use of elevation and rounded corners to delineate content blocks.

**Key Characteristics:**
*   **Brand Red Accent**: A prominent red (`{colors.brand-red-primary}` — #e2231a, `{colors.brand-red-accent}` — #c8322d) is used for borders, hover states, and key highlights.
*   **Clean Surfaces**: Extensive use of white (`{colors.surface-canvas}` — #ffffff) and light grays (`{colors.surface-extra-light}` — lab(98.2596 -0.247031 -0.706708)) for backgrounds.
*   **Strong Typography Hierarchy**: A clear distinction between large, impactful display headlines (Teko) and highly readable body text (Mukta).
*   **Modular Content Blocks**: News articles and sections are presented in distinct, often card-like, modules.
*   **Subtle Depth**: Minimal use of shadows to provide a slight lift to interactive elements and sticky navigation.
*   **Responsive Adaptation**: Layouts adjust from multi-column grids on larger screens to stacked, single-column presentations on mobile.
*   **Informational Tone**: The design prioritizes content delivery, avoiding excessive ornamentation.

## Colors

### Brand & Accent
*   **Brand Red Primary** (`{colors.brand-red-primary}` — #e2231a): Used prominently for text, borders, and as an accent color. Signals importance and brand identity.
*   **Brand Red Accent** (`{colors.brand-red-accent}` — #c8322d): A slightly darker red, notably used for the main navigation border and hover states, providing visual feedback.
*   **Brand Blue Primary** (`{colors.brand-blue-primary}` — #1b4f9c): Appears as a background or text color in specific sections, offering a secondary brand accent.
*   **Brand Blue Google** (`{colors.brand-blue-google}` — #4285f4): Used for specific link colors, likely for external service integration or social media.
*   **Accent Orange-Red** (`{colors.accent-orange-red}` — lab(48.4493 77.4328 61.5452)): An additional accent color for specific elements.
*   **Accent Orange** (`{colors.accent-orange}` — lab(55.4814 75.0732 48.8528)): Another accent, similar to the orange-red.

### Surface
*   **Surface Canvas** (`{colors.surface-canvas}` — #ffffff): The primary background color for the main content areas and overall page.
*   **Surface Extra Light** (`{colors.surface-extra-light}` — lab(98.2596 -0.247031 -0.706708)): A very subtle off-white, used for backgrounds.
*   **Surface Light Gray** (`{colors.surface-light-gray}` — lab(91.6229 -0.159115 -2.26791)): A light gray used for backgrounds and borders.
*   **Surface Card Background** (`{colors.surface-card-background}` — lab(96.1596 -0.0823438 -1.13575)): A very light gray, used for card backgrounds.
*   **Surface Hero Background** (`{colors.surface-hero-background}` — #fdf1f2): A light, subtle pinkish background for the hero section, adding a touch of warmth.
*   **Surface Footer Background** (`{colors.surface-footer-background}` — #f0f0f0): A light gray background for the footer area.
*   **Surface Dark Red** (`{colors.surface-dark-red}` — #7f0001): A deep, rich red used as a background for specific content sections, creating strong contrast.
*   **Surface Dark Blue** (`{colors.surface-dark-blue}` — #14222E): A very dark blue used as a background for certain content sections, providing a distinct visual break.

### Hairlines & Borders
*   **Border Light** (`{colors.border-light}` — lab(65.9269 -0.832707 -8.17473)): A medium gray used for subtle borders and dividers.
*   **Border Hairline** (`{colors.border-hairline}` — #f9f3f3): A very light gray, almost imperceptible, for fine separation.

### Text
*   **Text Primary** (`{colors.text-primary}` — #000000): The dominant color for most body text and headings, ensuring high contrast and readability.
*   **Text On Light Dark** (`{colors.text-on-light-dark}` — lab(8.11897 0.811279 -12.254)): A very dark gray, almost black, used for text on light backgrounds.
*   **Text Dark Secondary** (`{colors.text-dark-secondary}` — #1a1a1a): A slightly lighter dark gray for secondary text elements.
*   **Text Secondary** (`{colors.text-secondary}` — lab(27.1134 -0.956401 -12.3224)): A dark gray, used for less prominent text or interactive elements.
*   **Text Muted** (`{colors.text-muted}` — lab(47.7841 -0.393182 -10.0268)): A medium gray for less emphasized text, such as timestamps or meta-information.
*   **Text Dark Tertiary** (`{colors.text-dark-tertiary}` — lab(16.1051 -1.18239 -11.7533)): A dark, almost black, gray for specific text.

### Semantic
*   **Overlay Light** (`{colors.overlay-light}` — oklab(0.999994 0.0000455678 0.0000200868 / 0.2)): A semi-transparent white, likely used for overlays or subtle background effects.
*   **Overlay Dark** (`{colors.overlay-dark}` — oklab(0 0 0 / 0.5)): A semi-transparent black, likely for image overlays or modals.

## Typography

### Font Family
The primary typeface for content is "Mukta", a versatile sans-serif font, providing excellent readability for both headlines and body text, especially in Nepali script. For UI elements and general sans-serif fallback, the system utilizes `ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji"`. A distinct display typeface, "Teko", is employed for impactful section titles and large headlines, adding a unique and bold character to the design.

### Hierarchy
| Token                 | Font Family                                                                                             | Size     | Weight  | Line Height | Letter Spacing | Use                                       |
| :-------------------- | :------------------------------------------------------------------------------------------------------ | :------- | :------ | :---------- | :------------- | :---------------------------------------- |
| `{typography.display-xl}` | Mukta, sans-serif                                                                                       | 72px     | 600     | 100.8px     | 1px            | Main article headlines                    |
| `{typography.display-lg}` | Teko, sans-serif                                                                                        | 50px     | 600     | 60px        | normal         | Section titles, large callouts            |
| `{typography.heading-xl}` | Mukta, sans-serif                                                                                       | 22px     | 590     | 33px        | normal         | Card titles, prominent news items         |
| `{typography.heading-lg}` | Mukta, sans-serif                                                                                       | 19px     | 600     | 28.5px      | normal         | Navigation links, secondary headlines     |
| `{typography.heading-md}` | ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji" | 19px     | 700     | 28.5px      | normal         | Navigation links, emphasized UI text      |
| `{typography.heading-sm}` | Mukta, sans-serif                                                                                       | 17px     | 700     | 25.5px      | normal         | Category titles, emphasized text          |
| `{typography.body-lg}` | Mukta, sans-serif                                                                                       | 17px     | 400     | 25.5px      | normal         | Larger body text, article excerpts        |
| `{typography.body-base}` | Mukta, sans-serif                                                                                       | 16px     | 400     | 24px        | normal         | Default body text, general content        |
| `{typography.body-ui}` | ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji" | 16px     | 400     | 24px        | normal         | UI elements, buttons, metadata            |
| `{typography.body-sm}` | Mukta, sans-serif                                                                                       | 15px     | 600     | 22.5px      | normal         | Dates, secondary information              |
| `{typography.body-xs}` | Mukta, sans-serif                                                                                       | 13px     | 800     | 13px        | normal         | Labels, badges, uppercase text            |
| `{typography.caption}` | Mukta, sans-serif                                                                                       | 11px     | 700     | 16.5px      | normal         | Pagination, small labels                  |
| `{typography.legal}` | Mukta, sans-serif                                                                                       | 8px      | 900     | 12px        | normal         | Copyright, very small text                |

### Principles
The typography system establishes a clear visual hierarchy through varied font sizes and weights. "Mukta" serves as the workhorse for most content, offering excellent readability. "Teko" is reserved for high-impact headlines, providing a distinctive and bold aesthetic. Weights are used effectively to differentiate importance, with `600` and `700` (bold) common for headings and `400` (regular) for body text. Letter spacing is generally `normal`, except for the largest display text which uses a slight positive `1px` tracking for emphasis. Casing is typically sentence case, maintaining a natural reading flow.

## Layout

The layout is built on a flexible grid system, primarily using `display: block` for sections and `flex` or `grid` for internal content distribution. A common container width is implied by the consistent horizontal padding, suggesting a `max-width` for content areas.

**Spacing Scale (4px base):**
*   `{spacing.xxs}` — 2px
*   `{spacing.xs}` — 4px
*   `{spacing.sm}` — 6px
*   `{spacing.md}` — 8px
*   `{spacing.lg}` — 10px
*   `{spacing.xl}` — 12px
*   `{spacing.2xl}` — 16px
*   `{spacing.3xl}` — 20px
*   `{spacing.4xl}` — 24px
*   `{spacing.5xl}` — 32px
*   `{spacing.6xl}` — 40px
*   `{spacing.7xl}` — 48px

**Grid & Container Behavior:**
*   Content is typically centered within a main container, with generous horizontal padding on larger screens.
*   Many sections utilize `grid` layouts for news article cards, often with `gap` values like `{spacing.xl}` — 12px or `{spacing.2xl}` — 16px.
*   `flex` containers are used for individual component arrangements, such as aligning text and icons.
*   The site appears to use a responsive fluid grid that adapts to different screen sizes, collapsing columns as needed.

**Whitespace Philosophy:**
Whitespace is used generously to create clear separation between content blocks and improve readability. Vertical spacing between sections is substantial, often `py-6` (`{spacing.4xl}` — 24px) or `py-8` (`{spacing.5xl}` — 32px), with `mb-8` (`{spacing.5xl}` — 32px) or `mb-10` (`{spacing.lg}` — 10px, or a larger custom value not in the scale) commonly used for margins. This open approach prevents content from feeling cramped and guides the user's eye through the page.

## Elevation & Depth

Elevation is used subtly to highlight interactive elements and provide a sense of hierarchy, particularly for sticky navigation.

*   **Shadow Small** (`{shadow.sm}` — rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px): A light, subtle shadow used for cards or interactive elements to give a slight lift.
*   **Shadow Medium** (`{shadow.md}` — rgba(0, 0, 0, 0.2) 0px 4px 12px -3px): A more pronounced shadow, likely for modals or dropdowns, indicating a higher z-index.
*   **Shadow Large** (`{shadow.lg}` — rgba(0, 0, 0, 0.25) 0px 6px 20px -5px): Used for the sticky navigation bar, ensuring it stands out from the content scrolling beneath it.
*   **Shadow Extra Large** (`{shadow.xl}` — rgba(0, 0, 0, 0.25) 0px 25px 50px -12px): A very deep shadow, likely for prominent overlays or hero elements.

## Shapes

The design incorporates subtle rounded corners, primarily for cards and interactive elements, contributing to a softer, more approachable aesthetic.

*   **Rounded None** (`{rounded.none}` — 0px): Used for sharp edges, typically for full-width sections or elements that align perfectly with the grid.
*   **Rounded Small** (`{rounded.sm}` — 4px): A slight curve, common for input fields or small interactive components.
*   **Rounded Medium** (`{rounded.md}` — 6px): A more noticeable rounding, frequently applied to cards or containers.
*   **Rounded Large** (`{rounded.lg}` — 8px): The most prominent rounding, used for distinct content blocks or larger interactive elements.

## Components

### `nav-main`
The main navigation bar is sticky at the top.
*   **Structure**: Full-width container with internal content (logo, navigation links, utility buttons) aligned and spaced using flexbox.
*   **Background**: `{colors.surface-canvas}` — #ffffff.
*   **Border**: `border-bottom: 3px solid {colors.brand-red-accent}` — #c8322d.
*   **Shadow**: `{shadow.lg}` — rgba(0, 0, 0, 0.25) 0px 6px 20px -5px.
*   **Padding**: Vertical padding is implicit from content height, horizontal padding is likely `{spacing.4xl}` — 24px or similar for internal content.
*   **Typography**: Navigation links use `{typography.heading-lg}` — Mukta, sans-serif (19px, 600) or `{typography.heading-md}` — ui-sans-serif, system-ui, sans-serif (19px, 700).
*   **Text Color**: `{colors.text-primary}` — #000000, with hover state changing to `{colors.brand-red-accent}` — #c8322d.

### `button-icon`
Small, often hidden on mobile, icon-only buttons.
*   **Structure**: A simple button element, typically containing an icon.
*   **Background**: Transparent.
*   **Text Color**: `{colors.text-secondary}` — lab(27.1134 -0.956401 -12.3224), with hover state changing to `{colors.brand-red-primary}` — #e2231a.
*   **Padding**: `{spacing.md}` — 8px.
*   **Border Radius**: `{rounded.lg}` — 8px.
*   **Typography**: Uses `{typography.body-ui}` — ui-sans-serif, system-ui, sans-serif (16px, 400) for any associated text.

### `footer-main`
The main footer section of the website.
*   **Structure**: Full-width container with multiple columns of links, contact info, and copyright.
*   **Background**: `{colors.surface-footer-background}` — #f0f0f0.
*   **Padding**: `padding-top: {spacing.5xl}` — 32px, `padding-bottom: {spacing.2xl}` — 16px.
*   **Typography**: Primarily `{typography.body-base}` — Mukta, sans-serif (16px, 400).

### `card-news-item`
Generic card component for displaying news articles.
*   **Structure**: Typically a container with an image, title, and metadata. Often uses `overflow-hidden`.
*   **Background**: Can be transparent or `{colors.surface-card-background}` — lab(96.1596 -0.0823438 -1.13575).
*   **Border Radius**: `{rounded.md}` — 6px.
*   **Typography**:
    *   Titles: `{typography.heading-xl}` — Mukta, sans-serif (22px, 590) or `{typography.heading-lg}` — Mukta, sans-serif (19px, 600).
    *   Metadata: `{typography.body-sm}` — Mukta, sans-serif (15px, 600) or `{typography.body-xs}` — Mukta, sans-serif (13px, 800).
*   **Text Color**: Titles are `{colors.text-primary}` — #000000, changing to `{colors.brand-red-accent}` — #c8322d on hover. Metadata often uses `{colors.text-muted}` — lab(47.7841 -0.393182 -10.0268).

### `section-hero`
A prominent section at the top of the page, often featuring a main story.
*   **Structure**: Full-width container, often with a background image or color, containing a headline and possibly other elements.
*   **Background**: `{colors.surface-hero-background}` — #fdf1f2.
*   **Padding**: `padding-top: {spacing.4xl}` — 24px, `padding-bottom: {spacing.4xl}` — 24px.
*   **Border**: `border-bottom: 1px solid {colors.border-light}` — lab(65.9269 -0.832707 -8.17473).
*   **Typography**: Main headlines use `{typography.heading-xl}` — Mukta, sans-serif (22px, 590).

## Do's and Don'ts

**Do's:**
*   **Do** use `{colors.brand-red-primary}` — #e2231a or `{colors.brand-red-accent}` — #c8322d for primary calls to action, important highlights, and interactive states to maintain brand consistency.
*   **Do** ensure all body text uses `Mukta, sans-serif` with `{typography.body-base}` — 16px, 400 for optimal readability in Nepali script.
*   **Do** apply `{shadow.lg}` — rgba(0, 0, 0, 0.25) 0px 6px 20px -5px to sticky navigation elements to ensure they visually float above content.
*   **Do** maintain generous vertical spacing between major content sections, using at least `{spacing.4xl}` — 24px padding or margin.
*   **Do** use `{rounded.md}` — 6px for card-like content blocks to give them a modern, softer appearance.
*   **Do** reserve `Teko, sans-serif` for prominent section titles and display headlines to maximize visual impact.
*   **Do** use `{colors.text-muted}` — lab(47.7841 -0.393182 -10.0268) for secondary information like dates or author names to create a subtle hierarchy.

**Don'ts:**
*   **Don't** introduce new primary colors outside of the defined brand palette of reds and blues.
*   **Don't** use `Teko, sans-serif` for body text or small labels; its bold, condensed nature is not suitable for extended reading.
*   **Don't** use `{colors.text-primary}` — #000000 on dark backgrounds; ensure sufficient contrast with lighter text colors.
*   **Don't** apply strong shadows (`{shadow.md}` or `{shadow.xl}`) to every element; reserve them for interactive or elevated components.
*   **Don't** use inconsistent spacing values; always refer to the `{spacing}` scale for padding, margins, and gaps.
*   **Don't** use `