# StickerSmash 🎨

A fun and interactive mobile app built with Expo and React Native that lets you create custom stickers by adding emojis and effects to your photos.

## Features

- 📸 Upload photos from your device
- 😄 Add emojis and stickers to your photos
- 🎨 Apply image effects and filters
- 💾 Save your creations to your device
- 📱 Cross-platform support (iOS and Android)

## Technologies Used

- [Expo](https://expo.dev) - React Native development framework
- [React Native](https://reactnative.dev) - Mobile app framework
- [TypeScript](https://www.typescriptlang.org/) - Type-safe JavaScript
- Various Expo modules including:
  - expo-image-picker
  - expo-image
  - expo-blur
  - expo-haptics

## Getting Started

1. **Prerequisites**
   - Node.js (LTS version recommended)
   - npm or yarn
   - [Expo Go](https://expo.dev/go) app on your mobile device

2. **Installation**

   ```bash
   # Clone the repository (if applicable)
   git clone <repository-url>
   cd StickerSmash

   # Install dependencies
   npm install
   ```

3. **Running the App**

   ```bash
   # Start the development server
   npm start
   # or
   npx expo start
   ```

   Then, you can:
   - Scan the QR code with Expo Go (Android) or Camera app (iOS)
   - Press 'a' to open in Android emulator
   - Press 'i' to open in iOS simulator

## Available Scripts

- `npm start` - Start the Expo development server
- `npm run android` - Start the app in Android emulator
- `npm run ios` - Start the app in iOS simulator
- `npm run web` - Start the app in web browser
- `npm test` - Run tests
- `npm run lint` - Run linting

## Project Structure

```
StickerSmash/
├── app/              # Main application code
├── assets/           # Static assets (images, fonts)
├── components/       # Reusable React components
└── package.json      # Project dependencies and scripts
```

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details.
