## Overview

This design system for the Google Cloud console's Agent Platform presents a clean, functional, and information-dense interface. It leverages a modern Google-branded aesthetic, characterized by a primary dark canvas for the overall application shell, contrasted with lighter content surfaces. Typography is driven by Google Sans variants and Roboto, providing excellent readability and a consistent brand voice. Layouts are structured using flexible box models, ensuring content adaptability across various screen sizes. The visual design prioritizes clarity and efficiency, using subtle elevation and distinct color cues to guide user interaction and delineate information hierarchy.

**Key Characteristics:**
*   **Dual-theme support:** Appears to support both light and dark modes, with a dark primary canvas and lighter content areas.
*   **Google Typography:** Relies on "Google Sans Flex" and "Google Sans" for headings and key UI elements, paired with "Roboto" for body text.
*   **Subtle Elevation:** Uses a distinct, multi-layered shadow for elevated elements, providing depth without being overly intrusive.
*   **Structured Layouts:** Heavily utilizes Flexbox for dynamic and responsive content arrangement.
*   **Brand Blue Accents:** Employs Google's signature blue for interactive elements and highlights.
*   **Minimalist Borders:** Hairlines and borders are subtle, primarily using light gray tones to define boundaries.
*   **Functional Components:** Buttons and inputs are designed for clear action and readability.

## Colors

