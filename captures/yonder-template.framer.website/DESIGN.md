## Overview

The Yonder website presents a rugged, adventurous aesthetic, blending natural, earthy tones with a bold, almost industrial typography for display elements. The design heavily utilizes a dark, muted green as its primary canvas, creating a sense of depth and wilderness. White and a vibrant orange serve as key contrasting elements, highlighting calls to action and important information. The overall impression is one of a premium, experience-focused brand, with a clear hierarchy established through font choices and color contrasts.

**Key Characteristics**:
*   **Dark Theme**: Predominantly dark green backgrounds (`{colors.canvas}` — #2a2e1e) with white text (`{colors.on-dark}` — #ffffff).
*   **Bold Display Typography**: Uses the unique "Tanker" typeface for large, impactful headlines.
*   **Clean Body Text**: Employs "DM Sans" for readability in body copy and functional elements.
*   **Accent Color**: A bright, energetic orange (`{colors.brand-primary}` — #e94b17) for primary actions and highlights.
*   **Subtle Details**: Incorporates "Courier Prime" for specific, data-like text, adding a technical or archival touch.
*   **Minimalist Elevation**: Relies on color and typography for hierarchy, with no explicit shadows.
*   **Rounded Corners**: Moderate use of `6px` and `12px` radii for cards and interactive elements.
*   **Generous Spacing**: Utilizes ample whitespace, particularly vertical spacing, to create a breathable layout.

## Colors

### Brand & Accent
*   **Brand Primary** (`{colors.brand-primary}` — #e94b17): A vibrant orange used for primary calls to action, interactive elements, and key highlights.
*   **Brand Primary Dark** (`{colors.brand-primary-dark}` — #cd4213): A darker shade of the primary orange, likely for pressed states or subtle variations.
*   **Link Default** (`{colors.link-default}` — #0000ee): A standard blue for hyperlinks, standing out against both dark and light backgrounds.

### Surface
*   **Canvas** (`{colors.canvas}` — #2a2e1e): The primary background color for the overall page, a deep, muted forest green.
*   **Surface Secondary** (`{colors.surface-secondary}` — #373b2a): A slightly lighter shade of dark green, used for distinct sections or containers.
*   **Surface Tertiary** (`{colors.surface-tertiary}` — #434738): Another dark green, providing subtle variation for background elements.
*   **Surface Accent** (`{colors.surface-accent}` — #2e551e): A slightly more saturated green, used for specific background elements or containers.
*   **Surface Card** (`{colors.surface-card}` — #ffffff): A clean white used for card backgrounds, providing strong contrast for content.

### Text
*   **Text Primary** (`{colors.text-primary}` — #000000): Black text, primarily used on light backgrounds such as `{colors.surface-card}`.
*   **On Dark** (`{colors.on-dark}` — #ffffff): White text, used extensively for readability against dark backgrounds like `{colors.canvas}`.
*   **On Dark Muted** (`{colors.on-dark-muted}` — #ffffffbf): A semi-transparent white, used for secondary text or subtle details on dark backgrounds.
*   **On Dark Muted Light** (`{colors.on-dark-muted-light}` — #ffffffb3): A slightly more transparent white, for even subtler text on dark backgrounds.

### Semantic
*   **Overlay Dark** (`{colors.overlay-dark}` — #0000002b): A semi-transparent black, likely used for overlays or subtle darkening effects.

## Typography

### Font Family
The primary typefaces are "Tanker" for display headings, "DM Sans" for body text and functional elements, and "Courier Prime" for monospaced content. A generic `sans-serif` is used as a universal fallback.

*   **Display**: "Tanker", "Tanker Placeholder", sans-serif
*   **Body**: "DM Sans", "DM Sans Placeholder", sans-serif
*   **Monospace**: "Courier Prime", monospace
*   **Base/Fallback**: sans-serif

### Hierarchy

| Token                 | Font Family                               | Size   | Weight | Line Height | Letter Spacing | Use                                                                 |
| :-------------------- | :---------------------------------------- | :----- | :----- | :---------- | :------------- | :------------------------------------------------------------------ |
| `{typography.display-xl}` | Tanker, "Tanker Placeholder", sans-serif  | 76px   | 400    | 76px        | normal         | Hero headlines, primary branding statements                         |
| `{typography.display-lg}` | Tanker, "Tanker Placeholder", sans-serif  | 64px   | 400    | 64px        | normal         | Section titles, featured content headings                           |
| `{typography.display-md}` | Tanker, "Tanker Placeholder", sans-serif  | 45px   | 400    | 49.5px      | normal         | Large subheadings, prominent labels                                 |
| `{typography.heading-lg}` | Tanker, "Tanker Placeholder", sans-serif  | 32px   | 400    | 38.4px      | normal         | Card titles, prominent content headings                             |
| `{typography.heading-md}` | Tanker, "Tanker Placeholder", sans-serif  | 27px   | 400    | 35.1px      | normal         | Secondary card titles, smaller section headings                     |
| `{typography.heading-sm}` | Tanker, "Tanker Placeholder", sans-serif  | 23px   | 400    | 31.05px     | normal         | Price displays, numerical highlights                                |
| `{typography.body-lg}`    | "DM Sans", "DM Sans Placeholder", sans-serif | 19px   | 400    | 26.6px      | normal         | Lead paragraphs, descriptive text                                   |
| `{typography.body-md}`    | "DM Sans", "DM Sans Placeholder", sans-serif | 16px   | 400    | 24px        | normal         | Standard body text, longer descriptions                             |
| `{typography.body-sm-bold}` | "DM Sans", "DM Sans Placeholder", sans-serif | 16px   | 600    | 22.4px      | normal         | Button labels, emphasized body text                                 |
| `{typography.caption-md}` | "DM Sans", "DM Sans Placeholder", sans-serif | 14px   | 400    | 19.6px      | normal         | Metadata, small labels, secondary information                       |
| `{typography.caption-sm-bold}` | "DM Sans", "DM Sans Placeholder", sans-serif | 14px   | 600    | 21px        | normal         | Small button labels, emphasized captions                            |
| `{typography.monospace-lg}` | "Courier Prime", monospace                | 19px   | 400    | 26.6px      | normal         | Specialized data, code snippets, unique labels                      |
| `{typography.monospace-md}` | "Courier Prime", monospace                | 16px   | 400    | 22.4px      | normal         | Trail updates, specific data points                                 |
| `{typography.monospace-sm}` | "Courier Prime", monospace                | 14px   | 400    | 21px        | normal         | Smallest monospace text, e.g., "Next Departure" label               |
| `{typography.base}`       | sans-serif                                | 12px   | 400    | normal      | normal         | Default fallback, minor utility text, ticker items                  |

### Principles
The typography system creates a strong visual hierarchy through the deliberate pairing of a decorative, bold display font ("Tanker") with a highly legible, modern sans-serif ("DM Sans"). "Tanker" is reserved for high-impact headlines, often in all lowercase, giving a distinct brand voice. "DM Sans" handles the majority of content, ensuring readability with moderate line heights. "Courier Prime" adds a functional, almost retro-tech feel for specific data points. Weight contrast is primarily used within "DM Sans" for emphasis, while "Tanker" maintains a consistent regular weight across all its sizes.

## Layout

The layout employs a flexible grid system with a maximum content width, centered on the page. Spacing is generous, contributing to a premium feel and ensuring content breathability.

*   **Spacing Scale**: While not strictly adhering to a single base unit, the system uses a set of defined values:
    *   `{spacing.xxs}` — 6px
    *   `{spacing.xs}` — 10px
    *   `{spacing.sm}` — 12px
    *   `{spacing.md}` — 18px
    *   `{spacing.lg}` — 24px
    *   `{spacing.xl}` — 36px
    *   `{spacing.section-sm}` — 42px
    *   `{spacing.section-md}` — 60px
    *   `{spacing.section-lg}` — 84px
    *   `{spacing.section-xl}` — 96px
*   **Container Behavior**: Content is typically constrained within a maximum width, approximately 1200-1300px, and centered horizontally. Sections often utilize internal padding of `{spacing.lg}` — 24px on the sides.
*   **Whitespace Philosophy**: The design embraces ample whitespace, particularly vertical spacing between sections (`{spacing.section-lg}` — 84px, `{spacing.section-xl}` — 96px) and around content blocks, to enhance readability and visual separation. Horizontal gaps between items often use `{spacing.xs}` — 10px, `{spacing.sm}` — 12px, `{spacing.md}` — 18px, or `{spacing.lg}` — 24px.

## Elevation & Depth

The design system primarily relies on color contrast and typography for visual hierarchy rather than explicit depth.
*   No explicit shadow tokens (`shadows` array is empty).
*   Components generally have `box-shadow: none`.

## Shapes

The design incorporates subtle rounding for interactive elements and cards, with some specific corner radii for unique visual treatments.

*   **Rounded Small** (`{rounded.sm}` — 6px): Used for buttons and some card elements.
*   **Rounded Medium** (`{rounded.md}` — 12px): Applied to larger interactive elements or specific card styles.
*   **Rounded Full** (`{rounded.full}` — 200px): Used for pill-shaped elements or highly rounded containers.
*   **Rounded Circle** (`{rounded.circle}` — 50%): For perfectly circular elements like avatars or icons.
*   **Rounded Top Left** (`{rounded.top-left-sm}` — 6px 0px 0px 6px): Specific corner rounding for design accents.
*   **Rounded Top Left Medium** (`{rounded.top-left-md}` — 12px 0px 0px 12px): Specific corner rounding for design accents.
*   **Rounded Base** (`{rounded.base}` — 10px): A general-purpose rounded corner, less frequently used than `{rounded.sm}` or `{rounded.md}`.

## Components

*   **`button-default`**
    *   **Structure**: A simple rectangular button.
    *   **Background**: `{colors.canvas}` — #2a2e1e
    *   **Text Color**: `{colors.text-primary}` — #000000
    *   **Typography**: `{typography.base}` — sans-serif, 12px, 400
    *   **Padding**: `0px 18px` (`{spacing.md}` horizontal)
    *   **Border Radius**: `{rounded.sm}` — 6px
    *   **Border**: None

*   **`button-primary`** (Inferred from Brand Primary color usage)
    *   **Structure**: A prominent rectangular button.
    *   **Background**: `{colors.brand-primary}` — #e94b17
    *   **Text Color**: `{colors.on-dark}` — #ffffff (inferred for contrast)
    *   **Typography**: `{typography.body-sm-bold}` — "DM Sans", 16px, 600 (inferred)
    *   **Padding**: (Inferred, likely similar to `button-default` or slightly larger)
    *   **Border Radius**: `{rounded.sm}` — 6px (inferred)
    *   **Border**: None

*   **`nav-primary`**
    *   **Structure**: Horizontal navigation bar.
    *   **Background**: `{colors.canvas}` — #2a2e1e
    *   **Text Color**: `{colors.text-primary}` — #000000 (Note: This is low contrast on the background, suggesting it might be intended for a different context or is a specific design choice for subtle navigation links).
    *   **Typography**: `{typography.base}` — sans-serif, 12px, 400
    *   **Padding**: `0px 24px` (`{spacing.lg}` horizontal)
    *   **Border Radius**: `{rounded.none}` — 0px
    *   **Gap**: `{spacing.lg}` — 20px (between nav items)

*   **`input-text`**
    *   **Structure**: Standard text input field.
    *   **Background**: `rgba(0, 0, 0, 0)` (transparent)
    *   **Text Color**: `{colors.on-dark}` — #ffffff
    *   **Typography**: `{typography.caption-md}` — "DM Sans", 14px, 400
    *   **Padding**: `0px`
    *   **Border Radius**: `{rounded.none}` — 0px
    *   **Border**: None (suggests a bottom border or surrounding container defines its bounds)

*   **`card-surface`**
    *   **Structure**: A content container with a distinct background.
    *   **Background**: `{colors.surface-card}` — #ffffff
    *   **Text Color**: `{colors.text-primary}` — #000000 (default for content on this card)
    *   **Typography**: Inherits from parent or uses `{typography.base}` — sans-serif, 12px, 400
    *   **Padding**: `6px 6px 36px` (`{spacing.xxs}` horizontal/top, `{spacing.xl}` bottom)
    *   **Border Radius**: `{rounded.none}` — 0px
    *   **Border**: None

*   **`card-rounded`**
    *   **Structure**: A content container with rounded corners.
    *   **Background**: `rgba(0, 0, 0, 0)` (transparent)
    *   **Text Color**: Inherits from parent.
    *   **Typography**: Inherits from parent or uses `{typography.base}` — sans-serif, 12px, 400
    *   **Padding**: `0px`
    *   **Border Radius**: `{rounded.sm}` — 6px
    *   **Border**: None

## Do's and Don'ts

**Do's**:
*   **Do** use `{colors.canvas}` — #2a2e1e as the primary background for most sections to maintain the dark, earthy aesthetic.
*   **Do** prioritize `{colors.on-dark}` — #ffffff for text on dark backgrounds to ensure readability.
*   **