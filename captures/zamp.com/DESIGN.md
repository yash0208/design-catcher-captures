## Overview
The Zamp website presents a professional and modern aesthetic, characterized by a clean layout, a sophisticated color palette, and a clear typographic hierarchy. The visual identity balances corporate reliability with a touch of warmth and approachability. The design emphasizes readability and structured content, guiding the user through information with ample whitespace and distinct sectioning. A subtle use of brand colors, particularly a warm yellow and muted beige tones, adds character without overwhelming the primary black and white scheme.

**Key Characteristics**
*   **Color Palette**: Dominated by `{colors.canvas}` — #000000 and `{colors.surface-primary}` — #ffffff, accented by `{colors.brand-yellow}` — #ffec72 and `{colors.surface-secondary}` — #f6f5f3.
*   **Typography**: Features a strong contrast between the display serif typeface "Seasonmix" for headings and the highly readable sans-serif "Seasonsans" for body text.
*   **Layout**: Utilizes generous vertical spacing between sections and a consistent horizontal content constraint, creating a sense of order and clarity.
*   **Whitespace**: Abundant whitespace is used to separate content blocks, improving readability and reducing visual clutter.
*   **Minimalist Depth**: The design avoids shadows and complex layering, focusing on flat, clean surfaces.
*   **Structured Content**: Information is presented in clearly defined sections, often with distinct background colors to delineate different themes.
*   **Rounded Elements**: Minimal use of rounded corners, primarily for pill-shaped elements like buttons, otherwise sharp corners prevail.

## Colors

