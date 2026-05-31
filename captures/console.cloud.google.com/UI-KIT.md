## UI-KIT.md

### Recommended Stack

*   **shadcn/ui**: For foundational UI components like buttons, inputs, cards, and navigation. Its headless nature and Tailwind CSS integration make it ideal for matching the Google Cloud Console's precise styling and theming.
*   **Tailwind CSS**: To implement the specific color palette, typography, spacing, and border-radius values extracted, and to handle responsive design based on the detected breakpoints. This will be used to customize shadcn/ui components.

### Component Mapping

| Detected Pattern | Recommended Component | Library | Confidence | Notes |
| :--------------- | :-------------------- | :------ | :--------- | :---- |
| Primary Action Button (e.g., `glue-cookie-notification-bar__accept`) | `shadcn-button` | shadcn/ui | High | Rounded button with blue background. Will require custom `variant` or direct Tailwind styling for `background-color: rgb(26, 115, 232)` and `border-radius: 48px`. Install: `npx shadcn@latest add button` |
| Navigation Button (`pcc-platform-bar-button`) | `shadcn-button` | shadcn/ui | High | Appears as a text-only button within a navigation context. Can be styled as a ghost or link variant. Install: `npx shadcn@latest add button` |
| Search Input (`cm-input`) | `shadcn-input` | shadcn/ui | High | Standard text input field. Install: `npx shadcn@latest add input` |
| Header/Platform Bar (`pageSections[0]`) | `shadcn-navigation-menu` | shadcn/ui | Medium | This section acts as a top navigation/banner. While `shadcn-navigation-menu` is often for complex dropdowns, its base structure can be adapted for a simpler header bar containing navigation buttons and a search input. Install: `npx shadcn@latest add navigation-menu` |
| Content Panels/Cards (`components` of kind `card`, `pageSections[1]`) | `shadcn-card` | shadcn/ui | Medium | The detected "cards" (e.g., `.cfc-panel-container-outer`, `.cfc-panel-content`) are structural containers. They have transparent backgrounds and no explicit border-radius in samples, but the overall page likely uses them as distinct content blocks. The `shadcn-card` component can be used as the base, and custom Tailwind styling (e.g., for borders, shadows, and background colors like `--lt-color-background-default` or `--cm-sys-color-backdrop`) will be applied to match the visual design. Install: `npx shadcn@latest add card` |

### Animation Equivalents

| Detected Animation | Recommended Component | Library | Notes |
| :----------------- | :-------------------- | :------ | :---- |
| `css-transition` on `box-shadow` | N/A | Tailwind CSS | Can be implemented directly with Tailwind CSS transition utilities (e.g., `transition-shadow duration-150`). |
| `css-transition` on `height, visibility` | N/A | Tailwind CSS | Can be implemented directly with Tailwind CSS transition utilities (e.g., `transition-all duration-300 ease-in-out`). |

### Implementation Notes

1.  **Project Setup**: Initialize a Next.js (or desired framework) project with Tailwind CSS.
2.  **shadcn/ui Initialization**: Run `npx shadcn-ui@latest init` to configure shadcn/ui with Tailwind CSS.
3.  **Install Base Components**:
    *   `npx shadcn@latest add button`
    *   `npx shadcn@latest add input`
    *   `npx shadcn@latest add card`
    *   `npx shadcn@latest add navigation-menu`
4.  **Tailwind Configuration**:
    *   **Colors**: Define a custom color palette in `tailwind.config.js` based on the `colors` data and `cssVariables` like `--lt-color-background-default` (`#f1f3f9`), `--cm-sys-color-backdrop` (`#f0f5fe` light, `#282c32` dark).
    *   **Typography**: Configure font families (`"Google Sans Flex"`, `"Google Sans"`, `"Roboto"`) in `tailwind.config.js`.
    *   **Spacing**: Use Tailwind's default spacing scale, or extend it to include specific values like `4px`, `8px`, `12px`, `16px` if needed, referencing the `spacing` data.
    *   **Border Radius**: Extend Tailwind's `borderRadius` to include `4px` and `48px` (for the primary button), and potentially `50%` for circular elements.
    *   **Shadows**: Add the detected shadow (`rgba(0, 0, 0, 0.3) 0px 1px 2px 0px, rgba(0, 0, 0, 0.15) 0px 2px 6px 2px, rgb(80, 99, 139) 0px 0px 0px 1px inset`) as a custom shadow in `tailwind.config.js`.
    *   **Dark Mode**: Configure Tailwind CSS for dark mode, likely using the `class` strategy, and map the `light-dark` CSS variable values accordingly.
5.  **Header/Navigation**:
    *   Use the `shadcn-navigation-menu` as a container for the top bar (`pageSections[0]`).
    *   Place a `shadcn-input` (styled as the search input) and `shadcn-button` components (for navigation items) inside.
6.  **Main Content Area**:
    *   Structure the main content (`pageSections[1]`) using `div` elements with Tailwind flex utilities (`flex`, `flex-col`).
    *   For the content panels, use `shadcn-card` components. Apply custom styling for borders, backgrounds, and the detected shadow to achieve the desired visual separation.
7.  **Styling**: Apply Tailwind CSS classes directly to shadcn/ui components or create custom variants to match the extracted styles (e.g., button colors, input padding, card borders).

### Gaps

*   **Complex Layouts**: The extraction data shows a relatively simple, column-based layout. There are no complex grid layouts (like Bento Grid) or highly dynamic, asymmetric sections that would necessitate components like `aceternity-bento-grid`.
*   **Hero Sections**: No distinct "hero" section with marketing-style headlines or background effects (like `aceternity-hero-highlight`, `aceternity-background-beams`, `aceternity-spotlight`) were detected. The page appears to be a functional console interface rather than a marketing landing page.
*   **Carousels/Sliders**: No carousels or image sliders were detected, so `shadcn-carousel` or `swiper-coverflow` are not needed.
*   **Advanced Animations**: Only basic CSS transitions were found. There's no indication for advanced scroll-triggered animations (`framer-motion-scroll`), shimmer effects (`magicui-shimmer-button`), or animated beams (`magicui-animated-beam`).
*   **Testimonials/Pricing**: No testimonial or pricing sections were identified, so `21st-testimonials` or `21st-pricing` are not applicable.
*   **Modals/Dialogs**: No explicit modal or dialog components were detected, so `headlessui-dialog` is not required based on this data.