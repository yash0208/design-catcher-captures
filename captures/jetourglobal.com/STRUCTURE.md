## STRUCTURE.md

## Page Overview

This is a product landing page for the JETOUR G700 vehicle, focused on showcasing its features and specifications. The page title "JETOUR G700, JETOUR G700 photos, JETOUR G700 specs, JETOUR G700 review" confirms its dedicated product nature. It consists of 4 main sections, starting with a full-viewport hero experience. The scroll rhythm appears to be section-based, with each section likely highlighting a different aspect of the vehicle. The primary user journey involves exploring the car's attributes through visual content and descriptive text, culminating in potential engagement through the footer links.

## Section Map

1.  **Section 0 — Global Header**: `header` tag, 48px height, `display: block`.
    *   Contains the main navigation (`nav` tag) with branding, menu items (Models, JETOUR World, etc.), and language selection.
    *   Layout is `fixed` to the top, ensuring persistent navigation.
2.  **Section 1 — Main Navigation**: `nav` tag, 48px height, `display: flex`.
    *   Direct child of the header, responsible for the primary site navigation.
    *   Organizes navigation links and possibly utility actions like language switch.
3.  **Section 2 — Hero Section**: `section` tag, 1143px height (full viewport height), `display: block`.
    *   This is the main hero area, likely featuring a large visual of the car.
    *   Contains text like "Exceptional Off-Road Performance" and "Rapid Acceleration: 0-100 km/h in 4.6s", suggesting key feature highlights.
    *   `componentHints` suggest imagery is a primary element.
4.  **Section 3 — Global Footer**: `footer` tag, 377px height, `display: block`.
    *   Provides site-wide links, categorized under headings like "Models", "JETOUR World", and "Media Center".
    *   Includes a "Follow Us" section, likely with social media links.

## Hero Deep-Dive

The hero section (Section 2) is a full-viewport `section` element (`h-svh`) with a `relative` positioning. It serves as the primary visual introduction to the JETOUR G700.

*   **Layout Structure**: The hero itself is a full-width, full-height container. While `hero.headlineCount` and `ctaButtonCount` are reported as 0 for direct children, the `textSample` for the hero section ("Exceptional Off-Road PerformanceRapid Acceleration: 0-100 km/h in 4.6sHigh Effic") strongly indicates that prominent headlines and subcopy are present *within* this section, likely nested deeper or dynamically generated. The content suggests a focus on performance and off-road capabilities.
*   **Background Type**: The `hero.backgroundType` is "image", and `hero.hasBackgroundMedia` is true, indicating a large, impactful image or a series of images as the primary visual element. This is common for automotive product pages.
*   **CTA Count and Placement**: No explicit CTA buttons were directly identified by the `hero` analysis, which is unusual for a product hero. However, given the nature of the page, there might be interactive elements or calls to action that were not classified as "buttons" in this specific analysis.
*   **Typography Hierarchy**: Based on the `textSample`, there are likely large, bold headlines (e.g., "Exceptional Off-Road Performance") and smaller, descriptive text providing details (e.g., "Rapid Acceleration: 0-100 km/h in 4.6s"). The `Goldman` font family (38.5312px, 500 weight) is likely used for prominent headings, while `HarmonyOS Sans` (16.6969px, 400 weight) might be used for subcopy.

## Component Inventory

| Component | Count | Location | Description |
| :-------- | :---- | :------- | :---------- |
| Button    | 16    | Header, various sections | Interactive elements, likely for navigation, language selection, or other actions. |
| Nav       | 1     | Section 1 (Header) | Primary navigation menu for the website. |
| Footer    | 1     | Section 3 | Contains site-wide links, contact information, and social media links. |
| Heading   | 1     | Possibly within Hero or subsequent sections | A large heading, `h1.text-[0.6rem]`, likely used for a main title or section title. |
| Hero      | 1     | Section 2 | The main introductory section of the page, full-viewport height. |
| Carousel  | 13    | Likely within Hero or subsequent content sections | Multiple instances of carousels, often `sticky` and `h-svh`, suggesting full-screen image/video sliders. The `swiper-container` is the main carousel. |
| FAQ       | 4     | Likely a dedicated section | Accordion-style components for displaying frequently asked questions or detailed specifications. |
| Card      | 46    | Throughout the page | Versatile content containers, used for various purposes like displaying features, images, or interactive elements. Examples include `.absolute`, `.w-full`, `.size-full`, and `.relative` positioned cards. |

## Motion & Animation

