## Overview

The Divided by 13 Amplifiers website presents a robust and premium visual identity, blending classic craftsmanship with a modern, technical edge. The design is characterized by a strong contrast between its two primary typefaces: the bold, expressive "Bulevar" for headlines and the precise, monospace "Chivo Mono" for body content and functional elements. A rich, earthy color palette centers around deep charcoal, warm amber, and soft ivory, evoking both vintage audio equipment and contemporary design. Layouts are clean and spacious, utilizing generous padding and full-width sections to create a sense of solidity and focus on product imagery. The overall impression is one of quality, attention to detail, and a confident brand presence.

**Key Characteristics**:
*   **Typeface Pairing**: Bold "Bulevar" for display, technical "Chivo Mono" for body.
*   **Color Palette**: Dominant use of `{colors.charcoal-900}` — #161616, `{colors.amber-600}` — #bf862b, and `{colors.ivory-100}` — #f6f0df.
*   **Spacious Layout**: Generous vertical and horizontal padding, creating a breathable feel.
*   **High Contrast**: Strong visual hierarchy achieved through color and typography contrast.
*   **Minimalist Detailing**: Focus on core content and product, with minimal decorative elements.
*   **Monochromatic Text**: Primary text is either dark on light or light on dark, with limited accent colors for text.
*   **Full-width Sections**: Sections often span the full viewport width, creating distinct content blocks.

## Colors

