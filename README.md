# InnerPeace AI 🧘

A comprehensive mental health companion app with AI-powered support, mood tracking, journaling, and therapist finder.

## Features

### 1. 🤖 AI Chatbot (CBT/DBT Support)
- 24/7 empathetic AI companion trained in therapeutic techniques
- Cognitive Behavioral Therapy (CBT) exercises
- Dialectical Behavior Therapy (DBT) skills
- Crisis detection with helpline information

### 2. 📊 Mood Tracker
- Daily mood logging with 5-point scale
- Emotion tagging
- 7-day trend visualization
- Pattern analysis and insights

### 3. 📝 Smart Journal
- AI-powered sentiment analysis
- Daily writing prompts
- Emotion tracking per entry
- Personal insights and patterns

### 4. 🗺️ Therapist Finder
- Geo-location based search
- Find licensed therapists nearby
- One-tap call and directions
- Distance and availability info

## Tech Stack

- **Frontend**: React + TypeScript + Vite
- **Styling**: CSS with Framer Motion animations
- **AI**: Google Gemini API
- **Database**: Firebase Firestore
- **Maps**: Google Maps API
- **Charts**: Recharts

## Getting Started

### Prerequisites
- Node.js 18+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/InnerPeaceAi.git

# Navigate to project
cd InnerPeaceAi/InnerPeaceAi

# Install dependencies
npm install

# Start development server
npm run dev
```

### Environment Variables

Create a `.env` file in the `InnerPeaceAi` directory:

```env
# Gemini AI (https://aistudio.google.com/app/apikey)
VITE_GEMINI_API_KEY=your_gemini_api_key

# Google Maps (https://console.cloud.google.com/google/maps-apis)
VITE_GOOGLE_MAPS_API_KEY=your_google_maps_key

# Firebase (https://console.firebase.google.com/)
VITE_FIREBASE_API_KEY=your_firebase_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

> **Note**: The app works in demo mode without API keys, using intelligent mock responses.

## Project Structure

```
InnerPeaceAi/
├── src/
│   ├── components/      # UI components
│   │   ├── Chatbot.tsx
│   │   ├── MoodTracker.tsx
│   │   ├── Journal.tsx
│   │   ├── TherapistFinder.tsx
│   │   └── Navigation.tsx
│   ├── pages/           # Page components
│   │   └── Home.tsx
│   ├── services/        # API services
│   │   ├── geminiService.ts
│   │   ├── firestoreService.ts
│   │   └── geoService.ts
│   ├── context/         # React context
│   │   └── UserContext.tsx
│   ├── config/          # Configuration
│   │   └── firebase.ts
│   └── types/           # TypeScript types
│       └── index.ts
├── public/
└── package.json
```

## User Journey

1. **Self-Care** → Chat with AI, track mood, journal thoughts
2. **Pattern Recognition** → AI analyzes emotions and identifies trends
3. **Professional Support** → Find and connect with nearby therapists

## Crisis Support

If you're in crisis, please contact:
- **988 Suicide & Crisis Lifeline**: Call or text **988**
- **Crisis Text Line**: Text **HOME** to **741741**

## License

MIT License

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
