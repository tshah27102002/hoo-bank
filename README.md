# HooBank - Business Website Template

A modern, responsive business website template built with React, Vite, and Tailwind CSS. Perfect for financial services, fintech companies, or any professional business looking to establish an online presence.

## 🌟 Features

- **Modern Design**: Clean and professional UI with a dark theme
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Component-Based Architecture**: Modular React components for easy customization
- **Tailwind CSS**: Utility-first CSS framework for rapid styling
- **Lightning Fast**: Powered by Vite for instant HMR (Hot Module Replacement)
- **SEO Ready**: Semantic HTML structure and meta tags
- **Production Ready**: Pre-configured build and deployment setup

## 🎯 Key Sections

The template includes the following pre-built sections:

- **Navbar**: Responsive navigation bar with menu
- **Hero**: Eye-catching hero section with call-to-action
- **Stats**: Showcase key metrics and achievements
- **Business**: Business overview and features
- **Billing**: Pricing and subscription options
- **Card Deal**: Special offers or featured products
- **Testimonials**: Client testimonials and reviews
- **Clients**: Client logos or partnership section
- **CTA**: Call-to-action section for conversions
- **Footer**: Comprehensive footer with links and information

## 🚀 Quick Start

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd business-website-template
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

The application will be available at `http://localhost:5173` (or another port if 5173 is in use).

## 📦 Available Scripts

- **`npm run dev`** - Start the development server with hot module replacement
- **`npm run build`** - Create an optimized production build
- **`npm run preview`** - Preview the production build locally

## 🛠️ Tech Stack

- **React** (v18.2.0) - UI library
- **Vite** (v4.1.0) - Build tool and dev server
- **Tailwind CSS** (v3.2.7) - Utility-first CSS framework
- **PostCSS** (v8.4.21) - CSS transformation
- **Autoprefixer** - Automatic vendor prefixes

## 📁 Project Structure

```
src/
├── components/          # React components
│   ├── Navbar.jsx
│   ├── Hero.jsx
│   ├── Stats.jsx
│   ├── Business.jsx
│   ├── Billing.jsx
│   ├── CardDeal.jsx
│   ├── Testimonials.jsx
│   ├── Clients.jsx
│   ├── CTA.jsx
│   ├── Footer.jsx
│   ├── Button.jsx
│   ├── Feedback.jsx
│   ├── GetStarted.jsx
│   └── index.js
├── assets/              # Images and static assets
├── constants/           # Constants and configuration
├── App.jsx             # Main app component
├── main.jsx            # Application entry point
├── style.js            # Global styles and utilities
└── index.css           # Global CSS with Tailwind

public/                 # Static files
```

## 🎨 Customization

### Colors and Styling

Edit the Tailwind configuration in [tailwind.config.cjs](tailwind.config.cjs) to customize colors, fonts, and other design tokens.

### Content

Update component files in the `src/components/` directory to modify content, images, and text.

### Constants

Modify [src/constants/index.js](src/constants/index.js) to manage constant values used throughout the application.

## 🚢 Deployment

The project is ready to be deployed to various platforms:

1. **Build the application**:

```bash
npm run build
```

2. Deploy the `dist/` folder to your hosting service:
   - Vercel
   - Netlify
   - GitHub Pages
   - AWS S3
   - Any static hosting provider

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 💡 Tips

- Customize the components to match your brand identity
- Update images in the `src/assets/` directory
- Modify colors using Tailwind CSS utility classes
- Add additional components as needed
- Use the responsive utilities for mobile optimization

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests for any improvements.

## 📧 Support

For issues, questions, or suggestions, please open an issue in the repository.

---

**Happy coding!** 🎉
