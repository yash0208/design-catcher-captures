## Page Overview

This is a marketing landing page for "Browser Extractor," a tool designed to inspect, edit, and audit websites. The page features a total of 20 distinct sections, including a prominent hero, feature showcases, a playground for interaction, role-based explanations, and pricing. The scroll rhythm is characterized by a series of full-width content blocks, many of which appear to be interactive demonstrations or visual explanations of features. The primary user journey guides visitors through understanding the tool's capabilities, seeing it in action, identifying how it benefits different roles, and finally, presenting pricing options to convert them into users. The page title, "Browser Extractor | Inspect, edit and audit any website," clearly communicates the product's core value proposition.

## Section Map

1.  **Section 0 — Main Content Wrapper**: `main` tag, height ~14582px.
    *   Acts as the primary container for all page content.
    *   Contains multiple `section` elements, hinting at a long-scrolling layout.

2.  **Section 1 — Hero**: `section.hero.shell` tag, height ~1241px, grid layout with a single column.
    *   **Component hints**: hero, imagery, buttons.
    *   Contains the main headline and likely calls to action and a visual representation of the product.

3.  **Section 2 — Site Header (Sticky Navigation)**: `header.site-header.shell.glass` tag, height ~70px, flex layout with 24px gap.
    *   **Component hints**: navigation, imagery, buttons.
    *   Contains the site logo/name, a menu button, and a navigation bar.

4.  **Section 3 — Main Navigation**: `nav` tag, height ~44px, flex layout with 22px gap.
    *   **Component hints**: buttons.
    *   Contains navigation links, likely for features or different sections of the page.

5.  **Section 4 — AI Audit Report**: `section.hv-report.is-sweep` tag, height ~411px, block layout.
    *   A simulated report or audit display, likely part of the hero or an early feature showcase.
    *   Contains a header, multiple articles (insights/fixes), and a footer.

6.  **Section 5 — AI Audit Report Header**: `header.hv-rh` tag, height ~87px, block layout.
    *   Header for the AI Audit Report section, likely showing status or title.

7.  **Section 6 — Design System Audit Article**: `article.hv-sec` tag, height ~92px, block layout.
    *   An individual audit insight, possibly detailing design system inconsistencies.

8.  **Section 7 — Accessibility Fix Article**: `article.hv-sec.hv-sec--fix` tag, height ~92px, block layout.
    *   An individual audit insight, specifically highlighting an accessibility fix.

9.  **Section 8 — UX Audit Risk Article**: `article.hv-sec.hv-sec--risk` tag, height ~94px, block layout.
    *   An individual audit insight, indicating a UX-related risk.

10. **Section 9 — AI Audit Report Footer**: `footer.hv-rf` tag, height ~58px, flex layout with 10px gap.
    *   Footer for the AI Audit Report, possibly containing actions or status.

11. **Section 10 — How It Works / Stage**: `section.stage` tag, height ~5198px, block layout.
    *   **Heading**: "From “how did they build that?”to a change you can see."
    *   **Component hints**: buttons.
    *   A very tall section, likely showcasing multiple features or steps of the product.

12. **Section 11 — Stage Navigation Rail**: `nav.stage-rail` tag, height ~43px, flex layout.
    *   Navigation or progress indicator for the "How It Works" section, possibly sticky or scroll-triggered.

13. **Section 12 — Playground**: `section.section.shell` tag, height ~1466px, block layout.
    *   **Heading**: "Enough watching.Make your move."
    *   **Component hints**: imagery, buttons.
    *   An interactive area where users can experiment with the tool.

14. **Section 13 — Edits Rail**: `section.hf-node.edits-rail` tag, height ~89px, flex column layout with 12px gap.
    *   Displays code changes based on user interaction in the playground.

15. **Section 14 — Roles**: `section.section.shell.roles` tag, height ~974px, block layout.
    *   **Heading**: "Pick your role.See what you take away."
    *   **Component hints**: buttons.
    *   Explains how different user roles (designers, developers, etc.) can benefit from the tool.

16. **Section 15 — Extras / Takeaways**: `section.section.shell.extras` tag, height ~1150px, block layout.
    *   **Heading**: "Take the designout of the browser."
    *   **Component hints**: imagery, buttons.
    *   Details the outputs and benefits of using the tool.

