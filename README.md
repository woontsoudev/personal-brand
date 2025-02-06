# Personal brand website

A modern, performant web application built with Next.js and TailwindCSS, featuring a clean and accessible user interface with dynamic content management capabilities.

## Technology Stack

### Core

- **Next.js 14** - React framework for production-grade applications
- **React 18** - UI library for building user interfaces
- **TypeScript** - For type-safe code and better developer experience

### Styling & UI

- **TailwindCSS 4.0** - Utility-first CSS framework
- **HeadlessUI** - Unstyled, fully accessible UI components
- **Typography Plugin** - Beautiful typographic defaults for HTML content
- **Custom Themes** - Dark/Light mode support with system preference detection

### Content Management

- **MDX** - Write content with JSX in Markdown documents
- **Rehype Prism** - Syntax highlighting for code blocks
- **Remark GFM** - GitHub Flavored Markdown support

### Development & Tooling

- **ESLint** - Code linting and style enforcement
- **Prettier** - Code formatting
- **Sharp** - Image optimization

## Features

### Responsive Design

- Fully responsive layout that works seamlessly across all device sizes
- Mobile-first approach ensuring great UX on smartphones and tablets

### Theme Support

- 🌓 Automatic dark/light mode switching
- System preference detection
- Persistent theme selection
- Smooth theme transitions

### Navigation

- Dynamic routing with Next.js
- Smooth page transitions
- Active link highlighting
- Responsive navigation menu with mobile optimization

### Performance

- Server-side rendering for optimal performance
- Image optimization and lazy loading
- Fast page loads with automatic code splitting
- Optimized font loading

### Content Features

- MDX support for rich content creation
- Syntax highlighting for code blocks
- Responsive images with automatic optimization
- Support for GitHub Flavored Markdown
- RSS feed generation

### Accessibility

- ARIA-compliant components
- Keyboard navigation support
- Screen reader friendly
- High contrast mode support

## Getting started

To get started with this template, first install the npm dependencies:

```bash
npm install
```

Next, create a `.env.local` file in the root of your project and set the `NEXT_PUBLIC_SITE_URL` variable to your site's public URL:

```
NEXT_PUBLIC_SITE_URL=https://example.com
```

Next, run the development server:

```bash
npm run dev
```

Finally, open [http://localhost:3000](http://localhost:3000) in your browser to view the website.

## Customizing

You can start editing this template by modifying the files in the `/src` folder. The site will auto-update as you edit these files.
