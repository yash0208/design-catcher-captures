## STRUCTURE.md

## Page Overview

This is a marketing landing page for "Soale," a creative studio focusing on AI, brands, and digital futures. The page is a long-scrolling experience, structured into 20 distinct sections, including the navigation and footer. The scroll rhythm is characterized by vertically stacked, full-width sections of varying heights, creating a dynamic flow of content. The primary user journey guides visitors from an engaging hero introduction to understanding the studio's purpose, showcasing their portfolio and services, building trust through testimonials and process explanations, detailing pricing, and finally, prompting engagement via a call to action and FAQs.

## Section Map

1.  **Section 0 — Global Navigation**: `nav`, height ~108px, flex layout.
    *   Contains branding (likely a logo), primary navigation links (e.g., "About us", "Work", "Services", "Pricing", "Blog"), and a "Start a project" call-to-action button.
2.  **Section 1 — Main Content Wrapper**: `main`, height ~13658px, flex column layout.
    *   Acts as the primary container for all major content sections of the page.
3.  **Section 2 — Hero Section**: `section`, height ~883px, flex layout.
    *   Features a prominent headline: "Creative studio powering AI, brands & digital futures", a sub-headline "Design studio for AI & tech startups", and a background image or video.
4.  **Section 3 — Introduction/Purpose**: `section`, height ~822px, flex layout.
    *   Headline: "We design with purpose. We build with intelligence." Likely introduces the studio's philosophy or core values, possibly with supporting imagery.
5.  **Section 4 — Client Success/Support**: `section`, height ~861px, flex layout.
    *   Headline: "Your success, supported". Details the studio's commitment to client support and service quality.
6.  **Section 5 — Outcomes & Results**: `section`, height ~1121px, flex layout.
    *   Headline: "Outcomes that speak for themselves". Likely showcases metrics, case studies, or client achievements.
7.  **Section 6 — Project Portfolio**: `section`, height ~2824px, flex layout.
    *   Headline: "Featured Design + AI Project portfolio". Displays multiple project cards (e.g., "Vireo – Mental Health Care App", "Solara – Smart Home Dashboard", "OrbitPay – Banking and Fintech App", "NeuronIQ – AI-Powered Hiring Assistant", "Echo – AI Analytics Platform Design").
8.  **Section 7 — Services Overview**: `section`, height ~919px, flex column layout.
    *   Headline: "Services and solutions we offer." Introduces the range of services provided by the studio.
9.  **Section 8 — Detailed Services/Features**: `section`, height ~445px, flex layout.
    *   Contains specific service descriptions like "UI/UX Design" and "24/7 Priority Response", possibly presented as cards or list items. Includes a `fieldset`, suggesting interactive elements or a mini-form.
10. **Section 9 — Design Process**: `section`, height ~757px, flex column layout.
    *   Headline: "We simplify product Design process". Explains the studio's methodology or workflow.
11. **Section 10 — Target Audience/Value Proposition**: `section`, height ~1000px, flex layout.
    *   Headline: "Built for founders, Fine-tuned for teams." Addresses the specific benefits for founders and teams.
12. **Section 11 — Trust & Testimonials Introduction**: `section`, height ~936px, flex layout.
    *   Headline: "Trusted by forward - Thinking teams". Serves as an introductory section for client endorsements or trust signals.
13. **Section 12 — Testimonial Carousel**: `section` (framer-slideshow), height ~450px, flex layout.
    *   Displays client testimonials or quotes in a linear carousel format.
14. **Section 13 — Flexible Pricing**: `section`, height ~1127px, flex layout.
    *   Headline: "Flexible Pricing". Presents different pricing plans or service tiers.
15. **Section 14 — Case Studies & Insights Introduction**: `section`, height ~828px, flex layout.
    *   Headline: "Case Studies & Insights". Introduces a section dedicated to more in-depth project analyses or thought leadership.
16. **Section 15 — Case Studies Carousel**: `section` (framer-slideshow), height ~400px, flex layout.
    *   Showcases various case studies or project highlights in a linear carousel.
17. **Section 16 — Frequently Asked Questions**: `section`, height ~830px, flex layout.
    *   Headline: "Frequently Asked Questions". Likely contains an accordion component for common queries.
18. **Section 17 — Call to Action**: `section`, height ~489px, flex layout.
    *   Headline: "Get started for free". A prominent section designed to convert visitors into leads or customers.
19. **Section 18 — Visual Separator/Background**: `section`, height ~260px, flex column layout.
    *   A content-less section, possibly used for visual separation or to display a background element.
20. **Section 19 — Footer**: `footer`, height ~239px, flex layout.
    *   Contains copyright information, social media links, and other auxiliary navigation.

## Hero Deep-Dive

The hero section (`section.framer-4yhrb9`) is the first content block on the page, immediately following the navigation.
*   **Layout Structure**: It utilizes a flex layout (`display: flex`, `gap: 10px`), suggesting its internal elements are arranged flexibly. It features a central headline stack.
*   **Headline Stack**: The primary headline is an `h1` reading "Creative studio powering AI, brands & digital futures." A secondary, smaller text "Design studio for AI & tech startups" acts as a tagline or introductory statement.
*   **Subcopy**: While not explicitly labeled as subcopy, the smaller text serves this role.
*   **CTAs**: The `hero` object indicates `ctaButtonCount: 0`. This suggests the hero might prioritize conveying its message visually and textually, relying on scrolling or other sections for explicit calls to action, or that the primary CTA is not directly within the hero's immediate children but within its broader content area.
*   **Background Type**: The hero features an `image` background (`backgroundType: "image"`, `hasBackgroundMedia: true`), likely a visually striking graphic or photograph relevant to AI, brands, or digital futures.
*   **Typography Hierarchy**: The main headline uses `"Inter Display"` at `64px` font size and `400` weight, establishing a strong visual presence. The tagline uses the same font family at `14px` with `500` weight, providing clear contrast and readability.

