# Project

Next.js App Router + TypeScript strict + Tailwind.

## Commands
- Dev: `npm run dev`
- Build: `npm run build`
- Lint: `npm run lint`
- Test: `npm test`

## Rules
- Prefer Server Components. Only add "use client" when you need interactivity or browser APIs.
- Use named exports.
- No `any` types. Use proper types or `unknown`.
- Keep components small. Extract hooks and utilities when a file gets long.
- Styles go in Tailwind classes. Avoid inline styles.
- Put API routes in `app/api/`.
- Environment variables that are secret must never be prefixed with `NEXT_PUBLIC_`.

## Don't
- Don't edit files in `.next/` or `node_modules/`.
- Don't commit `.env` files.
- Don't add new dependencies without checking if one already exists.
