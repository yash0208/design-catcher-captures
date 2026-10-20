## Overview

This website presents a modern, clean, and professional aesthetic, heavily relying on a sophisticated dark-mode-friendly palette and a strong, sans-serif typeface. The visual identity conveys a sense of innovation and efficiency, suitable for a consulting firm focused on logistics and operational challenges. The design emphasizes clear hierarchy and ample whitespace, creating an uncluttered user experience. A vibrant chartreuse accent color provides energetic contrast against the otherwise muted, earthy tones.

**Key Characteristics:**
*   **Muted Earth Tones**: A primary palette of deep charcoal, off-white, and dark teal.
*   **Vibrant Accent**: A striking chartreuse (`{colors.brand-accent}` — #e5f937) for calls to action and highlights.
*   **Strong Typography**: Predominantly "Funnel Sans" for both headings and body text, with "Geist Mono" for data and numerical displays.
*   **Generous Whitespace**: Ample padding and margins create a breathable, premium feel.
*   **Structured Layouts**: Content is organized within clear, often column-based, sections.
*   **Subtle Rounding**: Minor `6px` and `12px` border radii provide a soft touch without being overly rounded.
*   **Minimalist Depth**: Absence of prominent shadows, focusing on flat design principles.
*   **Data-Driven Visuals**: Use of a monospace font for metrics suggests a focus on precision and data.

## Colors

### Brand & Accent
*   **Brand Accent** (`{colors.brand-accent}` — #e5f937): A vibrant chartreuse used for primary calls to action, highlighted elements, and interactive components. It provides a high-contrast pop against the darker surfaces.
*   **Brand Dark** (`{colors.brand-dark}` — #09342b): A deep, dark teal/green, serving as a background for prominent sections and components, often paired with light text.

### Surface
*   **Canvas** (`{colors.canvas}` — #f8f8f3): The primary background color for most light sections of the website, an off-white that feels soft and modern.
*   **Surface Dark** (`{colors.surface-dark}` — #3b3b33): A deep charcoal, used for backgrounds in dark sections, providing a strong contrast for light text.
*   **Surface Subtle** (`{colors.surface-subtle}` — #edede2): A slightly darker off-white, likely used for subtle background variations or secondary containers.
*   **Surface Light** (`{colors.surface-light}` — #fafafa): A very light off-white, used sparingly, possibly for very subtle distinctions.

### Text
*   **Text Primary** (`{colors.text-primary}` — #3b3b33): The main text color for content on light backgrounds, a deep charcoal for readability.
*   **Text Secondary** (`{colors.text-secondary}` — #222222): A slightly darker charcoal, used for more prominent text elements on light backgrounds.
*   **Text Body** (`{colors.text-body}` — #333333): A standard dark gray for general body text.
*   **Text Body Muted** (`{colors.text-body-muted}` — #3b3b33b3): A semi-transparent version of the primary text color, used for less emphasized body copy.
*   **Text On Dark** (`{colors.text-on-dark}` — #f8f8f3): The primary text color when placed on dark backgrounds, matching the `{colors.canvas}` for visual consistency.
*   **Text White** (`{colors.text-white}` — #ffffff): Pure white, used for specific elements or when maximum contrast is needed on very dark backgrounds.

## Typography

### Font Family
The primary typeface for both headings and body text is "Funnel Sans", a clean and modern sans-serif. For numerical data and specific labels, "Geist Mono" is employed, providing a technical and precise feel. "Inter var" is also present in the stylesheet but does not appear to be a primary font in use on the page.

*   **Headings & Body**: "Funnel Sans", Arial, sans-serif
*   **Monospace/Data**: "Geist Mono", "Trebuchet MS", sans-serif

### Hierarchy

| Token                      | Font Family                  | Size   | Weight | Line Height | Letter Spacing | Use                                       |
| :------------------------- | :--------------------------- | :----- | :----- | :---------- | :------------- | :---------------------------------------- |
| `{typography.display-xl}`  | "Geist Mono", "Trebuchet MS", sans-serif | 81px   | 300    | 72.9px      | normal         | Large numerical metrics, impactful stats  |
| `{typography.heading-h1}`  | "Funnel Sans", Arial, sans-serif | 64px   | 400    | 67.2px      | -1.28px        | Primary page titles, hero headlines      |
| `{typography.heading-h2}`  | "Funnel Sans", Arial, sans-serif | 51px   | 400    | 58.65px     | -0.51px        | Section titles, prominent subheadings     |
| `{typography.heading-h3}`  | "Funnel Sans", Arial, sans-serif | 40px   | 400    | 48px        | -0.4px         | Major subheadings, key statements         |
| `{typography.heading-h4}`  | "Funnel Sans", Arial, sans-serif | 32px   | 400    | 38.4px      | normal         | Smaller section titles, feature headings  |
| `{typography.heading-h4-tight}` | "Funnel Sans", Arial, sans-serif | 32px   | 400    | 38.4px      | -0.32px        | Similar to h4, with tighter tracking      |
| `{typography.heading-h5}`  | "Funnel Sans", Arial, sans-serif | 25px   | 400    | 31.25px     | normal         | Minor headings, strong emphasis           |
| `{typography.body-lead-medium}` | "Funnel Sans", Arial, sans-serif | 20px   | 500    | 28px        | normal         | Emphasized lead paragraphs                |
| `{typography.body-lead}`   | "Funnel Sans", Arial, sans-serif | 20px   | 400    | 28px        | normal         | Lead paragraphs, descriptive text         |
| `{typography.body-base}`   | "Funnel Sans", Arial, sans-serif | 16px   | 400    | 22.4px      | normal         | Standard body text, navigation items      |
| `{typography.body-medium}` | "Funnel Sans", Arial, sans-serif | 16px   | 500    | 22.4px      | normal         | Emphasized body text, navigation items    |
| `{typography.label-mono}`  | "Geist Mono", "Trebuchet MS", sans-serif | 13px   | 500    | 18.2px      | normal         | Small labels, metadata, copyright (mono)  |
| `{typography.body-small}`  | "Funnel Sans", Arial, sans-serif | 13px   | 400    | 18.2px      | normal         | Fine print, footer text                   |

### Principles
The typographic system relies on a clear hierarchy established through varying font sizes and weights within the "Funnel Sans" family. Headings utilize a slightly negative letter spacing for a modern, impactful appearance, especially at larger sizes. Body text maintains a comfortable line height for readability. The introduction of "Geist Mono" for specific numerical displays adds a distinct, technical flavor, breaking the sans-serif monotony and highlighting key data points. Weights are generally light (300, 400) or medium (500), avoiding heavy or bold styles for a refined feel.

## Layout

The layout adheres to a structured grid system with a strong emphasis on horizontal and vertical rhythm. A 6px base unit defines the spacing scale, ensuring consistency across elements.

*   **Spacing Scale (6px base):**
    *   `{spacing.xxs}` — 6px
    *   `{spacing.xs}` — 12px
    *   `{spacing.sm}` — 18px
    *   `{spacing.md}` — 24px (used for container gutters)
    *   `{spacing.lg}` — 36px
    *   `{spacing.xl}` — 48px (used for small section padding)
    *   `{spacing.xxl}` — 72px (used for strip heights)
    *   `{spacing.xxxl}` — 96px
    *   `{spacing.section}` — 144px (default section padding)

*   **Container Behavior:** Content is typically constrained within a main container of `{layout.container-main}` — 1366px, with smaller containers for specific column layouts:
    *   `{layout.container-10-cols}` — 1166px
    *   `{layout.container-8-cols}` — 928px
    *   `{layout.container-6-cols}` — 690px
    *   `{layout.container-5-cols}` — 571px
    *   `{layout.container-3-cols}` — 333px
    *   `{layout.container-2-cols}` — 214px
    These containers are centrally aligned, providing consistent margins on either side.

*   **Whitespace Philosophy:** The design embraces generous whitespace, particularly vertical spacing between sections (`{spacing.section}` — 144px) and within components. This creates a sense of openness, improves readability, and allows content to breathe, contributing to the premium and uncluttered aesthetic. Elements are often grouped with ample internal padding, reinforcing visual relationships.

## Elevation & Depth

The design philosophy largely avoids complex elevation and depth effects. There are no explicit shadow tokens defined in the extraction data. The design relies on flat surfaces and strong color contrasts rather than layered elements or subtle drop shadows to create visual hierarchy.

## Shapes

The design incorporates subtle rounding, primarily for interactive elements and content containers, contributing to a modern and approachable feel.

*   **Rounded Small** (`{rounded.sm}` — 6px): Applied to cards, input fields, and some interactive elements like the `flow-item` card.
*   **Rounded Medium** (`{rounded.md}` — 12px): Used for larger containers or more prominent rounded elements.
*   **Rounded Full** (`{rounded.full}` — 50%): Used for perfectly circular elements, such as avatars or small indicators.
*   **Rounded Pill Large** (`{rounded.pill-lg}` — 100px): Used for specific large, pill-shaped elements.
*   **Rounded Pill Extra Large** (`{rounded.pill-xl}` — 200px): Used for specific very large, pill-shaped elements.

## Components

*   **`button-primary`**
    *   **Structure**: Rectangular button with rounded corners.
    *   **Background**: `{colors.brand-accent}` — #e5f937
    *   **Text**: `{colors.text-primary}` — #3b3b33, `{typography.body-medium}` — "Funnel Sans", 16px, 500, 22.4px.
    *   **Padding**: `{spacing.xl}` — 48px horizontal, `{spacing.sm}` — 18px vertical (inferred from button height and padding variables).
    *   **Height**: `{component.button-height}` — 60px.
    *   **Border Radius**: `{rounded.sm}` — 6px.

*   **`button-secondary`** (Inferred, often used on dark backgrounds)
    *   **Structure**: Rectangular button with rounded corners.
    *   **Background**: `{colors.brand-dark}` — #09342b (or transparent with a border).
    *   **Text**: `{colors.text-on-dark}` — #f8f8f3, `{typography.body-medium}` — "Funnel Sans", 16px, 500, 22.4px.
    *   **Padding**: `{spacing.xl}` — 48px horizontal, `{spacing.sm}` — 18px vertical.
    *   **Height**: `{component.button-height}` — 60px.
    *   **Border Radius**: `{rounded.sm}` — 6px.

*   **`nav-link`**
    *   **Structure**: Text link within a navigation menu.
    *   **Text**: `{colors.text-primary}` — #3b3b33, `{typography.body-base}` — "Funnel Sans", 16px, 400, 22.4px.
    *   **Padding**: `0px` (appears as simple text links).

*   **`hero-section`**
    *   **Structure**: Full-width section, often with a dark background and prominent headline.
    *   **Background**: Can vary, often `{colors.brand-dark}` — #09342b or a video background.
    *   **Headline**: `{colors.text-on-dark}` — #f8f8f3, `{typography.heading-h1}` — "Funnel Sans", 64px, 400, 67.2px.
    *   **Body Text**: `{colors.text-on-dark}` — #f8f8f3, `{typography.body-lead}` — "Funnel Sans", 20px, 400, 28px.
    *   **Padding**: `{spacing.section}` — 144px vertical padding, with content constrained by `{layout.container-main}`.

*   **`testimonial-card`**
    *   **Structure**: Content block within a testimonial section, often on a dark background.
    *   **Background**: Transparent, within a `{colors.brand-dark}` — #09342b section.
    *   **Text**: `{colors.text-on-dark}` — #f8f8f3, `{typography.body-base}` — "Funnel Sans", 16px, 400, 22.4px.
    *   **Padding**: Varies, but typically generous. Testimonial section itself has `{spacing.xl}` — 48px vertical padding.

*   **`faq-item`**
    *   **Structure**: Accordion-like item, typically with a question and expandable answer.
    *   **Text**: `{colors.text-primary}` — #3b3b33, `{typography.body-medium}` — "Funnel Sans", 16px, 500, 22.4px for the question.
    *   **Padding**: Internal padding for text, often within a grid structure.

*   **`flow-item-card`**
    *   **Structure**: Small card-like element, often used in a sequence or grid.
    *   **Background**: `{colors.brand-accent}` — #e5f937.
    *   **Text**: `{colors.text-primary}` — #3b3b33, `{typography.body-base}` — "Funnel Sans", 16px, 400, 22.4px.
    *   **Padding**: `{spacing.xxs}` — 6px top/bottom, `{spacing.xs}` — 12px bottom, `{spacing.xxs}` — 6px left/right.
    *   **Border Radius**: `{rounded.sm}` — 6px.

## Do's and Don'ts

*   **Do** use "Funnel Sans" for all primary text elements, and "Geist Mono" exclusively for numerical data or technical labels.
*   **Do** maintain a clear visual hierarchy using the defined typography scale, especially the negative letter spacing for headings like `{typography.heading-h1}` — "Funnel Sans", 64px, -1.28px.
*   **Do** apply `{colors.brand-accent}` — #e5f937 judiciously for primary calls to action and key highlights to maintain its impact.
*   **Do** ensure ample whitespace, utilizing `{spacing.section}` — 144px for major section breaks and `{spacing.md}` — 24px for internal component spacing.
*   **Do** use `{colors.text-primary}` — #3b3b33 on light backgrounds (`{colors.canvas}` — #f8f8f3) and `{colors.text-on-dark}` — #f8f8f3 on dark backgrounds (`{colors.surface-dark}` — #3b3b33 or `{colors.brand-dark}` — #09342b).
*   **Do** apply `{rounded.sm}` — 6px to interactive elements and cards for a consistent, subtle softness.

*   **Don't** introduce new typefaces or weights outside of "Funnel Sans" (400, 500) and "Geist Mono" (300, 500).
*   **Don't** use `{colors.brand-accent}` — #e5f937 for large blocks of text or non-interactive elements, as it can be visually overwhelming.
*   **Don't** deviate from the 6px spacing scale; all padding and margins should be multiples of 6px.
*   **Don't** use shadows or complex depth effects; the design is intentionally flat.
*   **Don't** use pure white (`{colors.text-white}` — #ffffff) for body text unless absolutely necessary for contrast on extremely dark or photographic backgrounds.
*   **Don't** center-align large blocks of text; left-alignment is preferred for readability.

## Responsive Behavior

| Breakpoint | Min Width | Touch Targets | Collapse Strategy