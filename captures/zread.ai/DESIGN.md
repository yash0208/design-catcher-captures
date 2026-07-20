## Overview

This Zread documentation site presents a clean, functional, and developer-centric design. It prioritizes readability and clear information hierarchy, employing a largely monochromatic palette with subtle accents to guide the user. The overall aesthetic is modern and understated, focusing on content delivery without visual distractions. Typography plays a crucial role in establishing hierarchy, with a clear distinction between headings, body text, and code snippets. Layouts are structured and consistent, utilizing generous whitespace to enhance content legibility.

**Key Characteristics:**
*   **Minimalist Color Palette**: Dominated by shades of dark gray, light gray, and white, with teal as the primary accent.
*   **Structured Layouts**: Content is presented within well-defined containers, often with a fixed maximum width for optimal reading.
*   **Clear Typographic Hierarchy**: Uses a sans-serif for general text and a monospace font for code, with distinct sizes and weights for headings and body.
*   **Subtle Elevation**: Shadows are used sparingly to provide a sense of depth for interactive elements like buttons.
*   **Functional Aesthetics**: Design choices are driven by usability and content clarity rather than elaborate ornamentation.
*   **Generous Whitespace**: Ample padding and margins create a breathable interface, reducing visual clutter.
*   **Code-Friendly**: Dedicated monospace font and distinct styling for code blocks.
*   **Sticky Header**: Ensures consistent navigation and branding visibility.

## Colors

### Brand & Accent
*   **Brand Primary** (`{colors.brand-primary}` — #00b0aa): A vibrant teal used for links, interactive elements, and subtle brand highlights.
*   **Brand Green** (`{colors.brand-green}` — oklch(0.596 0.145 163.225)): A dark, muted green, observed in specific text accents.
*   **Brand Blue** (`{colors.brand-blue}` — oklch(0.623 0.214 259.815)): A medium blue, used for specific text accents.
*   **Brand Sky Blue** (`{colors.brand-sky-blue}` — oklch(68.5% .169 237.323)): A bright sky blue, defined in CSS variables but not widely used on the page.
*   **Brand Blue Light** (`{colors.brand-blue-light}` — oklch(80.9% .105 251.813)): A lighter blue tone, defined in CSS variables.
*   **Brand Gradient Start** (`{colors.brand-gradient-start}` — #00e7e7): A bright cyan, defined in CSS variables, potentially for background gradients not fully visible.

### Surface
*   **Canvas** (`{colors.canvas}` — oklch(0.99 0.0057 84.57)): The primary background color for the page, a very light, almost white tone with a subtle warm tint.
*   **Surface Card** (`{colors.surface-card}` — oklch(1 0 0)): Pure white, used for card backgrounds and other elevated content areas.
*   **Surface Popover** (`{colors.surface-popover}` — oklch(1 0 0)): Pure white, designated for popover backgrounds.
*   **Surface Code** (`{colors.surface-code}` — #282c34): A very dark gray, used as the background for code blocks, providing high contrast for code text.
*   **Surface Overlay Light** (`{colors.surface-overlay-light}` — oklab(0.923 0.00197934 0.00225438 / 0.5)): A semi-transparent light gray, likely for overlays or subtle background effects.
*   **Surface Overlay Medium** (`{colors.surface-overlay-medium}` — oklab(0.721417 -0.000695139 -0.00170797 / 0.3)): A semi-transparent medium gray, used for overlays.
*   **Surface Card Hover** (`{colors.surface-card-hover}` — oklab(0.885305 2.98023e-8 0 / 0.2)): A subtle transparent light gray, indicating a hover state for cards or interactive areas.
*   **Surface Header Transparent** (`{colors.surface-header-transparent}` — oklab(0.999994 0.0000455678 0.0000200868 / 0.72)): A nearly white, semi-transparent background for the sticky header, allowing content to subtly show through.
*   **Surface Sidebar Accent** (`{colors.surface-sidebar-accent}` — oklch(.97 0 0)): A very light gray, used for accenting sidebar elements.
*   **Surface Light Gray** (`{colors.surface-light-gray}` — oklch(96.7% .003 264.542)): A light gray, used for secondary surface elements.

### Hairlines & Borders
*   **Border Light** (`{colors.border-light}` — oklch(0.922 0 0)): A very light gray, used for general UI borders, providing subtle separation.
*   **Border Medium** (`{colors.border-medium}` — #d8d8d8): A light gray, slightly darker than `{colors.border-light}`, for more pronounced borders.
*   **Border Medium Light** (`{colors.border-medium-light}` — oklch(87% 0 0)): A light gray, defined in CSS variables.
*   **Border Dark** (`{colors.border-dark}` — oklch(0.145 0 0)): A very dark gray, used for strong borders or outlines.
*   **Border Focus** (`{colors.border-focus}` — oklch(0.869 0.022 252.894)): A light blue-gray, indicating a focused or active state.
*   **Border Shadow Light** (`{colors.border-shadow-light}` — oklab(0 0 0 / 0.06)): A subtle transparent black, used for very light border shadows.
*   **Border Shadow Medium** (`{colors.border-shadow-medium}` — oklab(0 0 0 / 0.08)): A slightly stronger transparent black, for more noticeable border shadows.

### Text
*   **Text Primary** (`{colors.text-primary}` — oklch(0.145 0 0)): The main body text color, a very dark gray, providing excellent readability on light backgrounds.
*   **Text Heading** (`{colors.text-heading}` — oklch(0.208 0.042 265.755)): A very dark blue-purple, used for prominent headings, offering a slightly softer contrast than pure black.
*   **Text Accent Dark** (`{colors.text-accent-dark}` — oklch(0.372 0.044 257.287)): A dark blue-purple, used for specific accent text.
*   **Text Muted** (`{colors.text-muted}` — oklch(0.556 0 0)): A medium gray, used for secondary information, less prominent text, or disabled states.
*   **Text On Accent** (`{colors.text-on-accent}` — oklch(0.205 0 0)): A dark gray, intended for text placed on accent-colored backgrounds.
*   **Text Secondary** (`{colors.text-secondary}` — oklch(0.929 0.013 255.508)): A light blue-gray, for tertiary information or less important details.
*   **Text Secondary M