### Brand & Accent
*   **Brand Yellow** (`{colors.brand-yellow}` — #ffec72): Used for subtle accents, highlights, and potentially interactive elements.
*   **Brand Green Secondary** (`{colors.brand-green-dark}` — #1b595a): A deep, rich green used sparingly, possibly for specific brand elements or backgrounds.
*   **Brand Light Green** (`{colors.brand-light-green}` — #afecdb): A soft, pastel green, likely used for background elements or subtle highlights.
*   **Brand Light Orange** (`{colors.brand-light-orange}` — #ffc6a4): A light, warm orange, potentially for secondary accents.

### Surface
*   **Canvas** (`{colors.canvas}` — #000000): Primary background for dark sections, such as the footer or specific content blocks.
*   **Surface Primary** (`{colors.surface-primary}` — #ffffff): Dominant background color for most content areas and the main page canvas.
*   **Surface Secondary** (`{colors.surface-secondary}` — #f6f5f3): A light, warm beige used for background sections, providing a subtle contrast to white. Also referred to as `{colors.brand-beige}`.
*   **Surface Light Beige** (`{colors.surface-light-beige}` — #fafaf9): A very light, almost off-white beige, used for backgrounds like the FAQ section. Also referred to as `{colors.brand-light-beige}`.

### Hairlines & Borders
*   **Border Primary** (`{colors.border-primary}` — #e6e1da): A light, muted beige used for borders, such as around input fields, providing subtle definition. Also referred to as `{colors.border-secondary}`.
*   **Hairline Dark** (`{colors.hairline-dark}` — #000000): Used for borders on dark backgrounds or to define elements against white.

### Text
*   **Text Primary** (`{colors.text-primary}` — #000000): Default text color for most content on light backgrounds. Also referred to as `{colors.text}`.
*   **Text Dark** (`{colors.text-dark}` — #0c0a08): A very dark grey, almost black, used for primary text, offering a slightly softer contrast than pure black.
*   **Text Muted** (`{colors.text-muted}` — #838383): A medium grey used for secondary information, captions, or less prominent text. Also referred to as `{colors.text-secondary}`.
*   **Text On Dark** (`{colors.text-on-dark}` — #ffffff): Text color used on dark backgrounds, such as the footer. Also referred to as `{colors.text-light}`.
*   **Text Light Secondary** (`{colors.text-light-secondary}` — #ecebeb): A very light grey, likely for secondary text on dark backgrounds. Also referred to as `{colors.neutral-lightest}`.

## Typography

### Font Family
The primary typefaces are "Seasonsans" and "Seasonmix", both with `Arial, sans-serif` as fallbacks.
*   **Seasonsans**: A clean, modern sans-serif typeface used for body text, paragraphs, and most UI elements, emphasizing readability.
*   **Seasonmix**: A distinctive display typeface, likely a serif or a more stylized sans-serif, used for prominent headings and titles to convey brand personality.

### Hierarchy
| Token                 | Font Family | Size     | Weight | Line Height | Letter Spacing | Use                                       |
| :-------------------- | :---------- | :------- | :----- | :---------- | :------------- | :---------------------------------------- |
| `{typography.display-xl}` | Seasonmix   | 43.89px  | 400    | 52.66px     | -0.44px        | Primary page titles, hero headlines      |
| `{typography.display-lg}` | Seasonmix   | 35.89px  | 400    | 43.06px     | -0.36px        | Section titles, prominent headings        |
| `{typography.heading-h2}` | Seasonmix   | 28px     | 400    | 33.6px      | -0.28px        | Sub-section headings                      |
| `{typography.heading-h3}` | Seasonmix   | 25.94px  | 400    | 33.73px     | normal         | Feature card titles, secondary headings   |
| `{typography.body-lg-bold}` | Seasonsans  | 18px     | 500    | 27px        | -0.18px        | Emphasized body text, FAQ questions       |
| `{typography.body-lg}`    | Seasonsans  | 18px     | 400    | 27px        | normal         | Large body text, introductory paragraphs  |
| `{typography.body-md-bold}` | Seasonsans  | 16px     | 500    | 24px        | normal         | Emphasized body text, callouts            |
| `{typography.body-md}`    | Seasonsans  | 16px     | 400    | 24px        | normal         | Standard body text, paragraphs (most common) |
| `{typography.body-sm-bold}` | Seasonsans  | 14px     | 500    | 21px        | normal         | Small emphasized text, navigation items   |
| `{typography.body-sm}`    | Seasonsans  | 14px     | 400    | 21px        | normal         | Small body text, navigation links         |
| `{typography.caption-bold}` | Seasonsans  | 12px     | 500    | 18px        | normal         | Smallest emphasized text, labels          |
| `{typography.caption}`    | Seasonsans  | 12px     | 400    | 18px        | normal         | Captions, footnotes, legal text           |
| `{typography.link}`       | Seasonsans  | 16px     | 400    | 24px        | 0.32px         | Links, calls to action                    |
| `{typography.phone-number}` | Seasonsans  | 12px     | 400    | 12px        | 0.24px         | Phone numbers                             |

### Principles
The typographic system creates a clear hierarchy by pairing a distinctive display font, "Seasonmix", for all headings with a highly legible sans-serif, "Seasonsans", for body copy and UI elements. Weight contrast within "Seasonsans" (400 and 500) is used to subtly emphasize text without resorting to different font families. Letter spacing is generally normal for body text but slightly condensed for larger headings, contributing to a refined and modern feel. Line heights are generous, enhancing readability across all text sizes.

## Layout
The layout is characterized by a strong vertical rhythm and a consistent content width.
*   **Spacing Scale (4px base)**:
    *   `{spacing.xxs}` — 4px
    *   `{spacing.xs}` — 8px
    *   `{spacing.sm}` — 12px
    *   `{spacing.md}` — 16px
    *   `{spacing.lg}` — 24px
    *   `{spacing.xl}` — 32px
    *   `{spacing.xxl}` — 48px
    *   `{spacing.section-padding-sm}` — 60px
    *   `{spacing.section-padding-md}` — 64px
    *   `{spacing.section-padding-lg}` — 80px
    *   `{spacing.section-margin-lg}` — 76px
    *   `{spacing.section-margin-xl}` — 144px
    *   `{spacing.section-margin-xxl}` — 173px
*   **Container Behavior**: Content is typically constrained within a maximum width container, centered on the page. Horizontal padding of `{spacing.section-padding-sm}` — 60px is applied to global content wrappers, ensuring content does not touch the viewport edges on larger screens.
*   **Whitespace Philosophy**: The design employs a generous amount of whitespace, particularly vertical spacing, to visually separate sections and content blocks. This creates a clean, uncluttered appearance and improves content scannability. Sections often have vertical padding of `{spacing.section-padding-lg}` — 80px or `{spacing.section-padding-md}` — 64px.

## Elevation & Depth
The design explicitly avoids the use of shadows. All `boxShadow` properties observed are `none`, indicating a flat, modern aesthetic. There is no visual elevation or depth applied to elements.

## Shapes
The design primarily uses sharp, 0px corners for most elements.
*   **Rounded Full** (`{rounded.full}` — 999px): Used for pill-shaped elements, such as specific buttons or tags, providing a distinct, soft contrast to the otherwise angular design.
*   **Rounded None** (`{rounded.none}` — 0px): Default for most UI elements, including cards, inputs, and standard buttons.

## Components

*   **`button-dropdown-toggle`**
    *   **Structure**: A button-like element for dropdowns.
    *   **Background**: `{colors.surface-primary}` — #ffffff
    *   **Text Color**: `{colors.text-primary}` — #000000
    *   **Typography**: `{typography.body-sm}` — Seasonmix, 14px, 400, 21px
    *   **Padding**: `8px 12px 8px 16px`
    *   **Border Radius**: `{rounded.none}` — 0px
    *   **Border**: `none`
    *   **Shadow**: `none`

*   **`input-form`**
    *   **Structure**: Standard text input field.
    *   **Background**: `{colors.surface-light-beige}` — #fafaf9
    *   **Text Color**: `{colors.text-primary}` — #000000
    *   **Typography**: `{typography.body-md}` — Seasonsans, 16px, 400, 24px
    *   **Padding**: `8px 18px`
    *   **Border Radius**: `{rounded.none}` — 0px
    *   **Border**: `1px solid {colors.border-primary}` — #e6e1da
    *   **Shadow**: `none`

*   **`footer`**
    *   **Structure**: Page footer section.
    *   **Background**: `{colors.canvas}` — #000000
    *   **Text Color**: `{colors.text-on-dark}` — #ffffff
    *   **Typography**: `{typography.body-md}` — Seasonsans, 16px, 400, 24px
    *   **Padding**: `0px` (internal content uses its own padding)
    *   **Border Radius**: `{rounded.none}` — 0px
    *   **Border**: `none`
    *   **Shadow**: `none`

*   **`faq-question-title`**
    *   **Structure**: Heading for an FAQ question.
    *   **Text Color**: `{colors.text-primary}` — #000000
    *   **Typography**: `{typography.body-lg-bold}` — Seasonsans, 18px, 500, 27px, -0.18px

## Do's and Don'ts

### Do's
*   **Do** use `{typography.body-md}` — Seasonsans, 16px, 400, 24px for all standard body text to maintain readability.
*   **Do** apply `{typography.display-lg}` — Seasonmix, 35.89px, 400, 43.06px for main section headings to ensure visual impact.
*   **Do** maintain generous vertical spacing between sections, using `{spacing.section-padding-lg}` — 80px or `{spacing.section-padding-md}` — 64px as a guide.
*   **Do** use `{colors.canvas}` — #000000 for backgrounds of dark sections and `{colors.surface-primary}` — #ffffff for light sections.
*   **Do** use `{colors.brand-yellow}` — #ffec72 sparingly for key accents or calls to action.
*   **Do** ensure all input fields use a `1px solid {colors.border-primary}` — #e6e1da border.
*   **Do** use `{rounded.full}` — 999px for pill-shaped elements like primary buttons, and `{rounded.none}` — 0px for all other rectangular elements.
*   **Do** use `{colors.text-muted}` — #838383 for secondary or less prominent text.

### Don'ts
*   **Don't** introduce new font families beyond "Seasonsans" and "Seasonmix".
*   **Don't** use shadows or any form of elevation on UI elements, as the design is flat.
*   **Don't** use overly tight line spacing; ensure generous line heights like 1.5x font size for body text.
*   **Don't** deviate from the established color palette; avoid introducing new bright or primary colors.
*   **Don't** use rounded corners on cards, input fields, or other block-level elements unless explicitly defined as `{rounded.full}`.
*   **Don't** use pure white text on `{colors.surface-secondary}` — #f6f5f3 backgrounds; stick to `{colors.text-primary}` — #000000.

## Responsive Behavior

| Breakpoint | Min Width | Touch Targets | Collapse Strategy