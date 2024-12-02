# Cybersecurity Training Platform

A modern web application for cybersecurity awareness training, featuring phishing simulation management and interactive learning modules.

![Cybersecurity Training Platform](https://images.unsplash.com/photo-1550751827-4bd374c3f58b?auto=format&fit=crop&q=80)

## Features

- 🔐 **User Authentication**
  - Secure login and registration
  - Role-based access control (Admin/User)
  - Password recovery functionality

- 📚 **Training Modules**
  - Interactive cybersecurity lessons
  - Progress tracking
  - Quizzes and assessments
  - Different difficulty levels (Beginner/Intermediate/Advanced)

- 📧 **Phishing Simulation**
  - Create and manage phishing campaigns
  - Track campaign performance
  - Detailed analytics and reporting
  - User response monitoring

- 📊 **Analytics Dashboard**
  - User engagement metrics
  - Training completion rates
  - Phishing campaign success rates
  - Visual data representation

## Tech Stack

- **Frontend**
  - React 18
  - TypeScript
  - Tailwind CSS
  - React Query
  - Zustand (State Management)
  - React Hook Form
  - Recharts
  - Lucide Icons

- **Development Tools**
  - Vite
  - ESLint
  - PostCSS
  - Autoprefixer

## Getting Started

### Prerequisites

- Node.js 18.x or higher
- npm 9.x or higher

### Local Development

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd cybersecurity-training-platform
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory:
   ```env
   VITE_API_URL=http://localhost:3000/api
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open [http://localhost:5173](http://localhost:5173) in your browser

### Production Build

1. Create a production build:
   ```bash
   npm run build
   ```

2. Preview the production build:
   ```bash
   npm run preview
   ```

## Deployment

### Netlify Deployment

1. Push your code to a Git repository

2. Connect your repository to Netlify

3. Configure build settings:
   - Build command: `npm run build`
   - Publish directory: `dist`

4. Set environment variables in Netlify dashboard:
   - `VITE_API_URL`: Your API URL

5. Deploy! Netlify will automatically build and deploy your application

## Project Structure

```
src/
├── components/         # Reusable UI components
│   ├── auth/          # Authentication components
│   ├── layout/        # Layout components
│   ├── modules/       # Training module components
│   ├── providers/     # Context providers
│   └── ui/            # Base UI components
├── lib/               # Utilities and helpers
│   ├── api.ts         # API client
│   ├── auth.ts        # Authentication utilities
│   ├── store.ts       # Global state management
│   ├── types.ts       # TypeScript types
│   └── utils.ts       # Helper functions
├── pages/             # Application pages
└── main.tsx           # Application entry point
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.