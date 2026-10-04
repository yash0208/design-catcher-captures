## Page Overview

This is a marketing landing page for "Unify | Outbound agents for every rep," a product aimed at sales teams. The page is structured into 9 distinct sections, presenting a comprehensive narrative about the product's value proposition. The scroll rhythm is a typical long-form marketing experience, guiding the user through problem statements, solutions, social proof, and feature highlights. The primary user journey is designed to attract potential customers, educate them on Unify's capabilities, build trust through testimonials and metrics, and ultimately drive them towards booking a demo or signing up for the service.

## Section Map

1.  **Section 0 — Navigation**: `nav` tag, approximately 64px height, `display: block`.
    *   Contains navigation links and potentially a logo and CTA buttons.
    *   `componentHints`: navigation, imagery, buttons.
2.  **Section 1 — Main Content Wrapper**: `main` tag, approximately 6330px height, `display: block` with `flex-direction: column`.
    *   Acts as the primary container for all subsequent content sections.
    *   `componentHints`: video, imagery, buttons.
3.  **Section 2 — Hero Section**: `section` tag, approximately 853px height, `display: flex`.
    *   Features the main headline "Outbound agents for every rep" and likely subcopy and calls to action.
    *   `componentHints`: hero, imagery.
4.  **Section 3 — Value Proposition**: `section` tag, approximately 1014px height, `display: block`.
    *   Presents a core message: "Escape tab hell with a unified platform for prospecting, research, and sequencing all backed by frontier AI models." Likely includes supporting text, imagery, or video.
    *   `componentHints`: video, imagery, buttons.
5.  **Section 4 — Social Proof/Metrics**: `section` tag, approximately 476px height, `display: block`.
    *   Highlights a significant metric: "Unify has powered $1,012345678900123456789001234567890123456789,0123456789012345670123456789012345012345678901234,012345".
    *   `componentHints`: imagery.
6.  **Section 5 — Product Features/Tabs**: `section` tag, approximately 821px height, `display: block`.
    *   Introduces "Purpose-built for sellers", suggesting a tabbed interface or distinct feature blocks.
    *   `componentHints`: None explicitly listed for this section, but likely contains interactive elements.
7.  **Section 6 — Testimonials/Case Studies**: `section` tag, approximately 1870px height, `display: block`.
    *   Showcases "The best sales teams win with Unify", likely featuring testimonials, case study snippets, or customer logos.
    *   `componentHints`: video, imagery.
8.  **Section 7 — Workflow/Product Overview**: `section` tag, approximately 1215px height, `display: block`.
    *   Likely details the workflow or how the product integrates into existing processes, with a focus on "Level up your workflow".
    *   `componentHints`: video, imagery.
9.  **Section 8 — Footer/Call to Action**: `section` tag, approximately 1406px height, `display: block` with `flex-direction: column` and `gap: 100px`.
    *   Concludes the page with a final call to action ("From prompt to pipeline") and standard footer content like navigation, contact info, and legal links.
    *   `componentHints`: footer.

## Hero Deep-Dive

The main hero content is found in `pageSections[2]` (classes: `cc-hero cc-home`), which occupies a significant portion of the initial viewport (y=106, height=853px).

*   **Layout Structure**: The hero section uses a `flex` layout. It features a prominent headline "Outbound agents for every rep" (an `h1` styled as `h2`, font size 86.31px, bold). Below this, there is likely subcopy and calls to action, although specific CTA elements are not directly identified within this section's `componentHints`. The `hero` object itself refers to a small, solid-background banner at the very top of the page (y=0, height=42px) with one CTA button, separate from the main visual hero.
*   **Background Type**: The main hero section (`pageSections[2]`) has a transparent background (`rgba(0, 0, 0, 0)`), suggesting a background image or video might be applied to a parent container or a pseudo-element, as "imagery" is hinted. The small top banner has a solid background.
*   **CTA Count and Placement**: The top banner (`hero` object) has 1 CTA button. For the main hero section, CTAs are implied but not explicitly counted in the provided data. Typically, a hero section would include at least one primary call to action button.
*   **Typography Hierarchy**: The main headline "Outbound agents for every rep" uses the "Feature Text" font, is 86.31px, and bold (700 weight), establishing a clear visual hierarchy. Other text in the hero would likely follow a descending scale from this dominant headline.

## Component Inventory

| Component    | Count | Location                                    | Description