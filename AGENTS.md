# Agent Guidelines for 0xk1k3's Personal Portfolio

## Commands
- **Development**: `bun run dev` (starts Astro dev server)
- **Build**: `bun run build` (builds production site)
- **Preview**: `bun run preview` (previews production build)
- **Type Checking**: Astro includes built-in TypeScript support with strict null checks

## Code Style
- **TypeScript**: Use strict TypeScript with Astro's type system (`astro:content`, `astro:types`)
- **Components**: Use `.astro` files with TypeScript frontmatter; define interfaces for props
- **Content**: Use Astro Content Collections with Zod schemas for type-safe content
- **Imports**: Use relative imports (`../components/Component.astro`); group imports logically
- **Naming**: Use PascalCase for components (`Header.astro`), camelCase for functions/variables
- **File Organization**: Components in `/components`, pages in `/pages`, content in `/content`
- **Styling**: Uses Tailwind CSS with Astro integration
- **Error Handling**: Use Astro's built-in error boundaries and proper prop validation
- **Astro Configuration**: Uses MDX and sitemap integrations; update `site` URL in `astro.config.mjs`