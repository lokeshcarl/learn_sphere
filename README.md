# LearnSphere

A responsive, client-side learning dashboard built with React 18, Vite, Tailwind CSS, and Lucide React. Course content is local mock data; there is no backend or external API. Learning state is saved in the browser's local storage.

## Run locally

```sh
npm install
npm run dev
```

Open the local URL printed by Vite (usually `http://localhost:5173/`).

## Build and lint

```sh
npm run build
npm run lint
npm run preview
```

## What you can do

- Browse, search, filter, sort, enroll in, and bookmark mock courses.
- Continue course lessons, navigate the syllabus, take quick quizzes, and track lesson completion.
- Earn XP and achievement badges, monitor goals and weekly activity, and view the sample learning leaderboard.
- Save lesson notes and bookmarks, and edit profile, theme, and notification preferences.
- Use the responsive sidebar and course player on desktop, tablet, and mobile.

Progress, notes, bookmarks, quiz best scores, XP, goals, achievements, and preferences are stored under `learnsphere-*` keys in local storage. Use the browser's site-data controls to reset the demo.
