## Recommended Stack

*   **shadcn/ui**: This will serve as the foundational UI library, providing accessible and customizable components for navigation, buttons, input fields, and general content cards. Its integration with Tailwind CSS makes styling consistent with the detected design.
*   **Aceternity UI**: Specifically for the `aceternity-spotlight` effect detected in the hero section, which adds a modern, interactive background element.
*   **Swiper**: Given the presence of a linear carousel with a large number of estimated slides (40+), Swiper offers robust and performant carousel functionality, including navigation controls.
*   **Framer Motion**: To implement the detected scroll-triggered `transform` animations (translate and opacity), providing smooth and engaging content reveals.

## Component Mapping

| Detected Pattern | Recommended Component | Library | Confidence | Notes |
| :--------------- | :-------------------- | :------ | :--------- | :---- |
| Global Navigation Bar (`navbar`, `nav-menu`) | `shadcn-navigation-menu` | shadcn/ui | High | Handles main navigation links and dropdown toggles (`nav-dropdown-toggle`). |
| Hero Section (`hero-section-a`) | Custom composition with `aceternity-spotlight` | Aceternity UI / Custom | Medium | Combine `aceternity-spotlight` for the background effect with custom content layout. The hero also has a background image which will need to be implemented. |
| Primary/Secondary Buttons (`nav-dropdown-toggle` as interactive elements) | `shadcn-button` | shadcn/ui | High | For all interactive button elements, including those in the navigation or within content sections. |
| Form Input Fields (`form-input`) | `shadcn-input` | shadcn/ui | High | Standard text input fields for forms. |
| Linear Carousel (`expertise-slider-section`, `slider`) | Swiper (general) | Swiper | Medium | A robust solution for the detected linear carousel with many slides and "both" control styles. `shadcn-carousel` is an alternative if simpler functionality is sufficient. |
| Content Cards (`section`, `expertise-slide`, `service-link-contents`) | `shadcn-card` | shadcn/ui | Medium | Use `shadcn-card` as a base for various content blocks. Specific styling (e.g., `rgba(255, 255, 255, 0.15)` background for `service-link-contents`) will be applied via Tailwind CSS. |

## Animation Equivalents

| Detected Animation | Recommended Component / Library | Notes |
| :----------------- | :------------------------------ | :---- |
| `aceternity-spotlight` | `aceternity-spotlight` | Direct match for the detected spotlight effect. |
| `transform` (translate3d, opacity) | `framer-motion-scroll` | For scroll-triggered entrance animations, particularly for elements that appear with a slight vertical shift and fade in. |
| `css-transition` (opacity, color, background-color) | Tailwind CSS transitions | These are standard CSS transitions that can be handled directly with Tailwind CSS utility classes. |

## Implementation Notes

1.  **Project Setup**: Initialize a Next.js (or preferred framework) project with Tailwind CSS.
2.  **shadcn/ui Installation**: Begin by installing `shadcn/ui` and its dependencies.
    *   `npx shadcn-ui@latest init`
    *   Install core components: `npx shadcn-ui@latest add button input navigation-menu card`
3.  **Aceternity UI Integration**: Copy the `Spotlight` component code directly from the Aceternity UI website (`ui.aceternity.com/components/spotlight`) into your project's `components/ui` directory.
4.  **Swiper Installation**: Install Swiper: `npm install swiper`. Integrate Swiper components for the carousel sections, customizing navigation and pagination as needed.
5.  **Framer Motion Setup**: Install Framer Motion: `npm install framer-motion`. Apply `motion` components and `useScroll` / `useInView` hooks for scroll-triggered animations on relevant sections.
6.  **Global Styles & Theming**:
    *   Configure `tailwind.config.js` to use the `Uncut Sans` font family as detected in the typography data.
    *   Define color variables in `tailwind.config.js` or `globals.css` based on the `colors` and `cssVariables` from the extraction (e.g., `--dark-100` as black, `--white` as white, `--dark-5` for subtle backgrounds). Refer to `DESIGN.md` for specific token names.
7.  **Component Structure**:
    *   Create a `components/layout/Header.tsx` for the `shadcn-navigation-menu`.
    *   Create `components/sections/HeroSection.tsx` to house the custom hero composition with `aceternity-spotlight`.
    *   Create `components/sections/ExpertiseCarousel.tsx` for the Swiper implementation.
    *   Utilize `shadcn-card` within various content sections, applying custom styling via Tailwind CSS classes.

## Gaps

*   **Complex Card Layouts**: While `shadcn-card` provides a good base, the specific visual designs of cards like `expertise-slide` (likely containing images and text) and `service-link-contents` (with a semi-transparent background) will require custom Tailwind CSS styling on top of the base component or custom `div` structures rather than relying solely on `shadcn-card`'s default slots.
*   **Background Imagery**: The hero section is identified with `backgroundType: "image"`. This background image will need to be implemented manually, possibly as an `<img>` tag or a background CSS property, positioned behind the `aceternity-spotlight` effect.