```markdown
## Recommended Stack

*   **shadcn/ui**: For foundational UI elements like buttons, cards, navigation, and carousels, providing accessibility and a solid styling base.
*   **Framer Motion**: To implement subtle scroll-triggered animations and replicate the detected CSS `slide-in` animation for the header, enhancing user experience.
*   **Magic UI**: Specifically for the `Marquee` component to create the infinite scrolling logo strip in the partnerships section.
*   **Tailwind CSS**: As the styling framework, leveraging its utility-first approach for rapid development and consistent theming, aligning with shadcn/ui's design.

## Component Mapping

| Detected Pattern | Recommended Component | Library | Confidence | Notes |
| :--------------- | :-------------------- | :------ | :--------- | :---- |
| Header Navigation | `shadcn-navigation-menu` | shadcn/ui | Medium | The main header navigation with multiple links. Will need custom styling for the logo and "Download app" section. |
| Hero Section (Video Background, CTA) | Custom composition with video + `shadcn-button` | shadcn/ui | Medium | A full-width hero with a video background and a prominent call-to-action button. No complex headline animation detected. |
| Primary Call-to-Action Button | `shadcn-button` | shadcn/ui | High | Large, rounded buttons like the one in the hero section. Can be styled with appropriate `variant` and `size` props. |
| Service Feature Cards | `shadcn-card` | shadcn/ui | High | The "services" section features distinct content blocks with headings and text. `shadcn-card` provides a good structure. |
| News Carousel | `shadcn-carousel` | shadcn/ui | High | A linear carousel for displaying news items, as indicated by `div.carousel` and `keen-slider`. |
| Partnerships Logo Strip | `magicui-marquee` | Magic UI | High | The `app-logo-strip` in the partnerships section is a perfect fit for an infinite horizontal scrolling marquee of logos. |
| Footer Navigation | Custom `nav` with `shadcn-button` | shadcn/ui | Medium | The footer contains navigation links and other elements. `shadcn-navigation-menu` can be adapted for links, or simple `a` tags. |
| Language Selector (`select`) | Custom HTML `select` element | N/A | High | A standard HTML `<select>` element for language switching. Will require custom styling to match the design. |

## Animation Equivalents

| Detected Animation | Recommended Library / Approach | Notes |
| :----------------- | :----------------------------- | :---- |
| `css-transition` (transform, opacity, color) | Tailwind CSS transitions / Framer Motion | Standard CSS transitions can be handled with Tailwind utility classes for hover states, or orchestrated with Framer Motion for more control. |
| `css-animation` `slide-in` (header) | Framer Motion | The header's `slide-in` animation can be replicated using Framer Motion's `initial` and `animate` props with `y` translation. |

## Implementation Notes

1.  **Project Setup**: Initialize a Next.js (or similar) project and configure Tailwind CSS.
2.  **shadcn/ui Installation**:
    *   `npx shadcn-ui@latest init`
    *   Install core components: `npx shadcn-ui@latest add button card navigation-menu carousel`.
3.  **Magic UI Installation**:
    *   Install Marquee: `npx shadcn-ui@latest add @magicui/marquee`.
4.  **Framer Motion Installation**:
    *   `npm install framer-motion`
5.  **Global Styles & Theming**:
    *   Refer to `DESIGN.md` for color tokens (e.g., `#000000`, `#ffffff`, `#fff066`).
    *   Apply typography settings from `DESIGN.md` (e.g., `fontFamily: "Unica77 LL TT"`) to `tailwind.config.js` and global CSS.
    *   Define spacing and border-radius values as Tailwind CSS theme extensions based on `DESIGN.md` (e.g., `spacing: { '17': '17px' }`, `borderRadius: { 'lg': '17.125px' }`).
6.  **Header Component**: Build the header using `shadcn-navigation-menu` for the main links. Implement the `slide-in` animation using Framer Motion on mount.
7.  **Hero Section**: Create a custom `Hero` component. Embed a video element for the background and place a `shadcn-button` (styled as primary CTA) on top.
8.  **Content Sections**:
    *   For the "Services" section, map each service item to a `shadcn-card`.
    *   For the "News" section, use `shadcn-carousel` to display news cards.
    *   For the "Partnerships" section, integrate `magicui-marquee` with logo images.
9.  **Footer Component**: Construct the footer with navigation links (either simple `a` tags or adapted `shadcn-navigation-menu` links) and other static content.
10. **Custom Elements**: Implement the language selector (`<select>`) with custom styling to match the design.

## Gaps

*   **Stats Section**: The "stats" section (e.g., "4.8 customer satisfaction rating") is primarily a layout of large numbers and descriptive text. There isn't a specific component in the catalog for this; it would be built using standard HTML elements (headings, paragraphs) and styled with Tailwind CSS for layout and typography.
*   **General Content Sections**: Sections like "The Airmee App" and "Smart logistics platform" are high-level content blocks comprising headings, paragraphs, and images. These are best built as custom sections composed of basic HTML elements and styled with Tailwind CSS, rather than mapping to a single component library item.