# PORTFOLIO
A neo-brutalist personal portfolio built with vanilla HTML & CSS No frameworks, no build tools, no dependencies - just raw code with bold design choices.

This is a personal fun project, not a production template. The code prioritizes creativity and experimentation over best practices. It's a playground for trying out ideas, animations, and interactions - not a reference architecture.

## INTRODUCTION 
This portfolio is a bold, high-energy digital showcase designed by Sreerag T C, a Computer Science and Engineering student. It serves as a professional hub that bridges the gap between technical engineering proficiency—spanning full-stack development, hardware innovation, and AI—and creative artistic passions like photography and editing. By moving away from conventional, minimalist design trends, this webpage establishes a unique digital identity that is as technically sound as it is visually striking.

The aesthetic foundation of the site is built on "Neo-Brutalism," a style that celebrates raw, tactile interfaces through the use of thick black borders, unblurred hard shadows, and vibrant color clashes. This design philosophy is intentionally provocative, utilizing a technical dotted-grid background and deliberately asymmetrical elements to create an atmosphere of energy and innovation. Every component is designed to feel like a physical object, responding dynamically to user interaction through scaling, rotation, and high-contrast color transitions.

Under the hood, the platform is engineered with clean, lightweight HTML5 and CSS3, prioritizing performance and responsiveness across all devices. Advanced layout techniques like CSS Grid and Flexbox are employed to create flexible content structures, while the photography showcase utilizes a sophisticated masonry column system for a modern gallery feel. By avoiding heavy third-party frameworks, the site achieves lightning-fast load times and maintains a high level of technical precision, ensuring that the bold visuals are backed by stable, professional code.


## What is Neo-Brutalism?
Neo-brutalism (also called neo-brutalist web design) is a UI style inspired by brutalist architecture - raw, bold, and unapologetically loud. It rejects the polished, rounded, drop-shadowed sameness of modern web design and replaces it with:

Thick black borders - every element has a hard, visible edge
Flat, offset box shadows - no soft gradients or blurs, just solid color blocks shifted by a few pixels (box-shadow: 8px 8px 0 #000)
High-contrast color palettes - bright yellows, pinks, cyans, and greens on white/dark backgrounds
Visible structure - the "bones" of the layout are intentionally exposed, not hidden behind smooth transitions
Playful imperfection - torn paper edges, tape stickers, hand-drawn vibes mixed with geometric precision
This site leans into a hand-crafted, scrapbook-like take on neo-brutalism: paper tear dividers, a falling SVG terminal icon, highlight markers that animate on scroll, and a treasure map hidden behind a book-flip animation.


## Design Decisions
## - Color System
| Color  | CSS Variable | HEX Code | Usage |
|-------|-------------|---------|------|
| Cream | `--bg-color` | `#fdf0d5` | The overall site background with the dotted grid. |
| Red | `--primary` | `#ff4747` | Your logo background and the main Contact section. |
| Blue | `--secondary` | `#4775ff` | Background for the Quote section and Tech Stack card. |
| Green | `--tertiary` | `#4add8c` | "Available for Work" badge and select achievement tags. |
| Yellow | `--accent` | `#ffeb3b` | "STUDENT" highlight, navigation hovers, and email link. |
| Black | `--border-color` | `#111111` | All text, thick borders, and the signature "Brutal" shadows. |

## - TYPOGRAPHY 
- Space Grotesk - headings and body text (geometric sans-serif that fits the brutalist aesthetic)

## - KEY DESIGN ELEMENTS 
This portfolio's Neo-Brutalist aesthetic is built on several specific, high-impact design elements. Here are the key components that give the site its signature "bold" look:
1. The "Brutal" Border & Shadow System :
This is the most critical element of the design. Unlike modern "clean" designs that use soft shadows and thin lines, yours uses:
Thick Borders: A consistent 4px solid black border on almost every interactive element.
Hard Shadows: Off-set black shadows (8px) with no blur, making buttons and cards look like physical slabs of material.
Tactile Feedback: When you hover or click, the shadow shrinks and the element "moves" (via translate), mimicking a physical button being pressed.

2. Dotted Grid Background :
Instead of a flat color, your site uses a radial-gradient pattern that creates a technical, blueprint-like grid of dots. This is a staple of brutalist design, making the page feel like a workspace or a draft.

3. Deliberate Asymmetry (The "Handmade" Feel) :
Your site avoids "perfect" alignment to feel more organic and energetic:
Rotated Elements: Your logo, hero badge, achievement cards, and even the marquee are slightly tilted (e.g., -3deg or 2deg).
Floating Shapes: Circular and rectangular shapes (shape-1, shape-2) float behind your profile picture to break the rigid structure.

4. Interactive Image Treatments :
To keep the site professional yet engaging, we've used dual-state visuals:
Grayscale to Color: Achievement and photography images start in high-contrast black and white.
The "Pop" Effect: On hover, they transition into full color. This guides the user's eye and makes the site feel alive as they scroll.

5. Kinetic Typography & Motion :
Infinite Marquee: The scrolling "PHOTOGRAPHY * DEVELOPMENT" bar adds constant energy to the middle of the page.
Bold Scaling: Using weights like 900 for headings ensures that your identity is the first thing a visitor sees.
Masonry Photography: The use of CSS columns allows photos of different sizes to fit together like a puzzle, rather than a boring square grid.
