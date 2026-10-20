## Overview

Alcazar Energy's visual design communicates a sense of professionalism, stability, and forward-thinking in the renewable energy sector. The identity is built on a clean, modern aesthetic, leveraging a palette of deep blues and grays contrasted with crisp white. Typography relies heavily on the "Public Sans" typeface, which provides excellent readability and a contemporary feel across various weights. Layouts are spacious and structured, utilizing generous padding and clear content separation to guide the user's eye. The overall impression is one of trustworthiness and expertise, avoiding overly flashy elements in favor of a refined and understated approach.

The brand signals its commitment to sustainability through its primary blue hues, which evoke clarity and environmental responsibility. Content is presented in well-defined sections, often within a contained width, ensuring focus and reducing visual clutter. Subtle use of elevation and minimal rounded corners contribute to a polished, digital-first experience.

**Key Characteristics:**
*   **Primary Typeface:** "Public Sans" for all textual content, ensuring consistency.
*   **Color Palette:** Dominance of deep blues (`{colors.brand-primary}` — #0170b9, `{colors.surface-dark-accent}` — #24345a) and dark grays (`{colors.text-primary}` — #222222) against a white canvas.
*   **Layout Philosophy:** Generous whitespace, centered content containers, and clear vertical rhythm.
*   **Hierarchy:** Established through font weight variations (400, 500, 600, 700) and distinct font sizes for headings and body text.
*   **Minimalist Depth:** Subtle shadows provide depth without distracting from content.
*   **Shape Language:** Predominantly sharp corners, with minimal rounding reserved for specific interactive elements or widgets.
*   **Brand Focus:** A clean, corporate, and trustworthy aesthetic suitable for an investment firm.

## Colors

### Brand & Accent
*   **Brand Primary** (`{colors.brand-primary}` — #0170b9): The core brand blue, used for key interactive elements, primary links, and prominent accents.
*   **Brand Secondary** (`{colors.brand-secondary}` — #32bceb): A lighter, more vibrant blue used for secondary accents or highlights.
*   **Accent Light** (`{colors.accent-light}` — #9bc1d7): A muted, light blue used for subtle decorative elements or secondary information.

### Surface
*   **Canvas** (`{colors.canvas}` — #ffffff): The primary background color for the entire page and most content areas.
*   **Surface Dark** (`{colors.surface-dark}` — #293038): A dark gray used for backgrounds of certain sections or components, providing contrast.
*   **Surface Dark Accent** (`{colors.surface-dark-accent}` — #24345a): A deep, rich blue used for prominent dark backgrounds, such as hero sections or footers.
*   **Surface Input** (`{colors.surface-input}` — #fafafa): A very light gray used as the background for input fields.
*   **Surface Subtle** (`{colors.surface-subtle}` — #e5e5e5): A very light gray used for subtle background differentiation or borders.

### Hairlines & Borders
*   **Border Light** (`{colors.border-light}` — #e5e5e5): A light gray used for subtle dividers and borders.
*   **Border Input** (`{colors.border-input}` — #c1c1c1): A light gray used for input field borders.

### Text
*   **Text Primary** (`{colors.text-primary}` — #222222): The main text color for body copy and most headings on light backgrounds.
*   **Text Secondary** (`{colors.text-secondary}` — #5e5e5e): A medium gray used for secondary information, less prominent text, or captions.
*   **Text Muted** (`{colors.text-muted}` — #626e81): A slightly desaturated gray used for less important text, placeholders, or disabled states.
*   **Text Tertiary** (`{colors.text-tertiary}` — #4b4f58): A dark gray, similar to secondary, used for specific text elements.
*   **Text Dark Gray** (`{colors.text-dark-gray}` — #3a3a3a): A dark gray used for specific text elements, slightly lighter than primary.
*   **Text Black** (`{colors.text-black}` — #000000): Pure black, used sparingly for very high contrast elements or specific icons.
*   **Text On Dark** (`{colors.text-on-dark}` — #ffffff): White text used on dark backgrounds for readability.

## Typography

### Font Family
The primary typeface used across the site is **"Public Sans"**, with a generic `sans-serif` fallback. This font is used consistently for all headings, body text, and UI elements, ensuring a unified and modern aesthetic. A very limited instance of "Helvetica, Arial, sans-serif" is observed in a third-party widget, but "Public Sans" defines the site's core typographic voice.

### Hierarchy

| Token                 | Font Family    | Size   | Weight | Line Height | Letter Spacing | Use                                       |
| :-------------------- | :------------- | :----- | :----- | :---------- | :------------- | :---------------------------------------- |
| `{typography.display-xl}` | "Public Sans"  | 56px   | 400    | 72.8px      | normal         | Hero headlines, primary page titles       |
| `{typography.display-lg}` | "Public Sans"  | 36px   | 600    | 46.8px      | normal         | Major section headlines                   |
| `{typography.display-md}` | "Public Sans"  | 32px   | 600    | 41.6px      | normal         | Secondary section headlines               |
| `{typography.heading-1}`  | "Public Sans"  | 20px   | 600    | 24px        | normal         | News titles, prominent subheadings        |
| `{typography.heading-2}`  | "Public Sans"  | 20px   | 400    | 26px        | normal         | General subheadings, section intros       |
| `{typography.body-xl}`    | "Public Sans"  | 20px   | 400    | 30px        | normal         | Lead paragraphs, introductory text        |
| `{typography.body}`       | "Public Sans"  | 16px   | 400    | 26.4px      | normal         | Standard body text, most common           |
| `{typography.body-sm}`    | "Public Sans"  | 16px   | 400    | 24px        | normal         | Slightly tighter body text                |
| `{typography.nav-item}`   | "Public Sans"  | 16px   | 500    | 24px        | normal         | Primary navigation links                  |
| `{typography.nav-item-expanded}` | "Public Sans"  | 16px   | 500    | 26.4px      | normal         | Navigation items in expanded lists        |
| `{typography.label-sm}`   | "Public Sans"  | 16px   | 500    | normal      | normal         | Compact labels, inline menu items         |
| `{typography.caption}`    | "Public Sans"  | 14px   | 400    | 26.4px      | normal         | Dates, metadata, secondary information    |
| `{typography.caption-sm}` | "Public Sans"  | 14px   | 400    | 18.2px      | normal         | Copyright text, small print               |
| `{typography.button-text}`| "Public Sans"  | 12px   | 400    | 12px        | normal         | Call to action text (e.g., "READ MORE")   |
| `{typography.strong}`     | "Public Sans"  | 16px   | 700    | 20.8px      | normal         | Bold emphasis within body text            |
| `{typography.semibold}`   | "Public Sans"  | 16px   | 600    | 20px        | normal         | Semibold emphasis, sub-labels             |

### Principles
The typographic system emphasizes readability and clear hierarchy using "Public Sans". Headings utilize higher font weights (600) and larger sizes to stand out, while body text maintains a comfortable reading experience with a 400 weight and generous line heights. Weight contrast is effectively used to differentiate navigation items (500) and strong emphasis (700) from standard body copy. Letter spacing remains `normal` across the board, contributing to the clean and uncluttered feel.

## Layout

The layout system is built around a flexible spacing scale, with a general rhythm derived from a 4px base unit, though some values deviate slightly. Content is typically constrained within a maximum width of `1365px` (`--ast-normal-container-width`), providing a focused reading experience.

*   **Spacing Scale (4px base):**
    *   `{spacing.xxs}` — 5px: Very small spacing, for tight elements.
    *   `{spacing.xs}` — 10px: Small spacing, for inline elements or minor separation.
    *   `{spacing.sm}` — 15px: Medium-small spacing, for padding within components.
    *   `{spacing.md}` — 16px: Standard spacing unit, common for internal padding.
    *   `{spacing.lg}` — 20px: Larger spacing, for element separation.
    *   `{spacing.xl}` — 24px: Significant spacing, for grouping related items.
    *   `{spacing.xxl}` — 30px: Larger spacing, for component margins.
    *   `{spacing.xxxl}` — 40px: Large spacing, for section sub-elements.
*   **Sectional Spacing:**
    *   `{spacing.section-gap}` — 61px: Vertical separation between major content blocks.
    *   `{spacing.section-padding-sm}` — 106px: Internal vertical padding for smaller sections.
    *   `{spacing.section-padding-md}` — 140px: Internal vertical padding for larger sections.
    *   `{spacing.hero-padding}` — 395px: Very large vertical padding, specifically for hero content areas.
*   **Content Container:** The main content area is centered and has a maximum width of `1365px`, ensuring readability and visual balance on larger screens.
*   **Whitespace Philosophy:** The design embraces ample whitespace around content blocks and within components, contributing to a clean, uncluttered, and professional appearance. This generous spacing enhances readability and helps delineate different sections of information.

## Elevation & Depth

Elevation is used subtly to provide a sense of hierarchy and interaction, primarily through shadows.

*   **Shadow Subtle** (`{shadow.subtle}` — rgba(0, 0, 0, 0.15) 0px 4px 16px 0px): A soft, diffused shadow used for general elevation, such as on cards or interactive elements.
*   **Shadow Inset** (`{shadow.inset}` — rgba(0, 0, 0, 0.15) 0px -2px 12px 0px): A subtle upward shadow, potentially used for sticky elements or elements that appear to be "under" others.
*   **Shadow Outline** (`{shadow.outline}` — rgb(128, 128, 128) 0px 0px 5px 0px): A very faint, tight shadow, possibly used for focus states or very subtle borders.

## Shapes

The design primarily uses sharp, unrounded corners for most elements, conveying a precise and modern aesthetic. Rounding is applied sparingly for specific interactive or decorative elements.

*   **Rounded None** (`{rounded.none}` — 0px): Default for most containers, cards, and structural elements.
*   **Rounded Small** (`{rounded.sm}` — 2px): A very subtle rounding, typically applied to input fields or small interactive elements.
*   **Rounded Large** (`{rounded.lg}` — 40px): A more pronounced rounding, used for specific widgets or distinct UI elements like cookie consent pop-ups.
*   **Rounded Full** (`{rounded.full}` — 9999px): Full pill-shape rounding, used for circular elements or tags.

## Components

### `nav-primary`
The main navigation bar, typically found in the header.
*   **Structure:** A list of text links.
*   **Typography:** `{typography.nav-item}` — "Public Sans", 16px, 500, 24px.
*   **Color:** `{colors.text-primary}` — #222222.
*   **Padding:** Varies, but individual items often have horizontal padding.

### `button-nav-text`
A text-based button used within navigation contexts, often on dark backgrounds.
*   **Structure:** Text label, potentially with an icon.
*   **Typography:** `{typography.label-sm}` — "Public Sans", 16px, 500, normal.
*   **Color:** `{colors.text-on-dark}` — #ffffff.
*   **Background:** Transparent.
*   **Padding:** `0px 10px 0px 0px`.
*   **Border/Shadow:** None.

### `input-text`
Standard text input field, including textareas.
*   **Structure:** A rectangular field with a border.
*   **Typography:** `{typography.body}` — "Public Sans", 16px, 400, 26.4px.
*   **Text Color:** `{colors.text-muted}` — #626e81.
*   **Background:** `{colors.surface-input}` — #fafafa.
*   **Border:** `1px solid {colors.border-input}` — #c1c1c1.
*   **Border Radius:** `{rounded.sm}` — 2px.
*   **Padding:** Not explicitly defined in sample, but typically internal padding would be applied.

### `hero-section`
Large, prominent section at the top of a page, often with background media.
*   **Structure:** Full-width container, often with a video or image background, containing a large headline and introductory text.
*   **Typography (Headline):** `{typography.display-xl}` — "Public Sans", 56px, 400, 72.8px.
*   **Text Color:** Typically `{colors.text-on-dark}` — #ffffff, when on a dark background.
*   **Padding:** Can be very generous, e.g., `{spacing.hero-padding}` — 395px vertical padding.

### `card-content`
A generic container for content, often used in multi-column layouts.
*   **Structure:** A block-level element, often without explicit background or border, serving as a content wrapper.
*   **Background:** Transparent or inherits parent background.
*   **Border/Shadow:** None by default.
*   **Padding:** Varies, can be `0px` or include significant horizontal padding like `54.8px`.
*   **Typography:** Inherits from parent or uses `{typography.body}`.

## Do's and Don'ts

### Do's
*   **Do** use "Public Sans" (`"Public Sans", sans-serif`) for all textual content to maintain brand consistency.
*   **Do** apply `{colors.brand-primary}` — #0170b9 for primary interactive elements and calls to action.
*   **Do** maintain generous line heights, especially for body text (`{typography.body}` — 26.4px), to ensure readability.
*   **Do** use `{spacing.section-gap}` — 61px to clearly separate major content sections vertically.
*   **Do** constrain main content within a `1365px` maximum width, centered on the page.
*   **Do** use `{colors.text-primary}` — #222222 for most body text on light backgrounds, reserving pure black for specific high-contrast needs.
*   **Do** use `{rounded.sm}` — 2px for subtle rounding on interactive elements like input fields.

### Don'ts
*   **Don't** introduce new font families; stick to "Public Sans" for all brand communications.
*   **Don't** use overly bright or saturated colors outside of the defined brand and accent palette.
*   **Don't** use pure black (`{colors.text-black}` — #000000) for large blocks of body text; it's too harsh.
*   **Don't** reduce line heights below the specified values, as it will negatively impact readability.
*   **Don't** apply strong, distracting shadows; prefer the subtle depth provided by `{shadow.subtle}`.
*   **Don't** use excessive or inconsistent border radii; maintain mostly sharp corners with minimal rounding.
*   **Don't** overcrowd content; ensure ample whitespace is maintained around and between elements.

## Responsive Behavior

The design is built with responsiveness in mind, adapting content and layout across different screen sizes.

| Breakpoint | Min Width | Touch Targets | Collapse Strategy