# FYP – Parking Spot Detection

This Final Year Project (FYP) implements a parking spot detection system. It uses computer vision and/or machine learning techniques to identify whether parking spaces are occupied or free, and displays the results through a web interface.

## Features

- Detects parking spots from camera input or images
- Classifies each spot as occupied or available
- Provides a web-based interface to view results
- Built with modern web technologies (TypeScript, Vite, React)

## Tech Stack

- **Frontend:** TypeScript, React, Vite
- **Styling:** CSS
- **AI/ML Integration:** As described in `GEMINI.md`
- **Tooling:** ESLint, TypeScript configuration

## Project Structure

- `src/` – Main application source code
- `public/` – Static assets
- `index.html` – Entry HTML file
- `vite.config.ts` – Vite configuration
- `tsconfig*.json` – TypeScript configuration
- `eslint.config.js` – ESLint rules
- `GEMINI.md` – Notes/documentation on AI/ML integration
- `package.json` – Project dependencies and scripts

## Getting Started

### Prerequisites

- Node.js (LTS version recommended)
- npm or yarn

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ac0915/FYP_ParkingSpotDetection.git
   cd FYP_ParkingSpotDetection
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open your browser and go to the URL shown in the terminal (usually `http://localhost:5173`).

## Usage

- Launch the app as described above.
- Upload images or connect a camera feed (depending on your implementation).
- The system will analyze the input and display which parking spots are occupied or free.

Refer to `GEMINI.md` for details on the AI/ML model, training process, and integration.

## Build for Production

To create a production build:

```bash
npm run build
```

The built files will be in the `dist` folder (or as configured in `vite.config.ts`).

## Development Notes

- Use `npm run lint` (if configured) to check code quality.
- Modify `vite.config.ts` for custom build or server settings.
- Adjust TypeScript settings in `tsconfig.app.json` and `tsconfig.node.json` as needed.

## License

This project is created as a Final Year Project and is provided as-is for educational purposes.
