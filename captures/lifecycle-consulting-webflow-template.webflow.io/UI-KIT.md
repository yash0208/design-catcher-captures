```markdown
## Recommended Stack

*   **shadcn/ui**: For foundational UI components such as navigation menus, buttons, cards, accordions, and carousels, providing a robust and accessible base for the page's structure and interactive elements.
*   **Magic UI**: Essential for implementing the distinct horizontal scrolling "marquee" effect detected for logo strips and other continuous content displays.
*   **21st.dev**: Recommended for accelerating the development of complex, pre-designed sections like the hero and testimonial blocks, offering curated layouts that match the page's aesthetic.
*   **Framer Motion**: To handle scroll-triggered reveal animations and other dynamic transitions, enhancing the user experience with subtle motion.

## Component Mapping

| Detected Pattern | Recommended Component | Library | Confidence | Notes |
| :--------------- | :-------------------- | :------ | :--------- | :---- |
| Header Navigation | `shadcn-navigation-menu` | shadcn/ui | High | Install: `npx shadcn@latest add navigation-menu`. Use for `nav.nav-menu`. |
| Hero Section (Layout & Content) | `21st-hero` | 21st.dev | High | Browse 21st.dev/components/hero for a suitable layout. The video background will need custom implementation. |
| Buttons (General CTAs) | `shadcn-button` | shadcn/ui | High | Install: `npx shadcn@latest add button`. Used for `div.dropdown-toggle` and other interactive elements. |
| Testimonial Section | `21st-testimonials` | 21st.dev | High | Browse 21st.dev/components/testimonials for section layout. |
| Testimonial Carousel | `shadcn-carousel` | shadcn/ui | High | Install: `npx shadcn@latest add carousel`. To be used within the `21st-testimonials` section for the `div.content.slider-testimonial`. |
| FAQ Section | `shadcn-accordion` | shadcn/ui | High | Install: `npx shadcn@latest add accordion`. Directly maps to `div.faq-grid`. |
| Marquee / Logo Strip | `magicui-marquee` | Magic UI | High | Install: `npx shadcn@latest add @magicui/marquee`. Perfect for the `div.marquee` elements and logo strips. |
| Content Cards (e.g., flow-item) | `shadcn-card` | shadcn/ui | Medium | Install: `npx shadcn@latest add card`. Can be adapted for `.flow-item` and other general content blocks. |
| Footer | Custom Build | N/A | High | The footer section (`section.footer`) is unique and best built using basic HTML/CSS with Tailwind CSS. |

## Animation Equivalents

| Detected Animation | Recommended Library / Component | Notes |
| :----------------- | :------------------------------ | :---- |
| `transform` (translate3d, opacity) on scroll | `framer-motion-scroll` | Install: `npm install framer-motion`. Use `useScroll`, `useTransform`, and `motion` components for reveal effects and parallax. |
| `marquee` (continuous scroll) | `magicui-marquee` | Already covered in component mapping. Provides the infinite horizontal scroll. |
| `css-transition` (opacity, transform) | Tailwind CSS transitions / `framer-motion` | For simple hover/focus states, Tailwind's built-in transitions are sufficient. For more complex interactions, Framer Motion can be used. |

## Implementation Notes

1.  **Project Setup**: Start with a Next.js or React project. Configure Tailwind CSS for styling.
2.  **Install Core Libraries**:
    *   `npx shadcn@latest init` to set up shadcn/ui.
    *   `npm install framer-motion`
3.  **Install shadcn/ui Components**: Add the necessary components:
    *   `npx shadcn@latest add button`
    *   `npx shadcn@latest add navigation-menu`
    *   `npx shadcn@latest add accordion`
    *   `npx shadcn@latest add carousel`
    *   `npx shadcn@latest add card`
4.  **Install Magic UI Components**:
    *   `npx shadcn@latest add @magicui/marquee`
5.  **Integrate 21st.dev Sections**: Browse 21st.dev for the Hero and Testimonial sections. Copy their code and adapt it to your project structure. These often come with their own dependencies or styling which will need to be integrated with Tailwind.
6.  **Styling**: Refer to the `DESIGN.md` (not provided here, but implied) for specific color tokens (e.g., `--_colors---ui--dark`, `--_colors---brand--brand-1`) and typography (e.g., `"Funnel Sans"`, `"Geist Mono"`). Apply these using Tailwind CSS utility classes and custom configurations.
7.  **Hero Section**: For the hero section with a video background, use the `21st-hero` layout and embed a `<video>` element as its background, ensuring it's responsive and covers the area.
8.  **Framer Motion**: Apply `motion.div` or `motion.section` to elements that require scroll-triggered animations. Use `whileInView` for simple reveals or `useScroll` and `useTransform` for more advanced effects.

## Gaps

*   **Video Section**: The `section.video-section` (index 8) is a prominent element but doesn't have a direct component match in the catalog. This section will need to be custom-built using a standard HTML5 `<video>` element or an embedded player (e.g., YouTube/Vimeo iframe) wrapped in a responsive container.
*   **Complex Layouts/Grids**: While `shadcn-card` can be used for individual items, the overall grid layouts for sections like "our process" or "metric summary" are not covered by a single component. These will require custom grid/flexbox layouts using Tailwind CSS.
*   **Specific Number Displays**: The "30%" metric display with a distinct "Geist Mono" font is a specific stylistic choice. While the number itself is text, the overall presentation within a section (e.g., `section.metric-summary`) will need careful custom styling to match the original design.