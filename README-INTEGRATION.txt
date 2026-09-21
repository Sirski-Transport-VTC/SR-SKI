SIRSKI TRANSPORT VTC + FRIDAY SPINNER

1. Upload the contents of the integrated folder to your web host.
2. The main website links directly to spinner/index.html (not the spinner folder).
3. Open spinner/index.html. Demo mode works even before Supabase is configured.
4. For real Friday spins, copy your working Supabase URL and ANON key into spinner/config.js.
5. Do NOT put the Supabase service-role key in config.js.
6. The spinner backend/Edge Functions must be deployed separately in Supabase.

LOCAL TESTING
Use a local web server (VS Code Live Server, Python http.server, etc.). Do not open index.html with file://.

The first 5 demo spins work locally and reset when the page is reloaded. Real spins require the configured backend.