### Brand & Accent
*   **Amber 600** (`{colors.amber-600}` — #bf862b): Used as the primary brand accent color, notably for calls-to-action, the main footer background, and interactive elements. It provides warmth and visual emphasis.

### Surface
*   **Charcoal 900** (`{colors.charcoal-900}` — #161616): The dominant dark background color for many sections, including the header, navigation, and product showcases. It provides a deep, sophisticated base.
*   **Charcoal 800** (`{colors.charcoal-800}` — #292927): A slightly lighter shade of charcoal, used for specific dark backgrounds.
*   **Ivory 100** (`{colors.ivory-100}` — #f6f0df): The primary light background color, serving as the canvas for introductory sections and general body content. It offers a soft, warm contrast to the dark elements.
*   **Ivory 50** (`{colors.ivory-50}` — #fffbef): A very light, almost off-white background used sparingly for subtle variations.
*   **Hero Background** (`{colors.hero-background}` — #ddd9cd): A light, muted grey-beige used specifically for the hero section background, providing a neutral base for the headline.

### Hairlines & Borders
*   **Border Light** (`{colors.border-light}` — #d0c9b7): A light, desaturated beige used for subtle borders and dividers, often on light backgrounds.
*   **Border Medium** (`{colors.border-medium}` — #a39a80): A slightly darker, more prominent beige-grey for borders where more definition is needed.
*   **Black** (`{colors.black}` — #000000): Used for very distinct borders or as a pure black background in specific, limited contexts.

### Text
*   **Text Primary** (`{colors.text-primary}` — #161616): The default text color used on light backgrounds.
*   **Text On Dark** (`{colors.text-on-dark}` — #ffffff): Pure white text used primarily on dark backgrounds like `{colors.charcoal-900}`.
*   **Text Muted** (`{colors.text-muted}` — #666666): A medium grey used for secondary or less prominent text, often for descriptions or metadata.
*   **Text On Charcoal** (`{colors.text-on-charcoal}` — #fcf7e8): A very light, warm off-white used for text on dark backgrounds, particularly in the marquee component, offering a softer contrast than pure white.

## Typography

### Font Family
The design utilizes two distinct font families:
*   **Display**: "Bulevar", sans-serif. This typeface is used for all major headings and display text, providing a strong, classic, and impactful presence.
*   **Body & UI**: "Chivo Mono", monospace. This font is used for all body text, navigation, labels, and detailed information, contributing a precise, technical, and modern feel. The full fallback stack is `"Chivo Mono", monospace`.

### Hierarchy

| Token                 | Font Family | Size   | Weight | Line Height | Letter Spacing | Use                                       |
| :-------------------- | :---------- | :----- | :----- | :---------- | :------------- | :---------------------------------------- |
| `{typography.display-xl}` | Bulevar     | 200px  | 800    | 160px       | 0.8px          | Hero headline                             |
| `{typography.display-lg}` | Bulevar     | 100px  | 400    | 126px       | normal         | Major section titles (e.g., "Amplifiers") |
| `{typography.display-md}` | Bulevar     | 72px   | 400    | 82px        | normal         | Product names (e.g., "BW 1969")           |
| `{typography.display-sm}` | Bulevar     | 50px   | 400    | 50px        | normal         | Marquee text                              |
| `{typography.display-xs}` | Bulevar     | 30px   | 400    | 30px        | normal         | Sub-section titles (e.g., "Amps" in footer) |
| `{typography.body-xl}`    | Chivo Mono  | 22px   | 400    | 32px        | normal         | Main navigation, general body text        |
| `{typography.body-lg}`    | Chivo Mono  | 16px   | 600    | 22px        | 1.28px         | Primary call-to-action buttons            |
| `{typography.body-md}`    | Chivo Mono  | 14px   | 400    | 22px        | normal         | Product specifications, detailed text     |
| `{typography.body-sm-bold}` | Chivo Mono  | 12px   | 700    | 17px        | 1.2px          | Labels, emphasized small text             |
| `{typography.body-sm}`    | Chivo Mono  | 12px   | 400    | 13.2px      | normal         | Small descriptions, secondary info        |
| `{typography.body-xs}`    | Chivo Mono  | 12px   | 400    | 12px        | normal         | Very small utility text                   |
| `{typography.body-xxs}`   | Chivo Mono  | 13px   | 400    | 14.3px      | normal         | Instagram post counts                     |

### Principles
The typographic system leverages a clear division of roles between its two typefaces. "Bulevar" is reserved for high-impact, large-scale headlines, often set in a regular weight, conveying a sense of established quality. "Chivo Mono" provides the functional backbone, offering excellent readability for body copy and UI elements. Weight contrast within "Chivo Mono" is used sparingly but effectively, with bold weights highlighting labels and a slightly heavier weight for primary CTAs, often accompanied by increased letter spacing for emphasis. The overall hierarchy is strong, guiding the user's eye through content with distinct visual cues.

## Layout

The layout philosophy emphasizes spaciousness and clear content separation. A consistent content width is maintained through a dynamic container padding, defined as `8vw`, which resolves to `{spacing.section-outer}` — 92px on the current viewport. Sections often span the full width of the viewport, creating strong visual blocks.

**Spacing Scale (4px base for smaller increments, larger values are direct)**:
*   `{spacing.xxs}` — 2px: Minimal spacing, often for tight internal element separation.
*   `{spacing.xs}` — 4px: Smallest common spacing unit.
*   `{spacing.sm}` — 6px: Small spacing for internal component elements.
*   `{spacing.md}` — 10px: Medium spacing, used for padding within smaller containers or between inline elements.
*   `{spacing.lg}` — 16px: Larger spacing for list items or small component margins.
*   `{spacing.xl}` — 18px: Standard spacing for elements like form fields or card content.
*   `{spacing.2xl}` — 32px: Generous internal padding within components or between minor sections.
*   `{spacing.3xl}` — 36px: Significant vertical spacing between content blocks or major component padding.
*   `{spacing.section-gap}` — 45px: Gap between items in a grid or carousel.
*   `{spacing.section-gap-lg}` — 50px: Larger gap for grid layouts.
*   `{spacing.section-inner}` — 54px: Internal padding for content within a section.
*   `{spacing.section-outer}` — 92px: Primary horizontal padding for main content areas, equivalent to `--container-padding`.
*   `{spacing.header-height}` — 103px: Fixed height for the main header.
*   `{spacing.hero-content-offset}` — 173px: Specific padding used within the hero section to position content.
*   `{spacing.huge}` — 431px: Very large margin, likely for specific content alignment or visual breaks.

Whitespace is used generously, particularly vertically, to create distinct content sections and prevent visual clutter. Content is generally left-aligned within its container, but large display elements can be centered or span across the layout.

## Elevation & Depth

The design does not utilize explicit shadow tokens. Elements appear flat against their backgrounds, relying on color contrast and clear boundaries for separation rather than simulated depth.

## Shapes

The design primarily uses sharp, unrounded corners for most elements, reinforcing a precise and structured aesthetic.
*   **Full Circle** (`{rounded.full}` — 50%): Used for perfectly circular elements, such as potential avatars or iconography.
*   **Large Decorative Radius** (`{rounded.xl}` — 120px): A very large radius observed on specific decorative elements, suggesting a deliberate, non-functional rounding for visual interest.

## Components

*   **`button-primary`**:
    *   **Structure**: A text label within a solid background.
    *   **Background**: `{colors.amber-600}` — #bf862b.
    *   **Text Color**: `{colors.charcoal-900}` — #161616.
    *   **Typography**: `{typography.body-lg}` (Chivo Mono, 16px, 600, 22px line-height, 1.28px letter-spacing).
    *   **Padding**: Not explicitly extracted, but appears generous horizontally.
    *   **Border Radius**: None (sharp corners).
*   **`nav-item`**:
    *   **Structure**: Simple text link.
    *   **Text Color**: `{colors.text-primary}` — #161616.
    *   **Typography**: `{typography.body-xl}` (Chivo Mono, 22px, 400, 32px line-height).
    *   **Padding**: Minimal, typically `{spacing.md}` — 10px or `{spacing.xl}` — 18px around text.
*   **`hero-headline`**:
    *   **Structure**: Large, impactful text block.
    *   **Text Color**: `{colors.ivory-100}` — #f6f0df.
    *   **Typography**: `{typography.display-xl}` (Bulevar, 200px, 800, 160px line-height, 0.8px letter-spacing).
*   **`marquee-text`**:
    *   **Structure**: Horizontally scrolling text.
    *   **Background**: `{colors.charcoal-900}` — #161616.
    *   **Text Color**: `{colors.text-on-charcoal}` — #fcf7e8.
    *   **Typography**: `{typography.display-sm}` (Bulevar, 50px, 400, 50px line-height).
*   **`amp-card-title`**:
    *   **Structure**: Product title within a product showcase.
    *   **Text Color**: `{colors.text-on-dark}` — #ffffff.
    *   **Typography**: `{typography.display-md}` (Bulevar, 72px, 400, 82px line-height).
*   **`amp-card-spec-label`**:
    *   **Structure**: Label for a product specification.
    *   **Text Color**: `{colors.text-on-dark}` — #ffffff.
    *   **Typography**: `{typography.body-sm-bold}` (Chivo Mono, 12px, 700, 17px line-height, 1.2px letter-spacing).
*   **`amp-card-spec-value`**:
    *   **Structure**: Value for a product specification.
    *   **Text Color**: `{colors.text-on-dark}` — #ffffff.
    *   **Typography**: `{typography.body-md}` (Chivo Mono, 14px, 400, 22px line-height).
*   **`footer-section`**:
    *   **Structure**: Full-width section at the bottom of the page.
    *   **Background**: `{colors.amber-600}` — #bf862b.
    *   **Text Color**: Primarily `{colors.charcoal-900}` — #161616 for headings and links.
    *   **Typography**: Mix of `{typography.display-xs}` and `{typography.body-xl}`.

## Do's and Don'ts

**Do's**:
*   **Do** use "Bulevar" exclusively for all display-level headings (`{typography.display-xl}` through `{typography.display-xs}`).
*   **Do** use "Chivo Mono" for all body text, navigation, labels, and detailed product information.
*   **Do** use `{colors.amber-600}` — #bf862b as the primary accent color for calls to action and key interactive elements.
*   **Do** maintain generous vertical spacing between major content sections, using values like `{spacing.section-inner}` — 54px or greater.
*   **Do** ensure high contrast between text and background, using `{colors.text-primary}` — #161616 on light backgrounds and `{colors.text-on-dark}` — #ffffff or `{colors.text-on-charcoal}` — #fcf7e8 on dark backgrounds.
*   **Do** apply `{spacing.section-outer}` — 92px as horizontal padding for main content areas within full-width sections.
*   **Do** use sharp, unrounded corners for most UI elements to maintain a precise aesthetic.

**Don'ts**:
*   **Don't** use "Bulevar" for body text or small UI elements; it is strictly for display purposes.
*   **Don't** use "Chivo Mono" for major headlines or section titles; reserve "Bulevar" for these.
*   **Don't** introduce new accent colors; stick to the established palette, especially `{colors.amber-600}` — #bf862b.
*   **Don't** use shadows for depth; the design relies on flat elements and color contrast.
*   **Don't** use pure black text (`#000000`) on `{colors.charcoal-900}` — #161616 backgrounds, as it lacks sufficient contrast.
*   **Don't** apply excessive border radii; most elements should have sharp corners unless specifically using `{rounded.full}` or `{rounded.xl}` for decorative purposes.

## Responsive Behavior

The design is built with a clear set of breakpoints to adapt content across various screen sizes.

| Breakpoint | Min Width | Touch Targets | Collapse Strategy