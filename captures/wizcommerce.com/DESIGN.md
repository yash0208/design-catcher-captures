## Overview

The WizCommerce website presents a modern and professional aesthetic, primarily targeting B2B wholesale distributors. The design emphasizes clarity, efficiency, and a forward-thinking approach, reflected in its clean layouts and strategic use of color. A dominant brand orange provides energetic accents against a largely neutral palette of dark grays, blacks, and off-whites. Typography plays a significant role, combining a contemporary sans-serif for body text and a distinctive serif for display headings, creating a sophisticated yet approachable feel. The overall impression is one of a reliable, innovative technology solution.

**Key Characteristics:**
*   **Brand Accent Color**: A vibrant orange (`{colors.brand-primary}` — #fd8143) used for call-to-action elements and key highlights.
*   **Clean & Minimal Surfaces**: Predominantly light backgrounds (`{colors.canvas-light}` — #fafafa) with dark text for high readability.
*   **Dual Typeface Strategy**: "General Sans" for functional text and "Recife Text TEST" for impactful headlines.
*   **Generous Whitespace**: Ample padding and margins create a sense of openness and reduce visual clutter.
*   **Subtle Depth**: Minimal use of shadows suggests hierarchy without heavy visual distraction.
*   **Structured Layouts**: Content is organized within clear sections, often with centered or left-aligned text blocks.
*   **Monochromatic Dark Palette**: Darker shades of gray and black are used for primary text and some background elements, creating contrast.
*   **Monospace for Labels**: "Geist Mono" provides a technical, precise feel for small labels and metadata.

## Colors

### Brand & Accent
*   **Primary Brand** (`{colors.brand-primary}` — #fd8143): Used for primary call-to-action buttons, interactive elements, and key highlights. It provides a warm, energetic accent.
*   **Secondary Brand** (`{colors.brand-secondary}` — #ff844f): A slightly softer orange, observed in specific section backgrounds, offering a complementary brand hue.

### Surface
*   **Canvas** (`{colors.canvas}` — #ffffff): Pure white, used as a background for cards, modals, and other elevated surfaces.
*   **Canvas Light** (`{colors.canvas-light}` — #fafafa): The primary background color for the overall page, providing a clean, almost-white base.
*   **Surface Accent Light** (`{colors.surface-accent-light}` — #f9c597): A pale, warm background color used for specific content blocks or sections, adding subtle variation.
*   **Surface Accent Pale** (`{colors.surface-accent-pale}` — #f1e1cd): An even lighter, warmer background, likely for subtle distinctions.
*   **Surface Pale** (`{colors.surface-pale}` — #e7e2dc): A very light, desaturated background color.
*   **Surface Dark 1** (`{colors.surface-dark-1}` — #1f2124): A very dark gray, used for some text or background elements that require high contrast.
*   **Surface Dark 2** (`{colors.surface-dark-2}` — #222525): A slightly different shade of very dark gray, similar to `surface-dark-1`.
*   **Surface Dark 3** (`{colors.surface-dark-3}` — #2c2c2b): Another dark gray, used for text or background elements.
*   **Surface Dark Contrast** (`{colors.surface-dark-contrast}` — #00040f): An almost black, very dark background color for high-contrast sections.

### Hairlines & Borders
*   **Border Light** (`{colors.border-light}` — #dfdfdf): A light gray used for subtle separators, outlines, and inactive states.
*   **Border Medium** (`{colors.border-medium}` — #c4c4c4): A slightly darker gray for more prominent borders.
*   **Border Dark** (`{colors.border-dark}` — #282441): A dark, desaturated purple-gray, used for borders in darker contexts.
*   **Border Dark Contrast** (`{colors.border-dark-contrast}` — #020801): An almost black border color for strong separation.
*   **Border Pale** (`{colors.border-pale}` — #ede9de): A very light, warm border color.
*   **Border Info** (`{colors.border-info}` — #3f5fac): A blue-gray border, potentially for informational elements.

### Text
*   **Text Primary** (`{colors.text-primary}` — #000000): The main color for body text, headings, and most content, ensuring high readability.
*   **Text Secondary** (`{colors.text-secondary}` — #111111): A slightly lighter black, used for secondary text, subheadings, or less emphasized content.
*   **Text On Dark** (`{colors.text-on-dark}` — #ffffff): White text used on dark backgrounds for optimal contrast.
*   **Text Dark Contrast** (`{colors.text-dark-contrast}` — #040214): A very dark, almost black text color, used for high contrast on light backgrounds.

### Semantic
*   **Semantic Success** (`{colors.semantic-success}` — #1fbf5b): A vibrant green, likely for success messages or positive indicators.
*   **Semantic Purple** (`{colors.semantic-purple}` — #9939eb): A bright purple, potentially used for specific highlights or interactive elements.

## Typography

### Font Family
The primary typeface for body text and functional elements is "General Sans", a clean and modern sans-serif font, with `sans-serif` as a fallback. For display headings and prominent titles, the site uses "Recife Text TEST", a distinctive serif font that adds character and sophistication. A monospace font, "Geist Mono", is utilized for small labels and technical-looking text, with `monospace` as a fallback. Finally, "Poppins" is used for some call-to-action buttons, with `Arial, sans-serif` as fallbacks.

### Hierarchy
| Token                       | Font Family           | Size        | Weight | Line Height | Letter Spacing | Use                                          |
| :-------------------------- | :-------------------- | :---------- | :----- | :---------- | :------------- | :------------------------------------------- |
| `{typography.display-xl}`   | "Recife Text TEST"    | 46px        | 300    | 54px        | -2.59px        | Hero headlines, large impactful statements   |
| `{typography.display-lg}`   | "Recife Text TEST"    | 46px        | 300    | 54px        | -1.2px         | Section headlines, prominent quotes          |
| `{typography.heading-xl}`   | "Recife Text TEST"    | 26px        | 300    | 34px        | -0.2px         | Sub-headlines, image box titles              |
| `{typography.heading-lg}`   | "General Sans"        | 24px        | 400    | 32px        | normal         | Section titles                               |
| `{typography.heading-lg-serif}` | "Recife Text TEST"    | 24px        | 300    | 32px        | -0.2px         | Section titles (serif variant)               |
| `{typography.heading-md}`   | "General Sans"        | 20px        | 600    | 26px        | normal         | Report titles, accordion titles              |
| `{typography.heading-sm}`   | "General Sans"        | 20px        | 500    | 28px        | 0.3px          | Feature titles, accordion titles             |
| `{typography.body-md}`      | "General Sans"        | 16px        | 400    | 24px        | normal         | Standard body text, navigation items         |
| `{typography.body-md-semibold}` | "General Sans"        | 16px        | 500    | 24px        | 0.4px          | Product names, emphasized body text          |
| `{typography.button-link}`  | "General Sans"        | 16px        | 500    | 28px        | -0.1px         | "Learn more" links                           |
| `{typography.body-sm}`      | "General Sans"        | 14px        | 400    | 22px        | 0.5px          | Smaller body text, descriptive labels        |
| `{typography.button-sm}`    | "General Sans"        | 13px        | 500    | 18px        | 0.5px          | Small buttons, login links                   |
| `{typography.label-sm}`     | "General Sans"        | 13px        | 500    | 19.5px      | 0.4px          | Small labels, product categories             |
| `{typography.link-sm}`      | "General Sans"        | 12px        | 500    | 12px        | normal         | Small links (e.g., "View report")            |
| `{typography.label-mono-bold}` | "Geist Mono"          | 12px        | 600    | 18px        | 1px            | Monospace labels, brand elements             |
| `{typography.caption-mono}` | "Geist Mono"          | 10px        | 500    | 19px        | normal         | Small, technical captions                    |
| `{typography.label-uppercase-mono}` | "monospace"           | 11px        | 700    | 11px        | 1px            | Uppercase monospace labels (e.g., "NOW LIVE") |
| `{typography.button-primary-lg}` | "Poppins"             | 28px        | 500    | normal      | normal         | Large primary CTA button                     |
| `{typography.button-primary-md}` | "Poppins"             | 19.7157px   | 600    | 23.6588px   | 0.5px          | Medium primary CTA button                    |
| `{typography.icon-text}`    | "General Sans"        | 18px        | 500    | 18px        | normal         | Text accompanying icons (e.g., arrows)       |

### Principles
The typography system establishes a clear hierarchy through a combination of font families, sizes, and weights. "Recife Text TEST" is reserved for high-impact display text, utilizing a light weight (`300`) with tight letter spacing to convey a sophisticated and modern feel. "General Sans" serves as the workhorse, providing excellent readability across various weights and sizes for body copy, navigation, and feature descriptions. Letter spacing is generally normal for body text, but slightly tracked for smaller labels and some buttons to enhance legibility, and negatively tracked for display headings to create a more impactful, condensed appearance. Uppercase text is used sparingly for emphasis, often paired with monospace fonts for a technical or alert-like quality.

## Layout

The layout system is built on a flexible spacing scale, with a base unit of approximately 5px, allowing for consistent and harmonious distribution of elements.

*   **Spacing Scale**:
    *   `{spacing.xxs}` — 5px
    *   `{spacing.xs}` — 8px
    *   `{spacing.sm}` — 10px
    *   `{spacing.md}` — 15px
    *   `{spacing.lg}` — 20px
    *   `{spacing.xl}` — 25px
    *   `{spacing.xxl}` — 30px
    *   `{spacing.section-sm}` — 40px
    *   `{spacing.section-md}` — 50px
    *   `{spacing.section-lg}` — 60px

*   **Container Behavior**: The site utilizes a `wide-size` container of `{layout.container-wide}` — 1200px and a `content-size` container of `{layout.container-content}` — 800px. Content is typically centered within these containers, providing a structured and readable experience. Sections often feature generous vertical padding, such as `{spacing.section-md}` or `{spacing.section-lg}`, to create distinct visual breaks.

*   **Whitespace Philosophy**: A generous whitespace philosophy is evident throughout the design. Elements are not crowded, and ample padding is used within components and between sections. This approach contributes to the clean, modern aesthetic and improves content readability and scannability. Negative margins are occasionally used to overlap elements or adjust alignment subtly.

## Elevation & Depth

The design uses subtle shadows to create a sense of depth and hierarchy, primarily for interactive elements or distinct content blocks.

*   **Shadow Medium** (`{shadow.md}` — rgba(26, 19, 72, 0.15) 0px 0px 18px 0px): A soft, diffused shadow, likely used for cards or elements that need to appear slightly lifted from the background, such as testimonial cards.
*   **Shadow Large** (`{shadow.lg}` — rgba(26, 19, 72, 0.45) 0px 0px 15px 0px): A slightly more pronounced and darker shadow, used for more significant elevation or interactive states where a stronger visual cue is needed.
*   **Focus Success** (`{shadow.focus-success}` — rgba(31, 191, 91, 0) 0px 0px 0px 7.98063px): This appears to be a transparent outline with a significant spread, likely used as a focus indicator for interactive elements, possibly with a green tint on interaction.

## Shapes

The design incorporates subtle rounded corners, contributing to a softer, more approachable feel without being overly playful.

*   **Rounded Small** (`{rounded.sm}` — 4px): Used for minor elements or subtle softening of edges.
*   **Rounded Medium** (`{rounded.md}` — 8px): Applied to cards or input fields for a gentle rounding.
*   **Rounded Large** (`{rounded.lg}` — 10px): Used for more prominent elements like testimonial headings or larger interactive components.
*   **Rounded Full** (`{rounded.full}` — 50%): For perfectly circular elements, such as avatars or small badges.
*   **Rounded None** (`{rounded.none}` — 0px): Used for sharp, rectangular elements, particularly for announcement buttons or navigation items where a crisp edge is desired.

## Components

*   **`button-announcement-close`**:
    *   **Structure**: A simple text button, often used for dismissing announcements.
    *   **Colors**: Text color `{colors.text-secondary}` — #111111. Background is transparent.
    *   **Typography**: `{typography.body-sm}` — "General Sans", 14px, 400, 22px, 0.5px.
    *   **Padding**: `{spacing.sm}` — 14px vertical, `{spacing.xl}` — 28px horizontal.
    *   **Shape**: `{rounded.none}` — 0px.
    *   **Border**: No visible border.

*   **`nav-main`**:
    *   **Structure**: Navigation links within the header or footer.
    *   **Colors**: Text color `{colors.text-primary}` — #000000. Background is transparent.
    *   **Typography**: `{typography.body-md}` — "General Sans", 16px, 400, 24px, normal.
    *   **Padding**: `{spacing.none}` — 0px.
    *   **Shape**: `{rounded.none}` — 0px.

*   **`heading-h1`**:
    *   **Structure**: The main page title.
    *   **Colors**: Text color `{colors.text-primary}` — #000000. Background is transparent.
    *   **Typography**: `{typography.display-xl}` — "Recife Text TEST", 46px, 300, 54px, -2.59px.
    *   **Padding**: `{spacing.none}` — 0px.

*   **`testimonial-heading`**:
    *   **Structure**: Heading for testimonial sections or similar prominent content blocks.
    *   **Colors**: Text color `{colors.text-primary}` — #000000. Background is transparent.
    *   **Typography**: `{typography.button-primary-lg}` — "Poppins", 28px, 500, normal, normal.
    *   **Padding**: `{spacing.none}` — 0px.
    *   **Shape**: `{rounded.lg}` — 10px.

*   **`marquee`**:
    *   **Structure**: A scrolling text element, likely for announcements or rotating content.
    *   **Colors**: Text color `{colors.text-secondary}` — #111111. Background is transparent.
    *   **Typography**: `{typography.body-md}` — "General Sans", 16px, 400, 24px, normal.
    *   **Padding**: `{spacing.none}` — 0px.

*   **`card`**:
    *   **Structure**: A generic container for content, often with an image, title, and description.
    *   **Colors**: Default text color `{colors.text-primary}` — #000000. Background is typically transparent, but can be `{colors.canvas}` — #ffffff or `{colors.surface-accent-light}` — #f9c597 for specific card types.
    *   **Typography**: Varies based on content, but often uses `{typography.heading-sm}` for titles and `{typography.body-md}` for descriptions.
    *   **Padding**: Varies, but commonly uses `{spacing.lg}` — 20px or `{spacing.xl}` — 25px internally.
    *   **Shape**: Can be `{rounded.none}` — 0px or `{rounded.md}` — 8px depending on context.
    *   **Elevation**: May use `{shadow.md}` — rgba(26, 19, 72, 0.15) 0px 0px 18px 0px for a subtle lift.

## Do's and Don'ts

**Do's**:
*   **Do** use `{colors.brand-primary}` — #fd8143 exclusively for primary calls-to-action and key interactive elements to maintain visual hierarchy.
*   **Do** pair `{typography.display-xl}` — "Recife Text TEST" for main headlines with `{typography.body-md}` — "General Sans" for supporting body text to leverage the established font pairing.
*   **Do** ensure generous vertical spacing between content sections, utilizing `{spacing.section-md}` — 50px or `{spacing.section-lg}` — 60px to maintain a clean layout.
*   **Do** apply `{rounded.lg}` — 10px to prominent cards or interactive containers to give them a modern, friendly appearance.
*   **Do** use `{colors.text-primary}` — #000000 for all primary content text on light backgrounds for optimal readability.
*   **Do** maintain the `{layout.container-wide}` — 1200px and `{layout.container-content}` — 800px max-widths for content to ensure consistent alignment and readability.
*   **Do** use `{typography.label-uppercase-mono}` — "monospace" for small, emphasized labels like "NOW LIVE" to convey urgency or a technical tone.

**Don'ts**:
*   **Don't** use "Recife Text TEST" for body copy or small text; it is reserved for display headings and large titles.
*   **Don't** introduce new accent colors outside of the established brand and semantic palette.
*   **Don't** reduce the whitespace between elements or sections, as this will compromise the clean and open aesthetic.
*   **Don't** use strong, opaque shadows for general elements; stick to `{shadow.md}` — rgba(26, 19, 72, 0.15) 0px 0px 18px 0px for subtle depth.
*   **Don't** use `{colors.text-secondary}` — #111111 for primary headings or critical information where `{colors.text-primary}` —