## Overview

The Hallandsposten website presents a clean, content-focused design with a strong emphasis on readability and clear information hierarchy. The visual identity is professional and journalistic, utilizing a classic serif typeface for headlines paired with a modern sans-serif for body text, creating a balanced and authoritative voice. A restrained color palette of dark blues, grays, and white underpins the design, with subtle accents of a brighter blue for interactive elements and a distinct red for urgent news. Layouts prioritize news articles, featuring prominent imagery and clear typographic distinctions for titles, summaries, and metadata. The overall impression is one of trustworthiness and clarity, designed to facilitate efficient consumption of news content.

**Key Characteristics:**
*   **Typographic Contrast:** Strong pairing of "Gothia Serif" for headlines and "Gothia Sans Serif" for body text.
*   **Dominant Dark Palette:** Extensive use of dark blue-gray (`#1e2d37`) and a deeper brand blue (`#0a324b`).
*   **Clean Surfaces:** Predominantly white (`#ffffff`) and light gray (`#f3f3f3`) backgrounds.
*   **Structured Layouts:** Articles and teasers are presented in clear, card-like structures with consistent internal padding.
*   **Minimalist Interactivity:** Interactive elements like navigation links are subtle, often text-based, and use a distinct accent blue.
*   **Subtle Depth:** Shadows are used sparingly, primarily to indicate elevated elements or focus.
*   **Content-First Approach:** Visual elements support, rather than distract from, the journalistic content.
*   **Responsive Adaptation:** Design scales gracefully across various breakpoints, maintaining readability.

## Colors

