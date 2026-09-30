# CasinoGPT Mobile App

Expo React Native mobile application for CasinoGPT.

## Prerequisites

- Node 18+
- npm or yarn
- Expo CLI: `npm install -g expo-cli`
- EAS CLI: `npm install -g eas-cli`
- Xcode (for iOS builds)
- Android Studio (for Android builds)

## Installation

```bash
cd apps/mobile
npm install
```

## Development

```bash
npm start

# On iOS
npm run ios

# On Android
npm run android

# On Web
npm run web
```

## Building

### Web Build

```bash
npm run build:web
```

### iOS Build (Production)

```bash
npm run build:ios
```

### Android Build (Production)

```bash
npm run build:android
```

### All Platforms

```bash
npm run build:all
```

## Submitting to App Stores

### iOS App Store

```bash
npm run submit:ios
```

### Google Play Store

```bash
npm run submit:android
```

## Testing

```bash
npm test
```

## Linting

```bash
npm run lint
```

## Type Checking

```bash
npm run type-check
```

## Configuration

- `app.json` - Expo app configuration
- `eas.json` - EAS build and submit configuration
- `tsconfig.json` - TypeScript configuration

## Environment Variables

Create a `.env` file based on `.env.example`:

```bash
cp .env.example .env
```

Update with your API credentials:

- `EXPO_TOKEN` - Expo authentication token
- `OPENAI_API_KEY` - ChatGPT API key
- `API_URL` - Backend API endpoint
