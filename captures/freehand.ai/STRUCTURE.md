## Page Overview

This document outlines the structure and UX patterns of the Freehand AI "Global Trade" marketing landing page. The page is a long-form marketing asset designed to inform users about Freehand's AI agents for trade and compliance. It features 12 distinct content sections (excluding the main wrapper), guiding the user through the product's benefits, how it works, features, integrations, resources, and frequently asked questions, culminating in a call to action. The scroll rhythm is linear, with each section presenting a clear block of information, often featuring imagery or interactive elements. The primary user journey is to educate potential customers about the value proposition of Freehand's AI in global trade, build trust through statistics and client logos, and ultimately drive them towards requesting a demo or downloading resources.

## Section Map

1.  **Section 1 — Hero**: `section.section_pp_hero`, approx. height 1271px, `display: block`.
    *   Contains the main headline, likely subcopy, and potentially a call to action.
    *   `componentHints`: `hero`, `imagery`.

2.  **Section 2 — Stats & Social Proof**: `section.section_pp_stats`, approx. height 943px, `display: block`.
    *   Displays key statistics and a logo marquee of trusted partners.
    *   `componentHints`: `stats`, `imagery`.

3.  **Section 3 — Problem/Solution Tabs**: `section.section_logitics_tab`, approx. height 5314px, `display: block`.
    *   A large section likely presenting problems and Freehand's solutions using a tabbed interface.
    *   `componentHints`: `imagery`.

4.  **Section 4 — Navigation Banner**: `div.nav_component`, approx. height 70px, `display: block`.
    *   A navigation or announcement banner, possibly sticky or appearing on scroll.
    *   `componentHints`: `navigation`, `imagery`, `buttons`.

5.  **Section 5 — Main Navigation**: `nav.nav_menu_wrap`, approx. height 69px, `display: block`.
    *   The primary navigation menu, likely part of the banner in Section 4.
    *   `componentHints`: `navigation`, `imagery`, `buttons`.

6.  **Section 6 — How It Works**: `section.section_gt_hiw`, approx. height 1096px, `display: block`.
    *   Explains the operational flow of Freehand's AI validation.
    *   `componentHints`: `video`, `imagery`.

7.  **Section 7 — Features**: `section.section_pp_features`, approx. height 826px, `display: block`.
    *   Highlights specific areas where Freehand's AI recovers and protects value.
    *   `componentHints`: `feature-grid`, `imagery`.

8.  **Section 8 — Integrations**: `section.section_int`, approx. height 919px, `display: block`.
    *   Details how Freehand integrates with existing systems.
    *   No specific component hints, but likely contains integration logos or descriptions.

9.  **Section 9 — Resources**: `section.section_pp_resources`, approx. height 1026px, `display: block`.
    *   Showcases insights and best practices, likely blog posts or case studies.
    *   `componentHints`: `imagery`.

10. **Section 10 — FAQ**: `section.section_faq`, approx. height 1154px, `display: block`.
    *   A frequently asked questions section, likely using an accordion pattern.
    *   `componentHints`: `faq`.

11. **Section 11 — Call to Action**: `section.section_cta`, approx. height 775px, `display: block`.
    *   A prominent call to action encouraging users to engage further.
    *   `componentHints`: `cta`, `imagery`.

12. **Section 12 — Footer**: `footer.footer_component`, approx. height 1100px, `display: block`.
    *   The page footer containing navigation, links, and copyright information.
    *   `componentHints`: `footer`, `imagery`.

## Hero Deep-Dive

The main hero section is `pageSections[1]` (`section.section_pp_hero`).
*   **Layout Structure**: The hero features a prominent headline: "Duties, tariffs, and broker fees - checked before you pay" (`h1.careers_hero_heading`). Based on typical marketing page structures, this headline is likely followed by supporting subcopy and one or more calls to action. The `componentHints` suggest `imagery`, indicating a visual element complementing the text.
*   **Background Type**: The `componentHints` include `imagery`, suggesting an image or potentially a video background for visual impact.
*   **CTA Count and Placement**: The provided `hero` object (which refers to a small banner, not this main hero) indicates 0 CTAs. However, a main hero section typically includes at least one primary CTA. Without explicit button selectors within `pageSections[1]`, the exact count and placement are not determinable from the provided data, but it's highly probable there's at least one "Request a Demo" or similar button.
*   **Typography Hierarchy**: The main headline uses a large, light font: `fontFamily: "BL Pylon Serif", fontSize: "58px", fontWeight: "300", lineHeight: "69.6px", letterSpacing: "-0.812px"`. This establishes a clear visual hierarchy, with supporting text likely using `Fustat` at smaller sizes.

## Component Inventory

| Component         | Count | Location