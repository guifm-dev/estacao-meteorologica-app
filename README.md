# Projeto EMEDE - Weather Station App

## Key Highlights

- React Native mobile application built with Expo.
- Firebase-powered real-time data synchronization using Cloud Firestore.
- Automated Excel reporting for environmental records.

## 1. The Challenge

Environmental data collection was previously handled manually, making the process slower, harder to standardize, and more exposed to transcription errors. The project needed a practical way to register, organize, monitor, and export weather station measurements from a mobile device.

## 2. The Solution

Projeto EMEDE is a mobile app for managing meteorological station records in a structured digital workflow. The app synchronizes collected data in real time with Firebase, allowing users to create weather records, manage observations, view tables and charts, and generate professional Excel reports with one click.

Main features include:

- User login and session persistence.
- Creation and management of weather monitoring periods.
- Real-time updates for observations, students, and announcements.
- Meteorological data tables with fields such as temperature, humidity, pressure, precipitation, wind speed, and direction.
- Excel export for 7, 15, or 31 days of collected data.
- Mobile-first navigation using Expo Router tabs and screens.

## 3. Technologies

- React Native
- Expo
- Expo Router
- Firebase / Cloud Firestore
- Expo Secure Store
- Expo File System
- XLSX
- React Native Gifted Charts
- TypeScript / JavaScript

## 4. How to Run

### Prerequisites

- Node.js installed.
- npm or Yarn installed.
- Expo CLI available through `npx expo`.
- A Firebase project configured with Cloud Firestore.

### Installation

Clone the repository and install the dependencies:

```bash
npm install
```

or:

```bash
yarn install
```

### Environment Variables

Create a `.env` file in the project root and add the Firebase public configuration values used by the app:

```env
EXPO_PUBLIC_FIREBASE_GOOGLE_API_KEY=your_firebase_api_key
EXPO_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
EXPO_PUBLIC_FIREBASE_APP_ID=your_firebase_app_id
EXPO_PUBLIC_FIREBASE_MEASUREMENT_ID=your_firebase_measurement_id
```

### Start the App

Run the Expo development server:

```bash
npm start
```

or:

```bash
yarn start
```

Then open the app with Expo Go or run it on a platform-specific target:

```bash
npm run android
```

```bash
npm run ios
```

```bash
npm run web
```
