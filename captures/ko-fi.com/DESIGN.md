## Overview

This design system for Ko-fi presents a clean, modern aesthetic with a strong emphasis on readability and clear content hierarchy. The visual identity is built around a neutral palette of dark grays and whites, punctuated by a vibrant red accent. Typography is primarily driven by the "DM Sans" typeface, providing a friendly yet professional feel. Layouts are content-focused, utilizing ample whitespace and a structured spacing system to ensure clarity and ease of navigation. Cards and content blocks are a prominent feature, often employing subtle rounded corners and occasional soft shadows to define interactive areas.

**Key Characteristics:**
*   **Minimalist Color Palette**: Dominated by `{colors.text-primary}` — #192025 and `{colors.canvas}` — #ffffff, with `{colors.accent-primary}` — #ff5f5f for emphasis.
*   **Clear Typography**: "DM Sans" is used consistently for body text and headings, with distinct weights for hierarchy.
*   **Card-Based Layouts**: Content is frequently presented within cards with `{rounded.md}` — 18px corners.
*   **Structured Spacing**: A modular spacing scale, likely based on a 4px or 8px grid, ensures consistent visual rhythm.
*   **Subtle Depth**: Soft shadows are used sparingly to elevate key components without being overly distracting.
*   **Functional Accent Color**: A vibrant red is reserved for important actions, icons, or indicators.
*   **Responsive Adaptation**: Layouts are designed to adjust across common breakpoints, particularly for mobile and tablet.
*   **Iconography**: "Font Awesome 6 Pro" is integrated for functional and decorative icons.

## Colors

