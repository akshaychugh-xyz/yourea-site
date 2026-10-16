# yourea-site

One-page waitlist site for your·ea, served by GitHub Pages at https://yourea.akshaychugh.xyz.

- `index.html` is the whole site (inline CSS and JS, Google Fonts).
- Sign-ups call `public.join_waitlist()` on the your-ea Supabase project with the public anon key. The `waitlist` table is closed to anon; read it in the Supabase SQL editor.
- Share links with `?ref=<source>` (for example `?ref=linkedin`) to see where sign-ups come from.
