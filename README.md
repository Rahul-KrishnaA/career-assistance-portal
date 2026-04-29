# Career Assistance Portal

A full-stack AI-powered career assistance platform built with Next.js 15. Helps users with resume building, interview preparation, and career guidance powered by Google Gemini AI.

**Author: Rahul Krishna**

---

## Features

- AI-powered career coaching and guidance
- Resume builder with PDF export
- Interview preparation tools
- User authentication via Clerk
- Background job processing with Inngest
- Dark/light theme support

## Tech Stack

- **Framework:** Next.js 15 (App Router)
- **Auth:** Clerk
- **Database:** Prisma ORM
- **AI:** Google Gemini API
- **UI:** Tailwind CSS, Radix UI, shadcn/ui
- **Background Jobs:** Inngest

## Getting Started

1. Clone the repository and install dependencies:

```bash
npm install
```

2. Create a `.env` file in the root with the following variables:

```env
DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=
```

3. Push the database schema:

```bash
npx prisma db push
```

4. Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## License

MIT © Rahul Krishna
