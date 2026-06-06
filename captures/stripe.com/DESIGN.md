## Overview

The Stripe website presents a sophisticated and modern aesthetic, emphasizing clarity, precision, and a strong brand identity. The visual design is characterized by a clean, spacious layout, a vibrant primary accent color, and a highly legible sans-serif typeface. The overall impression is one of trustworthiness and innovation, reflecting its role as a financial infrastructure provider. Content is organized into distinct, well-defined sections, often featuring large, impactful typography and illustrative graphics. The site balances a professional tone with engaging visual elements, creating an intuitive and efficient user experience.

**Key Characteristics:**
*   **Clean, spacious layout**: Generous use of whitespace, particularly around content blocks and sections.
*   **Vibrant brand accent**: A distinctive purple (`#533afd`) is used for primary calls to action and interactive elements.
*   **Monochromatic base palette**: Predominantly uses shades of black, dark grey, and white for text and surfaces, ensuring high contrast.
*   **Modern sans-serif typography**: "sohne-var" provides a contemporary and highly readable voice across all text sizes.
*   **Subtle elevation**: Minimal shadows add depth without distracting from the content.
*   **Structured content blocks**: Information is presented in modular, card-like sections, often with clear headings.
*   **Dynamic imagery**: Large, illustrative graphics and animations support key messages.
*   **Clear hierarchy**: Type scale and color contrast effectively guide the user's eye through the content.

## Colors

