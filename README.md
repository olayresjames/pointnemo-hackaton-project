# Point Nemo Film

React Native app powered by Expo, with TypeScript and Expo Router. The existing `index.html` page is kept in the repository alongside the app.

## Get started

Install dependencies, then start the development server:

```bash
npm install
npm start
```

From the Expo CLI, press `a` to open Android, `i` to open iOS, or `w` to open the web app. You can also run `npm run android`, `npm run ios`, or `npm run web` directly. iOS simulator builds require macOS; on Windows, use Expo Go or an iOS device.

## Project structure

- `src/app/` contains file based routes and navigation layouts.
- `src/components/` contains reusable UI components.
- `assets/` contains app icons and images.
- `app.json` contains the Expo app configuration.

Edit `src/app/index.tsx` to change the home screen.

## Useful commands

```bash
npm start          # Start Expo development server
npm run android    # Start on Android
npm run ios        # Start on iOS
npm run web        # Start on web
npm run reset-project  # Move the starter UI aside and create a clean route
```
