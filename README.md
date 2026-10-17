# yourea-site

One-screen waitlist page for your·ea ("Daily annoyances, handled."), served by GitHub Pages at
https://yourea.akshaychugh.xyz.

- `index.html` is the whole page (inline CSS and JS, Google Fonts). The left list of annoyances is struck through as
  the phone on the right shows the app handling each one (app-style Live call, MyGate and home help screens, in HTML).
- Sign-ups call `public.join_waitlist_v2()` on the your-ea Supabase project with the public anon key and get their
  place in line back. The form asks for name, WhatsApp number, email (the Gmail they'll sign in to the app with,
  which goes into `public.allowed_emails` when they're invited) and Android/iPhone. The `waitlist` table is closed to anon; read it in the Supabase SQL editor.
- Share links with `?ref=<source>` (for example `?ref=linkedin`) to see where sign-ups come from.
