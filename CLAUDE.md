# StudyMate AI Project Instructions

## Project Overview

StudyMate AI is an AI-powered study and revision assistant for students.

The application helps students understand and revise study material through AI-generated summaries, explanations, quizzes, flashcards, and revision tracking.

## Tech Stack

- Next.js
- TypeScript
- Tailwind CSS
- OpenAI API
- Next.js Route Handlers
- Supabase PostgreSQL
- Supabase Auth
- Zod
- Vercel

## Development Conventions

- Use TypeScript throughout the application.
- Use clear and descriptive names for variables, functions, components, and files.
- Keep components small and focused.
- Prefer reusable components over duplicated UI code.
- Keep API logic separate from presentation logic.
- Validate user input before processing it.
- Handle loading, error, and empty states in the UI.
- Do not expose API keys or secrets in client-side code.
- Store secrets in environment variables.
- Never commit `.env` files.
- Avoid unnecessary dependencies.
- Follow the existing project structure before introducing new patterns.



## AI Features

- AI-generated content should be clearly identified as AI-generated.
- Do not present generated answers as guaranteed facts.
- Keep prompts specific and structured.
- Validate and handle unexpected AI responses.
- Avoid sending unnecessary user data to external AI services.



## Git Conventions

Use Conventional Commits.

Examples:

- `feat: add quiz generation`
- `fix: handle empty study material`
- `docs: update README`
- `refactor: simplify quiz component`
- `chore: update dependencies`

Keep commits focused on a single logical change.

## Security

- Never hardcode API keys.
- Never commit credentials or private user data.
- Validate user-provided input.
- Keep server-side secrets on the server.

