## Page Overview

This is a marketing landing page for "defocus.me — One clear window.", an application designed to help users focus. The page consists of 9 distinct sections, including the header and footer. The scroll rhythm is generally smooth, alternating between full-width content blocks and sections with more structured layouts like grids. The primary user journey guides visitors from understanding the core value proposition (hero), through detailed features, customization options, native integration, pricing, and finally to a FAQ section and footer.

## Section Map

1.  **Section 0 — Site Header**: `header` tag, ~84px height, flex layout.
    *   `a` (logo/brand link)
    *   `nav` (main navigation links)
    *   `div` (likely contains a CTA button)
    *   Component hints: navigation, imagery, buttons.

2.  **Section 1 — Main Content Area**: `main` tag, ~5453px height, block layout.
    *   Contains all primary content sections of the page.
    *   Component hints: imagery, buttons.

3.  **Section 2 — Hero Section**: `section` tag with class `hero`, ~1167px height, block layout.
    *   `a` (likely a small introductory text or link)
    *   `h1` (main headline)
    *   `p` (subcopy)
    *   `div` (contains CTA buttons and possibly media)
    *   Component hints: hero, imagery, buttons.

4.  **Section 3 — Features Section**: `section` tag with classes `features`, `section`, ~1000px height, block layout.
    *   `div` (likely contains feature cards or grid items)
    *   Heading: "Everything you need to focus.Nothing asking for your attention."
    *   Component hints: feature-grid.

5.  **Section 4 — Personal Focus Section**: `section` tag with classes `section`, `personal-focus`, ~541px height, grid layout (`gridTemplateColumns: 418.976px 486.024px`, `gap: 75px`).
    *   `div` (likely contains content for the grid columns, such as text and imagery)
    *   Heading: "A setting forevery mindset."
    *   Component hints: imagery, buttons.

6.  **Section 5 — Native Integration Section**: `section` tag with classes `native-section`, `section`, ~700px height, block layout.
    *   `div` (likely contains content related to Mac integration, potentially imagery or a carousel)
    *   Heading: "Feels like part of your Mac."
    *   Component hints: imagery.

7.  **Section 6 — Pricing Section**: `section` tag with classes `pricing-section`, `section`, ~560px height, block layout.
    *   `div` (likely contains pricing details and CTAs)
    *   Heading: "A little investmentin your attention."
    *   Component hints: pricing, imagery, buttons.

8.  **Section 7 — FAQ Section**: `section` tag with classes `faq-section`, `section`, ~420px height, block layout.
    *   `div` (likely contains a list of frequently asked questions and answers, possibly as accordions)
    *   Heading: "A few things you might wonder."
    *   Component hints: faq.

9.  **Section 8 — Footer**: `footer` tag, ~129px height, block layout.
    *   `a` (logo/brand link or social links)
    *   `nav` (footer navigation links)
    *   `p` (copyright or legal text)
    *   Component hints: imagery.

## Hero Deep-Dive

The hero section (`section.hero`) is a prominent block spanning the full width of the viewport and approximately 1167px in height. It features a large `h1` headline "One clear window.A little more headspace." followed by a `p` element for subcopy. The layout is block-based, suggesting a stacked arrangement of text content. The background is an `image`, as indicated by `hero.backgroundType` and `hasBackgroundMedia: true`. There are 10 CTA buttons detected within this section, indicating multiple calls to action or a complex interactive element (e.g., a media player with controls). The typography hierarchy is led by the `h1` using the serif font "Instrument Serif" at ~50.87px, followed by a smaller `p` element (likely ~15px SF Pro Text) and button text (e.g., 14px SF Pro Text for "Download for Mac").

## Component Inventory

| Component    | Count | Location