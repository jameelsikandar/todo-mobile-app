# React Native Todo App

A modern cross-platform Todo application built with React Native and powered by Convex as the backend. The app allows users to efficiently manage their daily tasks with real-time synchronization and a clean, responsive user interface.

## Features

- User authentication
- Create new tasks
- Edit existing tasks
- Delete tasks
- Mark tasks as completed
- Real-time data synchronization
- Responsive and clean mobile UI
- Persistent cloud storage with Convex
- Cross-platform support (Android & iOS)

## Tech Stack

### Frontend

- React Native
- TypeScript
- Expo
- React Navigation

### Backend

- Convex

## Project Structure

```
.
├── app/
├── components/
├── hooks/
├── assets/
├── convex/
├── constants/
├── types/
├── utils/
└── package.json
```

## Getting Started

### Prerequisites

Make sure you have installed:

- Node.js (v18 or later)
- npm or yarn
- Expo CLI
- Expo Go (for testing on a physical device)
- A Convex account

## Installation

Clone the repository.

```bash
git clone https://github.com/jameelsikandar/todo-mobile-app.git
```

Navigate to the project directory.

```bash
cd todo-mobile-app
```

Install dependencies.

```bash
npm install
```

or

```bash
yarn
```

## Environment Variables

Create a `.env` file in the root directory and add your Convex deployment URL.

```env
EXPO_PUBLIC_CONVEX_URL=your_convex_deployment_url
```

## Running the App

Start the development server.

```bash
npx expo start
```

Then choose one of the following options:

- Press **a** to run on Android Emulator
- Press **i** to run on iOS Simulator (macOS only)
- Scan the QR code using Expo Go on your mobile device

## Backend Setup

Create a Convex project.

Install the Convex CLI if needed.

```bash
npm install -g convex
```

Login to Convex.

```bash
npx convex login
```

Initialize Convex.

```bash
npx convex dev
```

Deploy your backend when ready.

```bash
npx convex deploy
```

## Screenshots

Add screenshots of your application here.

```
screenshots/
├── home.png
├── add-task.png
├── completed.png
└── profile.png
```

## Future Improvements

- Task categories
- Due dates
- Task reminders
- Push notifications
- Dark mode
- Search and filtering
- Offline support
- Task priority levels

## Learning Outcomes

This project helped me gain practical experience with:

- React Native development
- TypeScript
- Expo
- Convex backend
- Real-time database synchronization
- Mobile UI development
- State management
- API integration
- Component-based architecture

## Author

**Jameel Sikandar**

Computer Science Student | MERN Stack & React Native Developer

GitHub: https://github.com/jameelsikandar

## License

This project is licensed under the MIT License.

---

If you found this project useful, consider giving it a star.