### Brand & Accent
*   **Brand Primary** (`{colors.brand-primary}` — #8ab4f8): A vibrant blue used for interactive elements, links, and primary actions.
*   **Brand Accent** (`{colors.brand-accent}` — #839cff): A slightly lighter, more saturated blue, likely for secondary accents or active states.
*   **Button Primary Background** (`{colors.button-primary-background}` — #1a73e8): A distinct blue used for the background of primary call-to-action buttons.

### Surface
*   **Canvas** (`{colors.canvas}` — #282c32): The primary background color for the application shell, indicating a dark mode or dark-themed header/sidebar. Also seen: `--cm-sys-color-backdrop` which is `light-dark(#f0f5fe,#282c32)`.
*   **Surface Default** (`{colors.surface-default}` — #f1f4f9): The most common light background color, likely for main content areas or panels within the dark canvas. Also seen: `--lt-color-background-default: #f1f3f9`.
*   **Surface Light** (`{colors.surface-light}` — #e8eaed): A slightly darker light gray, used for secondary surfaces or backgrounds. Also seen: `--lt-color-background-light: #f8f9fc`.
*   **Surface Overlay** (`{colors.surface-overlay}` — #ffffff): Pure white, likely for elevated components like modals or tooltips. Also seen: `--lt-color-overlay-default: #fff`.
*   **Surface Overlay Transparent** (`{colors.surface-overlay-transparent}` — rgba(0, 0, 0, 0.1)): A semi-transparent dark overlay, possibly for dimmed states or subtle backgrounds.

### Hairlines & Borders
*   **Border Default** (`{colors.border-default}` — #dadce0): A light gray used for general borders and separators. Also seen: `--lt-color-border-default: #dee3ed`.
*   **Border Muted** (`{colors.border-muted}` — #b9c0cc): A slightly darker gray for less prominent borders.
*   **Border Dark** (`{colors.border-dark}` — #9ca6b2): A darker gray for more defined borders or dividers. Also seen: `--lt-color-border-dark: #c2c9d6`.
*   **Border Light** (`{colors.border-light}` — #f1f3f9): A very light gray, almost indistinguishable from `surface-default`, for subtle separation. Also seen: `--lt-color-border-light: #f1f3f9`.
*   **Border Hairline** (`{colors.border-hairline}` — rgba(0,0,0,0.12)): A very subtle, almost transparent black for fine dividers.

### Text
*   **Text Primary** (`{colors.text-primary}` — #000000): The primary text color for content on light surfaces. Also seen: `rgba(0,0,0,0.99)`, `rgba(0,0,0,0.87)`.
*   **Text Secondary** (`{colors.text-secondary}` — #5e636e): A muted gray for secondary information, labels, or less emphasized text. Also seen: `--lt-color-gray-600: #5e636e`, `--lt-color-text-light: #5e636e`.
*   **Text On Canvas** (`{colors.text-on-canvas}` — #f1f4f9): Light text color used against the dark `{colors.canvas}` background.
*   **Text Dark** (`{colors.text-dark}` — #111213): A very dark gray, almost black, for high contrast text. Also seen: `--lt-color-gray-900: #111213`.

## Typography

### Font Family
The primary typefaces used are "Google Sans Flex" and "Google Sans" for headings and UI elements, paired with "Roboto" for body text and more utilitarian content. The fallback stack generally includes `sans-serif` or `Arial, sans-serif` for broad compatibility.

### Hierarchy

| Token                 | Font Family                 | Size     | Weight | Line Height | Letter Spacing | Use                                       |
| :-------------------- | :-------------------------- | :------- | :----- | :---------- | :------------- | :---------------------------------------- |
| `{typography.display-lg}` | "Google Sans Flex", sans-serif | 22px     | 400    | 28px        | normal         | Main page titles, prominent headings      |
| `{typography.heading-md}` | "Google Sans Flex", sans-serif | 18px     | 400    | 24px        | normal         | Section titles, important labels          |
| `{typography.heading-sm}` | "Google Sans", Roboto, Arial, sans-serif | 14px     | 500    | 24px        | 0.15px         | Sub-headings, emphasized labels           |
| `{typography.body-lg}`    | Roboto, sans-serif          | 16px     | 400    | 24px        | normal         | Larger body text, primary content         |
| `{typography.body-default}` | "Google Sans Flex", sans-serif | 14px     | 400    | 20px        | normal         | Standard body text, general UI labels     |
| `{typography.body-sm}`    | "Google Sans", Roboto, Arial, sans-serif | 14px     | 500    | 20px        | 0.15px         | Small emphasized text, navigation items   |
| `{typography.caption}`    | Roboto, "Helvetica Neue", sans-serif | 12px     | 400    | 16px        | normal         | Captions, metadata, small print           |
| `{typography.button}`     | "Google Sans", Arial, Helvetica, sans-serif | 16px     | 500    | -           | -              | Primary button text                       |

### Principles
The typographic scale emphasizes a clear hierarchy with "Google Sans" variants providing a distinctive, modern feel for headings and key interactive elements, often in a medium (500) weight. "Roboto" serves as a highly readable, neutral typeface for body copy and detailed information, typically in a regular (400) weight. Letter spacing is generally normal, with slight positive tracking (0.15px) on some "Google Sans" elements to enhance legibility. The system maintains a consistent baseline grid, with line heights carefully chosen to ensure comfortable reading.

## Layout

The layout system is built on a `4px` base unit, with a flexible approach to spacing and content arrangement.
*   **Spacing Scale:**
    *   `{spacing.xs}` — 4px
    *   `{spacing.sm}` — 8px
    *   `{spacing.md}` — 10px
    *   `{spacing.lg}` — 12px
    *   `{spacing.xl}` — 16px
    *   `{spacing.xxl}` — 20px
*   **Grid & Container Behavior:** The design heavily utilizes Flexbox for dynamic and responsive layouts, as evidenced by `display: flex`, `flex-direction: column`, and `flex: 1` properties. This allows for content to fill available space and adapt fluidly. Key container patterns include:
    *   `panel-flex`: `display: flex; flex: 1;` for flexible content areas.
    *   `root-panel-container`: `display: flex; flex-direction: row; height: 100%;` for main page structure.
    *   `cfc-panel`: A primary content panel, often `flex-direction: column` and `flex: 1`.
*   **Whitespace Philosophy:** The design employs generous but intentional whitespace, particularly around content blocks and interactive elements. This creates a clean, uncluttered interface that enhances readability and reduces cognitive load. Elements are clearly separated, preventing visual noise and guiding the user's eye.

## Elevation & Depth

The design uses a specific, multi-layered shadow to indicate elevation, primarily for interactive or distinct content blocks.

*   **Elevation Card Default** (`{elevation.card-default}` — rgba(0, 0, 0, 0.3) 0px 1px 2px 0px, rgba(0, 0, 0, 0.15) 0px 2px 6px 2px, rgb(80, 99, 139) 0px 0px 0px 1px inset): This complex shadow suggests a default elevated state for cards or containers. The `inset` shadow component `rgb(80, 99, 139) 0px 0px 0px 1px inset` provides a subtle inner border or highlight.
*   **Elevation Active** (`{elevation.active}` — 0 0 8px -2px rgba(0, 0, 0, 0.1),0 6px 20px -3px rgba(0, 0, 0, 0.2)): Used for active or focused elements, providing a more pronounced lift. (Derived from `--lt-shadowActive`).

Depth is primarily used to differentiate content layers and draw attention to interactive elements or primary information containers.

## Shapes

The design incorporates a few distinct border-radius values to define the shape of UI elements.

*   **Rounded Default** (`{rounded.default}` — 4px): A subtle rounding applied to many elements, providing a soft, modern aesthetic. Used for general containers and inputs.
*   **Rounded Full** (`{rounded.full}` — 50%): Creates perfectly circular shapes, typically for avatars, badges, or circular buttons.
*   **Rounded Button** (`{rounded.button}` — 48px): A very large radius, effectively creating pill-shaped buttons, notably for `{component.button-primary}`.
*   **Rounded Large** (`{rounded.lg}` — 12px): A more pronounced rounding, possibly for larger cards or panels.

## Components

*   `button-primary`
    *   **Structure:** A solid background button with rounded corners.
    *   **Background:** `{colors.button-primary-background}` — #1a73e8
    *   **Text Color:** `{colors.surface-overlay}` — #ffffff
    *   **Typography:** `{typography.button}` — "Google Sans", Arial, Helvetica, sans-serif, 16px, 500
    *   **Padding:** `{spacing.lg}` — 12px vertical, `{spacing.xxl}` — 24px horizontal
    *   **Border Radius:** `{rounded.button}` — 48px
    *   **Border:** None (`1px solid rgba(0, 0, 0, 0)`)
    *   **Box Shadow:** None

*   `nav-button`
    *   **Structure:** A text-based navigation item, often within a larger navigation bar.
    *   **Background:** Transparent (`rgba(0, 0, 0, 0)`)
    *   **Text Color:** `{colors.text-on-canvas}` — #f1f4f9
    *   **Typography:** `{typography.body-default}` — "Google Sans Flex", sans-serif, 14px, 400
    *   **Padding:** None (`0px`)
    *   **Border Radius:** `{rounded.none}` — 0px
    *   **Border:** None

*   `input-text`
    *   **Structure:** A basic text input field.
    *   **Background:** Transparent (`rgba(0, 0, 0, 0)`)
    *   **Text Color:** `{colors.text-on-canvas}` — #f1f4f9
    *   **Typography:** `{typography.body-default}` — "Google Sans Flex", sans-serif, 14px, 400
    *   **Padding:** 1px vertical, 2px horizontal
    *   **Border Radius:** `{rounded.none}` — 0px
    *   **Border:** None

*   `cfc-panel` (Content Panel)
    *   **Structure:** A flexible container for content, often acting as a main section.
    *   **Background:** Transparent (`rgba(0, 0, 0, 0)`)
    *   **Text Color:** `{colors.text-primary}` — rgba(0, 0, 0, 0.99)
    *   **Typography:** `{typography.caption}` — Roboto, "Helvetica Neue", sans-serif, 12px, 400 (This is likely for content *within* the panel, not the panel itself)
    *   **Padding:** Varies, often `0px` for the wrapper, content inside will have padding.
    *   **Border Radius:** `{rounded.none}` — 0px
    *   **Border:** None
    *   **Box Shadow:** None (The actual visual card shadow is likely applied to a child element or a different component).

## Do's and Don'ts

**Do's:**
*   **Do** use `{colors.brand-primary}` (#8ab4f8) for all primary interactive elements and links to maintain brand consistency.
*   **Do** ensure all headings and important UI text utilize "Google Sans Flex" or "Google Sans" as specified in `{typography.display-lg}`, `{typography.heading-md}`, and `{typography.heading-sm}`.
*   **Do** apply `{rounded.button}` (48px) to all primary action buttons for a consistent pill-shaped appearance.
*   **Do** maintain a clear visual hierarchy by using `{colors.canvas}` (#282c32) as the primary application background and `{colors.surface-default}` (#f1f4f9) for main content areas.
*   **Do** use `{spacing.xs}` (4px) as the fundamental unit for all internal padding and margins to ensure consistent rhythm.
*   **Do** apply `{elevation.card-default}` for any card-like containers that require visual separation and depth.
*   **Do** use `{colors.text-on-canvas}` (#f1f4f9) for text displayed directly on the dark `{colors.canvas}` background.

**Don'ts:**
*   **Don't** introduce new font families; stick strictly to "Google Sans Flex", "Google Sans", and "Roboto".
*   **Don't** use arbitrary spacing values; always refer to the `{spacing}` scale (e.g., `{spacing.sm}` for 8px).
*   **Don't** use hard-coded black or white for text; instead, use semantic tokens like `{colors.text-primary}` or `{colors.text-on-canvas}`.
*   **Don't** apply excessive or multiple shadows; limit elevation to `{elevation.card-default}` or `{elevation.active}` where appropriate.
*   **Don't** use `{rounded.none}` (0px) for primary buttons; always use `{rounded.button}` (48px).
*   **Don't** use `{colors.brand-primary}` (#8ab4f8) for large blocks of text; it is reserved for interactive elements and accents.

## Responsive Behavior

| Breakpoint | Min Width | Touch Targets | Collapse Strategy