### Brand & Accent
*   **Accent Primary** (`{colors.accent-primary}` — #ff5f5f): Used for key interactive elements, icons (e.g., pricing icons), and to draw attention to important information.
*   **Brand Green** (`{colors.brand-green}` — #10d773): A vibrant green, likely for success states or positive indicators (inferred from `--spring-green-500`).
*   **Brand Blue** (`{colors.brand-blue}` — #00aff1): A bright blue, likely for links or informational highlights (inferred from `--blue-500`).
*   **Brand Red Light** (`{colors.brand-red-light}` — #ffa970): A lighter red/orange hue, potentially for secondary brand accents (inferred from `--brand-red-300`).

### Surface
*   **Canvas** (`{colors.canvas}` — #ffffff): The primary background color for the overall page and most content surfaces like cards and navigation bars.
*   **Surface Light** (`{colors.surface-light}` — #f7f7f7): A very light gray used for subtle background differentiation, such as hover states on tabs.
*   **Surface Subtle** (`{colors.surface-subtle}` — #c0b6b3): A muted, slightly warmer gray for background elements, offering a gentle contrast.
*   **Surface Sidebar Active** (`{colors.surface-sidebar-active}` — #f0f5fe): A very light blue, indicating an active state in sidebar navigation (inferred from `--btn-bg-sidebar-active`).
*   **Surface Sidebar Hover** (`{colors.surface-sidebar-hover}` — #e4e4e4): A light gray for hover states on sidebar navigation items (inferred from `--btn-bg-sidebar-hover`).

### Hairlines & Borders
*   **Border Light** (`{colors.border-light}` — #d4cfcd): A light, subtle border color used for form elements and general UI separation.
*   **Border Muted** (`{colors.border-muted}` — #818181): A darker gray border, used for more prominent separations or outlines.
*   **Border Selected** (`{colors.border-selected}` — #192025): A dark border color, indicating a selected or focused state (inferred from `--border-selected`).

### Text
*   **Text Primary** (`{colors.text-primary}` — #192025): The dominant dark gray for most body text, headings, and primary UI labels.
*   **Text Heading** (`{colors.text-heading}` — #14171a): A slightly darker shade of primary text, often used for more prominent headings or titles.
*   **Text Secondary** (`{colors.text-secondary}` — #818181): A medium gray for secondary information, less emphasized text, or descriptive labels.
*   **Text Muted** (`{colors.text-muted}` — #848a95): A lighter gray for tertiary text, timestamps, or less important details.
*   **Text Danger** (`{colors.text-danger}` — #e5211d): A distinct red for error messages or critical warnings (inferred from `--text-danger`).

### Semantic
*   **Button Primary Background** (`{colors.button-primary-bg}` — #202020): A very dark gray, serving as the background for primary action buttons (inferred from `--btn-bg-primary`).

## Typography

### Font Family
The primary typeface for content and UI elements is "DM Sans", with "Nunito" as a fallback, followed by generic `sans-serif`. This pairing provides a clean, modern, and highly legible experience. For iconography, "Font Awesome 6 Pro" is used.

### Hierarchy

| Token                      | Font Family                     | Size   | Weight | Line Height | Letter Spacing | Use                                          |
| :------------------------- | :------------------------------ | :----- | :----- | :---------- | :------------- | :------------------------------------------- |
| `{typography.body}`        | "DM Sans", Nunito, sans-serif   | 16px   | 400    | 22.86px     | normal         | Standard paragraph text, general UI labels   |
| `{typography.body-bold}`   | "DM Sans", Nunito, sans-serif   | 16px   | 600    | 22.86px     | normal         | Emphasized body text, strong labels          |
| `{typography.label}`       | "DM Sans", Nunito, sans-serif   | 16px   | 600    | 20.8px      | normal         | Component labels, short emphasized phrases   |
| `{typography.heading-md}`  | "DM Sans", Nunito, sans-serif   | 22px   | 600    | 30px        | normal         | Section titles, prominent headings           |
| `{typography.heading-sm}`  | "DM Sans", Nunito, sans-serif   | 18px   | 600    | 25.71px     | normal         | Subheadings, date indicators                 |
| `{typography.heading-sm-tight}` | "DM Sans", Nunito, sans-serif   | 18px   | 600    | normal      | normal         | Specific subheadings with tighter line height |
| `{typography.button}`      | "DM Sans", Nunito, sans-serif   | 14px   | 600    | 20px        | normal         | Call-to-action text, interactive labels      |
| `{typography.caption}`     | "DM Sans", Nunito, sans-serif   | 14px   | 300    | 20px        | normal         | Secondary information, metadata              |
| `{typography.caption-small}` | "DM Sans", Nunito, sans-serif   | 13px   | 400    | 18.57px     | normal         | Smallest text, timestamps                    |
| `{typography.data-value}`  | "DM Sans", Nunito, sans-serif   | 15px   | 600    | 20.8px      | normal         | Numeric data, percentages                    |
| `{typography.icon}`        | "Font Awesome 6 Pro"            | 16px   | 400    | 16px        | normal         | Standard icons                               |
| `{typography.icon-bold}`   | "Font Awesome 6 Pro"            | 16px   | 900    | 16px        | normal         | Bold icons                                   |

### Principles
The typography system prioritizes legibility and a clear visual hierarchy. "DM Sans" is used across the board, with `font-weight: 400` for body text and `font-weight: 600` for all headings, labels, and emphasized text, creating a consistent bolding pattern. Line heights are generally generous for readability, while letter spacing remains `normal` to maintain the font's natural appearance. The system effectively uses size and weight variations to distinguish content types, from small captions to prominent section titles, without introducing excessive font families.

## Layout

The layout system is built on a modular spacing scale, primarily using multiples of 4px and 8px, which contributes to a clean and organized appearance.

*   **Spacing Scale**:
    *   `{spacing.none}` — 0px
    *   `{spacing.xxs}` — 4px
    *   `{spacing.xs}` — 8px
    *   `{spacing.sm}` — 12px
    *   `{spacing.md}` — 16px
    *   `{spacing.lg}` — 24px
    *   `{spacing.xl}` — 40px
    *   `{spacing.xxl}` — 60px
    *   Additional specific values observed include 1px, 5px, 6px, 7px, 10px, 14px, 15px, 18px, which are often used for fine-tuning component padding or margins.
*   **Container Behavior**: Content generally appears to be contained within a fluid width that adapts to the viewport, with common horizontal padding of `{spacing.md}` — 16px or `{spacing.component-padding-horizontal}` — 15px on larger blocks. This suggests a responsive grid system that centers content and provides consistent margins.
*   **Whitespace Philosophy**: The design embraces ample whitespace, particularly around content blocks and between elements, to reduce visual clutter and improve readability. This is evident in the generous padding within cards and around text elements.

## Elevation & Depth

Elevation and depth are used subtly to highlight interactive elements and distinguish content layers.
*   **Card Default Shadow** (`{shadow.card-default}` — rgba(0, 9, 128, 0.035) 0px 5px 10px 0px, rgba(0, 9, 128, 0.05) 0px 0px 8px 0px): A soft, multi-layered shadow used to give depth to cards and content containers.
*   **Card Soft Shadow** (`{shadow.card-soft}` — rgba(149, 185, 193, 0.2) 0px 4px 20px 0px): A slightly more pronounced, diffused shadow, likely for more elevated or interactive cards.
*   **Shadow None** (`{shadow.none}` — none): Explicitly removes shadows where no elevation is desired.

## Shapes

The design incorporates rounded corners to soften the aesthetic and define interactive areas.
*   **Rounded Small** (`{rounded.sm}` — 8px): Smallest common radius, used for minor elements.
*   **Rounded Base** (`{rounded.base}` — 14px): A standard radius for general components.
*   **Rounded Medium** (`{rounded.md}` — 18px): A more pronounced radius, frequently used for cards and content bubbles.
*   **Rounded Large** (`{rounded.lg}` — 25px): A larger radius, possibly for larger interactive elements.
*   **Rounded Extra Large** (`{rounded.xl}` — 50px): A very large radius, often used for pill-shaped buttons or input fields.
*   **Rounded Full** (`{rounded.full}` — 100px): Used for fully rounded elements like avatars or pill-shaped buttons, effectively creating a circle or oval.
*   **Rounded Circle** (`{rounded.circle}` — 100%): Ensures a perfect circular shape for elements like avatars.
*   **Rounded Card Bottom** (`{rounded.card-bottom}` — 0px 0px 14px 14px): A specific radius applied only to the bottom corners of certain card types, leaving the top corners sharp.

## Components

*   `button-sidemenu`
    *   **Structure**: Text label, often accompanied by an icon.
    *   **Typography**: `{typography.body-bold}` — "DM Sans", 16px, 600, 22.86px.
    *   **Colors**: Text `{colors.text-primary}` — #192025, Background transparent.
    *   **Padding**: `{spacing.xxs}` — 4px vertical, `{spacing.sm}` — 12px horizontal.
    *   **Shape**: `{rounded.full}` — 50px.
    *   **Border**: None.
*   `nav-bar`
    *   **Structure**: Horizontal strip, typically at the top of the page.
    *   **Typography**: `{typography.body}` — "DM Sans", 16px, 400, 22.86px.
    *   **Colors**: Text `{colors.text-primary}` — #192025, Background `{colors.canvas}` — #ffffff.
    *   **Padding**: `{spacing.none}` — 0px.
    *   **Border**: None.
    *   **Shadow**: None.
*   `input-field`
    *   **Structure**: Standard input element.
    *   **Typography**: `{typography.body}` — "DM Sans", 16px, 400, 22.86px.
    *   **Colors**: Text `{colors.canvas}` — #ffffff (unusual, possibly for placeholder or specific input type), Background transparent.
    *   **Padding**: `{spacing.none}` — 0px.
    *   **Border**: None.
*   `footer-primary`
    *   **Structure**: Bottom section of the page, containing links and copyright.
    *   **Typography**: `{typography.body}` — "DM Sans", 16px, 400, 22.86px.
    *   **Colors**: Text `{colors.text-primary}` — #192025, Background `{colors.canvas}` — #ffffff.
    *   **Padding**: `{spacing.none}` — 0px vertical, `{spacing.xs}` — 10px horizontal.
    *   **Border**: None.
*   `testimonial-bubble`
    *   **Structure**: Blockquote-like element for testimonials or updates.
    *   **Typography**: `{typography.body}` — "DM Sans", 16px, 400, 22.86px.
    *   **Colors**: Text `{colors.text-primary}` — #192025, Background `{colors.canvas}` — #ffffff.
    *   **Padding**: `{spacing.md}` — 16px.
    *   **Shape**: `{rounded.md}` — 18px.
    *   **Border**: None.
    *   **Shadow**: Implied by class `kfds-c-shadow-buble`, but `boxShadow` is `none` in sample. Should ideally use `{shadow.card-default}`.
*   `card-feed-item`
    *   **Structure**: A content card, often containing an