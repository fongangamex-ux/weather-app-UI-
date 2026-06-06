# Weather App Design

A modern weather application built with **Angular 21** and **Vite**, featuring a beautiful dark mode interface with real-time weather data.

## Features

- **City Search**: Search for any city worldwide to get current weather conditions
- **Quick City Selection**: One-click access to popular Cameroon cities:
  - Yaoundé
  - Douala
  - Bafoussam
  - Garoua
  - Limbe

- **Current Weather Display**: Shows temperature, weather conditions, date, and location with weather emoji icons

- **5-Day Forecast**: CSS Grid layout displaying daily forecasts with high/low temperatures and weather icons

- **Today's Highlights**: Detailed weather metrics including:
  - Wind Speed (m/s)
  - Humidity (%)
  - Visibility (km)
  - Air Pressure (hPa)
  - Feels Like Temperature (°C)
  - UV Index

- **Dark Mode Theme**: Sleek dark interface with gradient backgrounds and enhanced card effects with hover animations

- **Responsive Design**: Optimized for desktop and mobile devices

## Technology Stack

- **Framework**: Angular 21 (Standalone Components)
- **Build Tool**: Vite
- **Styling**: CSS with dark mode gradients
- **HTTP Client**: Angular HttpClient
- **Weather API**: OpenWeatherMap

## Getting Started

### Prerequisites
- Node.js v20+
- npm or yarn

### Installation

```bash
# Install dependencies
npm install

# Start development server
npm start
```

The app will open at `http://localhost:4200`

### Build for Production

```bash
npm run build
```

This will compile your project and store the build artifacts in the `dist/` directory.

## Running Tests

To execute unit tests with the [Vitest](https://vitest.dev/) test runner:

```bash
npm test
```

## File Structure

```
src/app/
├── features/
│   └── weather/
│       ├── components/
│       │   ├── current-weather/
│       │   ├── forecast/
│       │   ├── highlights/
│       │   └── sidebar/
│       └── pages/
│           └── home/
├── core/
│   └── services/
│       └── weather.service.ts
└── models/
    ├── weather.ts
    └── forecast.ts
```

## Design Highlights

- **Dark Mode**: Gradient backgrounds (#1a1a2e, #0f3460, #16213e)
- **Color Accents**: Cyan (#00d4ff) headings with purple gradient cards
- **Interactive Elements**: Hover effects with smooth transforms and enhanced shadows
- **Responsive Grid**: Adapts from 2-column (sidebar + content) to single column on mobile

## License

This project is open source and available under the MIT License.

---

Built with ❤️ using Angular 21 for learning modern web development practices.

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
