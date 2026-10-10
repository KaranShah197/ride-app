# Ride App

A ride-sharing application built with Next.js.

## Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later)
- npm, yarn, or pnpm

## Getting Started

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd ride-app
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Set up environment variables**

   Copy the example env file and fill in your values:

   ```bash
   cp .env.example .env.local
   ```

4. **Run the development server**

   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

   Open [http://localhost:3000](http://localhost:3000) in your browser.

## Scripts

| Command         | Description                        |
| --------------- | ---------------------------------- |
| `npm run dev`   | Start the development server       |
| `npm run build` | Build the app for production       |
| `npm run start` | Start the production server        |
| `npm run lint`  | Run ESLint                         |

## Project Structure

```
ride-app/
├── app/          # Next.js app directory (pages & layouts)
├── components/   # Reusable UI components
├── lib/          # Utility functions and helpers
├── public/       # Static assets
└── styles/       # Global styles
```

## Contributing

1. Create a new branch: `git checkout -b feature/your-feature`
2. Commit your changes: `git commit -m "feat: add your feature"`
3. Push to the branch: `git push origin feature/your-feature`
4. Open a pull request against `main`