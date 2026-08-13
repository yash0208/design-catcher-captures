## Page Overview

This document outlines the structure and user experience patterns of "Nepal Bahas - नेपाल बहस: नेपालको खोजमुलक पत्रकारिता," a news and investigative journalism website. The page is a marketing landing page type, designed to present a wide array of news articles across various categories. It features a total of 20 distinct sections, including a sticky navigation bar, a hero section, and numerous content blocks dedicated to different news topics. The scroll rhythm is continuous and content-heavy, with a clear vertical flow of news categories and articles. The primary user journey involves browsing headlines, clicking on articles of interest, and navigating through different news categories.

## Section Map

1.  **Section 0 — Main Navigation**: `nav` tag, approx. 79px height, `display: block`.
    *   Contains global navigation links (गृहपृष्ठ, भर्खरै, समाचार, राजनीति, etc.) and likely a search or utility menu.
    *   Features a sticky behavior, remaining visible as the user scrolls.
    *   Includes imagery (likely a logo) and buttons (e.g., for search or language toggle).

2.  **Section 1 — Hero/Featured News Carousel**: `section` tag, approx. 154px height, `display: block`.
    *   Visually prominent section with a background image.
    *   Displays multiple featured news headlines (`h3` elements) in a card-like format, suggesting a carousel or horizontally scrollable layout for top stories.
    *   Each headline is accompanied by a date/metadata.

3.  **Section 2 — Main Content Area (Banking & Finance)**: `main` tag, approx. 1651px height, `display: block`.
    *   A primary container for several news categories.
    *   Contains imagery and buttons, likely within nested news cards.

4.  **Section 3 — Banking & Finance News Block**: `section` tag, approx. 593px height, `display: block`.
    *   Nested within Section 2.
    *   Dedicated to "बैंकिङ तथा वित्त" (Banking & Finance) news.
    *   Features a prominent heading and multiple news cards with imagery and possibly action buttons.

5.  **Section 4 — Insurance News Block**: `section` tag, approx. 742px height, `display: block`.
    *   Nested within Section 2.
    *   Dedicated to "बीमा" (Insurance) news.
    *   Features a prominent heading and multiple news cards with imagery.

6.  **Section 5 — Main Content Area (Investment & Trade)**: `main` tag, approx. 1470px height, `display: block`.
    *   Another primary container for news categories.
    *   Contains imagery.

7.  **Section 6 — Investment & Trade News Block**: `section` tag, approx. 573px height, `display: block`.
    *   Nested within Section 5.
    *   Dedicated to "लगानी तथा व्यापार" (Investment & Trade) news.
    *   Features a prominent heading and multiple news cards with imagery.

8.  **Section 7 — Remittance News Block**: `section` tag, approx. 721px height, `display: block`.
    *   Nested within Section 5.
    *   Dedicated to "रेमिट्यान्स" (Remittance) news.
    *   Features a prominent heading and multiple news cards with imagery.

9.  **Section 8 — Politics News Block**: `section` tag, approx. 785px height, `display: block`.
    *   Distinct section with a dark background (`bg-[#7f0001]`).
    *   Dedicated to "राजनीति" (Politics) news.
    *   Contains multiple news cards with imagery.

10. **Section 9 — Main Content Area (Economy/Business)**: `main` tag, approx. 1483px height, `display: block`.
    *   Another primary container for news categories.
    *   Contains imagery.

11. **Section 10 — Economy/Business News Block**: `section` tag, approx. 1403px height, `display: block`.
    *   Nested within Section 9.
    *   Dedicated to "अर्थ/व्यापार" (Economy/Business) news.
    *   Contains multiple news cards with imagery and links.

12. **Section 11 — Main Content Area (Interviews)**: `main` tag, approx. 1450px height, `display: block`.
    *   Another primary container for news categories.
    *   Contains imagery.

13. **Section 12 — Interviews News Block**: `section` tag, approx. 1370px height, `display: block`.
    *   Nested within Section 11.
    *   Dedicated to "अन्तर्वार्ता" (Interviews) news.
    *   Contains multiple news cards with imagery.

14. **Section 13 — Photo Feature Section**: `section` tag, approx. 760px height, `display: block`.
    *   Distinct section with a dark background (`bg-[#14222E]`).
    *   Dedicated to "तस्वीर आफै बोल्छ" (Pictures Speak for Themselves).
    *   Likely displays a gallery or featured images with captions.

15. **Section 14 — Main Content Area (Parliamentary Activities)**: `main` tag, approx. 734px height, `display: block`.
    *   Another primary container for news categories.
    *   Contains imagery.

16. **Section 15 — Parliamentary Activities News Block**: `section` tag, approx. 560px height, `display: block`.
    *   Nested within Section 14.
    *   Dedicated to "संसद गतिविधि" (Parliamentary Activities) news.
    *   Contains multiple news cards with imagery.

17. **Section 16 — Main Content Area (Health)**: `main` tag, approx. 561px height, `display: block`.
    *   Another primary container for news categories.
    *   Contains imagery.

18. **Section 17 — Main Content Area (Entertainment)**: `main` tag, approx. 623px height, `display: block`.
    *   Another primary container for news categories.
    *   Dedicated to "मनोरञ्जन" (Entertainment) news.
    *   Contains imagery and buttons.

19. **Section 18 — Provincial News Block**: `section` tag, approx. 667px height, `display: block`.
    *   Dedicated to "प्रदेश समाचार" (Provincial News).
    *   Contains multiple news cards with imagery and buttons.

20. **Section 19 — General News Block**: `section` tag, approx. 637px height, `display: block`.
    *   Dedicated to "समाचार" (News).
    *   Contains multiple news cards with imagery.

## Hero Deep-Dive

The hero section (Section 1) is a `section` element with a background image, indicating `hasBackgroundMedia: true` and `backgroundType: "image"`. It spans the full width of the viewport and has an approximate height of 154px.

*   **Layout Structure**: The hero appears to be a horizontally oriented display of featured news items. Within its bounding box, `domLandmarks` indicate four `h3` elements, each serving as a headline for a news card. These headlines are likely part of a carousel or a grid of top stories.
*   **Background Type**: Image.
*   **CTA Count and Placement**: The `hero` object reports `ctaButtonCount: 0`. However, given the nature of news cards, it's highly probable that the entire card or headline acts as a clickable call to action to read the full article, rather than explicit buttons.
*   **Typography Hierarchy**: The primary text elements are `h3` headlines (e.g., "दशैँ-तिहारलाई लक्षित सुपथ मूल्य पसल एक महिनाअघि नै सञ्चालनमा ल्याइदै"). These use `Mukta, sans-serif` at `22px` with `font-weight: 590`, suggesting a clear emphasis for these featured stories.

## Component Inventory

| Component         | Count | Location                                  | Description