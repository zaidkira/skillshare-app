# SkillShare Platform

A skill-sharing platform built with React, TypeScript, and Firebase. Connect with people who share your skills and interests.

## Features

- **User Profiles**: Create detailed profiles with skills, education, and interests
- **Skill Management**: Add, edit, and categorize your skills
- **Advanced Search**: Find people by skills, availability, university, and more
- **Firebase Authentication**: Secure Google OAuth login
- **Real-time Database**: Firestore integration for live updates
- **Responsive Design**: Works on all devices

## Tech Stack

- **Frontend**: React 19.1.1, TypeScript, Vite
- **Backend**: Firebase (Authentication, Firestore)
- **Styling**: CSS with modern design system
- **Routing**: React Router DOM

## Getting Started

### Prerequisites
- Node.js
- Firebase project setup

### Installation

1. Clone the repository:
```bash
git clone https://github.com/zaidkira/skillshare-app.git
cd skillshare-app
```

2. Install dependencies:
```bash
npm install
```

3. Set up Firebase:
   - Create a Firebase project
   - Enable Authentication and Firestore
   - Update `firebase.ts` with your config

4. Run the development server:
```bash
npm run dev
```

## Project Structure

```
skillshare-app/
├── src/
│   ├── components/
│   │   ├── AuthContext.tsx
│   │   ├── Login.tsx
│   │   ├── ProfileManager.tsx
│   │   ├── ProfileView.tsx
│   │   ├── ProtectedRoute.tsx
│   │   └── SkillBrowser.tsx
│   ├── database.ts
│   ├── firebase.ts
│   ├── types.ts
│   ├── index.tsx
│   └── index.css
├── package.json
├── tsconfig.json
└── vite.config.ts
```

## Features in Detail

### User Profiles
- Complete profile creation with bio, education, skills
- Profile editing and updates
- Photo upload support
- Availability status

### Skill Management
- Pre-defined skill categories
- Custom skill addition
- Skill level indicators
- Interest tracking

### Search & Discovery
- Advanced filtering by skills, categories, availability
- Text search across profiles
- University and year filtering
- Real-time results

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is open source and available under the MIT License.