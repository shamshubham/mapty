# Mapty

Mapty is a web application that allows users to log and track their running and cycling activities on a map. It uses the browser's Geolocation API to pinpoint your current location and provides a convenient way to record and review your activities.

## Getting Started

### Prerequisites

To run this project locally, you need to have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd mapty
   ```

2. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   # or
   bun install
   ```

### Running the Development Server

Start the development server with:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

= Open http://localhost:3000 in your browser to view the application.

## Usage

Once the application is running:

- Grant Geolocation Permission: The app will request access to your location. This is necessary to log your activities on the map.
- Log an Activity: Click on the map at your current location and fill in the activity details (e.g., distance, duration, type).
- View Activities: All logged activities are displayed on the map with markers, showing the type and details of the activity.

## Technologies Used

- Next.js: For building the user interface and handling server-side rendering.
- Leaflet: For interactive maps.
- Geolocation API: To access the user's current location.

## Learn More

To learn more about the technologies used in this project, visit:

- Next.js Documentation
- Leaflet Documentation
- MDN Web Docs: Geolocation API

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request with your improvements.

## License

This project is licensed under the MIT License.

## Acknowledgments

This project is inspired by the "Mapty" project by Jonas Schmedtmann.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the Vercel Platform from the creators of Next.js.

Check out the Next.js deployment documentation for more details.

Feel free to customize this README with specific details about your project and add any additional sections you think are necessary.
