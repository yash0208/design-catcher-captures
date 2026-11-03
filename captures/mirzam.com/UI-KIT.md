```markdown
## Recommended Stack

*   **shadcn/ui**: This will be the primary UI library for foundational components like `Button`, `Card`, `Navigation Menu`, `Carousel`, and `Input`. It aligns well with the site's clean aesthetic and provides accessible, customizable building blocks for most interactive elements and content displays.
*   **Headless UI**: Specifically for the `Disclosure` component, which is a perfect match for the detected `details` tag pattern used in the mobile menu/FAQ sections, ensuring accessibility and flexibility.
*   **Framer Motion**: While many animations are CSS-based, the presence of `tailwind-animate` suggests a desire for dynamic UIs. Framer Motion can be integrated for more sophisticated scroll-triggered animations, page transitions, or interactive element effects beyond basic CSS transitions, offering a powerful animation toolkit.
*   **Tailwind CSS**: As the styling utility for `shadcn/ui` and the general styling framework, it will be essential for implementing the design system's colors, typography, spacing, and responsive layouts.

## Component Mapping

| Detected Pattern                               | Recommended Component       | Library        | Confidence | Notes