## Component Inventory

| Component | Count | Location | Description |
| :-------- | :---- | :------- | :---------- |
| Button | 16 | Throughout the page (e.g., nav, CTAs) | Standard interactive elements for user actions. |
| Navigation Bar | 1 | Top of page (Section 0) | Contains site navigation links and branding. |
| Footer | 1 | Bottom of page (Section 19) | Standard footer with copyright and supplementary links. |
| Heading (H1) | 1 | Hero section (Section 2) | The main, large headline of the page. |
| Carousel (Linear) | 2 | Sections 12, 15 | Displays multiple content slides horizontally, likely for testimonials or case studies. |
| Carousel Controls | 1 | Section 12 (or 15) | Provides navigation controls (arrows) for a carousel. |
| Marquee | 4 | Likely a dedicated section or within another | Continuously scrolling list items, typically used for logos or short, repeating messages. |
| Card (Style 1) | 20 | Throughout portfolio, services, pricing sections | General purpose content container, no specific styling mentioned beyond default. |
| Card (Style 2) | 20 | Throughout portfolio, services, pricing sections | Content container with `28px` bottom padding. |
| Card (Style 3) | 20 | Throughout portfolio, services, pricing sections | Content container with `24px` border-radius, suggesting rounded corners. |
| Card (Style 4) | 20 | Throughout portfolio, services, pricing sections | Content container with white background, `18px` padding, and `12px` border-radius. |
| Card (Style 5) | 20 | Throughout portfolio, services, pricing sections | General purpose content container, no specific styling mentioned beyond default. |

## Motion & Animation

The page makes extensive use of animation to enhance the user experience:

*   **Framer Motion**: The presence of `framer-motion` (123 instances) indicates a sophisticated animation library is used. This suggests a variety of declarative animations, likely including scroll-triggered effects (e.g., fade-ins, slide-ups as elements enter the viewport), interactive hover states, and transitions for elements.
*   **CSS Transform**: Eight instances of a `matrix(0.827081, 0.562083, -0.562083, 0.827081, 0, 0)` transform are detected. This is a 2D transform that combines scaling and skew/rotation, likely applied to elements for subtle visual flair or dynamic effects.
*   **CSS Transition**: A CSS transition on `opacity` is used (1 instance), possibly for smooth page load, element visibility changes, or interactive states.
*   **Carousels**:
    *   **Linear Carousels**: Two instances of `ul.framer--carousel` are present (Sections 12 and 15). These are linear carousels, one with an estimated 6 slides (likely testimonials) and another with 2 slides (likely case studies). They are noted with `controlStyle: "none"`, suggesting they might be auto-playing or rely on swipe gestures without explicit navigation buttons.
    *   **Carousel Controls**: A `fieldset.framer--carousel-controls` component is identified with `controlStyle: "arrows"` and 2 estimated slides. This likely provides explicit left/right arrow navigation for one of the linear carousels.
    *   **Marquee Carousels**: Four `li.ticker-item` elements are identified as marquee-type carousels. These are typically used for creating continuously scrolling horizontal content, such as client logos or short, repeating phrases, providing a dynamic background or informational strip.

## Interactive Patterns

*   **Navigation**: A standard top navigation bar is present with links and a call-to-action button. No explicit sticky behavior was detected in the provided styles.
*   **Hover States**: While not explicitly detailed in the CSS, it is highly probable that buttons, navigation links, and various card components feature hover states (e.g., background color changes, slight scaling, or shadow effects) for improved user feedback.
*   **Carousels**: The page employs both linear carousels (potentially swipeable or auto-playing) and a marquee-style carousel for continuous content display. One linear carousel explicitly uses arrow controls.
*   **Accordions**: Section 16, titled "Frequently Asked Questions," strongly suggests the implementation of an accordion pattern, where clicking a question reveals or hides its corresponding answer.
*   **Forms**: Section 8 contains a `fieldset`, indicating the presence of form elements, possibly for a contact form, subscription, or interactive input.

## Responsive Notes

The page is designed with standard breakpoints for `mobile` (0px min-width), `tablet` (768px min-width), and `desktop` (1024px min-width), with a `wide` breakpoint (1440px min-width) also defined but not active during extraction.

*   The prevalent use of `display: flex` across most `pageSections` indicates a flexible and adaptable layout.
*   It is expected that `flexDirection` properties will likely adjust from `row` to `column` on smaller screen sizes (tablet and mobile) to stack content vertically, ensuring readability and usability.
*   Spacing values (`gap` and `padding`) will likely be adjusted via media queries to optimize for different screen dimensions, maintaining visual hierarchy and content separation.
*   The `viewport` width of `1214px` during extraction confirms the desktop layout is currently active.

## Known Gaps

*   Specific CSS properties for hover states on buttons, links, and cards are not detailed in the provided data.
*   The exact content and visual styling of the images and videos used for backgrounds (e.g., in the hero section) are not available.
*   Any JavaScript-driven interactions beyond the general `framer-motion` library usage (such as custom form validation logic, modal pop-up behavior, or dynamic content loading) are not explicitly described.
*   Content that might be off-screen or lazy-loaded outside the captured viewport is not included in this analysis.
*   The precise content and styling of the `marquee` items (e.g., specific logos or text phrases) are not fully detailed.
*   The exact pairing of the `fieldset.framer--carousel-controls` with a specific `ul.framer--carousel` is not explicitly defined, though it's likely for one of the linear carousels.
*   The `hero` object reports `ctaButtonCount: 0`, which might be a limitation of the extractor's definition of a "hero CTA" if a button is present within the hero's broader content area but not directly as a primary child.