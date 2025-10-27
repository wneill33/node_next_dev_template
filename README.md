# Next.js Project with shadcn/ui

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app), featuring [shadcn/ui](https://ui.shadcn.com/) components for a modern, accessible UI.

## Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org) (React-based)
- **Package Manager**: [pnpm](https://pnpm.io/)
- **UI Components**: [shadcn/ui](https://ui.shadcn.com/) with [Tailwind CSS](https://tailwindcss.com/)
- **Code Quality**: ESLint & Prettier
- **Development**: VS Code Dev Container with Node.js 22

## Getting Started

### Using Dev Container (Recommended)

This project includes a Dev Container configuration for a consistent development environment. Open the project in VS Code and click "Reopen in Container" when prompted.

### Manual Setup

If not using Dev Containers, install dependencies with pnpm:

```bash
pnpm install
```

Then run the development server:

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

## Project Features

- **shadcn/ui Components**: Pre-built, customizable components built on Radix UI primitives
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development
- **Auto-formatting**: Code formatting on save with Prettier
- **Font Optimization**: Uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font)

## Adding shadcn/ui Components

Add new components using the shadcn/ui CLI:

```bash
pnpm dlx shadcn@latest add [component-name]
```

## Learn More

To learn more about the technologies used in this project:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial
- [shadcn/ui Documentation](https://ui.shadcn.com/) - explore available components
- [Tailwind CSS Documentation](https://tailwindcss.com/docs) - utility classes reference

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
