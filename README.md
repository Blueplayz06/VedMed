# VedMed - Cloud-Based Medical Platform

A modern, responsive landing page for a cloud-based medical website built with React and Tailwind CSS.

## Features

- **Modern Design**: Clean white and green theme with professional medical interface
- **Responsive Layout**: Mobile-friendly design that works on all devices
- **Component-Based**: Built with reusable React components
- **Interactive Elements**: Smooth animations and hover effects
- **Medical-Focused**: HIPAA compliance indicators and healthcare-specific features

## Tech Stack

- **React 18**: Modern React with hooks
- **Tailwind CSS**: Utility-first CSS framework
- **Lucide React**: Beautiful, customizable icons
- **Google Fonts**: Inter font family for clean typography

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd vedmed
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Project Structure

```
src/
├── components/
│   ├── Navbar.js          # Fixed navigation bar with logo and login
│   ├── Hero.js            # Hero section with main CTA
│   ├── Features.js        # Feature cards section
│   └── Footer.js          # Footer with links
├── App.js                 # Main app component
├── index.js              # React entry point
└── index.css             # Tailwind CSS and custom styles
```

## Components Overview

### Navbar
- Fixed top navigation
- Logo with gradient design
- Responsive mobile menu
- Login dropdown with Doctor/Patient options

### Hero
- Large heading with medical theme
- Trust indicators (HIPAA, Users, Security)
- CTA buttons
- Medical illustration with doctor-patient interaction

### Features
- 4 feature cards: EHR System, E-Prescriptions, Appointments, Lab Reports
- Interactive hover effects
- Trust indicators section
- Bottom CTA section

### Footer
- Company information
- Quick links
- Legal links (Terms, Privacy, HIPAA)
- Social contact icons

## Customization

### Colors
The project uses a custom medical color palette defined in `tailwind.config.js`:

- `medical-green`: Primary green colors (#22c55e, etc.)
- `medical-blue`: Secondary blue colors (#3b82f6, etc.)

### Styling
Custom CSS classes are defined in `src/index.css`:

- `.btn-primary`: Primary button styling
- `.btn-secondary`: Secondary button styling
- `.card`: Card component styling
- `.nav-link`: Navigation link styling

## Available Scripts

- `npm start`: Runs the app in development mode
- `npm test`: Launches the test runner
- `npm run build`: Builds the app for production
- `npm run eject`: Ejects from Create React App (not recommended)

## Deployment

The app can be deployed to any static hosting service:

1. Build the project:
```bash
npm run build
```

2. Deploy the `build` folder to your hosting service.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is licensed under the MIT License. 
