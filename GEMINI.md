You are a senior front‑end engineer. Using the attached reference image (canva_ss.png), recreate the exact hero section as HTML5 + CSS with no JS and no external frameworks or fonts. Deliver two files only: 1) index.html and 2) styles.css, linked together.

Visual requirements:
- Full‑bleed vertical background gradient transitioning from vivid purple at top to deep blue mid and teal at bottom; smooth and high‑contrast similar to the reference.
- Top navigation: left-aligned text logo “Canva”, center links: Design, Product, Plans, Business, Education, Help; right-aligned pill buttons: Sign up (filled purple) and Log in (white outline/solid white), matching spacing and corner radii.
- Hero copy centered and stacked: large display line “A new era” and larger second line “of imagination” with tight line-height and ample letter spacing reminiscent of the reference.
- Subheading text exactly: “Discover a whole new world of skills and tools designed to put your imagination to work.”
- CTA row: left button “Start designing for free” (light surface), right button “Explore our launches” (darker/contrast button), with subtle shadow and hover states.

Implementation constraints:
- Pure semantic HTML5 with header/nav/main/section tags and accessible landmarks and aria-labels where appropriate.
- CSS variables for colors, spacing, and typography; use system UI font stack with sane fallbacks.
- Use clamp() for fluid type; container width with max-width and responsive padding.
- Create pill buttons via border-radius: 9999px; include focus-visible outlines for accessibility.
- No external assets, icons, or fonts; approximate brand typography with system sans.
- Mobile-first responsive: center the nav on small screens with a stacked layout and keep CTAs on one or two lines; ensure headline scales down gracefully.

Deliverables:
- index.html containing the header/nav and one hero section only.
- styles.css containing the gradient background, layout, typography, and button styles with comments to tweak colors and breakpoints.
