# CareerRadar AI

CareerRadar AI is an AI-powered opportunity copilot for students. It helps them discover internships, jobs, hackathons, scholarships, and learning paths from one focused dashboard, then turns a profile or resume into ranked recommendations and outreach steps.

## Hackathon checkpoint package

- `index.html` - public landing page for first-time users.
- `radar.html` - clickable MVP app shell for screenshots and demo.
- `docs/product-brief.md` - product journey, problem, users, MVP scope, metrics.
- `docs/investor-pitch-one-pager.md` - one-page pitch for the checkpoint.
- `docs/user-flow.md` - user flow diagram and workflow notes.
- `docs/daily-progress-form-response.md` - copy-ready response for today's daily progress form.
- `docs/build-in-public-posts.md` - LinkedIn/X post drafts with `#OpenAIHackathon`.

## How to preview

Open `index.html` in a browser for the landing page, or `radar.html` for the app. It is a static prototype, so no install step is required.

## Clerk authentication setup

This prototype includes Clerk-powered sign-in, sign-up, and signed-in user controls for a static HTML app.

1. Open `clerk-config.js`.
2. Replace `pk_test_replace_me` with your Clerk publishable key.
3. Start the local server:

```bash
python -m http.server 4173 --bind 127.0.0.1
```

4. Open `http://127.0.0.1:4173/index.html`.
5. Use the Sign in or Sign up buttons in the app header.

Do not add `CLERK_SECRET_KEY` to any client-side file.
