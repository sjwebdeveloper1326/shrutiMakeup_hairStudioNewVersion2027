# Shuti Makeup Hair Studio Frontend

Luxury salon website frontend built with:

- HTML5
- CSS3
- Vanilla JavaScript

## Pages

- `index.html`
- `about.html`
- `services.html`
- `gallery.html`
- `offers.html`
- `contact.html`

## Structure

- `assets/css/variables.css`: global design tokens and theme colors
- `assets/css/style.css`: shared layout, luxury components, package cards, chatbot, and gallery system
- `assets/css/responsive.css`: breakpoint-specific responsive styling
- `assets/js/main.js`: mobile menu, scroll state, reveal animations, gallery filters, sliders, chatbot, and FAQ logic

## Integration Notes

- The code uses semantic HTML and modular shared assets to make later Django template extraction easier.
- Shared sections such as the header and footer can be moved into Django partials.
- The contact form is UI-only and has no backend handling yet.
- The map section is a placeholder ready for a future embedded map.

## Image Notes

- Existing local salon images were reused as placeholders across hero, gallery, services, branches, and offers directories.
- Additional placeholder image groups were organized into `packages`, `reviews`, and `clients` for richer premium UI sections.
- Replace the image files in `assets/images/` with final optimized photography as needed.
