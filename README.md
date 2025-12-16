# React + Vite
TecBus Website - Modern React Application
A sleek, responsive website for TecBus built with cutting-edge web technologies. Features modern UI components, smooth animations, and optimized performance.

https://img.shields.io/badge/React-19.1.0-61DAFB?style=for-the-badge&logo=react
https://img.shields.io/badge/Vite-6.3.5-646CFF?style=for-the-badge&logo=vite
https://img.shields.io/badge/Tailwind-4.1.7-38B2AC?style=for-the-badge&logo=tailwind-css

✨ Features
⚡ Blazing Fast - Built with Vite for instant hot module replacement

🎨 Modern Design - Styled with Tailwind CSS 4

📱 Fully Responsive - Works on all devices

🎪 Interactive Components - Swiper carousels & smooth animations

🔗 Client-Side Routing - React Router 7 for seamless navigation

🚀 Production Ready - Optimized builds & performance

✅ Code Quality - ESLint & TypeScript support

🛠️ Tech Stack
Technology	Purpose
React 19	UI Library
Vite 6	Build Tool & Dev Server
Tailwind CSS 4	Styling Framework
React Router 7	Navigation
Swiper	Touch Sliders & Carousels
React Icons	Icon Library
ESLint	Code Quality
📁 Project Structure
text
tecbus-website/
├── src/                    # Source code
│   ├── components/         # React components
│   ├── assets/            # Images, fonts, etc.
│   ├── styles/            # Global styles
│   └── main.jsx           # Application entry point
├── public/                # Static assets
├── index.html             # Main HTML file
├── vite.config.js         # Vite configuration
├── tailwind.config.js     # Tailwind configuration
├── eslint.config.js       # ESLint configuration
└── package.json           # Dependencies
🚀 Getting Started
Prerequisites
Node.js 18+

npm or yarn

Installation
Clone the repository

bash
git clone https://github.com/yourusername/tecbus-website.git
cd tecbus-website
Install dependencies

bash
npm install
# or
yarn install
Start development server

bash
npm run dev
# or
yarn dev
Open in browser
Navigate to http://localhost:5173

Available Scripts
Script	Description
npm run dev	Start development server
npm run build	Build for production
npm run preview	Preview production build
npm run lint	Run ESLint
🎨 Customization
Theme Configuration
Edit tailwind.config.js to customize colors, fonts, and breakpoints:

javascript
export default {
  theme: {
    extend: {
      colors: {
        primary: '#3B82F6',
        secondary: '#10B981',
      },
      fontFamily: {
        sans: ['Inter', 'system-ui'],
      },
    },
  },
}
Adding Pages
Create new components in src/components/

Add routes in your router configuration

Import and use in your application

📦 Building for Production
bash
npm run build
The build artifacts will be stored in the dist/ directory, ready for deployment.

🔧 Development
Code Quality
ESLint is configured for React best practices

Run npm run lint to check code quality

Use Prettier for consistent formatting (optional)

Best Practices
Component-based architecture

Responsive design patterns

Performance optimization

Accessibility compliance

🌐 Deployment
GitHub Pages
bash
npm run build
npm run deploy
Vercel / Netlify
Connect your repository to Vercel or Netlify for automatic deployments.

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🤝 Contributing
Fork the repository

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request


