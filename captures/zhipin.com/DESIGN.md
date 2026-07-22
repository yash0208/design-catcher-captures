## DESIGN.md

## Overview

This design system for Zhipin (BOSS直聘) presents a clean, professional, and functional interface, primarily focused on job search and recruitment. The visual identity is built around a distinctive teal-green accent color, which provides a sense of trust and modernity. The overall aesthetic is minimalist, prioritizing readability and clear information hierarchy. Whitespace is used generously to separate content blocks, contributing to an uncluttered user experience. The design leans towards a structured, card-based layout, making it easy to scan and digest job listings and related information.

**Key Characteristics:**
*   **Primary Accent Color**: A vibrant teal (`{colors.brand-primary}` — #00a6a7) for interactive elements and key information.
*   **Neutral Palette**: Predominantly white (`{colors.canvas}` — #ffffff) and light gray (`{colors.canvas-background}` — #eef0f5) surfaces, with dark gray (`{colors.text-primary}` — #333333) for primary text.
*   **Clear Typography**: Relies on a sans-serif font stack, with `arial` as the primary, ensuring high readability across various content types.
*   **Subtle Depth**: Minimal use of shadows, primarily for cards and interactive elements, to create a gentle sense of elevation.
*   **Rounded Corners**: A consistent application of `8px` (`{rounded.md}`) and `12px` (`{rounded.lg}`) radii for cards and buttons, softening the interface.
*   **Structured Layout**: Utilizes a grid-like structure with ample padding and margins to organize complex information into digestible blocks.

## Colors

### Brand & Accent
*   **Brand Primary** (`{colors.brand-primary}` — #00a6a7): The dominant accent color, used for active states, links, primary calls to action, and key informational highlights.
*   **Brand Secondary** (`{colors.brand-secondary}` — #00bebd): A slightly brighter teal, used for backgrounds of certain interactive elements or secondary accents.
*   **Button Primary Background** (`{colors.button-primary-bg}` — #00a6a7): The background color for primary action buttons (inferred from `{colors.brand-primary}`).
*   **Button Primary Background Disabled** (`{colors.button-primary-bg-disabled}` — #99e5e5): A lighter, desaturated version of the brand primary, indicating a disabled state for primary buttons.

### Surface
*   **Canvas** (`{colors.canvas}` — #ffffff): The primary background color for most content areas, cards, and interactive components.
*   **Canvas Background** (`{colors.canvas-background}` — #eef0f5): The overall page background color, providing a subtle contrast to content surfaces.
*   **Surface Light** (`{colors.surface-light}` — #f8f8f8): A very light gray used for subtle background variations or secondary content blocks.
*   **Surface Muted** (`{colors.surface-muted}` — #ededed): A light gray used for backgrounds or subtle separators.
*   **Surface Dark** (`{colors.surface-dark}` — #1f232a): A very dark background color, likely for specific sections or overlays (low count).

### Hairlines & Borders
*   **Border Primary** (`{colors.border-primary}` — #cae0e0): A light teal-gray border color for subtle separation.
*   **Border Muted** (`{colors.border-muted}` — #ededed): A light gray border, often for dividing lines or inactive states.
*   **Border Hairline** (`{colors.border-hairline}` — #cccccc): A very light gray used for fine separators.
*   **Border Placeholder** (`{colors.border-placeholder}` — #b8b8b8): A medium gray, potentially for input borders or inactive elements.

### Text
*   **Text Primary** (`{colors.text-primary}` — #333333): The main text color for body copy and general content, ensuring high readability.
*   **Text Heading** (`{colors.text-heading}` — #222222): A slightly darker text color, used for prominent headings and titles.
*   **Text Secondary** (`{colors.text-secondary}` — #414a60): A dark blue-gray text color, used for secondary information, descriptions, or less prominent text.
*   **Text Muted** (`{colors.text-muted}` — #999999): A medium gray text color for less important information, captions, or helper text.
*   **Text Placeholder** (`{colors.text-placeholder}` — #b8b8b8): A lighter gray for input placeholders or inactive text.
*   **Text On Accent** (`{colors.text-on-accent}` — #ffffff): White text used on brand-colored backgrounds, such as primary buttons.

### Semantic
*   **Semantic Warning** (`{colors.semantic-warning}` — #ff9f00): Used to indicate warnings or cautionary information.
*   **Semantic Danger** (`{colors.semantic-danger}` — #f44336): Used to indicate errors or critical actions.
*   **Semantic Success** (`{colors.semantic-success}` — #00c48f): Used to indicate successful operations or positive status.
*   **Semantic Info** (`{colors.semantic-info}` — #00afef): Used for informational messages.

## Typography

### Font Family
The primary typeface stack is "arial, verdana, helvetica, "PingFang SC", "HanHei SC", STHeitiSC-Light, "Microsoft Yahei", sans-serif". This provides a clean, highly legible sans-serif appearance, suitable for both English and Chinese characters. An additional `ui-icons` font is used for iconography.

### Hierarchy

| Token                 | Font Family                                                                                             | Size  | Weight | Line Height | Letter Spacing | Use                                          |
| :-------------------- | :------------------------------------------------------------------------------------------------------ | :---- | :----- | :---------- | :------------- | :------------------------------------------- |
| `{typography.heading-xl}` | arial, verdana, helvetica, "PingFang SC", "HanHei SC", STHeitiSC-Light, "Microsoft Yahei", sans-serif | 22px  | 500    | 33px        | normal         | Large section titles                         |
| `{typography.heading-md}` | arial, verdana, helvetica, "PingFang SC", "HanHei SC", STHeitiSC-Light, "Microsoft Yahei", sans-serif | 16px  | 500    | 22px        | normal         | Medium section headings, category titles     |
| `{typography.heading-sm}` | arial, verdana, helvetica, "PingFang SC", "HanHei SC", STHeitiSC-Light, "Microsoft Yahei", sans-serif | 16px  | 500    | 16px        | normal         | Small headings, prominent labels             |
| `{typography.heading-sm-alt}` | arial, verdana, helvetica, "PingFang SC", "HanHei SC", STHeitiSC-Light, "Microsoft Yahei", sans-serif | 16px  | 500    | 24px        | normal         | Alternative small headings                   |
| `{typography.body-lg}`    | arial, verdana, helvetica, "PingFang SC", "HanHei SC", STHeitiSC-Light, "Microsoft Yahei", sans-serif | 16px  | 400    | 22.4px      | normal         | Larger body text, descriptions               |
| `{typography.body-lg-alt}` | arial, verdana, helvetica, "PingFang SC", "HanHei SC", STHeitiSC-Light, "Microsoft Yahei", sans-serif | 16px  | 400    | 24px        | normal         | Alternative larger body text                 |
| `{typography.body-input}` | arial, verdana, helvetica, "PingFang SC", "HanHei SC", STHeitiSC-Light, "Microsoft Yahei", sans-serif | 16px  | 400    | normal      | normal         | Input field text                             |
| `{typography.body-medium}` | arial, verdana, helvetica, "PingFang SC", "HanHei SC", STHeitiSC-Light, "Microsoft Yahei", sans-serif | 14px  | 500    | 20px        | normal         | Standard body text, emphasized labels        |
| `{typography.body-regular}` | arial, verdana, helvetica, "PingFang SC", "HanHei SC", STHeitiSC-Light, "Microsoft Yahei", sans-serif | 14px  | 400    | 20px        | normal         | Standard body text, general content          |
| `{typography.nav-item-active}` | arial, verdana, helvetica, "PingFang SC", "HanHei SC", STHeitiSC-Light, "Microsoft Yahei", sans-serif | 14px  | 500    | 49px        | normal         | Active navigation item text                  |
| `{typography.nav-item-inactive}` | arial, verdana, helvetica, "PingFang SC", "HanHei SC", STHeitiSC-Light, "Microsoft Yahei", sans-serif | 14px  | 400    | 49px        | normal         | Inactive navigation item text                |
| `{typography.caption-medium}` | arial, verdana, helvetica, "PingFang SC", "HanHei SC", STHeitiSC-Light, "Microsoft Yahei", sans-serif | 12px  | 500    | 18px        | normal         | Captions, metadata, small emphasized text    |
| `{typography.tag-label}`  | arial, verdana, helvetica, "PingFang SC", "HanHei SC", STHeitiSC-Light, "Microsoft Yahei", sans-serif | 12px  | 500    | 12px        | normal         | Small labels, numerical tags                 |

### Principles
The typography emphasizes clarity and hierarchy through a consistent sans-serif font stack. Font weights are primarily `400` (regular) and `500` (medium), providing subtle emphasis without being overly bold. Line heights are generally generous, improving readability for longer text blocks. Letter spacing remains `normal` throughout, maintaining a natural text flow. The system uses distinct font sizes and weights to differentiate headings, body text, and metadata, ensuring that users can quickly discern the importance of information.

## Layout

The layout system is built on a base spacing unit of `4px`. This allows for a flexible yet consistent rhythm across the interface.

**Spacing Scale:**
*   `{spacing.hairline}` — 1px
*   `{spacing.xxs}` — 4px
*   `{spacing.xxs-tight}` — 5px
*   `{spacing.xxs-alt}` — 6px
*   `{spacing.xs}` — 8px
*   `{spacing.xsm}` — 10px
*   `{spacing.xsm-alt}` — 12px
*   `{spacing.sm}` — 16px
*   `{spacing.sm-tight}` — 15px
*   `{spacing.sm-loose}` — 18px
*   `{spacing.sm-alt}` — 20px
*   `{spacing.md-alt}` — 22px
*   `{spacing.md}` — 24px
*   `{spacing.lg}` — 32px
*   `{spacing.section}` — 86px (large margin for main sections)

**Grid & Container Behavior:**
The page appears to use a fixed-width container for its main content, centered on the screen. Content within these containers is organized into distinct cards and sections, with generous horizontal and vertical padding. The overall philosophy emphasizes ample whitespace around content blocks to prevent visual clutter and improve scannability.

**Whitespace Philosophy:**
Whitespace is a critical element of this design, used to create clear separation between different UI elements and content areas. This is evident in the generous padding within cards and the substantial margins between major sections. This approach enhances readability and guides the user's eye through the content.

## Elevation & Depth

Elevation and depth are used sparingly, primarily to highlight interactive elements or distinct content blocks.
*   **Shadow Card** (`{shadow.card}` — rgba(0, 0, 0, 0.06) 0px 1px 8px 0px): A subtle, diffused shadow used to lift cards and content panels from the background, providing a soft sense of depth.
*   **Shadow Control** (`{shadow.control}` — rgba(0, 0, 0, 0.5) 0px 0px 3px 0px): A more pronounced, tighter shadow, observed on map controls, suggesting a more interactive or functional element.
*   **Shadow Tooltip** (`{shadow.tooltip}` — rgba(0, 0, 0, 0.15) 0px 3px 5px 0px): A moderate shadow, used for informational pop-ups or tooltips, creating clear separation from underlying content.
*   **Shadow Modal** (`{shadow.modal}` — rgba(172, 187, 188, 0.2) 0px 10px 20px 0px): A larger, more spread-out shadow, likely used for modals or larger overlay components, indicating a higher z-index and focus.

## Shapes

The design incorporates rounded corners to soften the interface and improve visual appeal.
*   **Rounded Hairline** (`{rounded.hairline}` — 1px): A very subtle rounding, almost imperceptible, for fine details.
*   **Rounded Small** (`{rounded.sm}` — 4px): A small radius used for minor elements or internal components.
*   **Rounded XSmall** (`{rounded.xsm}` — 7px): A slightly larger small radius.
*   **Rounded XSmall Alt** (`{rounded.xsm-alt}` — 6px): An alternative small radius.
*   **Rounded Medium** (`{rounded.md}` — 8px): A common radius applied to buttons and smaller interactive elements.
*   **Rounded Large** (`{rounded.lg}` — 12px): A larger radius primarily used for cards and larger content containers.
*   **Rounded Pill** (`{rounded.pill}` — 30px): A very large radius, typically used for input fields or tags to create a pill-like shape.
*   **Rounded Full** (`{rounded.full}` — 100%): For perfectly circular elements like avatars or badges.

## Components

### `button-primary`
A prominent button for primary actions.
*   **Structure**: Solid background, white text.
*   **Background**: `{colors.button-primary-bg}` — #00a6a7
*   **Text Color**: `{colors.text-on-accent}` — #ffffff
*   **Typography**: `{typography.body-regular}` — 14px, 400, arial...
*   **Padding**: `9px` top/bottom, `30px` left/right (`{spacing.button-y}` — 9px `{spacing.button-x}` — 30px)
*   **Border Radius**: `{rounded.md}` — 8px
*   **Disabled State**: Background is `{colors.button-primary-bg-disabled}` — rgb(153, 229, 229).

### `input-text`
Standard text input field.
*   **Structure**: White background, rounded pill shape.
*   **Background**: `{colors.canvas}` — #ffffff
*   **Text Color**: `{colors.text-secondary}` — #414a60
*   **Typography**: `{typography.body-lg}` — 16px, 400, arial...
*   **Padding**: `0px` top/bottom, `18px` left/right (`{spacing.input-x}` — 18px)
*   **Border Radius**: `{rounded.pill}` — 30px
*   **Border**: None (suggests an implicit border or shadow for focus state, not captured).

### `card-job`
Container for individual job listings.
*   **Structure**: White background, large rounded corners. Content is typically nested within an inner element with its own padding.
*   **Background**: `{colors.canvas}` — #ffffff
*   **Border Radius**: `{rounded.lg}` — 12px
*   **Padding**: `0px` (the card itself has no direct padding, content padding is applied to inner elements like `.job-info`)
*   **Inner Content Padding (`.job-info`)**: `16px` top/bottom, `24px` left/right (`{spacing.sm}` — 16px `{spacing.md}` — 24px)
*   **Shadow**: None directly on `.job-card-box`, but parent `.job-card-wrap` might imply a shadow for the overall card structure, or it's implicitly part of the layout.

## Do's and Don'ts

### Do's
*   **Do** use `{colors.brand-primary}` — #00a6a7 for all primary calls to action and interactive elements to maintain brand consistency.
*   **Do** ensure all headings use `{colors.text-heading}` — #222222 and body text uses `{colors.text-primary}` — #333333 for optimal readability.
*   **Do** apply `{rounded.lg}` — 12px to all card-like containers and `{rounded.md}` — 8px to buttons for a consistent soft aesthetic.
*   **Do** utilize `{spacing.md}` — 24px for horizontal padding within content blocks and `{spacing.sm}` — 16px for vertical padding to create clear visual separation.
*   **Do** maintain a clear typographic hierarchy, using `arial` as the primary font, to guide users through information.
*   **Do** use `{shadow.card}` — rgba(0, 0, 0, 0.06) 0px 1px 8px 0px for all content cards to provide subtle elevation.

### Don'ts
*   **Don't** introduce new font families or weights outside of the defined `arial` stack and specified weights (`400`, `500`) to avoid visual dissonance.
*   **Don't** use `{colors.brand-primary}` — #00a6a7 for large blocks of text or non-interactive elements, as it should be reserved for emphasis.
*   **Don't** use sharp corners (`{rounded.none}`) for interactive elements or cards; always apply a minimum of `{rounded.md}` — 8px.
*   **Don't** deviate from the established spacing scale; avoid arbitrary pixel values for margins and padding.
*   **Don't** use excessive or multiple shadows on a single element, as this can create a cluttered or heavy appearance.
*   **Don't** use `{colors.text-muted}` — #999999 for critical information, as its lower contrast can hinder readability.

## Responsive Behavior

| Breakpoint | Min Width | Touch Targets | Collapse Strategy