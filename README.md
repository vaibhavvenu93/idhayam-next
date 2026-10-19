# Idhayam Next — Interactive demo

An interactive **concept prototype** covering the feature families in Annexure A of the Idhayam Matrimony agreement. Uses fictional sample profiles and browser-local state. Not a production application.

## Run locally

```bash
npm install
npm run dev
```

## Deploy to Vercel

1. Upload this directory to a new GitHub repository.
2. Import the repository in Vercel.
3. Framework: Vite. Build command: `npm run build`. Output: `dist`.
4. Deploy, then test on mobile and desktop.

No API keys, backend, or database needed. All interactive demo changes are saved in `localStorage` on the current browser. Admin and member experiences are connected **only in the same browser**. Different devices will not share state.

## Coverage

- Registration/profile wizard, bio, family, education, occupation, photos/video selection, horoscope and preferences
- Discovery, search filters, simulated recommendations/compatibility, saved searches, interest, shortlists
- Private messages, icebreakers, simulated video call, notifications
- Privacy, reporting/blocking, simulated email/phone/document/video verification, simulated 2FA, safety information
- Events/webinars RSVP, sample reminders
- VIP membership, concierge requests, consultation requests
- Government employment matching filters and sample employment status
- Admin member directory, approval/rejection queue, reports, usage analytics, content/article publishing, ad campaign creation, support tickets, help center and simulated live chat

## Demo limitations

Authentication/social sign-in, email/SMS, real verification, secure media uploads, actual video calls, live chat, encryption of customer data, push notifications, actual astrological compatibility, cross-device data persistence, and real business analytics are **not implemented**. All are represented through sample screens or local simulations. This demo must not be used with real personal data.

Photo examples load from Unsplash and may depend on network access. Check image rights before any public production use.
