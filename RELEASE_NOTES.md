# Idhayam Next — client preview V3

This is a fictional, browser-local interactive product simulation. It is not a production matrimonial service.

## Changes
- Reworked landing hero with editorial photograph and a more human visual direction.
- Added sample journey seeding and connected member-to-admin activity.
- Improved profile step validation and profile preview.
- Added richer discovery card actions and a simulated interest acceptance pathway.
- Rebuilt the messaging screen with a thread list, conversational bubbles, icebreakers and a sample video call.
- Added sample curated profiles to VIP and concierge booking flow.
- Captured specialist government preferences; sample dataset only supports the government-professional category.
- Added event detail previews and simulated RSVP state.
- Added an operational snapshot and clearer admin navigation.
- Improved responsive layout and keyboard focus visibility.

## Known limitations
- No server, authentication, actual document verification, live chat, payments, real video, persistent shared database, or actual notification delivery.
- State is stored in the visitor's browser localStorage; a different browser/device does not see their changes.
- Unsplash photographs are externally hosted and require an internet connection. They illustrate fictional personas, not actual members.
- Dashboard sample totals are illustrative, not measured metrics.
- Government preferences are captured but not all are reflected in matching because the sample data lacks department and posting metadata.
- No full browser/device or production build verification was possible in this environment (dependency installation timed out). Run npm install, npm run build, npm run preview and perform manual QA before sharing with a client.

## Quick start
Extract ZIP; `cd idhayam-next`; `npm install`; `npm run dev`.

## Vercel
Import repository, choose Vite, build `npm run build`, output `dist`. Run production preview locally first.
