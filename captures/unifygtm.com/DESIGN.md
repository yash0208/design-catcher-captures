## Overview

The Unify website presents a sophisticated and modern aesthetic, characterized by a strong emphasis on clean typography, a muted yet warm color palette, and a structured, spacious layout. The visual design balances a professional, data-driven feel with approachable, human-centric elements. Large, impactful display typography is a key feature, often paired with more subtle body text to create clear hierarchy. The site utilizes subtle background colors and minimal borders, giving an impression of lightness and digital efficiency. Interactive elements are clearly defined through color accents and rounded corners, guiding user attention without being overly flashy.

**Key Characteristics:**
*   **Muted Warm Palette**: Dominant off-white `{colors.canvas}` — #fffff9 and dark brown/black `{colors.text-primary}` — #241e20, accented by a vibrant orange `{colors.brand-primary}` — #f23b0a.
*   **Typographic Contrast**: Bold, large "Feature Text" for headlines, complemented by the clean "Saans" typeface for body content.
*   **Spacious Layout**: Generous use of whitespace, particularly vertical spacing, to create a sense of calm and readability.
*   **Subtle Depth**: Minimal shadows and borders, suggesting a modern, flat-ish design with occasional soft elevation for interactive elements.
*   **Controlled Rounding**: A mix of sharp edges and subtly rounded corners, especially on interactive components like inputs and buttons.
*   **Content-First Approach**: Design elements support the content, with clear visual hierarchy guiding the user through information.
*   **Responsive Adaptability**: Design appears to scale gracefully across various breakpoints, maintaining readability and usability.

## Colors

### Brand & Accent
*   **Brand Primary** (`{colors.brand-primary}` — #f23b0a): A vibrant orange-red used sparingly for key calls-to-action, highlights, and interactive elements to draw attention.
*   **Brand Secondary** (`{colors.brand-secondary}` — #f16055): A slightly softer red-orange, observed in dynamic elements like the "supercharge" text effect.
*   **Brand Tertiary** (`{colors.brand-tertiary}` — #f6ba42): A warm yellow-orange, also used in dynamic "supercharge" text effects.
*   **Brand Quaternary** (`{colors.brand-quaternary}` — #58bd59): A fresh green, complementing the other accents in dynamic effects.
*   **Brand Blue** (`{colors.brand-blue}` — #0073e6): A bright blue, likely used for links or secondary interactive states, derived from a CSS variable.
*   **Brand Peach Light** (`{colors.brand-peach-light}` — #ffeae3): A very light peach tone, potentially for subtle backgrounds or highlights, derived from a CSS variable.

### Surface
*   **Canvas** (`{colors.canvas}` — #fffff9): The primary background color for the page, an off-white with a hint of warmth, providing a clean and inviting base.
*   **White** (`{colors.white}` — #ffffff): Pure white, used for specific background elements or overlays.
*   **Surface Light** (`{colors.surface-light}` — #e8e1d8): A light beige, used for secondary background sections.
*   **Surface Light Alt** (`{colors.surface-light-alt}` — #dcdcd4): A slightly cooler light grey background.
*   **Surface Dark** (`{colors.surface-dark}` — #241e20): A very dark brown-black, used for backgrounds of elements like the banner close button.
*   **Transparent** (`{colors.transparent}` — rgba(0, 0, 0, 0)): Used for backgrounds where content should show through.

### Hairlines & Borders
*   **Border Input** (`{colors.border-input}` — rgba(222, 222, 218, 0.5)): A semi-transparent light grey, used for input field borders.
*   **Border Light** (`{colors.border-light}` — #dcdcdc): A light grey, used for general border elements.
*   **Border Muted** (`{colors.border-muted}` — #86817a): A muted grey, used for less prominent borders.

### Text
*   **Text Primary** (`{colors.text-primary}` — #241e20): The dominant dark brown-black color for most body text and headings, providing strong contrast against light backgrounds.
*   **Text Secondary** (`{colors.text-secondary}` — #252521): A slightly different dark brown-black, used for specific text elements like in carousels and pricing grids.
*   **Text Muted** (`{colors.text-muted}` — #86817a): A medium-dark grey, used for secondary or less emphasized text.
*   **Text Subtle** (`{colors.text-subtle}` — #625d56): A medium grey, for subtle text or supporting information.
*   **Text Dark Alt** (`{colors.text-dark-alt}` — #070707): A near-black, used for high-contrast text.
*   **Text Dark Variant** (`{colors.text-dark-variant}` — #171714): Another dark text variant.
*   **Text Medium Grey** (`{colors.text-medium-grey}` — #57544f): A medium grey for various text uses.
*   **Text On Dark Button** (`{colors.text-on-dark-button}` — #dcdcdc): A light grey, specifically for text on dark-colored buttons.

## Typography

### Font Family
The primary display typeface is "Feature Text", typically paired with "Trebuchet MS" and generic sans-serif as fallbacks. For body and UI elements, the "Saans" typeface is used, with "Verdana", "Avenir Next", and "Helvetica" as common sans-serif fallbacks. This creates a clear distinction between expressive headlines and highly readable body content.

### Hierarchy
| Token                      | Font Family                               | Size     | Weight | Line Height | Letter Spacing | Use                                   |
| :------------------------- | :---------------------------------------- | :------- | :----- | :---------- | :------------- | :------------------------------------ |
| `{typography.display-xxl}` | "Feature Text", "Trebuchet MS", sans-serif | 86.31px  | 700    | 86.31px     | -3.4524px      | Primary page headings (H1)            |
| `{typography.display-xl}`  | "Feature Text", "Trebuchet MS", sans-serif | 72px     | 700    | 72px        | -2.88px        | Large section titles (H2)             |
| `{typography.heading-xl}`  | "Feature Text", Verdana, sans-serif       | 40px     | 400    | 48px        | -1.2px         | Secondary section titles (H2 variant) |
| `{typography.heading-lg}`  | "Feature Text", Georgia, serif            | 24px     | 400    | 24px        | -0.48px        | Component or sub-section headings (H3)|
| `{typography.heading-md}`  | Saans, "Avenir Next", Helvetica, sans-serif | 28px     | 30.24px | -0.28px        | 400            | Smaller section headings (H3 variant) |
| `{typography.body-lg-bold}`| Saans, Verdana, sans-serif                | 16px     | 700    | 24px        | -0.16px        | Emphasized body text, navigation links|
| `{typography.body-lg-medium}`| Saans, Verdana, sans-serif              | 16px     | 500    | 19.2px      | -0.16px        | Medium-weight body text, buttons      |
| `{typography.body-lg}`     | Saans, Verdana, sans-serif                | 16px     | 400    | 22.4px      | -0.16px        | Standard body text                    |
| `{typography.body-lg-normal}`| Saans, "Avenir Next", Helvetica, sans-serif | 16px     | 400    | 22.4px      | normal         | Standard body text (variant)          |
| `{typography.body-md}`     | Saans, "Avenir Next", Helvetica, sans-serif | 15px     | 430    | 20.25px     | normal         | Medium-sized body text, pricing       |
| `{typography.body-sm}`     | Saans, "Avenir Next", Helvetica, sans-serif | 13px     | 400    | 19.24px     | normal         | Small body text, descriptions         |
| `{typography.body-xs}`     | Saans, "Avenir Next", Helvetica, sans-serif | 14px     | 400    | 17.36px     | normal         | Extra-small body text                 |
| `{typography.button-text}` | Saans, Verdana, sans-serif                | 16px     |