The page heavily utilizes animations and transitions, particularly for interactive elements and content presentation.

*   **Library Animations**:
    *   **Swiper**: Used extensively for carousels (14 instances detected). This indicates smooth, interactive content sliders for images, videos, or feature blocks.
    *   **Tailwind-Animate**: 9 instances, suggesting utility-class based animations, possibly for UI elements or transitions.
*   **CSS Animations**:
    *   `fadeInUp`: A CSS animation causing elements to fade in while moving upwards. Used on text elements (e.g., `text-[0.28rem]`, `md:text-2xl`, `opacity-50`).
    *   `fadeOutUp`: A CSS animation causing elements to fade out while moving upwards. Used on text elements, likely for transitions or when elements are hidden.
*   **CSS Transitions**:
    *   `transform`: 12 instances, indicating elements changing position, scale, or rotation smoothly.
    *   `color, background-color, border-color, outline-color, text-decoration-color, fill, stroke, --tw-gradient-from, --tw-gradient-via, --tw-gradient-to`: 5 instances, for smooth color changes on hover or state changes.
    *   `grid-template-rows`: 3 instances, suggesting dynamic grid layout changes.
    *   `transform, translate, scale, rotate`: 2 instances, for more specific transform animations.
    *   `opacity`: 2 instances, for fade-in/out effects.
    *   `translate, width`: 1 instance, for elements that slide and change width.
*   **Carousels**:
    *   A primary linear carousel (`div.sticky`, `home-swiper`, `swiper-container`) with `both` control style (likely arrows and pagination/dots) and an estimated 7 slides. This is a full-viewport carousel, often used for hero sections or main feature showcases.
    *   Multiple `swiper-slide` instances, some with `arrows` control, others with `none`, suggesting various types of carousels or individual slides within a larger carousel structure.

## Interactive Patterns

*   **Sticky Navigation**: The `header` (Section 0) is `fixed` to the top (`fixed top-0`), making it a sticky navigation bar that remains visible as the user scrolls.
*   **Accordion/FAQ**: The presence of `faq` components with `data-[state=open]` and `data-[state=closed]` attributes, along with `accordion-down` and `accordion-up` animations, indicates an interactive accordion pattern. Users can click to expand/collapse content sections, likely for detailed specifications or FAQs.
*   **Carousel Navigation**: Carousels are interactive, featuring `both` control styles (likely arrows and pagination) for manual navigation between slides.
*   **Button Interactions**: Buttons (`button.cursor-pointer`) are present, implying click interactions for various actions. While hover states are not explicitly detailed in the provided data, they are a standard interactive pattern for buttons.

## Responsive Notes

The page is designed with responsiveness in mind, using breakpoints and responsive utility classes:

*   **Breakpoints**: The detected breakpoints are `mobile` (0px), `tablet` (768px), and `desktop` (1024px). The `wide` breakpoint (1440px) is also defined but not currently matched.
*   **Header/Navigation**: The header uses `px-12` for padding on larger screens and `md:px-[0.7rem]` for medium (tablet) screens, indicating adjusted spacing.
*   **Hero Section**: The hero section uses `pt-60` for padding on larger screens and `md:pt-[1.88rem]` for medium screens, adapting its top padding. Its `h-svh` class ensures it takes up the full viewport height across different device sizes.
*   **Typography**: Text elements like `h2` use `text-2xl` and `h3` uses `text-[0.24rem]` with `md:text-base`, showing font size adjustments for different screen sizes.
*   **Layout**: The use of `flex` and `grid` (implied by `grid-template-rows` transitions) layouts, combined with responsive classes, suggests content will reflow and adapt to available screen width.

## Known Gaps

*   **Hero Content Details**: While the `hero.textSample` indicates headlines and subcopy, the `hero.headlineCount` and `ctaButtonCount` are reported as 0. This suggests that the extraction might not have identified these elements as direct children of the hero or as standard headline/button components, possibly due to complex nesting or custom component structures.
*   **Off-screen/Lazy-loaded Content**: The extraction data does not provide information about content that might be off-screen initially or lazy-loaded as the user scrolls.
*   **Full Component Details**: While `components[]` lists many cards, their specific content and purpose within each section are not fully detailed without deeper DOM inspection.
*   **Specific Image/Video Content**: The `backgroundType: "image"` for the hero and the presence of carousels imply rich media, but the actual images or videos are not part of this structural analysis.
*   **Form Functionality**: No explicit form components were identified, though a product page might typically include forms for inquiries or test drives.