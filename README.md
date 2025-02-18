
<img width="700" alt="S" src="https://github.com/user-attachments/assets/7d06d5a6-dc8e-4537-9558-07009470496a" />
# TransitX Ride
<img width="500" alt="Screenshot 2025-02-17 at 4 36 48 PM" src="https://github.com/user-attachments/assets/a1573fc1-5834-41d7-9bdc-156a7c9e13cd" />



## Full Stack Ride-Sharing Platform

Build this project step by step with our detailed tutorial on JavaScript Mastery YouTube. Join the JSM family!

## 📋 Table of Contents
- 🤖 Introduction
- ⚙️ Tech Stack
- 🔋 Features
- 🤸 Quick Start
- 🕸️ Snippets (Code to Copy)
- 🔗 Assets

## 🤖 Introduction
TransitX Ride is a ride-sharing platform built with React Native for handling the user interface, Google Maps for rendering maps with directions, Stripe for handling payments, serverless PostgreSQL for managing databases, and styled with TailwindCSS. The primary goal is to demonstrate how to develop full-stack mobile applications to showcase the developer's skills in a unique manner that creates a lasting impact.

## ⚙️ Tech Stack
- React Native
- Expo
- Stripe
- PostgreSQL
- Google Maps
- Zustand
- Clerk
- Tailwind CSS

## 🔋 Features
- **Onboarding Flow**: Seamless user registration and setup process.
- **Email Password Authentication with Verification**: Secure login with email verification.
- **oAuth Using Google**: Easy login using Google credentials.
- **Authorization**: Secure access control for different user roles.
- **Home Screen with Live Location & Google Map**: Real-time location tracking with markers on a map.
- **Recent Rides**: View a list of recent rides at a glance.
- **Google Places Autocomplete**: Search any place on Earth with autocomplete suggestions.
- **Find Rides**: Search for rides by entering 'From' and 'To' locations.
- **Select Rides from Map**: Choose available cars near your location from the map.
- **Confirm Ride with Detailed Information**: View complete ride details, including time and fare price.
- **Pay for Ride Using Stripe**: Make payments using multiple methods like cards and others.
- **Create Rides After Successful Payment**: Book a ride after confirming payment.
- **Profile**: Manage account details in the profile screen.
- **History**: Review all rides booked so far.
- **Responsive on Android and iOS**: Optimized for both Android and iOS devices.

## 🤸 Quick Start
Follow these steps to set up the project locally on your machine.

### Prerequisites
Make sure you have the following installed on your machine:
- Git
- Node.js
- npm (Node Package Manager)

### Cloning the Repository
```sh
git clone https://github.com/Dhrumit26/TransitX-Ride.git
cd TransitX-Ride
```

### Installation
Install the project dependencies using npm:
```sh
npm install
```

### Set Up Environment Variables
Create a new file named `.env` in the root of your project and add the following content:
```sh
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=
EXPO_PUBLIC_PLACES_API_KEY=
EXPO_PUBLIC_DIRECTIONS_API_KEY=
DATABASE_URL=
EXPO_PUBLIC_SERVER_URL=
EXPO_PUBLIC_GEOAPIFY_API_KEY=
EXPO_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
```
Replace the placeholder values with your actual Clerk, Stripe, PostgreSQL, Google Maps, and Geoapify credentials. You can obtain these credentials by signing up on the respective websites.

### Running the Project
```sh
npx expo start
```
Download the Expo Go app and scan the QR code on your respective device to view the project.

## 🕸️ Snippets
Here are some code snippets from the project to help you get started quickly.

### Setup
- `.vscode/settings.json`
- `tailwind.config.js`
- `types/type.d.ts`
- `types/image.d.ts`
- `constants/index.ts`

### Root Layout Fonts

### Components
- `components/CustomButton`
- `components/InputField`
- `components/DriverCard.tsx`

### Utilities
- `lib/fetch.ts`
- `lib/map.ts`
- `lib/utils.ts`

### Queries
- `GET Rides SQL Query`
- `SEED Drivers Query`

### Schema
- `CREATE Drivers Table SQL Query`
- `CREATE Rides Table SQL Query`
- `CREATE Users Table SQL`

### Mock Data
- `Mock Drivers`
- `Mock Rides`

### API Endpoints
- `(api)/ride/create+api.ts`
- `(api)/ride/[id]+api.ts`

### Screens
- `(root)/book-ride`
- `(root)/(tabs)/profile`
- `(root)/(tabs)/chat`

## 🔗 Assets
Assets used in the project can be found [here](#).

