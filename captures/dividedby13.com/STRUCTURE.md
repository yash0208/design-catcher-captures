## Page Overview

This is a marketing and product landing page for "Divided by 13 Amplifiers," designed to showcase their handcrafted guitar amplifiers. The page features 6 primary content sections, excluding the header and footer, creating a varied scroll rhythm. It begins with a large, impactful hero section, followed by an introductory text block, a horizontal product scroller, and an Instagram feed for social engagement. The user journey is designed to introduce the brand's philosophy, highlight key products, and encourage further exploration and community interaction.

## Section Map

1.  **Section 2 — Main Header**: `header` tag, approximate height 103px, `block` layout.
    *   Contains the site logo and the main navigation menu.
    *   **Child Element**: `nav` (Section 3) - The primary navigation links.
2.  **Section 1 — Hero**: `section.home-hero` tag, approximate height 767px, `flex` layout with `flexDirection: column`.
    *   Features a large headline, a call-to-action button, and a prominent background image.
3.  **Section 4 — Home Introduction**: `section.home-intro` tag, approximate height 584px, `block` layout.
    *   Provides descriptive text about the brand's quality and philosophy.
    *   Includes a `marquee` component (identified by `components[7]`) likely displaying "Hand built amplifiers from California, USA".
4.  **Section 5 — Amplifiers Scroller**: `section.amps-scroller` tag, approximate height 991px, `block` layout.
    *   Displays a collection of amplifier products in a horizontally scrollable format.
    *   Contains individual product cards (`amp-item-inner` component hint).
5.  **Section 6 — Instagram Feed**: `section.instagram-feed` tag, approximate height 866px, `block` layout.
    *   Integrates an Instagram feed, showcasing posts related to the brand.
    *   Composed of multiple carousel/card components (`sbi_item`).
6.  **Section 7 — Main Footer**: `footer.main-footer` tag, approximate height 1520px, `block` layout.
    *   Contains copyright information, social media links, a newsletter subscription form, and extensive navigation.
    *   **Child Element**: `nav` (Section 8) - Detailed sitemap-like navigation for products and other pages.

## Hero Deep-Dive

The hero section (`section.home-hero`) is a full-width, substantial block (1140px wide, 767px tall) at the top of the page. Its layout is a `flex` container with `flexDirection: column`, indicating content is stacked vertically.

*   **Headline**: A single, dominant headline "Turn it up. Break the rules." is present. It uses the "Bulevar" font at an extremely large size (200px) and heavy weight (800), making a strong visual statement.
*   **Subcopy**: No explicit subcopy is detected, but the large headline and CTA suggest a direct, impactful message.
*   **CTAs**: There is 1 primary call-to-action button, likely with the text "Explore amps" (inferred from typography samples).
*   **Background**: The hero features a `backgroundType: image`, indicating a visually rich backdrop.
*   **Typography Hierarchy**: The headline is the largest and most prominent text on the page, establishing a clear visual hierarchy.

## Component Inventory

| Component      | Count | Location                                  | Description