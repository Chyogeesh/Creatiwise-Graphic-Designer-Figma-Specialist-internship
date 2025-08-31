Creatiwise Brand Guide Documentation
Overview
This document describes the 5-slide Brand Guide presentation for Creatiwise, a fictional creative agency, designed to showcase Figma skills. The design is implemented as a React-based webpage with Tailwind CSS to simulate a Figma layout, ensuring it’s runnable in a browser and translatable to Figma. The presentation includes a Cover Slide, Logo Usage, Color Palette, Typography, and Imagery & Brand Applications.
Design Objectives

Brand Identity: Position Creatiwise as a vibrant, modern creative agency.
Figma Alignment: Use Auto Layout-like flexbox, reusable components, and consistent styling to mirror Figma’s structure.
Visual Cohesion: Maintain a professional, approachable aesthetic with clear hierarchy and spacing.
Branding: Use a custom color palette and Inter font to reflect creativity and professionalism.

Color Palette

Primary: #2A4D69 (Navy Blue, RGB: 42, 77, 105) - Headers, backgrounds, and text.
Secondary: #F5A623 (Warm Yellow, RGB: 245, 166, 35) - Accents and highlights.
Accent: #E8ECEF (Light Gray, RGB: 232, 236, 239) - Backgrounds and neutral elements.

Typography

Font: Inter (Google Fonts) - Clean, versatile, and modern.
Styles:
Heading: Inter Bold, 36px (slide titles, hero text).
Subheading: Inter SemiBold, 24px (section headers).
Body: Inter Regular/Light, 16px (descriptions).



Slide Breakdown
Slide 1: Cover

Purpose: Introduce Creatiwise with a bold, welcoming design.
Components:
Centered title (“Creatiwise”) in 48px Inter Bold, white on #2A4D69 background.
Tagline: “Unleashing Creativity, Shaping Futures” in 24px Inter Light.
Hero image: Placeholder for a vibrant creative graphic (600x400px) with glow and hover-scale effects.


Figma Notes: Use Auto Layout for vertical stacking, create a text style for title/tagline.

Slide 2: Logo Usage

Purpose: Define logo variations and guidelines.
Components:
Grid layout with three columns: Primary Logo, Secondary Logo, Incorrect Usage.
Images (200x100px placeholders) for each logo variant.
Text descriptions in 16px Inter Regular, #2A4D69.
Note on 20px clear space.


Figma Notes: Create logo components with variants (primary, secondary, monochrome), use Auto Layout for grid.

Slide 3: Color Palette

Purpose: Showcase brand colors with HEX/RGB codes.
Components:
Three-column grid with 100x100px color swatches (#2A4D69, #F5A623, #E8ECEF).
Labels with color codes in 16px Inter Regular.
Glow effect on swatches for visual appeal.


Figma Notes: Define color styles in Figma’s Team Library, use Auto Layout for swatch alignment.

Slide 4: Typography

Purpose: Define text styles for consistency.
Components:
Examples of Heading (36px), Subheading (24px), and Body Text (16px).
Descriptions in 16px Inter Regular, #2A4D69.


Figma Notes: Create text styles for each level, apply to frames with Auto Layout.

Slide 5: Imagery & Brand Applications

Purpose: Illustrate imagery style and mockups.
Components:
Three-column grid: Imagery Style, Social Post, Business Card.
Placeholder images (200x150px for imagery, 200x200px for social, 200x100px for card).
Descriptions in 16px Inter Regular, white on #2A4D69 background.


Figma Notes: Create components for mockups, use Auto Layout for grid, add to Team Library.

Figma-Specific Implementation

Auto Layout: Used flexbox in code to mimic Figma’s Auto Layout (e.g., flex, gap, items-center).
Components/Variants: Each slide is a reusable React component, translatable to Figma components with variants (e.g., logo variations).
Team Libraries: Colors and typography defined as reusable styles (e.g., bg-[#2A4D69], font-bold).
Layer Structure: Organized with clear naming (e.g., CoverSlide, LogoSlide) to mirror Figma frame names.
Grids & Spacing: Consistent 8px grid system (Tailwind’s gap-6, p-8) for alignment.

How to Run

Save index.html and preview using a local server (e.g., npx vite or Live Server).
Test responsiveness on mobile, tablet, and desktop.

Figma Submission

Import: Use a plugin like “HTML to Figma” to import the rendered HTML into Figma, or manually recreate frames.
Frames: Create one Figma frame per slide (1280x720px recommended).
Components: Convert logos, buttons, and mockups into components with variants.
Styles: Define color styles (#2A4D69, #F5A623, #E8ECEF) and text styles (Heading, Subheading, Body) in Team Library.
Auto Layout: Apply Auto Layout to all frames for responsive spacing.
Share: Export the Figma file or share a link with edit access.

Notes

Replace placeholder images with custom Creatiwise assets (e.g., logo, hero graphic, mockups).
Ensure accessibility in Figma (e.g., sufficient contrast, alt text).
The design is optimized for a professional, cohesive look, with animations (glow, hover-scale) to enhance creativity.
