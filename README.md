# yourea-site

One-screen waitlist page for your·ea, served by GitHub Pages at https://yourea.akshaychugh.xyz.

- `index.html` is the whole page (inline CSS and JS, Google Fonts).
- `app.mp4` / `app.jpg`: a recording of the app's real onboarding pitch screen (web build, demo data), cut to the
  home help, family, scam and gate examples.
- Sign-ups call `public.join_waitlist_v2()` on the your-ea Supabase project with the public anon key and get their
  place in line back. The `waitlist` table is closed to anon; read it in the Supabase SQL editor.
- Share links with `?ref=<source>` (for example `?ref=linkedin`) to see where sign-ups come from.
