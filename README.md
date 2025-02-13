# CollaBro - Collaboration Platform

CollaBro is a modern web application designed to foster collaborative innovation by bringing together individuals from diverse streams and domains to work on impactful projects.

## Features

- 🔐 User Authentication (Login/Signup)
- 👤 Comprehensive User Profiles
- 🎯 Domain-specific Collaboration
- 📝 Project Posting and Management
- 🤝 Team Formation and Networking
- 📊 Progress Tracking

## Prerequisites

Before you begin, ensure you have the following installed on your system:
- [Node.js](https://nodejs.org/) (v18 or higher)
- npm (comes with Node.js)

## Getting Started

Follow these steps to get the frontend running on your local machine:

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd collabro
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```
   The application will start running at `http://localhost:5173`

## Project Structure

```
collabro/
├── src/
│   ├── pages/              # Page components
│   │   ├── Login.jsx
│   │   ├── SignUp.jsx
│   │   ├── Profile.jsx
│   │   └── onboarding/     # Onboarding flow components
│   ├── App.jsx            # Main application component
│   ├── main.jsx          # Application entry point
│   └── index.css         # Global styles
├── public/               # Static assets
├── index.html           # HTML template
├── package.json         # Project dependencies and scripts
├── tailwind.config.js   # Tailwind CSS configuration
└── vite.config.js       # Vite configuration
```

## Available Scripts

- `npm run dev` - Starts the development server
- `npm run build` - Builds the app for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check code quality

## Technology Stack

- **React** - Frontend library
- **Vite** - Build tool and development server
- **Tailwind CSS** - Utility-first CSS framework
- **React Router** - Client-side routing
- **Lucide React** - Icon library

## Development Flow

1. The application starts at the login page (`/login`)
2. New users can sign up through the registration page (`/signup`)
3. First-time users go through an onboarding process:
   - Basic Information
   - Category Selection
   - Domain Selection
   - Resume Upload
4. After onboarding/login, users are directed to the dashboard
5. Users can access their profile page through the navigation

## Styling Guidelines

- The application uses Tailwind CSS for styling
- Custom animations are defined in `src/index.css`
- Consistent color scheme:
  - Primary: Blue (`blue-500`, `blue-600`)
  - Background: Gray (`gray-100`, `gray-900`)
  - Text: White/Gray for dark backgrounds, Gray for light backgrounds

## Best Practices

1. **Code Organization**
   - Keep components focused and single-responsibility
   - Use meaningful component and variable names
   - Maintain consistent file structure

2. **Performance**
   - Lazy load routes when possible
   - Optimize images and assets
   - Use proper React hooks and memoization

3. **Accessibility**
   - Use semantic HTML elements
   - Provide proper ARIA labels
   - Ensure keyboard navigation works

4. **State Management**
   - Use React hooks for local state
   - Implement proper form validation
   - Handle loading and error states

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## Support

For any questions or issues, please open an issue in the repository.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
