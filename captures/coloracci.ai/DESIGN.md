## Overview

Coloracci presents a modern, sophisticated, and technically oriented visual identity, primarily characterized by a dark, almost black, background contrasted with vibrant purple and blue accents. The design leverages a clean, sans-serif typeface, Inter, to convey clarity and professionalism across all content. Ample whitespace and a structured grid system ensure readability and a premium feel, while subtle gradients and depth effects add visual interest without clutter. The overall impression is one of precision and innovation, aligning with its AI-powered tools for color management.

The brand signals a focus on digital tools and creativity, using a consistent dark theme that makes its interactive elements and core content pop. The use of strong typographic hierarchy guides the user's attention, emphasizing key features and calls to action. The aesthetic is clean, functional, and contemporary, designed to appeal to designers and developers.

**Key Characteristics**
*   **Dark Canvas**: Predominantly dark backgrounds using `{colors.canvas-dark}` — #0f1729 and `{colors.surface-card}` — #131d34.
*   **Vibrant Accents**: Strategic use of purples and blues like `{colors.accent-primary}` — #7c7ef4 and `{colors.accent-purple}` — #a855f7 for interactive elements and highlights.
*   **Clean Typography**: Exclusive use of the "Inter" typeface for most content, ensuring high readability and a modern feel.
*   **Generous Whitespace**: Ample padding and margins, such as `{spacing.section-md}` — 80px, create breathing room and structure.
*   **Subtle Depth**: Minimal shadows like `{shadow.sm}` — rgba(0, 0, 0, 0.3) 0px 2px 8px 0px provide hierarchy without heavy visual weight.
*   **Rounded Elements**: Softly rounded corners, primarily `{rounded.md}` — 6px and `{rounded.lg}` — 8px, on interactive components and cards.
*   **Structured Layout**: Content is typically centered within a constrained width, providing a focused user experience.
*   **Monochromatic Text**: Text primarily uses `{colors.text-on-dark}` — #f8fafc for primary content and `{colors.text-muted}` — #94a3b8 for secondary information.

## Colors

