# Soaked

Soaked is an Angular-based web application that serves as a leaderboard and promotional platform for online gaming affiliates. The project focuses on tracking and displaying user statistics from Roobet and Packdraw gaming platforms, providing a seamless interface for users to view leaderboard rankings and access the gaming platforms.

## Tech Stack

- **Frontend Framework**: Angular 17.3.x
- **Server-Side Rendering**: Angular SSR (Server-Side Rendering)
- **Backend**: Express.js
- **HTTP Communication**: Angular HttpClient
- **Styling**: CSS with custom animations and responsive design
- **Routing**: Angular Router for navigation between different views
- **API Integration**: RESTful API integration with gaming platforms

## Features

- **Dual Platform Integration**: Seamlessly connects with both Roobet and Packdraw gaming platforms
- **Leaderboard Display**: Shows real-time leaderboard data from affiliate programs
- **Responsive Design**: Optimized for both desktop and mobile devices
- **Server-Side Rendering**: Improved performance and SEO with Angular SSR
- **API Authentication**: Secure API calls with token-based authentication
- **Date Range Filtering**: Filter statistics based on custom date ranges

## Main Components

- **Landing Component**: The main entry point displaying user statistics and promotional content
- **Packdraw Component**: Dedicated view for Packdraw-specific leaderboard and information
- **User Lists**: Displays user rankings and statistics
- **Header/Footer**: Navigation and branding elements

## API Integration

The application integrates with two primary APIs:
1. **Roobet API**: Fetches affiliate statistics and user data
2. **Packdraw API**: Retrieves leaderboard information and promotional content

## Getting Started

### Prerequisites

- Node.js (v18.x or later recommended)
- Angular CLI (v17.3.x)

### Installation

```bash
# Clone the repository
git clone <repository-url>

# Navigate to the project directory
cd soaked

# Install dependencies
npm install
```

### Development Server

```bash
# Start the development server
ng serve

# Navigate to http://localhost:4200/
```

### Building for Production

```bash
# Build the project
ng build

# For SSR build
ng build && ng run soaked:server
```

### Running the Server

```bash
# After building, run the server
node dist/soaked/server/server.mjs
```

## Project Structure

- `src/app/components/`: Contains all Angular components
- `src/app/services/`: API services for data fetching
- `src/app/pipe/`: Custom Angular pipes
- `src/assets/`: Static assets like images and icons
- `server.ts`: Express server configuration for SSR

## Deployment

The application is configured for deployment on platforms like Vercel with server-side rendering support.

## License

This project is proprietary software.
