# Template Screen Project

A collection of high-quality landing page templates to demonstrate various styles to customers.

## Project Purpose

This project serves as a showcase of various landing page templates designed to demonstrate different design styles and approaches to customers. Each template is ready for implementation and can be customized based on client needs.

## Available Templates

1. **Corporate/Professional** - Clean, trustworthy, ready-to-implement business style with smooth animations
2. **Retro Game Theme** - Pixel art and 8-bit aesthetic with nostalgic gaming vibes
3. **Modern SaaS/Creative** - Sleek, dark mode with vibrant gradients and modern UI elements
4. **Shopping/E-commerce** - Vibrant, product-focused design with modern shopping features
5. **Dashboard/Monitoring** - Dark theme with real-time metrics and data visualization
6. **Creative Portfolio** - Bold, artistic design showcasing creative work and projects
7. **AI Chat Interface** - Modern, dark-themed chat UI with sidebar and message history
8. **Admin Dashboard** - Professional admin interface with sidebar navigation, stats cards, and charts
9. **Fresh Dashboard** - Modern, clean dashboard with emerald accents and fresh design language
10. **AI Chat Studio** - Animated AI chat interface with tools sidebar and modern gradient design
11. **Game Top-Up Store** - Gaming store with top-up options, game cards, and instant delivery
12. **Game Item Shop** - Simplified shop for game items, IDs, and in-game currency

## Technical Constraints

**IMPORTANT:** This project uses Bun as the package manager. All commands must use Bun, not npm.

### Package Manager Commands

- Install dependencies: `bun install`
- Run development server: `bun run dev`
- Build for production: `bun run build`
- Preview production build: `bun run preview`

**NOTE:** Do NOT run `bun run dev` or `bun run build` commands per project rules.

## Project Structure

```
src/
├── pages/
│   ├── index.astro           # Main catalog page with search and filter
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

## Search and Filter Functionality

The main catalog page (index.astro) includes:

- **Search Bar**: Filters templates by name, description, or tags in real-time
- **Tag Filter Selector**: Dropdown to filter templates by specific tags
- **Type-Safe JavaScript**: Client-side filtering with proper null checks and type guards
- **Glassmorphism UI**: Modern, semi-transparent design with backdrop blur effects

Each template card displays at least 3 relevant tags for easy categorization and filtering.

## Technology Stack

- **Astro 5** - Modern web framework for content-driven websites
- **Bun** - Fast JavaScript runtime and package manager
- **CSS-in-JS** - Scoped styling within Astro components
- **Responsive Design** - Mobile-first approach with responsive layouts
