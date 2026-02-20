# Template Screen Project

A collection of high-quality landing page templates to demonstrate various styles to customers.

## Project Purpose

This project serves as a showcase of various landing page templates designed to demonstrate different design styles and approaches to customers. Each template is ready for implementation and can be customized based on client needs.

## Available Templates

1. **Corporate/Professional** - Clean, trustworthy, ready-to-implement business style
2. **Retro Game Theme** - Pixel art or 8-bit aesthetic, nostalgic feel
3. **Modern SaaS/Creative** - Sleek, dark mode or vibrant gradients, modern UI elements

## Technical Constraints

**IMPORTANT:** This project uses Bun as the package manager. All commands must use Bun, not npm.

### Package Manager Commands

- Install dependencies: `bun install`
- Run development server: `bun run dev`
- Build for production: `bun run build`
- Preview production build: `bun run preview`

## Project Structure

```
src/
├── pages/
│   ├── index.astro           # Main catalog page
│   ├── template-one.astro    # Corporate/Professional template
│   ├── template-two.astro    # Retro Game Theme template
│   └── template-three.astro  # Modern SaaS/Creative template
├── components/
│   ├── template-one/         # Components for template-one
│   ├── template-two/         # Components for template-two
│   └── template-three/       # Components for template-three
└── layouts/
    └── Layout.astro          # Base layout
```

## Component Organization

For each landing page template:

- Create a dedicated folder in `src/components/[template-name]/`
- Place all HTML/Astro components and CSS specific to that page inside its dedicated folder
- Maintain clean separation between different template components

## Development Guidelines

- Use Astro for building components and pages
- Follow the existing folder structure for consistency
- Keep components modular and reusable
- Use smooth, professional animations
- Ensure responsive design across all templates