### Brand & Accent
*   **Brand Primary** (`{colors.brand-primary}` — #533afd): The dominant accent color, used for primary calls to action, interactive elements, and brand highlights.
*   **Brand Primary Hover** (`{colors.brand-hover}` — #b9b9f9): A lighter shade of the primary brand color, likely used for hover states on interactive elements.
*   **Accent Green** (`{colors.accent-green}` — #81b81a): Used for specific highlights, notably a hero headline, indicating a positive or successful tone.
*   **Accent Orange** (`{colors.accent-orange}` — #ff6118): Another secondary accent color, used for specific highlights or thematic elements.
*   **Accent Blue** (`{colors.accent-blue}` — #000eff): A tertiary accent, used sparingly for specific interactive elements or highlights.

### Surface
*   **Canvas** (`{colors.canvas}` — #ffffff): The primary background color for most sections, providing a clean, bright canvas.
*   **Surface Canvas Light** (`{colors.surface-canvas-light}` — #f8fafd): A very subtle off-white, used for backgrounds, particularly in the footer, to provide a slight visual separation from pure white.
*   **Surface Subtle** (`{colors.surface-subtle}` — #e5edf5): A light grey, used for subtle background variations or borders, providing a soft contrast.
*   **Surface Dark** (`{colors.surface-dark}` — #061b31): A very dark blue-grey, used for backgrounds in sections that require a strong contrast or a different mood.
*   **Surface Darker** (`{colors.surface-darker}` — #1a2c44): An even darker blue-grey, used for backgrounds in specific content blocks or elements within dark sections.
*   **Surface Accent Orange Light** (`{colors.surface-accent-orange-light}` — #ffe0d1): A very light, desaturated orange, used as a background for specific accent elements.
*   **Surface Accent Green** (`{colors.surface-accent-green}` — #00d66f): A vibrant green, used as a background for specific accent elements.

### Hairlines & Borders
*   **Border Dark** (`{colors.border-dark}` — #000000): Used for strong borders or dividers, often in components like navigation.
*   **Border Muted** (`{colors.border-muted}` — #64748d): A medium grey, used for less prominent borders or dividers.
*   **Border Light** (`{colors.border-light}` — #e5edf5): A very light grey, used for subtle separators or outlines.
*   **Border Input** (`{colors.border-input}` — #273951): A dark grey, used for input field borders.

### Text
*   **Text Primary** (`{colors.text-primary}` — #000000): The main text color for most content, providing maximum readability on light backgrounds.
*   **Text Dark** (`{colors.text-dark}` — #061b31): A very dark blue-grey, used for primary text in some contexts, offering a slightly softer alternative to pure black.
*   **Text Secondary** (`{colors.text-secondary}` — #50617a): A medium-dark grey, used for secondary information, descriptions, or less prominent text.
*   **Text Muted** (`{colors.text-muted}` — #64748d): A medium grey, used for tertiary text, captions, or less emphasized content.
*   **Text Tertiary** (`{colors.text-tertiary}` — #3c4f69): A slightly darker grey than muted, used for specific textual elements.
*   **Text Input** (`{colors.text-input}` — #273951): A dark blue-grey, used for text within input fields and labels.

## Typography

### Font Family
The primary typeface used across the site is "sohne-var", complemented by "SF Pro Display" as a fallback, and finally a generic sans-serif. This pairing ensures a modern, clean, and highly legible aesthetic suitable for both display and body text.

### Hierarchy
| Token              | Font Family                               | Size   | Weight | Line Height | Letter Spacing | Use                                          |
| :----------------- | :---------------------------------------- | :----- | :----- | :---------- | :------------- | :------------------------------------------- |
| `{typography.display-xl}` | sohne-var, "SF Pro Display", sans-serif | 48px   | 300    | 55.2px      | -0.96px        | Hero headlines, primary page titles          |
| `{typography.heading-lg}` | sohne-var, "SF Pro Display", sans-serif | 32px   | 300    | 35.2px      | -0.64px        | Section titles, prominent subheadings        |
| `{typography.heading-md}` | sohne-var, "SF Pro Display", sans-serif | 26px   | 400    | 29.9px      | -0.78px        | Card titles, major content headings          |
| `{typography.heading-sm}` | sohne-var, "SF Pro Display", sans-serif | 24px   | 400    | 24px        | normal         | Customer story descriptions, sub-section titles |
| `{typography.body-lg}` | sohne-var, "SF Pro Display", sans-serif | 16px   | 400    | normal      | normal         | Standard body text, main navigation items    |
| `{typography.body-md}` | sohne-var, "SF Pro Display", sans-serif | 14px   | 300    | normal      | -0.42px        | Secondary body text, detailed descriptions   |
| `{typography.body-sm}` | sohne-var, "SF Pro Display", sans-serif | 14px   | 400    | 14px        | normal         | Navigation links, smaller interactive text   |
| `{typography.caption-lg}` | sohne-var, "SF Pro Display", sans-serif | 10px   | 400    | 11.5px      | 0.1px          | Small labels, metadata                       |
| `{typography.caption-md}` | sohne-var, "SF Pro Display", sans-serif | 10px   | 300    | 11.5px      | 0.1px          | Muted captions, small descriptive text       |
| `{typography.caption-sm}` | sohne-var, "SF Pro Display", sans-serif | 10px   | 300    | 8px         | normal         | Very small labels, card details              |
| `{typography.caption-xs}` | sohne-var, "SF Pro Display", sans-serif | 9px    | 300    | normal      | normal         | Tiny labels, fine print                      |
| `{typography.label-xs}` | sohne-var, "SF Pro Display", sans-serif | 8px    | 400    | 8.96px      | normal         | Smallest labels, form hints                  |

### Principles
The typographic system prioritizes readability and a clear hierarchy. Headings (`{typography.display-xl}`, `{typography.heading-lg}`, `{typography.heading-md}`) often use a lighter weight (300) to convey a modern, airy feel, while body text (`{typography.body-lg}`, `{typography.body-md}`) maintains a standard weight (400 or 300) for optimal legibility. Letter spacing is subtly adjusted, with larger display text often having negative tracking for a more refined appearance, while smaller text maintains normal or slightly positive tracking for clarity. The consistent use of "sohne-var" across all scales creates a unified and professional brand voice.

## Layout

The layout is built on a generous use of whitespace and a flexible grid system, primarily utilizing `flex` and `grid` for content arrangement.

*   **Spacing Scale**: The system appears to be based on a 4px increment, with some exceptions for very small or very large values.
    *   `{spacing.xxs}` — 2px
    *   `{spacing.xs}` — 4px
    *   `{spacing.sm}` — 6px
    *   `{spacing.md}` — 8px
    *   `{spacing.lg}` — 12px
    *   `{spacing.xl}` — 16px
    *   `{spacing.xxl}` — 24px
    *   `{spacing.section-gap-sm}` — 32px (used for gaps between carousel items)
    *   `{spacing.section-gap-md}` — 48px (used for gaps between major content blocks)
    *   `{spacing.section-gap-lg}` — 64px (used for larger gaps between sections or within complex layouts)
    *   `{spacing.section-padding-lg}` — 96px (used for substantial vertical padding in sections)
    *   `{spacing.container-margin}` — 218px (large horizontal margin for page content)

*   **Grid/Container Behavior**:
    *   Main content areas are typically constrained within a maximum width, centered on the page, with large horizontal margins (`{spacing.container-margin}`).
    *   Sections often employ `display: flex` with `flex-direction: column` for vertical stacking of content blocks, using `{spacing.section-gap-sm}`, `{spacing.section-gap-md}`, or `{spacing.section-gap-lg}` for vertical separation.
    *   Headers within sections sometimes use `display: grid` with `grid-template-columns` defined by fixed pixel values (e.g., `88px` columns), suggesting a precise, column-based layout for specific content arrangements.
    *   Navigation elements utilize `display: flex` with `gap` for horizontal spacing between items.

*   **Whitespace Philosophy**: The design embraces ample whitespace to create a sense of openness, reduce visual clutter, and enhance content readability. Large paddings and margins around sections and components ensure that elements breathe, drawing attention to key information and imagery. This deliberate use of space contributes to the premium and professional feel of the brand.

## Elevation & Depth

Elevation and depth are used subtly to provide hierarchy and focus, primarily through soft shadows.

*   **Shadow Small** (`{shadow.sm}` — rgba(23, 23, 23, 0.06) 0px 3px 6px 0px): A light, diffused shadow, likely used for subtle lifts on cards or interactive elements.
*   **Shadow Medium** (`{shadow.md}` — rgba(23, 23, 23, 0.08) 0px 15px 35px 0px): A more pronounced shadow, used for elements requiring a greater sense of depth or prominence.
*   **Shadow Large** (`{shadow.lg}` — rgba(0, 0, 0, 0.1) 0px 30px 60px -50px, rgba(50, 50, 93, 0.25) 0px 30px 60px -10px): A complex, multi-layered shadow, reserved for highly elevated elements like modals or significant overlays, creating a strong sense of depth.

## Shapes

The design primarily uses subtly rounded corners, contributing to a modern and approachable feel without being overly soft.

*   **Rounded Small** (`{rounded.sm}` — 4px): Used for smaller interactive elements or subtle corner softening.
*   **Rounded Medium** (`{rounded.md}` — 5px): A slightly more rounded corner, used for elements like input fields or small cards.
*   **Rounded Large** (`{rounded.lg}` — 6px): Applied to navigation containers and larger interactive components.
*   **Rounded Extra Large** (`{rounded.xl}` — 16px): Used for more prominent, softer-edged containers or cards.

## Components

*   `button-transparent`:
    *   **Appearance**: Text-only button with no background or border.
    *   **Color**: `{colors.text-dark}` — #061b31
    *   **Background**: `transparent`
    *   **Typography**: `{typography.body-sm}` — sohne-var, 14px, 400, normal
    *   **Padding**: `{spacing.lg}` — 12px vertical, 0px horizontal
    *   **Rounded**: `{rounded.sm}` — 4px
    *   **Use**: Navigation links, secondary actions within content blocks.

*   `nav-menu`:
    *   **Appearance**: A container for navigation items, often appearing as a horizontal bar.
    *   **Color**: `{colors.text-primary}` — #000000
    *   **Background**: `transparent`
    *   **Typography**: Inherits from child elements, but base is `{typography.body-lg}` — sohne-var, 16px, 400, normal
    *   **Padding**: `{spacing.xs}` — 10px vertical, `{spacing.xl}` — 16px horizontal
    *   **Rounded**: `{rounded.lg}` — 6px
    *   **Use**: Primary navigation bar, often sticky at the top of the page.

*   `footer`:
    *   **Appearance**: The bottom section of the page, containing links and copyright information.
    *   **Color**: `{colors.text-primary}` — #000000
    *   **Background**: `{colors.surface-canvas-light}` — #f8fafd
    *   **Typography**: Inherits from child elements, but base is `{typography.body-lg}` — sohne-var, 16px, 400, normal
    *   **Padding**: 0px vertical, `{spacing.xl}` — 16px horizontal
    *   **Rounded**: `{rounded.none}` — 0px
    *   **Use**: Global footer for site-wide links and legal information.

*   `hero-headline`:
    *   **Appearance**: Large, impactful headline for the hero section.
    *   **Color**: `{colors.accent-green}` — #81b81a (for foreground variant)
    *   **Typography**: `{typography.display-xl}` — sohne-var, 48px, 300, 55.2px, -0.96px
    *   **Use**: Primary visual and textual anchor of the hero section.

*   `card`:
    *   **Appearance**: Generic base for content blocks, often transparent backgrounds. Specific card types (e.g., `section-row`, `feature-detail`) will build upon this.
    *   **Color**: `{colors.text-primary}` — #000000
    *   **Background**: `transparent`
    *   **Typography**: Inherits from child elements, but base is `{typography.body-lg}` — sohne-var, 16px, 400, normal
    *   **Use**: Modular content containers throughout the site.

## Do's and Don'ts

### Do's
*   **Do** use `{colors.brand-primary}` — #533afd for all primary calls to action and interactive elements to maintain brand consistency.
*   **Do** ensure ample whitespace using `{spacing.section-gap-md}` — 48px and `{spacing.section-gap-lg}` — 64px between major content blocks to enhance readability.
*   **Do** apply `{typography.display-xl}` — sohne-var, 48px, 300 for hero headlines to create a strong visual impact.
*   **Do** use `{colors.text-primary}` — #000000 on `{colors.canvas}` — #ffffff backgrounds for optimal contrast in main content.
*   **Do** apply `{rounded.lg}` — 6px to navigation elements and `{rounded.sm}` — 4px to buttons for a consistent modern aesthetic.
*   **Do** use `{shadow.sm}` — rgba(23, 23, 23, 0.06) 0px 3px 6px 0px for subtle elevation of interactive components like cards.

### Don'ts
*   **Don't** use pure black (`#000000`) for backgrounds; prefer `{colors.surface-dark}` — #061b31 or `{colors.surface-darker}` — #1a2c44 for dark sections.
*   **Don't** use `{typography.body-md}` — sohne-var, 14px, 300 for primary navigation links; `{typography.body-sm}` — sohne-var, 14px, 400 is more appropriate.
*   **Don't** introduce new font families; stick to "sohne-var" and its fallbacks.
*   **Don't** overcrowd sections; always provide sufficient padding and margins, especially `{spacing.section-padding-lg}` — 96px for vertical separation.
*   **Don't** use `{colors.accent-green}` — #81b81a or `{colors.accent-orange}` — #ff6118 as primary text colors; reserve them for highlights or specific thematic elements.
*   **Don't** apply `{shadow.lg}` — rgba(0, 0, 0, 0.1) 0px 30px 60px -50px, rgba(50, 50, 93, 0.25) 0px 30px 60px -10px to minor elements; it's intended for significant overlays.

## Responsive Behavior

The design appears to be built with a mobile-first approach, adapting gracefully to larger screens.

| Breakpoint | Min Width | Touch Targets                               | Collapse Strategy