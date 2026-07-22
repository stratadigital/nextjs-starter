# nextjs-starter

A starter template for building informational websites.

**Stack:** Next.js 16 (App Router) · TypeScript · Tailwind CSS v4 · Catalyst UI · Resend

## Getting started

```bash
npm install
cp .env.example .env.local   # then fill in the values
npm run dev                  # http://localhost:3000
```

## Environment variables

Copy `.env.example` to `.env.local` and fill in the values. See `AGENTS.md` for what each one is for.

## Notes

- UI components live in `src/components/ui/` (Catalyst UI Kit).
- Contact form email is handled by [Resend](https://resend.com).
- See `AGENTS.md` for stack details, conventions, and folder structure.
