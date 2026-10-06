## UI-KIT.md

## Recommended Stack

*   **shadcn/ui**: For core UI elements like buttons, navigation, cards, and an accessible accordion component, providing a solid foundation.
*   **Swiper**: The original site explicitly uses Swiper for its carousels, making it the most accurate choice for replicating the complex carousel behavior.
*   **Framer Motion**: To replicate detected CSS animations (`fadeInUp`, `fadeOutUp`) and provide a robust solution for scroll-triggered effects and other dynamic UI elements.
*   **Tailwind CSS**: For styling and utility classes, leveraging the existing class structure and design tokens identified in the extraction.

## Component Mapping

| Detected Pattern | Recommended Component | Library | Confidence | Notes |
| :--------------- | :-------------------- | :------ | :--------- | :---- |
| Header Navigation | `shadcn-navigation-menu` | shadcn/ui | High | Fixed header with navigation links, suitable for potential dropdowns. Install: `npx shadcn@latest add navigation-menu` |
| Primary Buttons | `shadcn-button` | shadcn/ui | High | Standard clickable elements found throughout the page. Install: `npx shadcn@latest add button` |
| Hero Section | `21st-hero` | 21st.dev | Medium | Overall layout for the full-height hero section with background media. Install: Browse 21st.dev/components/hero |
| Product Carousels | `swiper-coverflow` | Swiper | High | The site explicitly uses Swiper, and the `linear` type with `both` controls (arrows/pagination) aligns well. Install: `npm install swiper` |
| FAQ/Accordion Section | `shadcn-accordion` | shadcn/ui | High | The `data-[state=open]:animate-[accordion-down]` classes are a direct indicator of shadcn's Accordion. Install: `npx shadcn@latest add accordion` |
| Content Cards | `shadcn-card` | shadcn/ui | Medium | Generic content containers used for various sections. Install: `npx shadcn@latest add card` |
| Footer | Custom HTML/CSS | N/A | Low | A standard multi-column footer with links and social media. Can be built using basic semantic HTML and Tailwind CSS. |

## Animation Equivalents

| Detected Animation | Recommended Component | Library | Notes |
| :----------------- | :-------------------- | :------ | :---- |
| Swiper Library Animations | Swiper | Swiper | The site uses Swiper directly, which handles its own carousel transitions and effects. |
| `fadeInUp`, `fadeOutUp` CSS Animations | `framer-motion-scroll` | Framer Motion | Can be implemented using `initial={{ opacity: 0, y: 20 }}` and `animate={{ opacity: 1, y: 0 }}` with `whileInView` or `useInView` hooks. Install: `npm install framer-motion` |
| `tailwind-animate` | Framer Motion / Tailwind CSS | Framer Motion / Tailwind CSS | For simple transitions, Tailwind's built-in transition utilities are sufficient. For more complex or orchestrated animations, Framer Motion is recommended. |
| CSS `transform` transitions | Tailwind CSS / Framer Motion | Tailwind CSS / Framer Motion | Standard CSS transitions can be handled by Tailwind's utility classes or by Framer Motion for more controlled component-level animations. |

## Implementation Notes

1.  **Project Setup**: Initialize a Next.js (or React) project with Tailwind CSS configured.
2.  **Install Core Libraries**:
    *   Install shadcn/ui: Follow the shadcn/ui documentation to initialize and add `button`, `navigation-menu`, `accordion`, and `card` components.
    *   Install Swiper: `npm install swiper`
    *   Install Framer Motion: `npm install framer-motion`
3.  **Design Tokens**: Refer to the `colors`, `typography`, and `spacing` data in the original extraction JSON. Define these as Tailwind CSS custom values or CSS variables in `tailwind.config.js` and `globals.css` respectively. Pay attention to the `--ui-*` and `--color-old-neutral-*` CSS variables for consistent theming.
4.  **Header Implementation**: Use `shadcn-navigation-menu` for the main navigation. The `fixed` positioning and `z-50` class should be applied to the `header` element.
5.  **Hero Section**:
    *   Start with a basic `section` element for the hero.
    *   Integrate the Swiper carousel as the main visual element within this section, potentially using a `21st-hero` layout as a guide for content placement (headlines, CTAs).
    *   The headlines (`h1`, `h2`) within the hero can use Framer Motion for `fadeInUp` and `fadeOutUp` effects.
6.  **Carousel Integration**: For the product carousels, use Swiper directly. Configure it with navigation arrows and/or pagination based on the `controlStyle: "both"` hint.
7.  **FAQ Section**: Implement using `shadcn-accordion`. The detected `accordion-down` and `accordion-up` animations are built-in.
8.  **General Styling**: Apply Tailwind CSS classes for layout, typography, and spacing, referencing the extracted `spacing` and `typography` data.
9.  **Responsiveness**: Utilize Tailwind's responsive prefixes (e.g., `md:px-[0.7rem]`) to ensure the design adapts across breakpoints, as indicated by the `breakpoints` data.

## Gaps

*   **Specific UI Effects**: No direct catalog matches were found for highly specific visual effects like custom background patterns (e.g., `aceternity-background-beams`, `magicui-dot-pattern`) or interactive 3D elements (e.g., `aceternity-3d-card`). These would require custom implementation or exploring other specialized libraries if desired.
*   **Complex Layouts**: While `shadcn-card` is versatile, highly asymmetric or unique grid layouts (like `aceternity-bento-grid`) would need custom CSS Grid/Flexbox implementation.
*   **Iconography**: The JSON includes inline SVG data for icons (e.g., `i-jietu:full-screen`, `i-jietu:play`). These should be extracted and integrated using an icon library (e.g., Lucide, React Icons) or as custom SVG components.