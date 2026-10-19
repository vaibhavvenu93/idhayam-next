# Idhayam Next — Final Founder Demo

This is a **browser-local interactive product concept**, not a deployed matrimonial service. All profiles, verification states, compatibility scores, business metrics, bookings and conversations are fictional or simulated.

## Run on Windows PowerShell
1. Extract the ZIP.
2. Open the folder that contains `package.json`.
3. In that folder run:
   ```powershell
   npm install
   npm run dev
   ```
4. Open the local URL printed by Vite (normally http://localhost:5173).

**If ENOENT appears:** PowerShell is in the wrong folder. Run `dir package.json` and navigate to the directory containing it.

## Founder walkthrough (10–12 minutes)
1. **Home:** Show premium positioning and the customer experience.
2. **My profile:** Demonstrate profile creation, family and preference fields, then profile preview.
3. **Discover:** Filter by city/age/language, open a profile, shortlist and express interest.
4. **Connections:** Show interest states; use *Simulate acceptance* for a new interest.
5. **Messages:** Open accepted connections, select a conversation, send an icebreaker and demonstrate the video-call preview.
6. **Privé:** Activate the illustrative premium experience and request a concierge introduction.
7. **Government:** Show the specialist public-service profile and preferences.
8. **Events, trust and support:** RSVP, change privacy, and create a support ticket.
9. **Founder command centre:** Show the corresponding activity, moderation queue, ticket resolution, member directory and analytics.
10. **Reset demo:** Restore the starting state for the next walkthrough.

## Final pass changes
- More compact page layout, reduced excess spacing and improved mobile presentation.
- Conversation selection and message history tied to the correct accepted profile.
- Saved search retrieval and one-click application.
- More meaningful demo activity, VIP request and consultation tracking.
- Expanded CSV export with live browser-local activity counts.
- Clearer demo-only media upload and privacy messaging.
- More consistent reset behaviour, interest deduplication and moderation actions.
- Founder walkthrough remains inside the app without a separate presentation/decision room.

## Important limits
- No live accounts, authentication, backend, payments, email/SMS, video calling or identity verification.
- Selecting media does not upload or permanently save it.
- Simulated analytics and sample base counts are **not real Idhayam operating figures**.
- Browser localStorage persists state only within the same browser and origin.
- Sample profile photographs are externally hosted; internet access is needed to load them.

## QA checklist
- [ ] `npm install` and `npm run dev` work in the folder containing package.json
- [ ] Navigation and mobile layout render
- [ ] Onboarding step progression and profile preview
- [ ] Discovery filtering, save and restore search
- [ ] Shortlist, interest, acceptance, per-profile conversations
- [ ] VIP consultation and concierge requests
- [ ] Government filter and events RSVP
- [ ] Privacy controls and support ticket
- [ ] Admin approvals, member directory, analytics, ticket resolution, CSV export
- [ ] Reset returns to seed data

JavaScript syntax was checked. Full browser end-to-end tests have **not** been run in this environment; complete the checklist before the founder meeting.
