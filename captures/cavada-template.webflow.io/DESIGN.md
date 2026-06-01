## Overview

The Cavada website presents a warm, inviting, and modern aesthetic, perfectly suited for a coffee and bakery business. The visual identity balances a clean, contemporary feel with touches of classic elegance. This is achieved through a thoughtful combination of earthy background tones, strong, legible typography, and vibrant accent colors. The design emphasizes content clarity and a pleasant user experience, utilizing generous whitespace and softly rounded elements.

The site leverages a dual-font strategy, employing a modern sans-serif for body text and UI elements, and a robust sans-serif for impactful headlines. Interactive elements are clearly defined with distinct accent colors, while content is often presented within well-spaced cards and dynamic carousels. The overall impression is one of quality and approachability.

**Key Characteristics:**
*   Warm, off-white primary background (`{colors.canvas}` — #f3ebe8).
*   Clear typographic hierarchy with "IBM Plex Sans" for headings and "Inter" for body text.
*   Vibrant accent colors (`{colors.accent-primary}` — #ff7377, `{colors.accent-secondary}` — #6025cd).
*   Generous and consistent spacing, often centered for readability.
*   Softly rounded corners on interactive components and content blocks.
*   Prominent use of carousels for showcasing products and testimonials.
*   Minimalist input fields with subtle borders.

## Colors

**Brand & Accent**
*   **Accent Primary** (`{colors.accent-primary}` — #ff7377): Used for primary call-to-action elements, highlights, and other key interactive components.
*   **Accent Secondary** (`{colors.accent-secondary}` — #6025cd): A secondary accent color, likely for interactive states or specific brand elements.

**Surface**
*   **Canvas** (`{colors.canvas}` — #f3ebe8): The dominant background color for the overall page, providing a warm, light base.
*   **Canvas Light** (`{colors.canvas-light}` — #f2f4f6): A slightly lighter background or surface color, used for subtle differentiation.
*   **Surface Card** (`{colors.surface-card}` — #ffffff): Pure white used for card backgrounds, input fields, and other content surfaces.
*   **Surface Light Alt** (`{colors.surface-light-alt}` — #f8f9fc): A very light, almost white background, derived from `--lt-color-gray-100` and `--lt-color-background-light`.
*   **Surface Default** (`{colors.surface-default}` — #f1f3f9): A light background color, derived from `--lt-color-background-default`.

**Hairlines & Borders**
*   **Border Default** (`{colors.border-default}` — #e4e7eb): A light gray used for subtle borders, such as around input fields.
*   **Border Light** (`{colors.border-light}` — #f1f3f9): A very light border color, derived from `--lt-color-border-light`.
*   **Border Dark** (`{colors.border-dark}` — #c2c9d6): A darker gray border color, derived from `--lt-color-border-dark`.

**Text**
*   **Text Primary** (`{colors.text-primary}` — #374151): The most common text color for body copy and general content, providing good contrast against light backgrounds.
*   **Text Heading** (`{colors.text-heading}` — #1f2937): A darker, more impactful text color used primarily for headings and prominent titles.
*   **Text Secondary** (`{colors.text-secondary}` — #4b5563): A slightly lighter text color for secondary information or less prominent content.
*   **Text Muted** (`{colors.text-muted}` — #9ba3af): A light gray for less emphasized text, such as captions or supplementary details.
*   **Text Subtle** (`{colors.text-subtle}` — #6a7280): A slightly darker muted text color.
*   **Text Body** (`{colors.text-body}` — #333333): A general dark gray used for input text and some body content.
*   **Text Dark** (`{colors.text-dark}` — #111827): A very dark, almost black text color used for high contrast.
*   **Text Light** (`{colors.text-light}` — #5e636e): A medium gray text color, derived from `--lt-color-text-light`.
*   **Text Black** (`{colors.text-black}` — #111213): The darkest text color, derived from `--lt-color-black` and `--lt-color-gray-900`.

## Typography

### Font Family
The primary typefaces used are "Inter" for body text and UI elements, and "IBM Plex Sans" for headings and display text. A serif typeface, "Georgia", is also used for specific content like quotes or certain form elements, adding a touch of classic sophistication.

*   **Body & UI**: "Inter", sans-serif
*   **Headings & Display**: "IBM Plex Sans", sans-serif
*   **Accent/Serif**: "Georgia", Times, "Times New Roman", serif

### Hierarchy

| Token                      | Font Family           | Size    | Weight | Line Height | Letter Spacing | Use                                       |
| :------------------------- | :-------------------- | :------ | :----- | :---------- | :------------- | :---------------------------------------- |
| `{typography.body-default}` | Inter, sans-serif     | 16px    | 400    | 24px        | normal         | Standard body text, paragraphs            |
| `{typography.body-default-tight}` | Inter, sans-serif     | 16px    | 400    | 24px        | -0.24px        | Body text with tighter letter spacing     |
| `{typography.body-lg}`     | Inter, sans-serif     | 18px    | 400    | 31.5px      | -0.24px        | Larger body text, descriptive paragraphs  |
| `{typography.body-medium}` | Inter, sans-serif     | 16px    | 500    | 24px        | -0.24px        | Navigation items, button labels           |
| `{typography.heading-xs}`  | "IBM Plex Sans", sans-serif | 16px    | 700    | 19.2px      | -0.24px        | Small, bold headings                      |
| `{typography.body-serif}`  | Georgia, serif        | 16px    | 400    | 24px        | normal         | Serif body text, quotes                   |
| `{typography.heading-md}`  | "IBM Plex Sans", sans-serif | 32px    | 700    | 35.2px      | -0.4px         | Medium-sized section headings             |
| `{typography.display-lg}`  | "IBM Plex Sans", sans-serif | 56px    | 700    | 61.6px      | -0.4px         | Large display numbers or short statements |
| `{typography.display-serif-alt}` | Inter, sans-serif     | 40px    | 400    | 60px        | normal         | Large decorative text (e.g., empty state) |
| `{typography.heading-md-tight}` | "IBM Plex Sans", sans-serif | 32px    | 700    | 32px        | -0.4px         | Medium headings with tighter line height  |
| `{typography.body-serif-lg}` | Georgia, serif        | 18px    | 400    | 31.5px      | -0.24px        | Larger serif body text                    |
| `{typography.body-serif-medium}` | Georgia, serif        | 16px    | 500    | 24px        | -0.24px        | Serif text for form labels                |
| `{typography.body-serif-sm}` | Georgia, serif        | 14px    | 400    | 21px        | normal         | Small serif text, captions                |
| `{typography.display-serif}` | Georgia, serif        | 40px    | 400    | 60px        | normal         | Large serif display text                  |
| `{typography.body-xl}`     | Inter, sans-serif     | 24px    | 400    | 36px        | normal         | Extra-large body text                     |
| `{typography.display-md}`  | "IBM Plex Sans", sans-serif | 48px    | 700    | 52.8px      | normal         | Medium display headings                   |
| `{typography.display-md-light}` | "IBM Plex Sans", sans-serif | 48px    | 400    | 52.8px      | normal         | Medium display headings, lighter weight   |
| `{typography.heading-md-loose}` | "IBM Plex Sans", sans-serif | 32px    | 700    | 38.4px      | -0.4px         | Medium headings with looser line height   |
| `{typography.body-form-select}` | Inter, sans-serif     | 16px    | 400    | normal      | -0.24px        | Text within form select elements          |
| `{typography.body-form-label}` | Inter, sans-serif     | 14px    | 400    | normal      | normal         | Form field labels                         |
| `{typography.body-medium-normal}` | Inter, sans-serif     | 16px    | 500    | 24px        | normal         | Medium weight body text, normal spacing   |

### Principles
The typographic system employs a clear distinction between headings and body text, with "IBM Plex Sans" providing a strong, modern voice for titles, often in bold weights and with slight negative letter spacing for impact. "Inter" serves as the workhorse for readability in body copy and UI elements, maintaining a comfortable line height and standard letter spacing. The occasional use of "Georgia" adds a classic, editorial touch, particularly for quotes or specific content blocks. Hierarchy is established through significant size and weight variations, ensuring content is easily scannable and digestible.

## Layout

The layout system is built on a 4px base unit, with a preference for larger increments to create generous whitespace and clear content separation. Content is typically centered within a main container, and sections are often padded vertically to provide breathing room.

*   **Spacing Scale (4px base):**
    *   `{spacing.xs}` — 8px
    *   `{spacing.sm}` — 12px
    *   `{spacing.md}` — 16px
    *   `{spacing.lg}` — 20px
    *   `{spacing.xl}` — 24px
    *   `{spacing.xxl}` — 40px
    *   `{spacing.xxxl}` — 48px
    *   `{spacing.xxxxl}` — 64px
    *   `{spacing.xxxxxl}` — 72px
    *   `{spacing.xxxxxl-plus}` — 80px
    *   `{spacing.hero-offset}` — 142px (Used for specific large offsets, e.g., hero sections)
    *   `{spacing.md-alt}` — 21px (Specific use case, not part of main scale)

*   **Container Behavior:** Content sections (`section.l`) often use vertical padding of `{spacing.xxxl}` — 48px. Inner content wrappers (`wrapper`) typically apply horizontal padding of `{spacing.sm}` — 12px.
*   **Whitespace Philosophy:** The design embraces ample whitespace, particularly vertical spacing between sections and elements, to enhance readability and give content a premium feel. Elements within sections are well-separated, preventing visual clutter.

## Elevation & Depth

The design uses subtle shadows to create a sense of elevation and depth, primarily on interactive elements and content cards.

*   **Shadow Default** (`{elevation.default}` — `0 2px 6px -1px rgba(0, 0, 0, 0.16),0 1px 4px -1px rgba(0, 0, 0, 0.04)`): A soft, subtle shadow used for general elevated elements, providing a slight lift from the background.
*   **Shadow Active** (`{elevation.active}` — `0 0 8px -2px rgba(0, 0, 0, 0.1),0 6px 20px -3px rgba(0, 0, 0, 0.2)`): A more pronounced shadow, likely used for active states or elements requiring greater emphasis.
*   **Shadow Overlay** (`{elevation.overlay}` — `0 0 7px 0 rgba(0, 0, 0, 0.3)`): A darker, more focused shadow, potentially used for modal overlays or elements that sit above the main content.

## Shapes

The design incorporates various levels of rounded corners, contributing to a soft and approachable aesthetic.

*   **Rounded XS** (`{rounded.xs}` — 4px): Smallest radius, used for minor elements.
*   **Rounded SM** (`{rounded.sm}` — 6px): Slightly larger radius, for subtle rounding.
*   **Rounded MD** (`{rounded.md}` — 8px): Standard radius for input fields.
*   **Rounded Base** (`{rounded.base}` — 15px): A common radius for larger interactive elements and cards, such as carousel slides.
*   **Rounded LG** (`{rounded.lg}` — 16px): Larger radius, used for prominent content blocks.
*   **Rounded XL** (`{rounded.xl}` — 20px): Largest common radius, for significant containers or visual elements.
*   **Rounded Full** (`{rounded.full}` — 100%): Used for perfectly circular elements, such as avatars or badges.

## Components

*   **`button-menu`**
    *   **Structure**: Text-based button, often used for navigation toggles.
    *   **Background**: Transparent (`rgba(0, 0, 0, 0)`).
    *   **Text**: `{colors.text-primary}` — #374151, `{typography.body-xl}` — Inter, 24px, 400, 36px, normal.
    *   **Padding**: `{spacing.xs}` — 8px.
    *   **Border Radius**: `{rounded.xs}` — 4px.
    *   **Border**: None.

*   **`nav-menu`**
    *   **Structure**: Navigation container, typically appearing as a dropdown or sidebar on mobile.
    *   **Background**: `{colors.canvas}` — #f3ebe8.
    *   **Text**: `{colors.text-primary}` — #374151,