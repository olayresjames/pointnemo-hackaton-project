# Team PointNemo - AppBuilders Hackathon

This repository contains Team PointNemo's project for the AppBuilders Hackathon. It brings together an Expo mobile and web app prototype for Point Nemo Film and a standalone bilingual About page.

Point Nemo Film is presented in the About page as an independent production company telling stories that encourage people to look at the world differently. The Expo app is built with React Native, TypeScript, and Expo Router; its screens are currently based on the Expo starter template and are the foundation for the app prototype.

## Run the app

Install dependencies and start Expo:

```bash
npm install
npm start
```

From the Expo CLI, press `a` for Android, `i` for iOS, or `w` for web. You can also start a platform directly:

```bash
npm run android
npm run ios
npm run web
```

The iOS simulator requires macOS. On Windows, use Expo Go on a device or run the web version.

## Repository layout

- `src/app/` - Expo Router screens and navigation layout.
- `src/components/` - reusable app UI components.
- `src/constants/` and `src/hooks/` - theme values and app hooks.
- `assets/` - app icons, images, and other visual assets.
- `index.html` - standalone Italian and English About page for Point Nemo.
- `app.json` - Expo app configuration.

## Useful commands

```bash
npm start                 # Start the Expo development server
npm run android           # Start on Android
npm run ios               # Start on iOS
npm run web               # Start on web
npm run lint              # Run Expo lint
npm run reset-project     # Reset the Expo starter project
```
