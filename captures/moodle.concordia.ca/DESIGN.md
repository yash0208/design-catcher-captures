## Overview
The visual design of the Moodle dashboard at Concordia University presents a clean and structured interface focused on clarity and usability. The design utilizes a primarily light color palette, emphasizing spaciousness and ease of navigation. Header elements use bold typography to demarcate sections and enhance readability, while interactive components like buttons and links maintain a consistent visual style to encourage engagement.

Utilizing a responsive layout, the site adapts seamlessly across devices, making critical information accessible whether viewed on mobile or desktop. The integration of a sidebar navigation enhances user experience by providing quick access to primary sections without overwhelming content.

**Key Characteristics:**
- Dominant palette featuring whites and soft grays for a clean interface.
- Strong emphasis on key actions through a monochromatic color scheme with pops of accent colors such as `{colors.primary}` — #0072a8.
- Hierarchical typography contrasting display and body text, enhancing legibility.
- Flexible layout accommodating diverse content formats, utilizing cards to bundle information effectively.
- Subtle use of shadows for depth and dimensionality within components.

## Colors
### Brand & Accent
- **Primary** (`{colors.primary}` — #0072a8): Used for primary buttons and calls to action, providing a clear indicator of interactivity.
  
### Surface
- **Canvas** (`{colors.canvas}` — #ffffff): The main background color, offering a clean and bright space that supports readability.
- **Card Background** (`{colors.card-background}` — #f8f9fa): A soft gray for card elements, providing slight contrast against the canvas without being distracting.

### Hairlines & Borders
- **Border Default** (`{colors.border-default}` — #dee2e6): Used for light borders around cards and inputs, maintaining a light visual hierarchy.
  
### Text
- **Text Light** (`{colors.text-light}` — #212529): Utilized for body text, ensuring readability against the white canvas.
- **Text Muted** (`{colors.text-muted}` — #6c757d): Applied for secondary information and less prominent text, maintaining visual balance.

## Typography
### Font Family
The primary typefaces used in the design are:
- "Arial, Helvetica, sans-serif" for user interface text making it legible and straightforward.
- "GillSansNova-CnBold" for headings, providing a modern and elegant touch.

### Hierarchy
| Token                | Font Family                              | Size    | Weight | Line Height | Letter Spacing | Use                     |
|----------------------|------------------------------------------|---------|--------|-------------|----------------|-------------------------|
| `{typography.h1}`    | GillSansNova-CnBold                     | 39.808px| 400    | 51.68px     | 0.5px          | Primary headers         |
| `{typography.h2}`    | GillSansNova-CnBold                     | 33.184px| 400    | 49.76px     | 0.5px          | Subheadings             |
| `{typography.body}`   | Arial, Helvetica, sans-serif             | 16px    | 400    | 24px        | normal         | Body text               |
| `{typography.body-bold}`| Arial, Helvetica, sans-serif           | 16px    | 700    | 24px        | normal         | Bold body text          |
| `{typography.caption}`| Arial, Helvetica, sans-serif             | 14px    | 400    | 21px        | normal         | Captions and notes      |

### Principles
The typography displays a clear contrast between font sizes and weights to guide user attention effectively. Bold styles are reserved for headings, while body text maintains a regular weight, promoting legibility without unnecessary emphasis. Letter spacing is kept normal, enhancing readability while maintaining a modern aesthetic.

## Layout
The layout employs a grid system that utilizes a variety of spacing tokens based on a base of 4px:
- **Small Spacing**: `{spacing.small}` — 4px (used for margins/padding between small elements).
- **Medium Spacing**: `{spacing.medium}` — 16px (used for larger containers and cards).
- **Large Spacing**: `{spacing.large}` — 24px (used for broader containers and sections).

Whitespace is carefully considered, with generous margins around active elements, ensuring that each section feels distinct yet connected.

## Elevation & Depth
The primary shadow utilized is:
- **Default Shadow** (`{shadows.default}` — rgba(0, 0, 0, 0.075) 0px 2px 4px 0px): Applied to cards and elevated components to enhance depth perception and visual layering.

## Shapes
The design favors subtle curves and rounded edges:
- **Card Radius** (`{radius.card}` — 0px): Standard for most UI elements, emphasizing a flat modern style, creating an organized appearance.

## Components
- **Button** (`button-primary`): Styled in `rgb(255, 255, 255)` text on `rgb(0,114,168)` background, with `{padding}` set to 10px 15px for a touch-friendly design.
- **Navigation Bar** (`nav.navbar`): Uses `rgb(33, 37, 41)` for text colors on a `rgb(255, 255, 255)` background, providing high contrast, maintaining clear navigation.
- **Card Component**: Varies between `{spacing.large}` — 16px padding, with content using `{typography.body}` styled text ensuring readability and visual separation.

## Do's and Don'ts
### Do's:
- **Use the primary color** for active buttons to ensure essential actions stand out.
- **Maintain proper spacing** for elements to avoid crowding.
- **Utilize headings correctly** to create a clear content hierarchy.
- **Stick to the font families** specified to maintain brand consistency.
- **Employ shadowing** to indicate interactive components and depth.
- **Adhere to the grid system** for maintaining layout consistency.

### Don'ts:
- **Don't use colors** outside the established palette for text or backgrounds, as this affects brand recognition.
- **Avoid excessive font styles** to prevent distraction and inconsistency.
- **Refrain from cramming elements** too close; it detracts from usability.
- **Steer clear of non-responsiveness**; all design must adapt fluidly to various screen sizes.

## Responsive Behavior
| Breakpoint | Min Width | Touch Targets | Collapse Strategy                     |
|------------|-----------|---------------|---------------------------------------|
| Mobile     | 0px       | 48px          | Stack elements vertically              |
| Tablet     | 768px     | 48px          | Group related elements horizontally   |
| Desktop    | 1024px    | 48px          | Retain multi-column layout            |
| Wide       | 1440px    | 48px          | Add extra spacing to expand layout    |

## Iteration Guide
1. **Maintain the established color palette** to ensure brand consistency.
2. **Follow the typography hierarchy** to preserve readable and accessible content.
3. **Utilize the grid layout** for organization and clarity across all components.
4. **Keep shadows subtle** to ensure depth without clutter.
5. **Sample spacing tokens accurately** for margins and padding adjustments.
6. **Test every component across breakpoints** to verify responsive behavior.
7. **Document any new components** added to ensure consistency with existing designs.

## Known Gaps
- No evident hover states documented for components.
- Limited breakpoints; further adaptation strategies may be necessary for very small or very large screens.
- Missing detailed states for components, such as disabled or loading states beyond the active and default.