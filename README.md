# Youssef & Safaa Invitation

A faithful static recreation of the supplied `rana-mohamed-invetation.vercel.app` invitation flow, with the event details updated for Youssef and Safaa.

## Run locally

```bash
pnpm install
pnpm dev
```

Then open the Vite URL shown in the terminal. To create a production build:

```bash
pnpm check
pnpm build
```

## Edit event information

All event-specific values are centralized at the top of [`client/src/pages/Home.tsx`](./client/src/pages/Home.tsx), in the exported `EVENT` object. Update `bride`, `groom`, `displayNames`, `dateIso`, the formatted date fields, `time`, `venue`, `location`, and `mapUrl` there.

The page preserves the reference’s two-stage experience: a full-screen envelope cover, a click-to-open reveal with music, the floral hero, event details, venue map link, animated countdown, and closing invitation message. It is responsive across mobile, tablet, and desktop sizes and respects `prefers-reduced-motion`.

## Current event

- **Names:** Youssef & Safaa
- **Date:** 22 September 2026
- **Time:** 8:00 PM
- **Venue:** Villa El Wazir
- **Location:** El Warraq, Giza, Egypt