### Brand & Accent
*   **Accent Primary** (`{colors.accent-primary}` — #7c7ef4): Used for links, primary call-to-action elements, and interactive highlights. It provides a vibrant, tech-forward feel.
*   **Accent Primary Dark** (`{colors.accent-primary-dark}` — #6467f2): A slightly deeper shade of the primary accent, used for backgrounds of accent elements or borders.
*   **Accent Purple** (`{colors.accent-purple}` — #a855f7): Another key accent color, often seen in gradients or as a secondary highlight, particularly for "new" features or special sections.
*   **Accent Purple Dark** (`{colors.accent-purple-dark}` — #7241ff): A darker, more saturated purple used for backgrounds in gradient sections or borders.

### Surface
*   **Canvas Dark** (`{colors.canvas-dark}` — #0f1729): The primary background color for the entire application, establishing a dark theme.
*   **Surface Card** (`{colors.surface-card}` — #131d34): Used for distinct content blocks, cards, and panels, providing a subtle separation from the main canvas.
*   **Surface Subtle** (`{colors.surface-subtle}` — #1d283a): A slightly lighter dark surface, used for elements like input fields or secondary background areas.
*   **White** (`{colors.white}` — #ffffff): Used sparingly, primarily for text on very dark or transparent backgrounds where `{colors.text-on-dark}` might not stand out enough, or for specific iconography.

### Hairlines & Borders
*   **Border Subtle** (`{colors.border-subtle}` — #222f44): A dark, subtle border color used for separating UI elements, outlines on cards, and input fields.

### Text
*   **Text On Dark** (`{colors.text-on-dark}` — #f8fafc): The primary text color used on dark backgrounds for headings, body copy, and most UI labels.
*   **Text Muted** (`{colors.text-muted}` — #94a3b8): Used for secondary information, descriptions, helper text, and less prominent UI labels.
*   **Text Dark** (`{colors.text-dark}` — #111111): Appears in very specific contexts, potentially for text on light elements if any, or as a very dark foreground color.

### Semantic
*   **Semantic Success** (`{colors.semantic-success}` — #22c55e): Used to indicate successful operations or positive status.
*   **Semantic Success Dark** (`{colors.semantic-success-dark}` — #10b981): A darker variant for success states, potentially for backgrounds or borders.
*   **Semantic Warning** (`{colors.semantic-warning}` — #ffd60a): Used for warnings or cautionary messages.
*   **Semantic Warning Dark** (`{colors.semantic-warning-dark}` — #f59e0b): A darker variant for warning states.
*   **Semantic Error** (`{colors.semantic-error}` — #f43f5e): Used to indicate errors or critical issues.
*   **Semantic Info** (`{colors.semantic-info}` — #3b82f6): Used for informational messages.

## Typography

### Font Family
The primary typeface used across the Coloracci website is "Inter", a versatile sans-serif font known for its legibility at various sizes and on screens. It is used for all headings, body text, and UI elements. The full fallback stack is `Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif`. For specific technical or countdown displays, a monospace font stack `ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace` is employed.

### Hierarchy

| Token                 | Font Family                                                              | Size   | Weight | Line Height | Letter Spacing | Use                                          |
| :-------------------- | :----------------------------------------------------------------------- | :----- | :----- | :---------- | :------------- | :------------------------------------------- |
| `{typography.display-xl}` | Inter                                                                    | 60px   | 700    | 60px        | -1.5px         | Main hero headlines                          |
| `{typography.display-lg}` | Inter                                                                    | 48px   | 700    | 48px        | -1.2px         | Section titles, prominent feature headlines  |
| `{typography.heading-xl}` | Inter                                                                    | 36px   | 700    | 40px        | normal         | Major section headings                       |
| `{typography.heading-lg}` | Inter                                                                    | 24px   | 700    | 32px        | normal         | Sub-section titles, key feature titles       |
| `{typography.heading-md}` | Inter                                                                    | 20px   | 700    | 28px        | normal         | Card titles, prominent sub-headings          |
| `{typography.heading-sm}` | Inter                                                                    | 20px   | 600    | 28px        | -0.5px         | Feature callouts, specific tool names        |
| `{typography.body-lg-medium}` | Inter                                                                    | 20px   | 500    | 28px        | normal         | Hero sub-text, important descriptive text    |
| `{typography.body-lg}` | Inter                                                                    | 18px   | 400    | 28px        | normal         | Detailed descriptions, longer paragraphs     |
| `{typography.body-md-semibold}` | Inter                                                                    | 16px   | 600    | 24px        | normal         | Component titles, strong emphasis in body    |
| `{typography.body-md-medium}` | Inter                                                                    | 16px   | 500    | 24px        | normal         | Button text, navigation items                |
| `{typography.body-md}` | Inter                                                                    | 16px   | 400    | 24px        | normal         | Standard body text, general UI labels        |
| `{typography.label-bold}` | Inter                                                                    | 14px   | 700    | 20px        | normal         | Numbered lists, strong labels                |
| `{typography.label-semibold}` | Inter                                                                    | 14px   | 600    | 20px        | normal         | Navigation links, emphasized labels          |
| `{typography.label-medium}` | Inter                                                                    | 14px   | 500    | 20px        | normal         | Input labels, secondary navigation           |
| `{typography.label-regular}` | Inter                                                                    | 14px   | 400    | 20px        | normal         | Small descriptions, form field text          |
| `{typography.caption-bold}` | Inter                                                                    | 12px   | 700    | 16px        | normal         | Small emphasized text, "See more" links      |
| `{typography.caption-semibold}` | Inter                                                                    | 12px   | 600    | 16px        | normal         | Badges, small feature highlights             |
| `{typography.caption-medium}` | Inter                                                                    | 12px   | 500    | 16px        | normal         | Accessibility labels (AAA), status indicators |
| `{typography.caption-regular}` | Inter                                                                    | 12px   | 400    | 16px        | normal         | Metadata, small helper text                  |
| `{typography.caption-spaced}` | Inter                                                                    | 12px   | 400    | 16px        | 0.6px          | Uppercase labels with increased letter spacing |
| `{typography.micro-semibold}` | Inter                                                                    | 10px   | 600    | 15px        | normal         | Smallest labels, "NEW" tags                  |
| `{typography.micro-regular}` | Inter                                                                    | 10px   | 400    | 15px        | normal         | Very small descriptive text, meta info       |
| `{typography.code-mono-bold}` | ui-monospace                                                             | 13px   | 700    | 16px        | normal         | Countdown timers, code snippets              |
| `{typography.code-mono-regular}` | ui-monospace                                                             | 12px   | 400    | 16px        | normal         | Hex codes, technical values                  |

### Principles
The typographic system relies on a clear hierarchy established through significant size and weight variations, primarily using Inter. Headings utilize bold (700) and semibold (600) weights with larger sizes and tighter line heights to command attention, while body text maintains readability with regular (400) and medium (500) weights. Letter spacing is generally normal, with slight negative tracking for larger display text to improve visual density, and a single instance of increased tracking for small, all-caps labels. The consistent use of Inter across most elements ensures a unified and professional voice.

## Layout

The layout system is built on a 4px base unit, creating a consistent rhythm throughout the design. Content is primarily centered within a maximum width container, ensuring readability and focus on larger screens.

**Spacing Scale**
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
*   `{spacing.6xl}` — 48px

**Section Spacing**
*   `{spacing.section-sm}` — 64px: Used for smaller vertical separation between content blocks.
*   `{spacing.section-md}` — 80px: Standard vertical padding for main sections.
*   `{spacing.section-lg}` — 96px: Larger vertical padding for prominent sections or between major content areas.

**Grid & Container Behavior**
The primary content container uses a fluid width up to a maximum of `1280px` on desktop, with `16px` horizontal padding (`{spacing.2xl}`) on smaller screens. This ensures content is always legible and well-aligned. Sections often feature internal grids (e.g., 4-column layouts for tools) with consistent `gap` values like `{spacing.4xl}` — 24px.

**Whitespace Philosophy**
Whitespace is generous and intentional, creating a clean and uncluttered interface. Large vertical and horizontal spacing is used to separate distinct content blocks and improve readability, giving elements ample room to breathe. This contributes to the premium and professional feel of the site.

## Elevation & Depth

Elevation and depth are used subtly to create visual hierarchy and indicate interactivity. Shadows are soft and generally dark, complementing the overall dark theme.

*   **Shadow Small** (`{shadow.sm}` — rgba(0, 0, 0, 0.3) 0px 2px 8px 0px): Used for subtle lift on interactive elements or small cards, providing a slight sense of depth.
*   **Shadow Interactive** (`{shadow.interactive}` — rgb(255, 255, 255) 0px 0px 0px 0px, rgba(100, 103, 242, 0.15) 0px 0px 0px 1px, rgba(0, 0, 0, 0.3) 0px 2px 8px 0px): Applied to interactive components like buttons or inputs, featuring a subtle accent ring (`rgba(100, 103, 242, 0.15) 0px 0px 0px 1px`) for focus indication, combined with a soft shadow.
*   **Shadow Medium** (`{shadow.md}` — rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(100, 103, 242, 0.15) 0px 8px 30px 0px): Used for more prominent elements like dropdowns or modals, providing a distinct lift with a subtle accent glow.
*   **Shadow Large** (`{shadow.lg}` — rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0.4) 0px 4px 20px 0px): Deeper shadow for significant elements, drawing more attention.
*   **Shadow Extra Large** (`{shadow.xl}` — rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px): The deepest shadow, used for elements requiring strong visual separation, like large popovers or persistent UI.

## Shapes

Shapes are predominantly rectangular with soft, consistent rounding, contributing to a friendly yet professional aesthetic.

*   **Rounded Small** (`{rounded.sm}` — 4px): Used for very subtle rounding on small elements or as a minimal edge treatment.
*   **Rounded Medium** (`{rounded.md}` — 6px): The most common border-radius, applied to input fields, buttons, and many card-like elements.
*   **Rounded Large** (`{rounded.lg}` — 8px): Used for slightly more pronounced rounding on cards and larger interactive elements.
*   **Rounded Extra Large** (`{rounded.xl}` — 12px): Applied to larger containers or specific UI components where a softer, more distinct shape is desired.
*   **Rounded 2XL** (`{rounded.2xl}` — 16px): Used for prominent cards or sections that require a very soft, pill-like corner.
*   **Rounded Full** (`{rounded.full}` — 9999px): Used for fully circular elements like avatars, small badges, or pill-shaped buttons.

## Components

### `button-primary`
A prominent call-to-action button.
*   **Structure**: Solid background with light text.
*   **Background**: `{colors.accent-primary}` — #7c7ef4.
*   **Text**: `{colors.text-on-dark}` — #f8fafc.
*   **Typography**: `{typography.body-md-medium}` — Inter, 16px, 500, 24px.
*   **Padding**: `py-{spacing.md}` — 8px, `px-{spacing.xl}` — 12px.
*   **Border Radius**: `{rounded.md}` — 6px.
*   **Shadow**: `{shadow.interactive}` — rgb(255, 255, 255) 0px 0px 0px 0px, rgba(100, 103, 242, 0.15) 0px 0px 0px 1px, rgba(0, 0, 0, 0.3) 0px 2px 8px 0px.

### `button-secondary`
A less prominent button, often used for secondary actions or navigation.
*   **Structure**: Transparent background with colored text.
*   **Background**: `transparent`.
*   **Text**: `{colors.accent-primary}` — #7c7ef4.
*   **Typography**: `{typography.body-md-medium}` — Inter, 16px, 500, 24px.
*   **Padding**: `py-{spacing.md}` — 8px, `px-{spacing.xl}` — 12px.
*   **Border Radius**: `{rounded.md}` — 6px.
*   **Shadow**: None.

### `input-text`
Standard text input field.
*   **Structure**: Slightly transparent background with a subtle border.
*   **Background**: `rgba(255, 255, 255, 0.1)` (a semi-transparent white over `{colors.surface-subtle}`).
*   **Border**: `1px solid rgba(255, 255, 255, 0.2)`.
*   **Text**: `{colors.white}` — #ffffff.
*   **Typography**: `{typography.label-regular}` — Inter, 14px, 400, 20px.
*   **Padding**: `py-{spacing.md}` — 8px, `px-{spacing.xl}` — 12px.
*   **Border Radius**: `{rounded.md}` — 6px.

### `navbar-sticky`
The main navigation bar at the top of the page.
*   **Structure**: Sticky, top-aligned, with a blurred background effect.
*   **Background**: `rgba(15, 23, 41, 0.6)` (semi-transparent `{colors.canvas-dark}`).
*   **Border**: `border-b` (bottom border, color derived from context, likely `{colors.border-subtle}`).
*   **Text**: `{colors.text-on-dark}` — #f8fafc.
*   **Typography**: Navigation links use `{typography.body-md}` — Inter, 16px, 400, 24px, with active/emphasized links using `{typography.label-medium}` — Inter, 14px, 500, 20px.
*   **Height**: 64px (`h-16`).
*   **Padding**: `px-{spacing.2xl}` — 16px for content within.

### `card-tool`
A card used to display individual tools or features.
*   **Structure**: Flexible container, often with an icon or image, title, and description.
*   **Background**: Transparent, or subtle gradient when highlighted.
*   **Text**: Title uses `{typography.body-md-semibold}` — Inter, 16px, 600, 24px; description uses `{typography.label-regular}` — Inter, 14px, 400, 22.75px.
*   **Padding**: `p-{spacing.4xl}` — 24px.
*   **Border Radius**: `{rounded.lg}` — 8px (inferred from common card patterns).
*   **Shadow**: Often none, relying on background contrast or subtle borders for separation.

### `footer-main`
The page footer.
*   **Structure**: Top border, semi-transparent background.
*   **Background**: `rgba(19, 29, 52, 0.5)` (semi-transparent `{colors.surface-card}`).
*   **Border**: `border-t` (top border, color derived from context, likely `{colors.border-subtle}`).
*   **Text**: `{colors.text-on-dark}` — #f8fafc.
*   **Typography**: `{typography.body-md}` — Inter, 16px, 400, 24px for general text.

## Do's and Don'ts

### Do's
*   **Do** use `{colors.canvas-dark}` — #0f1729 as the primary background for most sections to maintain the dark theme.
*   **Do** apply `{colors.accent-primary}` — #7c7ef4 for all primary interactive elements and links to ensure brand consistency.
*   **Do** maintain a clear typographic hierarchy using "Inter" with appropriate weights and sizes, especially for headlines using `{typography.display-xl}` — Inter, 60px, 700.
*   **Do** utilize `{spacing.md}` — 8px and its multiples for consistent internal padding and gaps between elements.
*   **Do** apply `{rounded.md}` — 6px to interactive elements like buttons and inputs for a consistent soft-edged feel.
*   **Do** use `{colors.text-on-dark}` — #f8fafc for primary text on dark backgrounds and `{colors.text-muted}` — #94a3b8 for secondary information.
*   **Do** ensure ample whitespace, such as `{spacing.section-md}` — 80px between major content sections, to enhance readability and visual breathing room.
*   **Do** use `ui-monospace` with `{typography.code-mono-bold}` — ui-monospace, 13px, 700 for countdowns and technical data like hex codes.

### Don'ts
*   **Don't** introduce new primary background colors that deviate from the dark theme established by `{colors.canvas-dark}` — #0f1729 and `{colors.surface-card}` — #131d34.
*   **Don't** use bright, high-contrast colors for large text blocks; reserve vibrant colors like `{colors.accent-purple}` — #a855f7 for accents and interactive states.
*   **Don't** use typefaces other than "Inter" or "ui-monospace" without explicit approval, to maintain typographic consistency.
*   **Don't** use arbitrary spacing values; always refer to the `{spacing}` scale to maintain layout rhythm.
*   **Don't** use sharp, unrounded corners on interactive elements; `{rounded.md}` — 6px is the standard.
*   **Don't** use `{colors.text-dark}` — #111111 on dark backgrounds; it's intended for specific, very dark elements or light backgrounds.
*   **Don't** overcrowd sections; maintain the generous whitespace philosophy.
*   **Don't** apply heavy, opaque shadows; prefer the subtle, dark shadows defined in `{shadow.sm}` or `{