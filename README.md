# React Native Expo Boilerplate

A modern, feature-rich boilerplate for building React Native applications with Expo. This template includes everything you need to start building production-ready mobile apps.

## Features

- 🎨 Beautiful, modern UI with dark mode support
- 🔐 Authentication ready with Supabase
- 📱 Cross-platform (iOS/Android)
- 🔄 Offline support built-in
- 🎯 TypeScript for type safety
- 📍 Navigation setup with Expo Router
- 💫 Smooth animations with Reanimated
- 📸 Camera and image picker integration
- 🔔 Push notifications ready
- 🎮 Haptic feedback support
- 🔄 State management setup
- 🧪 Testing configuration with Jest

## Tech Stack

- React Native with Expo
- TypeScript
- Supabase for authentication and data storage
- Expo Router for navigation
- React Native Reanimated for animations
- Expo's comprehensive SDK features
- Jest for testing

## Getting Started

### Prerequisites

- Node.js (v14 or newer)
- npm or yarn
- Expo CLI
- iOS Simulator or Android Emulator (optional)
- Supabase account (optional)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/react-native-expo-boilerplate.git
cd react-native-expo-boilerplate
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
- Copy `.env.example` to `.env`
- Update the variables as needed for your project

4. Start the development server:
```bash
npx expo start
```

5. Run on your device:
- Scan the QR code with Expo Go (Android)
- Press 'i' for iOS Simulator
- Press 'a' for Android Emulator

## Project Structure

```
├── assets/            # Static assets like images and fonts
├── src/
│   ├── components/    # Reusable UI components
│   ├── screens/       # Screen components
│   ├── navigation/    # Navigation configuration
│   ├── hooks/        # Custom React hooks
│   ├── utils/        # Utility functions
│   ├── services/     # API and third-party service integrations
│   ├── constants/    # App constants and configuration
│   └── types/        # TypeScript type definitions
├── app/              # Expo Router app directory
├── tests/            # Test files
└── docs/             # Documentation
```

## Environment Variables

Create a `.env` file in the root directory:
```
# Add your environment variables here
EXPO_PUBLIC_SUPABASE_URL=your_supabase_url
EXPO_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## Features in Detail

### Authentication
- Ready-to-use authentication flow with Supabase
- Social login support
- Secure token management

### Navigation
- File-based routing with Expo Router
- Deep linking support
- Type-safe navigation

### UI/UX
- Clean, intuitive interface
- Dark mode support
- Haptic feedback
- Smooth animations
- Offline capability
- Loading states and error boundaries

### Development
- TypeScript configuration
- ESLint and Prettier setup
- Jest testing environment
- Development tools and debugging setup

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


Need help?
Join our AI Tech Community - skool.com/vibecodepioneers

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

If you find this template helpful, please give it a ⭐️ on GitHub!
