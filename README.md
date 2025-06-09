# Video-Analyzer (Using Gemini AI)

This is a Video Analyzer project for YouTube videos using Gemini API (gemini-2.0-flash-lite)

## Features

- Analyzes YouTube Videos by using Video URL, and provide summary for each video using Gemini
  - For API docunmentation, Refer to: https://ai.google.dev/gemini-api/docs
  - For API Keys, Refer to: https://aistudio.google.com/apikey

## TODOs

- Video transcripts
- Chat with AI about the Video 

## Tech Stack

- [Next.js](https://nextjs.org) - React framework
- [Shadcn UI](https://ui.shadcn.com/) - Component library
- [Tailwind CSS](https://tailwindcss.com) - Styling
- [TypeScript](https://www.typescriptlang.org/) - Type safety

## Getting Started

1. Clone the repository
2. Install dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Set up your environment variables in the `.env` file.

4. Start the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.

## Project Structure

- `app/page.tsx` - Main page with Todo list implementation
- `app/example/page.tsx` - Data fetching example with loading states
- `app/actions/*` - Server Actions for data mutations
- `components/ui/*` - Shadcn UI components
- `components/ui/*` - Shadcn UI components

## Learn More

To learn more about the technologies used in this project:

- [Next.js Documentation](https://nextjs.org/docs) - Next.js features and API
- [Server Actions](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions) - Learn about Next.js Server Actions
- [Shadcn UI Documentation](https://ui.shadcn.com) - Learn about Shadcn UI components
- [Tailwind CSS Documentation](https://tailwindcss.com/docs) - Learn about Tailwind CSS

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme).

Check out the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
