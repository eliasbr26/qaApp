# qaApp

A React Native application built with Expo and TypeScript for creating a Q&A (Question and Answer) platform.

## 📋 Overview

qaApp is a mobile application starter project designed for building question and answer functionality. The project is built using modern React Native technologies with full TypeScript support.

## 🛠️ Tech Stack

- **React Native** - Cross-platform mobile development framework
- **Expo** - Development platform for React Native applications
- **TypeScript** - Strongly typed programming language (100% TypeScript)
- **Expo Status Bar** - Native status bar component

## 📁 Project Structure

```
qaApp/
├── App.tsx           # Main application component
├── index.ts          # Application entry point
├── app.json          # Expo configuration
├── package.json      # Dependencies and scripts
├── tsconfig.json     # TypeScript configuration
├── assets/           # Images, fonts, and other static files
└── .gitignore        # Git ignore rules
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Expo CLI
- Expo Go app (for testing on physical devices)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/eliasbr26/qaApp.git
cd qaApp
```

2. Install dependencies:
```bash
npm install
```

### Running the Application

Start the development server:
```bash
npm start
```

This will open the Expo developer tools in your browser. From there, you can:
- Press `i` to open in iOS simulator
- Press `a` to open in Android emulator
- Scan the QR code with Expo Go app on your physical device

## 📱 Development

The main application logic is in `App.tsx`. The entry point `index.ts` registers the root component using Expo's `registerRootComponent`.

### Current Features

- Basic Expo setup with TypeScript
- StatusBar configuration
- Styled components with React Native StyleSheet

## 🎨 Customization

To start building your Q&A features:

1. Open `App.tsx`
2. Replace the placeholder text with your custom components
3. Add navigation, state management, and Q&A functionality as needed

## 📦 Dependencies

Key dependencies include:
- `expo` - Expo SDK
- `react` - React library
- `react-native` - React Native framework
- `expo-status-bar` - Status bar component

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 👤 Author

**eliasbr26**
- GitHub: [@eliasbr26](https://github.com/eliasbr26)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🔮 Future Enhancements

- [ ] Add navigation system
- [ ] Implement authentication
- [ ] Create question posting functionality
- [ ] Add answer submission features
- [ ] Implement voting system
- [ ] Add user profiles
- [ ] Include search and filtering
- [ ] Add real-time updates

---

**Note**: This is a starter template. The main Q&A functionality needs to be implemented based on your specific requirements.
