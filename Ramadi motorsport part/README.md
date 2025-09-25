# Ramadi Motorsports Parts Website

## Project Overview
This is a static website for **Ramadi Motorsports Parts**, a business specializing in premium auto parts and accessories for motorsports enthusiasts. The site showcases high-performance components (e.g., engines, turbos, rims, suspensions) and services (e.g., tuning, diagnostics), targeting South African customers. Built with pure HTML and CSS for simplicity and fast loading, it emphasizes professionalism, responsiveness, and user engagement through interactive elements like product hover details.

Key features:
- Multi-page structure with home, about, products, services, and contact sections.
- Responsive design for desktop, tablet, and mobile devices.
- Integrated media (images, videos) and a contact form.
- No external dependencies—runs in any modern browser.

## File Structure
```
ramadi-motorsport-part/
├── index.html                 # Home page (hero, featured products, CTA)
├── pages/
│   ├── about.html             # About page (mission, team, history)
│   ├── products.html          # Products catalog (grid of 20+ items)
│   ├── services.html          # Services overview (tuning, installation)
│   └── contact.html           # Contact page (form, map, info)
├── css/
│   └── styles.css             # Global styles (layout, colors, responsive)
├── assests/                   # Media files (images, videos)
│   ├── LOGO PIC.jpg           # Site logo
│   ├── V8 supercharger engine.jpeg  # Product images
│   ├── OUR FOUNDER.jpg        # Team photos
│   ├── Turbo Sound Effect.mp4 # Videos
│   └── [40+ other assets]     # Additional product/team/media files
├── Miscellaneous/             # Unused/empty directory
└── TODO.md                    # Task tracker for updates
```

## Page Descriptions and Layout
Each page follows a consistent structure: header (logo + nav) > main content sections > footer (contact + social links). Layout uses flexbox/grid for alignment, with padding/margins for spacing.

### index.html (Home)
- **Header**: Logo image, site title, tagline, horizontal nav bar (Home, About, Products, Services, Contact).
- **Hero Section**: Gradient background, large welcome heading, description, "Shop Now" button linking to products.
- **Featured Products**: 3-card grid (V8 Supercharger, Turbocharger, BBS Rims) with images, names, prices, and descriptions.
- **Why Choose Us**: 4-feature grid (Quality Parts, Fast Shipping, Expert Support, Satisfaction) with icons and text.
- **Call to Action**: Dark background, heading, description, buttons for "Contact Us" and "Call Now".
- **Footer**: Company details (address, phone, email), social links (Facebook, Instagram, Twitter, YouTube), copyright.

### pages/about.html (About Us)
- **Header**: Similar to home, with "About Us" active in nav.
- **Gallery**: Large image of motorcycle parts.
- **Video**: Embedded MP4 video (watermarked preview).
- **Mission**: Heading + paragraphs on goals and sustainability.
- **Vision**: Subheading + paragraph on industry leadership.
- **Values**: Bulleted list (Integrity, Quality, Innovation, Sustainability, Customer Focus).
- **History**: Subheading + paragraphs on founder's story (Ramadi Ndivhuwo starting in garage, social media growth).
- **Team**: Subheading + bios with photos (Founder, CEO, Manager, Staff) and descriptions.
- **Why Choose Us**: Bulleted list (Wide Selection, Competitive Prices, Expert Support, Fast Shipping, Satisfaction Guarantee).
- **Footer**: Same as home.

### pages/products.html (Products)
- **Header**: Similar, with "Products" active.
- **Intro**: Heading, description of catalog.
- **Product Grid**: CSS Grid layout (auto-fit columns, min 300px width). 20+ cards with:
  - Image, name, price.
  - Hover effect: Reveals details (description, specs) via transform and shadow.
  - Examples: V8 Supercharger (R25,000), 2JZ Engine (R18,500), Turbocharger (R8,500), etc.
- **Footer**: Same as home.

### pages/services.html (Services)
- **Header**: Similar, with "Services" active.
- **Intro**: Heading + description of offerings.
- **Services List**: 6 items (Engine Tuning, Suspension Optimization, Brake Upgrades, Exhaust Installation, Diagnostics, Custom Fabrication) with headings and descriptions.
- **Service Process**: Ordered list (Consultation to Follow-up) with steps.
- **Footer**: Same as home.

### pages/contact.html (Contact Us)
- **Header**: Similar, with "Contact Us" active.
- **Contact Info**: Phone, address, email link.
- **Map**: Embedded Google Maps iframe (Polokwane location).
- **Contact Form**: Fields for name, email, message; submit button.
- **Footer**: Same as home.

## Design and Styling
- **Fonts**: Arial, sans-serif for clean readability.
- **Colors**:
  - Primary: Dark blues (#2c3e50, #34495e) for header/footer/nav.
  - Accent: Red (#e74c3c) for buttons/links, green (#27ae60) for call button.
  - Backgrounds: Light gray (#f4f4f4, #ecf0f1) for sections, gradient (#667eea to #764ba2) for hero.
  - Social: Platform-specific (e.g., Instagram pink #e4405f).
- **Layout**: Flexbox for nav/features/CTA, CSS Grid for products. Centered text, rounded borders (10px), box shadows for depth.
- **Interactive Elements**: Nav hover, product card hovers (scale + shadow + details reveal), button styles.
- **Responsive Design**:
  - Desktop: Full grid/flex layouts.
  - Tablet (768px): Stacks nav/features vertically, reduces padding.
  - Mobile (480px): Smaller fonts/padding, single-column stacks.
- **Accessibility**: Alt text on images, semantic HTML (header, main, section, footer), form labels.

## Assets
- **Images**: 30+ JPEGs (products like engines/turbos, team photos, logo). Used in headers, galleries, product cards.
- **Videos**: 4 MP4s (e.g., turbo sounds, previews). Embedded in about page.
- **Other**: No external links except social placeholders and Google Maps.

## How to View/Run
1. Clone or download the project.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Safari).
3. Navigate via links—site is fully static, no server needed.
4. For testing responsiveness: Resize browser or use dev tools (e.g., mobile view).

## Contributing/Next Steps
- Based on `TODO.md`, recent updates include CSS standardization and interactive features.
- Potential improvements: Add JavaScript for form validation, optimize images, integrate real social links, or add e-commerce functionality.
- For changes: Edit HTML/CSS directly, test in browser, update `TODO.md`.

© 2025 Ramadi Motorsports Parts. All rights reserved.
