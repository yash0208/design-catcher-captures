## Overview

Mirzam Chocolate's visual design embodies a sophisticated yet approachable aesthetic, reflecting the artisanal nature of its products. The brand utilizes a dark, rich color palette with stark white contrasts, creating a sense of luxury and clarity. Typography plays a crucial role, pairing the elegant `Adobe Devanagari` for prominent headings with the highly legible `Poppins` for body text and navigation, establishing a clear hierarchy. Layouts are clean and spacious, emphasizing product imagery and brand storytelling through generous whitespace and well-defined content blocks. The overall impression is one of quality, tradition, and modern elegance, with a focus on a premium user experience.

The design leverages subtle visual cues rather than strong graphical elements, relying on strong photographic content and refined typography to convey its message. Interactive elements, such as buttons, feature a distinct brand accent color, guiding user actions without being overly obtrusive. The consistent use of a dark primary text color against light backgrounds, or vice-versa, ensures readability across various sections of the site.

**Key Characteristics:**
*   **Rich Contrast:** Dominant use of dark charcoal (`{colors.text-primary}` — #212326) and pure white (`{colors.canvas}` — #ffffff).
*   **Elegant Typography:** A clear distinction between display (`Adobe Devanagari`) and functional (`Poppins`) typefaces.
*   **Spacious Layouts:** Ample whitespace, particularly `{spacing.section}` — 72px, creating a premium feel.
*   **Subtle Brand Accent:** A warm, deep red (`{colors.brand-primary}` — #801f08) used for calls to action.
*   **Minimalist Depth:** Absence of prominent shadows, focusing on flat design elements.
*   **Structured Content:** Clear sectioning and alignment, often centered or left-aligned for readability.
*   **Rounded Elements:** Subtle use of `{rounded.md}` — 10px for interactive components like buttons.
*   **Uppercase Emphasis:** Frequent use of uppercase for headings and navigation items to convey importance.

## Colors

### Brand & Accent
*   **Brand Primary** (`{colors.brand-primary}` — #801f08): Used for primary call-to-action buttons and interactive elements, signifying key user actions.
*   **Link Default** (`{colors.link-default}` — #0000ee): Standard browser blue for unvisited links, appearing in less prominent text areas.

### Surface
*   **Canvas** (`{colors.canvas}` — #ffffff): The primary background color for most page content, providing a clean, bright base.
*   **Surface Dark** (`{colors.surface-dark}` — #212326): Used as a background for certain sections or components where a darker contrast is desired, often paired with `{colors.text-on-dark}`.
*   **Surface Light Muted** (`{colors.surface-light-muted}` — #f3f3f3): A very light grey used for subtle background differentiation, such as input fields or minor section breaks.
*   **Surface Subtle** (`{colors.surface-subtle}` — #ebebeb): An even lighter grey, used sparingly for very subtle background variations.
*   **Surface Black** (`{colors.surface-black}` — #000000): Used for specific background elements, often in conjunction with bold typography.

### Hairlines & Borders
*   **Border Dark** (`{colors.border-dark}` — #212326): Used for outlines and separators, particularly around interactive elements or content blocks.
*   **Border Dark Muted** (`{colors.border-dark-muted}` — #282828): A slightly lighter dark grey for borders, offering a softer contrast than `{colors.border-dark}`.

### Text
*   **Text Primary** (`{colors.text-primary}` — #212326): The dominant text color for body copy, navigation, and general content on light backgrounds.
*   **Text Secondary** (`{colors.text-secondary}` — #282828): A slightly lighter shade than primary, used for less emphasized text or secondary information.
*   **Text Heading** (`{colors.text-heading}` — #303030): Used for primary headings, providing a distinct, slightly softer tone than `{colors.text-primary}`.
*   **Text Price** (`{colors.text-price}` — #1a1b18): A very dark, almost black color specifically designated for product pricing.
*   **Text On Dark** (`{colors.text-on-dark}` — #ffffff): Used for text elements placed on dark backgrounds, ensuring high contrast and readability.
*   **Text Light Muted** (`{colors.text-light-muted}` — #fafafa): A very light, almost white color used for text on darker backgrounds where a subtle, less stark contrast is desired.
*   **Text Black** (`{colors.text-black}` — #000000): Pure black text, used for maximum emphasis or specific branding elements.

## Typography

### Font Family
The primary typeface for body text, navigation, and most functional elements is "Poppins", a geometric sans-serif, with `sans-serif` as a fallback. Display headings and prominent brand statements utilize "Adobe Devanagari", a serif typeface, for an elegant and distinctive touch. Price information is designated to "Cormorant", a serif font, though its specific usage is primarily indicated by a CSS variable.

### Hierarchy

| Token                 | Font Family        | Size      | Weight | Line Height | Letter Spacing | Use                                          |
| :-------------------- | :----------------- | :-------- | :----- | :---------- | :------------- | :------------------------------------------- |
| `{typography.display-xl}` | Adobe_Devanagari   | 73.6px    | 400    | 73.6px      | -1.472px       | Hero titles, main page headings              |
| `{typography.display-lg}` | Adobe_Devanagari   | 46px      | 400    | 56.8px      | 0.92px         | Section titles, prominent statements         |
| `{typography.heading-md}` | Poppins, sans-serif | 14px      | 400    | 17.287px    | 0.69px         | Collection titles, card headings             |
| `{typography.body-lg}`    | Poppins, sans-serif | 14.4px    | 400    | 27.2px      | 0.54px         | Main body text, detailed descriptions        |
| `{typography.body-md}`    | Poppins, sans-serif | 12.9px    | 400    | 18.6333px   | normal         | Secondary body text, product descriptions    |
| `{typography.body-sm}`    | Poppins, sans-serif | 12.6px    | 400    | 23.8px      | 0.54px         | Footer links, less prominent text            |
| `{typography.nav-item}`   | Poppins, sans-serif | 12px      | 400    | 22.6667px   | 2.4px          | Primary navigation links                     |
| `{typography.button-primary}` | Poppins, sans-serif | 12px      | 600    | 14.6667px   | 2.4px          | Call-to-action buttons                       |
| `{typography.announcement}` | Poppins, sans-serif | 11.7px    | 400    | 14.625px    | 0.702px        | Announcement bar text                        |
| `{typography.label-sm}`   | Poppins, sans-serif | 10.8px    | 600    | 13.2px      | 2.16px         | Small labels, skip links (uppercase)         |

### Principles
The typography establishes a clear visual hierarchy through a distinct pairing of serif and sans-serif fonts. `Adobe Devanagari` is reserved for impactful, large-scale headings, creating a strong brand presence. `Poppins` handles the majority of content, ensuring readability with varying sizes and weights. Weight contrast is primarily used for buttons and labels (`{typography.button-primary}` — 600) to draw attention. Letter spacing is often expanded for navigation items and buttons (`{typography.nav-item}` — 2.4px, `{typography.button-primary}` — 2.4px) and sometimes slightly for body text to improve legibility. Uppercase styling is frequently applied to navigation, buttons, and some headings to convey importance and structure.

## Layout

The layout system is built on a base spacing unit of approximately 3px, creating a rhythmic and consistent visual flow. Content is typically contained within a main wrapper, allowing for generous horizontal padding on larger screens. Sections are clearly delineated with substantial vertical spacing.

**Spacing Scale (3px base):**
*   `{spacing.xxs}` — 2px: Minimal separation, often for inline elements or very tight spacing.
*   `{spacing.xs}` — 6px: Smallest common spacing, used for internal component padding or tight element separation.
*   `{spacing.sm}` — 9px: Used for minor spacing between related elements.
*   `{spacing.md}` — 12px: Standard spacing for elements within a group.
*   `{spacing.md-lg}` — 14px: Slightly larger than medium, for more breathing room.
*   `{spacing.lg}` — 18px: Common padding for components and spacing between distinct elements.
*   `{spacing.xl}` — 27px: Generous spacing for content blocks and larger internal padding.
*   `{spacing.xxl}` — 45px: Significant spacing, often used for vertical separation between major content areas.
*   `{spacing.section}` — 72px: The primary vertical separator between main page sections, ensuring ample breathing room.
*   `{spacing.gap-lg}` — 60px: Used for larger gaps in grid layouts.
*   `{spacing.hero-padding}` — 416px: Exceptionally large padding, likely for hero sections to control image aspect ratios or content alignment.

**Grid & Container Behavior:**
The site employs a fluid layout that adapts to viewport width. Main content areas appear to be constrained by a maximum width, centered on the page, with `0rem` page width margin (`--page-width-margin`). Headers often utilize a grid structure, such as `grid-template-columns: 316.75px 633.5px 316.75px`, to align elements like logo and navigation. Product listings and galleries often use flexible grids that adjust column counts based on screen size.

**Whitespace Philosophy:**
Whitespace is used generously to create a premium, uncluttered experience. Large `{spacing.section}` values between content blocks prevent visual fatigue and highlight individual sections. Internal padding within components is also ample, ensuring elements do not feel cramped. This deliberate use of negative space directs user attention and enhances the perceived quality of the content.

## Elevation & Depth

The design philosophy largely avoids overt elevation and depth through shadows. All observed shadow values are `0px 0px 0px 0px`, indicating that visible drop shadows are not a primary design element for creating hierarchy or depth. Any listed shadow values (e.g., `rgb(168, 232, 226) 0px 0px 0px 0px`) are effectively transparent or serve as placeholders for focus states that are not currently active. The design relies on color contrast, typography, and spacing to establish visual hierarchy rather than simulated depth.

## Shapes

The design incorporates subtle rounding for interactive elements, contributing to a softer, more approachable feel without being overly playful.

*   **Rounded Extra Small** (`{rounded.xs}` — 1.8px): Very subtle rounding, likely for very small elements or internal component details.
*   **Rounded Small** (`{rounded.sm}` — 9px): Used for some interactive elements, offering a gentle curve.
*   **Rounded Medium** (`{rounded.md}` — 10px): The most common border-radius, applied to primary buttons and other interactive components like the skip-to-content link.
*   **Rounded Large** (`{rounded.lg}` — 15px): Larger radius, used for specific containers or visual elements that require a more pronounced rounded aesthetic.

## Components

*   **`button-primary`**
    *   **Structure:** A text label within a rectangular container.
    *   **Background:** `{colors.brand-primary}` — #801f08.
    *   **Text:** `{colors.text-on-dark}` — #ffffff, using `{typography.button-primary}` (Poppins, 12px, 600, 14.6667px line-height, 2.4px letter-spacing).
    *   **Padding:** `7.2px` vertical, `18px` horizontal (top: `{spacing.xs}` approx, bottom: `{spacing.xs-minus}` approx, horizontal: `{spacing.lg}`).
    *   **Border:** `1px` solid `{colors.brand-primary}` — #801f08.
    *   **Border Radius:** `{rounded.md}` — 10px.
    *   **Shadow:** None visible.

*   **`nav-main`**
    *   **Structure:** A list of text links.
    *   **Text:** `{colors.text-primary}` — #212326, using `{typography.nav-item}` (Poppins, 12px, 400, 22.6667px line-height, 2.4px letter-spacing).
    *   **Background:** Transparent.
    *   **Padding:** `0px`.
    *   **Border:** None.

*   **`input-text`**
    *   **Structure:** A simple text input field.
    *   **Text:** `{colors.text-primary}` — #212326, using `{typography.body-lg}` (Poppins, 14.4px, 400, 0px line-height, 0.54px letter-spacing).
    *   **Background:** Transparent.
    *   **Padding:** `0px`.
    *   **Border:** None (implies borders are handled by parent containers or focus states).

*   **`header-logo`**
    *   **Structure:** An `h1` element, likely containing an SVG or image, but text sample implies it can also be text-based.
    *   **Text:** `{colors.text-heading}` — #303030, using `{typography.display-lg}` (Adobe_Devanagari, 46px, 400).
    *   **Background:** Transparent.
    *   **Padding:** `0px`.
    *   **Border:** None.

*   **`card-collection`**
    *   **Structure:** Typically an image followed by a heading.
    *   **Heading Text:** `{colors.text-primary}` — #212326, using `{typography.heading-md}` (Poppins, 14px, 400, 17.287px line-height, 0.69px letter-spacing). Often uppercase.
    *   **Background:** Transparent for the card itself, but may sit on a `{colors.surface-light-muted}` or `{colors.canvas}` background.
    *   **Padding:** `0px` for the card wrapper, content within may have internal padding.
    *   **Border:** None.

## Do's and Don'ts

**Do's:**
*   **Do** use `{colors.brand-primary}` — #801f08 exclusively for primary calls-to-action and key interactive elements.
*   **Do** maintain a clear typographic hierarchy by using `Adobe Devanagari` for large display headings and `Poppins` for all body, navigation, and functional text.
*   **Do** apply `{spacing.section}` — 72px between major content blocks to ensure ample visual separation and a premium feel.
*   **Do** use `{rounded.md}` — 10px for all primary buttons and interactive components to maintain consistency.
*   **Do** use uppercase styling for navigation links and button labels with `{typography.nav-item}` and `{typography.button-primary}`.
*   **Do** ensure high contrast between text and background, typically `{colors.text-primary}` on `{colors.canvas}` or `{colors.text-on-dark}` on `{colors.surface-dark}`.
*   **Do** utilize `{spacing.lg}` — 18px for horizontal padding within components and `{spacing.xl}` — 27px for vertical padding in content areas.

**Don'ts:**
*   **Don't** introduce new shadow styles; the design explicitly avoids visible elevation for content hierarchy.
*   **Don't** use `Adobe Devanagari` for body text or small labels; it is reserved for display purposes.
*   **Don't** deviate from the established spacing scale; avoid arbitrary pixel values for margins and padding.
*   **Don't** use `{colors.brand-primary}` — #801f08 for decorative elements or non-interactive text.
*   **Don't** use overly rounded corners (e.g., full circles) unless explicitly defined for a specific component.
*   **Don't** use `Arial` for any user-facing text; it appears to be a fallback or for internal/system elements.
*   **Don't** clutter layouts; prioritize whitespace and clear content separation using `{spacing.section}`.

## Responsive Behavior

| Breakpoint | Min Width | Touch Targets | Collapse Strategy