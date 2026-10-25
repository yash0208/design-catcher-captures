## Page Overview

This document outlines the structure and UX patterns of a marketing landing page for Zamp's U.S. Sales Tax Solutions, titled "U.S. Sales Tax Solutions | Zamp". The page is designed to inform potential customers about Zamp's offerings for managing sales tax. It features 11 distinct sections, including a prominent hero, a client logo marquee, problem/solution blocks, expert testimonials, integration showcases, and an extensive FAQ section, culminating in a call-to-action in the footer.

The scroll rhythm is typical for a marketing page, guiding the user through the problem, Zamp's solution, key features, and trust signals before addressing common questions. The primary user journey involves understanding the complexities of sales tax, seeing how Zamp simplifies it, building trust through testimonials and integrations, and ultimately engaging with the company for more information or a demo.

## Section Map

1.  **Section 0 — Global Navigation**: `div` tag, approximately 72px height, flex layout.
    *   Contains the main navigation menu (`navbar_menu`), likely including branding, product/solution links, and calls to action (e.g., login, contact).
    *   Component hints: navigation, imagery, buttons.

2.  **Section 1 — Main Content Wrapper**: `main` tag, approximately 5915px height, block layout.
    *   Serves as the primary container for all content sections below the header.
    *   Component hints: imagery.

3.  **Section 2 — Hero**: `section` tag, approximately 944px height, block layout.
    *   Features the main headline: "The smartest way to manage U.S. sales tax."
    *   Likely includes a subcopy and primary call-to-action.
    *   Component hints: imagery.

4.  **Section 3 — Trust/Social Proof**: `section` tag, approximately 285px height, block layout.
    *   Likely contains a client logo marquee or testimonials, indicated by "Trusted by 1,200+ finance and accounting teams."
    *   Component hints: imagery.

5.  **Section 4 — Problem/Solution Introduction**: `section` tag, approximately 754px height, block layout.
    *   Highlights the problem: "50+ states & territories. 13,000+ jurisdictions. Zero room for error."
    *   Presents Zamp as "the next-gen managed sales tax platform."
    *   Features a dark background with a bottom-left pattern.
    *   Component hints: imagery.

6.  **Section 5 — Solution Overview**: `section` tag, approximately 373px height, block layout.
    *   Introduces "How Zamp fully manages sales tax — from first sale to final remittance."
    *   Features a beige background.
    *   Component hints: None explicitly listed, but likely includes text and possibly supporting visuals.

7.  **Section 6 — Product Tabs/Features**: `section` tag, approximately 928px height, block layout.
    *   Likely presents detailed features or product modules using a tabbed interface (e.g., "Tax calculations", "Nexus & registration", "Filing & remittance").
    *   Features a beige background.
    *   Component hints: imagery.

8.  **Section 7 — Expert Support**: `section` tag, approximately 879px height, block layout.
    *   Focuses on human expertise: "Real tax experts, when you need them."
    *   Component hints: imagery.

9.  **Section 8 — Integrations**: `section` tag, approximately 821px height, block layout.
    *   Showcases platform integrations: "Integrations built for where you sell."
    *   Includes a call-to-action: "Everything you need for U.S. sales tax — in one place."
    *   Component hints: imagery.

10. **Section 9 — FAQs**: `section` tag, approximately 931px height, block layout.
    *   Provides answers to frequently asked questions: "FAQs."
    *   Features a light beige background.
    *   Component hints: faq.

11. **Section 10 — Footer**: `footer` tag, approximately 1137px height, block layout.
    *   Contains a final call-to-action: "Get sales tax off your plate."
    *   Includes navigation links, contact information, and other legal/company details.
    *   Component hints: footer, imagery.

## Hero Deep-Dive

The primary hero content is located in Section 2 (`pageSections[2]`).
*   **Layout Structure**: The hero uses a block layout, suggesting a top-down flow of content. It features a prominent `h1` headline: "The smartest way to manage U.S. sales tax." This headline is centrally placed (x=300, width=632 within a 1233px viewport), indicating a strong visual focus. Below the headline, there's likely a subcopy ("We handle calculations, filings, regis...") and potentially CTAs, though no specific buttons are identified in the `domLandmarks` for this exact `bbox`.
*   **Background Type**: The hero section (`section_component`) does not explicitly declare a background image or video. Its `backgroundColor` is transparent, implying the body background or a parent element's background (white) is visible, or there's a subtle background pattern not captured as an image.
*   **CTA Count and Placement**: No explicit CTA buttons are identified directly within the hero's `bbox` in the provided `domLandmarks`. However, a typical marketing hero would include at least one primary CTA. Given the `navbar_component` has button hints, it's possible the main CTA is part of the sticky navigation or immediately below the visible hero fold.
*   **Typography Hierarchy**: The main headline is an `h1` with `font-family: Seasonmix, Arial, sans-serif`, `font-size: 35.8871px`, and `font-weight: 400`. This establishes a clear visual hierarchy, with the `Seasonmix` font likely being a display font for impact. Subcopy and other text would follow with `Seasonsans` at smaller sizes.

## Component Inventory

