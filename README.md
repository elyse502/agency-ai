<div align="center">

# AGENCY AI 🤖

Revolutionizing Digital Agencies with Artificial Intelligence

![Last Commit](https://img.shields.io/github/last-commit/elyse502/agency-ai?style=flat-square)
![Languages](https://img.shields.io/github/languages/top/elyse502/agency-ai?style=flat-square&color=blue)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

_Powered by modern technologies:_

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

## LIVE - DEMO 🌐

Visit the 👉 [_LINK 🔗_](https://agencyai-opal.vercel.app/)

</div>

---

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Environment Variables](#environment-variables)
- [Components Overview](#components-overview)
- [Customization](#customization)
- [Deployment](#deployment)
- [Performance](#performance)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

AGENCY-AI is a modern, responsive landing page template designed for AI-powered digital agencies. This project showcases:

- 🎨 Modern, sleek design with dark/light theme support
- ⚡ Blazing fast performance with Vite
- 📱 Fully responsive across all devices
- 🤖 AI-focused content and design elements
- 🎯 Conversion-optimized sections

Perfect for agencies specializing in AI, machine learning, and digital transformation services.

---

## Key Features

### Design Excellence

- **Dual Theme Support**: Light and dark mode toggle
- **Modern UI**: Clean, professional design with smooth animations
- **Responsive Design**: Flawless experience on desktop, tablet, and mobile
- **Accessibility**: WCAG compliant design principles

### Sections Included

- **Hero Section**: Compelling headline with call-to-action
- **Services**: Showcase AI services with interactive cards
- **Our Work**: Portfolio/case studies display
- **Team**: Team member profiles with expertise
- **Trusted By**: Client logos and testimonials
- **Contact**: Contact form and information

### Technical Features

- **Fast Loading**: Optimized with Vite for instant loading
- **SEO Ready**: Proper meta tags and structured data
- **Easy Customization**: Modular component structure
- **Performance Optimized**: Optimized images and code splitting

---

## Tech Stack

### Frontend

- **React 18** - Modern React with hooks
- **Vite** - Next-generation build tool
- **Tailwind CSS** - Utility-first CSS framework
- **React Icons** - Comprehensive icon library
- **Framer Motion** (optional) - Smooth animations

### Development Tools

- **ESLint** - Code linting and quality
- **Git** - Version control
- **Vercel** - Deployment platform
- **npm** - Package management

---

## Project Structure

```json
agency-ai/
├── public/                 # Static assets
│   ├── favicon.ico        # Site favicon
│   └── index.html         # HTML template
│
├── src/                   # Source code
│   ├── assets/           # Images, icons, fonts
│   ├── components/       # Reusable components
│   │   ├── ContactUs.jsx # Contact section
│   │   ├── Footer.jsx    # Footer component
│   │   ├── Hero.jsx      # Hero section
│   │   ├── Navbar.jsx    # Navigation bar
│   │   ├── OurWork.jsx   # Portfolio section
│   │   ├── ServiceCard.jsx # Individual service card
│   │   ├── Services.jsx  # Services section
│   │   ├── Teams.jsx     # Team section
│   │   ├── ThemeToggleBtn.jsx # Theme switcher
│   │   ├── Title.jsx     # Section titles
│   │   └── TrustedBy.jsx # Clients section
│   │
│   ├── App.jsx           # Main application component
│   ├── index.css         # Global styles
│   └── main.jsx          # Application entry point
│
├── .env                  # Environment variables
├── .gitignore           # Git ignore rules
├── eslint.config.js     # ESLint configuration
├── index.html           # Main HTML file
├── package.json         # Dependencies and scripts
├── vercel.json          # Vercel deployment config
└── vite.config.js       # Vite configuration
```

---

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm (v8 or higher)
- Modern web browser

### Installation

1. Clone the repository:

```console
git clone https://github.com/elyse502/agency-ai.git
cd agency-ai
```

2. Install dependencies:

```console
npm install
```

3. Start the development server:

```console
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

### Environment Variables

Create a `.env` file in the root directory:

```console
VITE_APP_TITLE="Agency AI"
VITE_APP_DESCRIPTION="Modern AI agency landing page"
VITE_CONTACT_EMAIL=your-email@example.com
VITE_CONTACT_PHONE=+1234567890
```

---

## Components Overview

### 🧭 Navigation

- **Navbar.jsx**: Responsive navigation with mobile menu
- **ThemeToggleBtn.jsx**: Dark/light mode toggle

### 🎯 Main Sections

- **Hero.jsx**: Attractive hero section with CTA
- **Services.jsx**: Service offerings with ServiceCard components
- **OurWork.jsx**: Portfolio and case studies
- **Teams.jsx**: Team members and profiles
- **TrustedBy.jsx**: Client logos and testimonials
- **ContactUs.jsx**: Contact form and information

### 🎨 UI Components

- **Title.jsx**: Consistent section titles
- **ServiceCard.jsx**: Individual service cards
- **Footer.jsx**: Site footer with links

---

## Customization

### Content Updates

1. **Text Content**: Edit component files in `/src/components/`
2. **Images**: Replace images in `/src/assets/`
3. **Colors**: Modify Tailwind classes or CSS variables
4. **Theme**: Update color scheme in `index.css`

### Adding New Sections

1. Create new component in `/src/components/`
2. Import and add to `App.jsx`
3. Style with Tailwind CSS classes

### Styling

- Uses Tailwind CSS utility classes
- Custom CSS in `index.css`
- Responsive design with breakpoints

---

## Deployment

### Vercel (Recommended)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fyourusername%2Fagency-ai)

1. Push code to GitHub
2. Connect repository to Vercel
3. Automatic deployments on push

### Manual Build

```bash
npm run build
npm run preview
```

### Other Platforms

- Netlify
- GitHub Pages
- Firebase Hosting
- Any static hosting service

---

## Performance

- ⚡ Lighthouse Score: 95+
- 📦 Bundle Size: < 500KB
- 🖼️ Optimized Images
- 🔄 Code Splitting
- 🎯 SEO Optimized

---

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the project
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## License

Distributed under the MIT License. See [`LICENSE`](https://github.com/elyse502/agency-ai/blob/main/LICENSE) for more information.

---

**AGENCY-AI** - Transforming digital experiences with artificial intelligence! 🚀

---

## Support

For support, email elyseniyibizi502@gmail.com or create an issue in the GitHub repository.

---

## 📞 Contact

For any questions or support, please contact:

- [**NIYIBIZI Elysée**](https://linktr.ee/niyibizi_elysee)👨🏿‍💻 | [Github](https://github.com/elyse502) | [Linkedin](https://www.linkedin.com/in/niyibizi-elys%C3%A9e/) | [Twitter](https://twitter.com/Niyibizi_Elyse).
- **Email**: <elyseniyibizi502@gmail.com>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/niyibizi-elys%C3%A9e/) [![@phenrysay](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/Niyibizi_Elyse) [![pH-7](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/elyse502)

---

<div align="center">

_Built with ❤️ using modern web technologies._

**Made with ❤️ by <i>[Elysée NIYIBIZI](https://elyse502.github.io/Elysee-Portfolio/)</i>**

[⬆ Back to Top](#table-of-contents)

</div>