17. **Section 16 — Pricing Section**: `section.section.pricing-section` tag, height ~1490px, block layout.
    *   **Heading**: "Try it all for 7 days.Keep the free tools forever."
    *   **Component hints**: pricing.
    *   Contains pricing plans and calls to action.

18. **Section 17 — Free Price Card**: `article.price-card.glass` tag, height ~1017px, grid layout (flex column implied) with 0px normal gap.
    *   **Heading**: "Free"
    *   **Component hints**: feature-grid.
    *   Details the features and benefits of the free tier.

19. **Section 18 — Pro Price Card (Featured)**: `article.price-card.glass.price-card--featured` tag, height ~1017px, grid layout (flex column implied) with 0px normal gap.
    *   **Heading**: "Pro"
    *   **Component hints**: feature-grid.
    *   Details the features and benefits of the Pro tier, marked as featured.

20. **Section 19 — Trust / What Stays**: `section.section.shell.trust` tag, height ~686px, block layout.
    *   **Heading**: "What stays with you,and what leaves."
    *   Likely discusses data privacy, security, or the non-intrusive nature of the tool.

## Hero Deep-Dive

The hero section (Section 1) is a `section` element with classes `hero` and `shell`, spanning a height of approximately 1241px.
*   **Layout structure**: It uses a `grid` layout, though the `gridTemplateColumns` is specified as `1320px`, suggesting a single main content column centered within the `shell`. The main headline, "Every website is your brandlet audience = "brand";palette & typeArabic localizeresponsive viewsdesign playground.", is a single `h1` (`hero-title`) that is likely stacked. There are no explicit subcopy elements identified in the hero data, but the headline itself is quite long and descriptive.
*   **Background type**: The hero has a `backgroundType` of "image" and `hasBackgroundMedia` is true, indicating a visual background, likely a product screenshot or demo.
*   **CTA count and placement**: There are 4 CTA buttons within the hero, suggesting multiple entry points or actions for the user, possibly "Add to Chrome", "Learn More", "Watch Demo", etc. Their exact placement isn't specified but they would be prominent.
*   **Typography hierarchy**: The primary typography for the hero's main headline (`h1.hero-title`) is `"Space Grotesk"`, `88px` font size, `500` font weight, `91.52px` line height, and a tight `letterSpacing` of `-4.84px`, indicating a large, impactful display font.

## Component Inventory

| Component | Count | Location | Description |
| :-------- | :---- | :------- | :---------- |
| button    | 110   | `button.menu-button` | Ghost-style buttons with `rgb(212, 212, 212)` text, `14px` font size, `10px` border radius. |
| nav       | 5     | `nav` | Navigation elements, some with `rgb(250, 250, 250)` text. |
| input     | 4     | `input` | Input fields, likely for forms or search, with `rgb(250, 250, 250)` text, `11px` font size. |
| footer    | 2     | `footer.hv-rf` | Footers, specifically for the AI Audit Report, with `rgb(250, 250, 250)` text, `16px` font size, `11px 16px 12px` padding. |
| heading   | 1     | `h1.hero-title` | The main hero headline, `88px` "Space Grotesk" font. |
| hero      | 3     | `section.hero` | Hero sections, likely including the main hero and possibly other large introductory sections, with `80px 0px 64px` padding. |
| pricing   | 5     | `section.section` | Pricing sections, including the main pricing section and individual price cards, with `112px 0px` padding. |
| faq       | 18    | `section.section` | FAQ sections, with `72px 0px` padding. |
| card      | 15    | `.demo-mount` | Cards used for mounting demos, transparent background. |
| card      | 8     | `.product-window` | Cards resembling product windows, with `rgba(24, 24, 24, 0.97)` background, `18px` border radius, and multiple box shadows. |
| card      | 8     | `.demo-layout` | Cards for demo layouts, with `rgb(8, 8, 46)` background. |
| card      | 8     | `.reference-area` | Cards for reference areas, with `rgb(8, 8, 46)` background and `0px 0px 90px` padding. |
| card      | 8     | `.reference` | Generic reference cards, with `rgb(255, 255, 255)` background and text. |

## Motion & Animation

The page incorporates several CSS transitions and animations to enhance interactivity and visual appeal:

*   **CSS Transitions**:
    *   `transform`: Widely used (30 instances), suggesting elements moving, scaling, or rotating on hover or interaction.
    *   `background-color, transform`: (10 instances) Likely for buttons or interactive elements changing background and moving.
    *   `color, border-color, background-color, box-shadow, transform`: (10 instances) Comprehensive transitions for interactive elements, possibly buttons with complex hover states.
    *   `opacity`: (8 instances) For fading elements in or out.
    *   `color`: (7 instances) For text color changes.
    *   `background-color, border-color, box-shadow, transform`: (3 instances) Similar to above, for interactive elements.
    *   `top, bottom`: (2 instances) For vertical positioning changes.
    *   `opacity, transform, visibility`: (2 instances) For showing/hiding elements with animation.
    *   `background, color`: (2 instances) For background and text color changes.
    *   `opacity, --r`: (1 instance) Custom property `--r` likely involved in a visual effect.
    *   `background`: (1 instance) Simple background change.
    *   `opacity, translate`: (1 instance) Fading and moving.
    *   `opacity, filter, scale, translate`: (1 instance) Complex animation involving multiple properties.

*   **CSS Animations**:
    *   `ht-tag-in`: (3 instances) Suggests an animation for tags or labels appearing.
    *   `rise`: (2 instances) Applied to `hero-title`, indicating the main headline animates upwards, likely on page load or scroll.
    *   `ht-type`: (1 instance) Possibly a typing effect or text animation.
    *   `hero-recede`: (1 instance) Applied to `hero-product`, suggesting a product visual recedes, potentially creating depth or revealing other content.

No carousels or explicit keyframe names were detected in the provided data.

## Interactive Patterns

*   **Sticky Navigation**: Section 2, the `header.site-header.shell.glass`, is likely a sticky navigation bar. The `glass` class suggests a frosted or translucent background effect, and the presence of navigation links and a menu button indicates it remains accessible as the user scrolls.
*   **Hover States**: Numerous CSS transitions for `background-color`, `color`, `border-color`, `box-shadow`, and `transform` on buttons (`button.menu-button`) and other interactive elements indicate rich hover states. For example, buttons transition `background-color` and `transform`, implying visual feedback and subtle movement on hover. The CSS variables `--button-ghost-bg-hover` and `--button-ghost-text-hover` confirm specific hover styling for ghost buttons.
*   **Interactive Demos/Playground**: Section 12, "Playground," and Section 13, "Edits Rail," strongly suggest an interactive demo area where user actions directly influence displayed code or visual output.
*   **Pricing Cards**: Sections 17 and 18 are pricing cards, which typically involve interactive elements like "Sign Up" buttons and possibly hover effects to highlight features or tiers.

## Responsive Notes

The page appears to be designed with responsiveness in mind, as indicated by the presence of `flex` and `grid` layouts in many sections. The `breakpoints` data shows that the page is currently matching `mobile`, `tablet`, `desktop`, and `wide` viewports, implying the extraction was performed at a wide resolution (2667px viewport width). Sections with `flex-direction: column` on smaller screens would likely stack vertically, while `grid` layouts would adapt by changing column counts or reordering elements. The `shell` class used in many sections suggests a common container width that likely adjusts responsively, centering content and providing consistent padding.

## Known Gaps

*   **Off-screen/Lazy-loaded Content**: The `main` tag has a significant height (~14582px), but not all content within this vast area is explicitly detailed in the `pageSections` array. There might be additional sections or dynamically loaded content not captured.
*   **Exact Image/Media Content**: While `hero.hasBackgroundMedia` is true and component hints mention "imagery," specific image URLs or video sources are not provided.
*   **Full Interactivity Details**: The JSON indicates many CSS transitions and animations, but the precise JavaScript-driven interactions (e.g., what triggers specific animations, how the playground works, form submission flows) are not fully discernible from the static HTML/CSS extraction.
*   **Carousel Details**: The `carousels` array is empty, implying no standard carousel components were detected, or they are custom implementations not recognized by the extractor.
*   **Form Flows**: While `input` components are present, the structure and flow of any forms (e.g., contact forms, sign-up forms) are not detailed.
*   **Dynamic Content**: Any content loaded via AJAX or client-side rendering after the initial page load would not be fully represented.