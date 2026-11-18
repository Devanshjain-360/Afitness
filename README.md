# 🏋️ FitBuddy AI - Personalized Workout & Diet Assistant 🥗

FitBuddy AI is an AI-powered fitness and nutrition assistant that generates personalized workout and diet plans, provides real-time AI voice coaching, and tracks fitness metrics.

## ✨ Features

- 🎙️ **AI Voice Coach:** Real-time voice interaction with your personal AI assistant.
- ⚙️ **Manual Preferences:** Submit physical stats, restrictions, and fitness goals.
- 📊 **Metric Dashboard:**
  - Workout streak tracking
  - Calorie tracking
  - BMI calculator
  - Water intake tracker
- 📄 **Download Plan as PDF:** Export personalized fitness plans.
- 🔒 **Guest & Profile Modes:** Save and view plans using Clerk authentication or guest profiles.

## 🛠️ Tech Stack

- **Frontend:** Next.js 15, React 19
- **Styling:** Tailwind CSS and Lucide Icons
- **Database:** Convex
- **AI:** Google Gemini API
- **Voice Assistant:** Vapi
- **Authentication:** Clerk

## ⚙️ Environment Variables

Create a `.env.local` file in the root directory and add your own API keys:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_key
CLERK_SECRET_KEY=your_key
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_VAPI_ASSISTANT_ID=your_assistant_id

CONVEX_DEPLOYMENT=your_deployment
NEXT_PUBLIC_CONVEX_URL=your_convex_url

GEMINI_API_KEY=your_api_key
```

Never upload your actual API keys or `.env.local` file to GitHub.

## 🚀 Getting Started

### 1. Install dependencies

```bash
npm install
```

### 2. Set up Convex

```bash
npx convex dev --once
```

### 3. Start the development server

```bash
npm run dev
```

Open http://localhost:3000 in your browser.

## 📦 Production Build

```bash
npm run build
```

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