| Component | Count | Location | Description |
| :-------- | :---- | :------- | :---------- |
| Button    | 17    | Navigation, various sections | Interactive elements, likely for navigation, form submission, or calls to action. Styles suggest standard buttons. |
| Navigation | 6     | Header | Main site navigation, likely including dropdowns. |
| Input     | 4     | Footer (form) | Form input fields for user data entry, styled with a light beige background and a border. |
| Footer    | 1     | Bottom of page | Contains site-wide links, contact info, and a final CTA. Dark background. |
| Heading   | 1     | Hero | Main page title, large and prominent. |
| Hero      | 1     | Top of page (Section 2) | The main introductory section of the page. |
| Testimonial | 1     | Section 3 (implied) | A component for displaying customer reviews or endorsements. |
| FAQ       | 54    | Section 9 | Accordion-like components for frequently asked questions, with titles and expandable answers. |
| Marquee   | 1     | Section 3 | A horizontally scrolling display of customer logos. |
| Card      | 9     | Various sections | General-purpose content containers, often used for layout and grouping. |
| Card      | 9     | Various sections | General-purpose content containers, often used for layout and grouping. |
| Card      | 7     | FAQ section | Specific card-like containers for FAQ answers, likely hidden by default. |
| Card      | 7     | Footer | List of links within the footer, structured as cards. |
| Card      | 6     | Various sections | General-purpose content containers with section-level padding. |

## Motion & Animation

The page incorporates several motion and animation elements:

*   **Marquee**: An infinite, right-to-left scrolling marquee (`customers-logo-component`) is present in Section 3, displaying customer logos. This uses a CSS animation named `customers-logo-marquee-rtl`. It's identified as a "marquee" type carousel with no visible controls, suggesting it loops automatically.
*   **CSS Transitions**:
    *   `background-color`: 7 instances, likely for hover states on buttons or interactive elements.
    *   `border-color, color, background-color`: 4 instances, also indicative of hover or focus states for interactive elements like buttons or links.
    *   `transform`: 2 instances, potentially for subtle scaling or movement on hover, or for interactive elements like dropdowns.
    *   `opacity`: 1 instance, possibly for fade-in/out effects on elements or overlays.
*   **Transform**: A specific `transform: matrix(1, 0, 0, 1, -2797.96, 0)` is detected, which is likely part of the marquee animation for horizontal translation.

No complex scroll-triggered animations or other advanced library-based animations (like Framer Motion) are explicitly identified beyond the marquee.

## Interactive Patterns

*   **Sticky Navigation**: The `navbar_component` (Section 0) is likely sticky or fixed at the top, given its common usage in `w-nav` class systems and its position at y=32.
*   **Hover States**: Multiple CSS transitions (`background-color`, `border-color`, `color`, `transform`, `opacity`) are present, indicating that interactive elements like buttons, links, and possibly navigation items will change appearance on hover.
*   **Accordions**: The presence of the `faq` component in Section 9, with `faq_question_title` and `faq_answer-container` elements, strongly suggests an accordion pattern where clicking a question reveals its answer.
*   **Form Flow**: The footer contains `input` components, indicating a form (likely for lead generation or contact) is present.

## Responsive Notes

The page is built with responsiveness in mind, as indicated by the `breakpoints` data:
*   **Mobile (min-width: 0)**, **Tablet (min-width: 768px)**, and **Desktop (min-width: 1024px)** breakpoints are active. A `wide` breakpoint (min-width: 1440px) is defined but not currently matched.
*   The `w-nav-overlay` media query for `max-width: 991px` suggests that the main navigation (`navbar_menu`) likely transforms into a mobile-friendly overlay menu (e.g., a hamburger menu) on smaller screens (tablet and mobile). This overlay is designed to be scrollable (`overflow-y: auto`) and fill the viewport height (`max-height: 100dvh`).
*   Section layouts, currently shown as `block` for most main sections, would likely adapt using flexbox or grid properties (not fully captured in `pageSections.layout` for nested elements) to stack vertically on smaller screens and arrange horizontally on wider viewports. For example, the problem/solution cards in Section 4 would probably stack on mobile.

## Known Gaps

*   **Specific Image Content**: While `componentHints` frequently mention "imagery," the extraction does not provide details about the actual images (e.g., URLs, alt text, purpose), making it difficult to fully assess visual content and its role.
*   **Detailed Layout for Nested Components**: The `pageSections` `layout.display` often shows "block" for the main section container. However, the internal layout of components (e.g., how cards are arranged within a section, or the precise structure of the hero's text and CTAs) is not fully detailed at this level.
*   **JavaScript-driven Interactions**: Beyond the CSS animations and transitions, any complex interactive elements (e.g., dynamic content loading, custom form validation, advanced tab functionality in Section 6, or other JS-only components) are not explicitly captured.
*   **Off-screen/Lazy-loaded Content**: The extraction captures the current viewport state. Any content that is initially off-screen and lazy-loaded, or dynamically injected by JavaScript, would not be fully represented.
*   **Full CTA Details**: While buttons are identified, the specific text, linking destinations, and exact placement of all calls-to-action within each section are not exhaustively listed.