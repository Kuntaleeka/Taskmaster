# TaskMaster

A gamified life planner and productivity tracker.

## Features

- **Character Progression:** Gain XP and level up attributes (Strength, Intelligence, Wealth, Vitality, Charisma).
- **Quest Log (Calendar):** Manage Side, Main, and Epic quests with notifications.
- **Daily Vault (Notes):** Bullet-style journaling with mood tracking.
- **Habit Tracking:** Maintain streaks and build routines.
- **AI Taskmaster:** Get AI-generated smart missions, preparation tips, and relief recommendations (Powered by Gemini).
- **The Map:** Visualize your journey and current status.
- **Archives:** Tabular views for past notes and calendar events.

## Tech Stack

Next.js 15, Tailwind CSS, Drizzle ORM, PostgreSQL (Neon), Google Gemini API.

## Setup

```bash
# 1. Install
npm install

# 2. Environment (.env)
# DATABASE_URL="..."
# gemini_key="..."

# 3. Database
npx drizzle-kit push

# 4. Run
npm run dev
```

## Customization

Adjust XP values and gamification metrics in `src/lib/constants.ts`.