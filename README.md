# David Olmos - Personal Portfolio

A modern, responsive personal portfolio website built with **Astro** and **Tailwind CSS**. This website showcases my skills as a Senior Frontend Engineer with a clean, professional design featuring interactive elements and smooth animations.

## ✨ Features

-   **Modern Design**: Clean, professional layout with gradient accents and smooth animations
-   **Responsive**: Fully responsive design that works on all devices
-   **Interactive Elements**: Particle background, smooth scrolling, and hover effects
-   **Performance Optimized**: Built with Astro for optimal performance and SEO
-   **Accessible**: Proper semantic HTML and ARIA labels
-   **Mobile-First**: Mobile navigation with hamburger menu
-   **TypeScript Support**: Full TypeScript integration for better development experience

## 🚀 Tech Stack

-   **Framework**: [Astro](https://astro.build/) - The web framework for content-driven websites
-   **Styling**: [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
-   **Icons**: [Lucide](https://lucide.dev/) - Beautiful & consistent icon toolkit
-   **Fonts**: [Inter](https://fonts.google.com/specimen/Inter) - Modern, clean typography
-   **Animations**: CSS animations and transitions
-   **TypeScript**: Type-safe development

## 🛠️ Getting Started

### Prerequisites

-   Node.js (version 18 or higher)
-   npm, yarn, or pnpm

### Installation

1. Clone the repository:

```bash
git clone <your-repo-url>
cd portfolio
```

2. Install dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Start the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

4. Open your browser and navigate to `http://localhost:4321`

### Build for Production

```bash
npm run build
# or
yarn build
# or
pnpm build
```

### Preview Production Build

```bash
npm run preview
# or
yarn preview
# or
pnpm preview
```

## 📁 Project Structure

```
portfolio/
├── public/                 # Static assets
│   └── favicon.svg
├── src/
│   ├── components/         # Reusable components
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   ├── MobileNav.astro
│   │   └── ParticleBackground.astro
│   ├── layouts/           # Layout components
│   │   └── Layout.astro
│   ├── pages/             # Page components
│   │   ├── about.astro
│   │   ├── index.astro
│   │   ├── projects.astro
│   │   └── skills.astro
│   └── styles/            # Global styles
│       └── global.css
├── astro.config.mjs       # Astro configuration
├── package.json           # Dependencies and scripts
├── tsconfig.json          # TypeScript configuration
└── README.md              # Project documentation
```

## 🎨 Design Features

-   **Gradient Text**: Beautiful gradient text effects using CSS
-   **Particle Background**: Animated floating particles for visual appeal
-   **Smooth Animations**: Hover effects, transitions, and micro-interactions
-   **Glass Morphism**: Backdrop blur effects and transparent elements
-   **Color Scheme**: Purple and blue gradient theme with dark mode support
-   **Typography**: Clean, readable fonts with proper hierarchy

## 📱 Pages

1. **Home** (`/`): Landing page with hero section and overview
2. **About** (`/about`): Personal information and background
3. **Skills** (`/skills`): Technical skills and expertise
4. **Projects** (`/projects`): Portfolio of work and projects

## 🔧 Customization

### Colors

The color scheme can be customized by modifying the CSS variables in `src/styles/global.css`:

```css
:root {
    --accent: 136, 58, 234;
    --accent-light: 224, 204, 250;
    --accent-dark: 49, 10, 101;
}
```

### Content

Update the content in the respective page files to personalize:

-   Personal information in `src/pages/about.astro`
-   Skills and experience in `src/pages/skills.astro`
-   Project descriptions in `src/pages/projects.astro`
-   Contact information in components

### Configuration

Modify `astro.config.mjs` to customize Astro settings, build options, and integrations.

## 🚀 Deployment

This project can be deployed to various platforms:

-   **Vercel**: Connect your GitHub repository for automatic deployments
-   **Netlify**: Drag and drop the `dist` folder or connect your repository
-   **GitHub Pages**: Use GitHub Actions for automated deployment
-   **Cloudflare Pages**: Fast, global deployment with edge functions

### Build Output

After running `npm run build`, the production-ready files will be in the `dist/` directory.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Contact

-   **Website**: [Your Website URL]
-   **LinkedIn**: [Your LinkedIn Profile]
-   **GitHub**: [Your GitHub Profile]
-   **Email**: [Your Email]

---

**Built with ❤️ using Astro**
