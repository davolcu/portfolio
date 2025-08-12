# David Olmos - Personal Website

A modern, flashy personal website built with **Astro** and **Tailwind CSS**. This website showcases my skills as a Senior Frontend Engineer with a creative, modern design inspired by Astro's website.

## ✨ Features

-   **Modern Design**: Clean, professional layout with gradient accents and smooth animations
-   **Responsive**: Fully responsive design that works on all devices
-   **Interactive Elements**: Particle background, smooth scrolling, and hover effects
-   **Performance Optimized**: Built with Astro for optimal performance and SEO
-   **Accessible**: Proper semantic HTML and ARIA labels
-   **Mobile-First**: Mobile navigation with hamburger menu

## 🚀 Tech Stack

-   **Framework**: [Astro](https://astro.build/) - The web framework for content-driven websites
-   **Styling**: [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
-   **Fonts**: [Inter](https://fonts.google.com/specimen/Inter) - Modern, clean typography
-   **Icons**: Custom SVG icons and emojis
-   **Animations**: CSS animations and transitions

## 🛠️ Getting Started

### Prerequisites

-   Node.js (version 16 or higher)
-   npm or yarn

### Installation

1. Clone the repository:

```bash
git clone <your-repo-url>
cd dolmos-dev
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:4321`

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## 📁 Project Structure

```
src/
├── components/          # Reusable components
│   ├── MobileNav.astro
│   └── ParticleBackground.astro
├── layouts/            # Layout components
│   └── Layout.astro
├── pages/              # Page components
│   └── index.astro
└── styles/             # Global styles
    └── global.css

public/                 # Static assets
├── favicon.svg
└── ...
```

## 🎨 Design Features

-   **Gradient Text**: Beautiful gradient text effects using CSS
-   **Particle Background**: Animated floating particles for visual appeal
-   **Smooth Animations**: Hover effects, transitions, and micro-interactions
-   **Glass Morphism**: Backdrop blur effects and transparent elements
-   **Color Scheme**: Purple and blue gradient theme with dark mode

## 📱 Sections

1. **Hero Section**: Eye-catching introduction with animated elements
2. **About**: Personal information and statistics
3. **Skills**: Technical skills with progress bars
4. **Projects**: Featured projects with technology tags
5. **Contact**: Contact form and social links

## 🔧 Customization

### Colors

The color scheme can be customized by modifying the CSS variables in `src/layouts/Layout.astro`:

```css
:root {
    --accent: 136, 58, 234;
    --accent-light: 224, 204, 250;
    --accent-dark: 49, 10, 101;
}
```

### Content

Update the content in `src/pages/index.astro` to personalize:

-   Personal information
-   Skills and experience levels
-   Project descriptions
-   Contact information

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

---

**Built with ❤️ using Astro**
