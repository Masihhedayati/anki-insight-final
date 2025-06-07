# Anki Insight Dashboard

## Overview

Anki Insight Dashboard is a modern, comprehensive analytics dashboard for Anki spaced repetition software. Built with React, TypeScript, and shadcn/ui, it provides powerful visualization and tracking capabilities for your study patterns, retention metrics, and learning progress.

## Features

### 📊 Study Analytics
- **Review Activity Tracking**: Visualize daily, weekly, and monthly review patterns
- **Statistics Overview**: Key metrics including total cards, retention rate, study streak
- **Card Performance Analysis**: Track card difficulty distribution and performance trends
- **Retention Metrics**: Monitor retention rates across different time intervals
- **Future Workload Prediction**: Forecast upcoming review sessions and workload
- **Study Pattern Analysis**: Identify your most productive study times and habits

### 🎨 User Experience
- **Modern UI Design**: Clean, intuitive interface built with shadcn/ui components
- **Dark/Light Theme**: Toggle between dark and light modes for comfortable studying
- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile
- **Interactive Charts**: Dynamic, interactive visualizations powered by Recharts
- **Customizable Settings**: Adjust chart settings and display preferences

### 🛠 Technical Features
- **Type-Safe Development**: Built with TypeScript for robust, maintainable code
- **Fast Performance**: Powered by Vite for lightning-fast development and builds
- **Component Architecture**: Modular, reusable React components
- **Modern Styling**: Tailwind CSS with custom animations and transitions
- **State Management**: Context API for efficient state management

## Tech Stack

- **Framework**: React 18.3.1
- **Language**: TypeScript 5.5.3
- **Build Tool**: Vite 5.4.1
- **UI Components**: shadcn/ui (Radix UI primitives)
- **Styling**: Tailwind CSS 3.4.11
- **Charts**: Recharts 2.12.7
- **Routing**: React Router DOM 6.26.2
- **State Management**: React Context API
- **Date Handling**: date-fns 3.6.0
- **Form Handling**: React Hook Form 7.53.0
- **Notifications**: Sonner 1.5.0

## Project Structure

```
├── src/
│   ├── components/      # UI components
│   │   ├── ui/         # shadcn/ui components
│   │   ├── DashboardHeader.tsx
│   │   ├── ReviewActivity.tsx
│   │   ├── StatsOverview.tsx
│   │   ├── CardPerformance.tsx
│   │   ├── RetentionMetrics.tsx
│   │   ├── FutureWorkload.tsx
│   │   ├── StudyPatterns.tsx
│   │   └── ...
│   ├── context/        # React context providers
│   ├── data/           # Mock data and types
│   ├── hooks/          # Custom React hooks
│   ├── lib/            # Utility functions
│   ├── pages/          # Page components
│   ├── utils/          # Helper functions
│   ├── App.tsx         # Main app component
│   └── main.tsx        # Entry point
├── public/             # Static assets
├── index.html          # HTML template
├── package.json        # Dependencies
├── tailwind.config.ts  # Tailwind configuration
└── vite.config.ts      # Vite configuration
```

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Masihhedayati/anki-insight-final.git
cd anki-insight-final
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

### Building for Production

```bash
npm run build
```

The built files will be in the `dist` directory.

### Preview Production Build

```bash
npm run preview
```

## Development

### Available Scripts

- `npm run dev` - Start development server with hot reload
- `npm run build` - Build for production
- `npm run build:dev` - Build in development mode
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint for code quality

### Key Components

1. **DashboardHeader**: Main header with app branding and navigation
2. **ReviewActivity**: Displays review activity over time with interactive charts
3. **StatsOverview**: Shows key statistics and metrics at a glance
4. **CardPerformance**: Analyzes card difficulty and performance distribution
5. **RetentionMetrics**: Tracks retention rates across different intervals
6. **FutureWorkload**: Predicts upcoming review sessions
7. **StudyPatterns**: Identifies study habits and optimal study times

### Customization

The dashboard includes several customization options:

- **Theme**: Toggle between light and dark themes
- **Chart Settings**: Adjust chart display options
- **Date Ranges**: Filter data by different time periods
- **Animations**: Smooth transitions and data-focused animations

## Data Integration

This dashboard currently uses mock data for demonstration. To integrate with real Anki data:

1. Export your Anki statistics
2. Replace the mock data in `src/data/` with your actual data
3. Adjust data parsing logic as needed

Future versions will include direct Anki integration via AnkiConnect or similar APIs.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Development Guidelines

- Follow TypeScript best practices
- Use the existing component patterns
- Ensure responsive design works on all devices
- Add appropriate type definitions
- Test thoroughly before submitting PR

## License

This project is open source and available under the MIT License.

## Acknowledgments

- Built with [Lovable](https://lovable.dev)
- UI components from [shadcn/ui](https://ui.shadcn.com)
- Charts powered by [Recharts](https://recharts.org)
- Icons from [Lucide](https://lucide.dev)

## Contact

For questions, suggestions, or issues, please open an issue on GitHub.