### Brand & Accent
*   **Brand Primary Dark** (`{colors.brand-primary-dark}` — #0a324b): A deep, rich blue used for significant background areas like the footer, and occasionally for borders or strong textual elements.
*   **Brand Accent** (`{colors.brand-accent}` — #0a5582): A vibrant blue used for interactive elements, links, and highlights, drawing attention to clickable areas.
*   **Black** (`{colors.black}` — #000000): Pure black, used sparingly for very strong emphasis or specific brand elements like the `--tt-brand` variable suggests.

### Surface
*   **Canvas** (`{colors.canvas}` — #ffffff): The primary background color for most content areas and cards, providing a clean, bright surface.
*   **Canvas Light** (`{colors.canvas-light}` — #f3f3f3): A very light gray used for subtle background variations, such as in long-read footers, to differentiate sections.
*   **Surface Dark** (`{colors.surface-dark}` — #1e2d37): A dark blue-gray, sometimes used as a background for certain sections, providing contrast to lighter text.
*   **Surface Footer** (`{colors.surface-footer}` — #0a324b): Specifically identified as the background for the site's footer.
*   **Surface Overlay Subtle** (`{colors.surface-overlay-subtle}` — rgba(0,0,0,0.05)): A semi-transparent dark overlay, likely used for subtle hover effects or background dimming.

### Hairlines & Borders
*   **Border Primary** (`{colors.border-primary}` — #1e2d37): A dark blue-gray used for general borders, providing structure and separation.
*   **Border Secondary** (`{colors.border-secondary}` — #526066): A muted gray-blue, used for less prominent borders or dividers.
*   **Border Hairline** (`{colors.border-hairline}` — #9eacb2): A light, desaturated blue-gray for fine lines and subtle dividers, such as in menus.

### Text
*   **Text Primary** (`{colors.text-primary}` — #1e2d37): The dominant text color for body copy, headings, and general content on light backgrounds.
*   **Text Secondary** (`{colors.text-secondary}` — #526066): A muted gray-blue for secondary information, metadata, or less prominent text.
*   **Text On Dark** (`{colors.text-on-dark}` — #ffffff): Inferred white text color used on dark backgrounds, such as the footer, for optimal contrast and readability.

### Semantic
*   **Semantic Breaking News** (`{colors.semantic-breaking-news}` — #bd1800): A distinct red color used to highlight urgent or breaking news content.
*   **Semantic Link** (`{colors.semantic-link}` — #2451c6): A specific blue for standard hyperlinks, distinct from the brand accent blue.

## Typography

### Font Family
The primary typeface for body text and UI elements is **"Gothia Sans Serif"**, which is a sans-serif font, accompanied by a robust fallback stack: `-apple-system, "system-ui", "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji"`. For headlines and display text, the site employs **"Gothia Serif"**, a serif typeface, with `serif` as its fallback. This pairing creates a classic yet modern journalistic feel, with the serif providing gravitas for headlines and the sans-serif ensuring high readability for longer passages.

### Hierarchy

| Token                 | Font Family       | Size   | Weight | Line Height | Letter Spacing | Use                                   |
| :-------------------- | :---------------- | :----- | :----- | :---------- | :------------- | :------------------------------------ |
| `{typography.display-xl}` | "Gothia Serif"    | 42px   | 700    | 50.4px      | normal         | Main article headlines, prominent titles |
| `{typography.display-lg}` | "Gothia Serif"    | 27.008px | 700    | 32.4096px   | normal         | Secondary article headlines, large subheadings |
| `{typography.display-lg-light}` | "Gothia Serif"    | 27.008px | 400    | 32.4096px   | normal         | Secondary article headlines, lighter variant |
| `{typography.display-md}` | "Gothia Serif"    | 24px   | 500    | 28.8px      | normal         | Section titles, medium headlines      |
| `{typography.heading-lg}` | "Gothia Sans Serif" | 24px   | 600    | 28.8px      | normal         | Section titles, bold sans-serif       |
| `{typography.heading-lg-light}` | "Gothia Sans Serif" | 24px   | 400    | 28.8px      | normal         | Section titles, lighter sans-serif    |
| `{typography.heading-sm}` | "Gothia Serif"    | 16px   | 600    | 19.2px      | normal         | Small article titles, emphasized text |
| `{typography.body-lg-bold}` | "Gothia Sans Serif" | 17.008px | 700    | 21.5435px   | normal         | Emphasized body text, lead paragraphs |
| `{typography.body-lg}` | "Gothia Sans Serif" | 17.008px | 400    | 21.5435px   | normal         | Lead paragraphs, slightly larger body text |
| `{typography.body-strong}` | "Gothia Sans Serif" | 16px   | 700    | 24px        | normal         | Strong emphasis in body, navigation items |
| `{typography.body-bold}` | "Gothia Sans Serif" | 16px   | 700    | 20.8px      | normal         | Bold text, timestamps, short labels   |
| `{typography.body-medium}` | "Gothia Sans Serif" | 16px   | 500    | 20.8px      | normal         | Medium weight body text, navigation links |
| `{typography.body-base}` | "Gothia Sans Serif" | 16px   | 400    | 24px        | normal         | Standard body text, general UI elements |
| `{typography.label-bold}` | "Gothia Sans Serif" | 14px   | 900    | 18.2px      | normal         | Uppercase labels, strong callouts     |
| `{typography.caption}` | "Gothia Sans Serif" | 12px   | 500    | 15.6px      | normal         | Image captions, metadata, small print |

### Principles
The typographic system leverages a clear contrast between serif and sans-serif typefaces to establish hierarchy and tone. "Gothia Serif" is reserved for impactful headlines, conveying authority and journalistic tradition, often in bold weights. "Gothia Sans Serif" serves as the workhorse, ensuring high legibility for extensive body copy and UI elements, with varying weights (400, 500, 700) to denote importance without resorting to excessive size changes. Letter spacing remains `normal` throughout, prioritizing natural reading flow. The hierarchy is well-defined, guiding the reader's eye through content from large, bold headlines to smaller, informative captions.

## Layout

The layout system is built on a foundational spacing scale of 4px, providing granular control and consistent rhythm. Content is primarily presented within a main container, with articles and sections often occupying a significant width, allowing for prominent display of imagery and text.

*   **Spacing Scale:**
    *   `{spacing.xxs}` — 4px
    *   `{spacing.xs}` — 8px
    *   `{spacing.sm-12}` — 12px
    *   `{spacing.sm}` — 16px
    *   `{spacing.md}` — 24px
*   **Container Behavior:** Main content areas appear to be constrained to a maximum width, centered on the page, with consistent horizontal padding (`{spacing.sm}` — 16px) on smaller viewports.
*   **Grid System:** Content is often arranged in vertical stacks of articles or teasers, with implicit grid-like structures for related content blocks (e.g., "Utvalda klipp" section showing multiple items side-by-side).
*   **Whitespace Philosophy:** Ample whitespace is used to separate content blocks and improve readability. Vertical spacing between articles and sections is generous, often using `{spacing.sm}` — 16px or larger, to prevent visual clutter and create a sense of calm. Internal padding within components like cards is consistently `{spacing.sm}` — 16px.

## Elevation & Depth

The design employs subtle elevation to highlight interactive elements or distinguish content blocks.

*   **Shadow Medium** (`{shadow.md}` — rgba(0, 0, 0, 0.2) 0px 8px 16px 0px): A soft, diffused shadow used to give a sense of depth, likely applied to modals, dropdowns, or perhaps certain interactive cards upon hover/focus (though hover states are not documented). It is observed on a limited number of elements, suggesting it's reserved for specific interactive or prominent components.

## Shapes

The design primarily uses subtle rounding for UI elements, maintaining a clean and modern aesthetic.

*   **Rounded Small** (`{rounded.sm}` — 2px): A very slight curve, used for subtle softening of corners on smaller interactive elements or input fields.
*   **Rounded Medium** (`{rounded.md}` — 4px): A more noticeable but still gentle curve, applied to buttons or cards.
*   **Rounded Large** (`{rounded.lg}` — 30px): A larger radius, likely for specific, more decorative elements or larger buttons/tags.
*   **Rounded Full** (`{rounded.full}` — 50%): Used for perfectly circular elements, such as avatars or small icons.

## Components

*   `button-text`
    *   **Structure**: Text-only button, often used for navigation or secondary actions.
    *   **Colors**: Text color `{colors.brand-primary-dark}` — #0a324b. Background is transparent.
    *   **Typography**: `{typography.body-medium}` — "Gothia Sans Serif", 16px, 500, 20.8px.
    *   **Padding**: `0px`.
    *   **Radius**: `{rounded.none}` — 0px.
    *   **Border**: `none`.
    *   **Shadow**: `none`.

*   `nav-main`
    *   **Structure**: Horizontal navigation bar, typically at the top of the page.
    *   **Colors**: Text color `{colors.text-primary}` — #1e2d37. Background is transparent.
    *   **Typography**: `{typography.body-base}` — "Gothia Sans Serif", 16px, 400, 24px.
    *   **Padding**: `0px 0px 0px {spacing.sm}` — 16px.
    *   **Radius**: `{rounded.none}` — 0px.
    *   **Border**: `none`.
    *   **Shadow**: `none`.

*   `footer`
    *   **Structure**: Site-wide footer section.
    *   **Colors**: Background `{colors.surface-footer}` — #0a324b. Text color `{colors.text-on-dark}` — #ffffff (inferred).
    *   **Typography**: `{typography.body-base}` — "Gothia Sans Serif", 16px, 400, 24px.
    *   **Padding**: `0px` (internal content likely has its own padding).
    *   **Radius**: `{rounded.none}` — 0px.
    *   **Border**: `none`.
    *   **Shadow**: `none`.

*   `section-hero`
    *   **Structure**: A prominent content section, often at the top of a page, featuring a main article or set of teasers.
    *   **Colors**: Background `{colors.canvas}` — #ffffff. Text color `{colors.text-primary}` — #1e2d37.
    *   **Typography**: Varies based on content, but typically uses `{typography.display-xl}` for main headlines.
    *   **Padding**: `0px`.
    *   **Border**: `none`.
    *   **Shadow**: `none`.

*   `carousel`
    *   **Structure**: A horizontal scrolling container for multiple items.
    *   **Colors**: Background transparent. Text color `{colors.text-primary}` — #1e2d37.
    *   **Typography**: Varies based on item content, often `{typography.body-base}` or `{typography.body-medium}`.
    *   **Padding**: `0px {spacing.sm}` — 16px.
    *   **Radius**: `{rounded.none}` — 0px.
    *   **Border**: `none`.
    *   **Shadow**: `none`.

*   `card-article`
    *   **Structure**: A container for individual articles or teasers, often with an image and text.
    *   **Colors**: Background `{colors.surface-card}` — #ffffff. Text color `{colors.text-primary}` — #1e2d37.
    *   **Typography**: Varies, but typically uses `{typography.display-lg}` or `{typography.heading-sm}` for titles and `{typography.body-base}` for summaries.
    *   **Padding**: `{spacing.sm}` — 16px.
    *   **Radius**: `{rounded.none}` — 0px.
    *   **Border**: `none`.
    *   **Shadow**: `none`.

## Do's and Don'ts

**Do's:**
*   **Do** use "Gothia Serif" for all primary headlines and titles to maintain a strong, authoritative voice.
*   **Do** ensure body text uses "Gothia Sans Serif" at `{typography.body-base}` — 16px, 400, 24px for optimal readability.
*   **Do** apply `{colors.text-primary}` — #1e2d37 for text on light backgrounds and `{colors.text-on-dark}` — #ffffff for text on dark backgrounds.
*   **Do** maintain consistent vertical spacing between content blocks using `{spacing.sm}` — 16px or `{spacing.md}` — 24px.
*   **Do** use `{colors.brand-accent}` — #0a5582 for interactive links and buttons to clearly indicate functionality.
*   **Do** use `{shadow.md}` — rgba(0, 0, 0, 0.2) 0px 8px 16px 0px sparingly for elements requiring subtle elevation, such as dropdowns or modals.
*   **Do** use `{colors.semantic-breaking-news}` — #bd1800 to highlight critical news alerts or breaking stories.

**Don'ts:**
*   **Don't** use "Gothia Serif" for extensive body copy; it is reserved for headlines.
*   **Don't** introduce new font families or weights outside of the defined typographic scale.
*   **Don't** use `{colors.brand-primary-dark}` — #0a324b as a text color on dark backgrounds, as it will lack sufficient contrast.
*   **Don't** deviate from the 4px-based spacing scale; avoid arbitrary pixel values for padding and margins.
*   **Don't** apply shadows to every component; reserve `{shadow.md}` for elements that truly need to stand out or indicate interactivity.
*   **Don't** use `{rounded.full}` for general UI elements; it is specifically for circular shapes like avatars.
*   **Don't** use `{colors.semantic-link}` — #2451c6 for general UI accents; it is specifically for standard hyperlinks.

## Responsive Behavior

| Breakpoint | Min Width | Touch Targets                               | Collapse Strategy