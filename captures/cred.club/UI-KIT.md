## Recommended Stack

*   **shadcn/ui**: For robust, accessible base components like `Card` and `Button` that can be easily customized to match the site's dark theme and minimal aesthetic.
*   **Framer Motion**: Crucial for implementing the detected `transform` and `css-transition` animations, especially for scroll-triggered effects and dynamic section reveals.
*   **Tailwind CSS**: As the foundational styling utility, it will be used for layout, spacing, and custom styling of all components, aligning with shadcn/ui's design philosophy.

## Component Mapping

| Detected Pattern | Recommended Component | Library | Confidence | Notes |
| :--------------- | :-------------------- | :------ | :--------- | :---- |
| Hero Section (with video background) | Custom Hero + `framer-motion-scroll` | Framer Motion / Custom | High | The `hero` sections with `backgroundType: video` and `hasBackgroundMedia: true` indicate a need for a custom component to embed video, combined with `framer-motion-scroll` for the detected `transform` animations (likely parallax or scroll-linked effects). `21st-hero` could inspire layout but won't provide the video integration directly. |
| Card (transparent, with borders) | `shadcn-card` | shadcn/ui | High | Multiple `card` components are detected with custom styling (transparent backgrounds, borders). `shadcn-card` provides a solid, accessible base that can be styled with Tailwind CSS to match these specific designs. Install: `npx shadcn@latest add card` |
| Footer | Custom Footer | Tailwind CSS | High | The `footer` is a standard content block. No specific component library footer is in the catalog, so a custom component built with Tailwind CSS will be most appropriate. |
| General Buttons (implied) | `shadcn-button` | shadcn/ui | Medium | Although no CTA buttons were explicitly detected in the hero, any interactive buttons on the site can leverage `shadcn-button` for consistency and accessibility. Install: `npx shadcn@latest add button` |

## Animation Equivalents

| Detected Animation Type | Recommended Component | Library | Notes |
| :---------------------- | :-------------------- | :------ | :---- |
| `transform` (matrix, scroll-based) | `framer-motion-scroll` | Framer Motion | The presence of `transform` animations, especially `matrix` transformations, strongly suggests scroll-triggered effects like parallax or complex element movements. Framer Motion's `useScroll` and `motion` components are ideal for this. Install: `npm install framer-motion` |
| `css-transition` (transform, top, width) | `framer-motion-scroll` / CSS | Framer Motion / Custom | While simple `css-transition` can be handled with plain CSS, integrating these with Framer Motion provides a unified animation API and allows for more sophisticated orchestration, especially if linked to scroll events. |

## Implementation Notes

1.  **Project Setup**: Initialize a new Next.js or React project with Tailwind CSS.
2.  **Install Libraries**:
    *   Install `shadcn/ui` and its dependencies. Run `npx shadcn@latest init` and then `npx shadcn@latest add button card`.
    *   Install `Framer Motion`: `npm install framer-motion`.
3.  **Theme Configuration**:
    *   Configure `tailwind.config.js` to use the primary colors (`#000000`, `#ffffff`, `#333333`) and any other detected colors.
    *   Import and configure the custom fonts (`gilroy-regular`, `denton`, `gilroy`, etc.) as defined in `DESIGN.md` (or directly from the `typography` data) into your global CSS and Tailwind config.
4.  **Hero Sections**:
    *   Create a custom `HeroVideoSection` component. This component will embed the background video and contain the main content.
    *   Utilize `Framer Motion`'s `useScroll` hook and `motion` components within the `HeroVideoSection` to apply the detected `transform` animations, creating parallax or reveal effects as the user scrolls.
5.  **Cards**:
    *   Implement `shadcn-card` components. Customize their appearance using Tailwind CSS classes to achieve transparent backgrounds, specific border styles, and text colors as seen in the extraction data.
6.  **Footer**:
    *   Build a custom `Footer` component using semantic HTML (`<footer>`) and style it entirely with Tailwind CSS, referencing the detected dark background and white text.

## Gaps

*   **Navigation Menu**: No explicit navigation menu pattern was detected in the provided data. If the full website requires a navigation bar, a `shadcn-navigation-menu` or a custom-built responsive navigation component would be needed.
*   **Interactive Elements**: No carousels, tabs, accordions, or form inputs (beyond basic text) were detected. If these are present on other parts of the site, `shadcn-carousel`, `shadcn-tabs`, `shadcn-accordion`, or `shadcn-input` would be suitable.
*   **Specific Aceternity/Magic UI Components**: The current data does not indicate patterns like `aceternity-background-beams`, `aceternity-spotlight`, `aceternity-bento-grid`, `magicui-marquee`, or `magicui-animated-beam`. These would only be recommended if visual patterns matching their specific effects are identified.