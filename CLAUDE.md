\# IsThisAScam Development Guidelines



\## Project Overview

Malaysian anti-scam detection platform helping users identify scams through AI analysis.



\*\*Stack:\*\*

\- Frontend: Next.js 14, React, TypeScript, Capacitor

\- Backend: Supabase (atviwmdqxpgmrabnjnfx.supabase.co)

\- AI: OpenAI GPT-4o/4o-mini

\- Deployment: Vercel (isthisascam-alpha.vercel.app)

\- Mobile: Android (internal testing, not yet published)



\*\*Key URLs:\*\*

\- Live app: https://isthisascam-alpha.vercel.app

\- Admin dashboard: https://isthisascam-alpha.vercel.app/slwong

\- GitHub: https://github.com/kickmeafter0810ok-ui/Isthisascam



\## Git Conventions

\- \*\*NEVER commit directly to main\*\* — always use feature branches

\- Use conventional commits: `feat:`, `fix:`, `docs:`, `refactor:`, `chore:`

\- Commit frequently — at least after each completed subtask

\- Keep commit messages clear and descriptive

\- \*\*NEVER commit .env files or secrets\*\*



\## Security Rules

\- All API keys must be in `.env.local` (already gitignored)

\- Keystore is stored outside project in `D:\\Isthisscam-for planning purpose\\Secrets`

\- Admin dashboard password is in `.env.local` as `ADMIN\_PASSWORD`

\- Never log or expose Supabase service keys



\## Testing Requirements

\- Always test admin dashboard (`/slwong`) after making changes

\- Verify Supabase connections before committing

\- Test mobile build compatibility when touching Capacitor code



\## Current Priorities

1\. \*\*Play Store submission prep\*\* — register Google Play Developer account, write store listing

2\. \*\*UX fixes\*\* — mark-as-read card styling in admin dashboard

3\. \*\*RSS intelligence optimization\*\* — improve keyword tuning for scam detection

4\. \*\*ILMU API integration\*\* — pending API access from founders@ilmu.ai



\## Code Style

\- Use TypeScript strict mode

\- Prefer functional components with hooks

\- Keep components small and focused

\- Use Tailwind CSS for styling

\- Follow Next.js 14 app router conventions



\## Important Notes

\- This is a bootstrapped project (self-funded development)

\- 20 scans/month free tier implemented to manage costs

\- Focus on Malaysian context (EN/MS/ZH/TA language support)

\- Community intelligence and education are core features

