# infoscale demos

Static client demos. Each demo lives in its own folder with an `index.html`.

- `/thehour/` — The Hour London Instagram profile demo

## Deploy (Vercel + GitHub)
1. Push this folder to a GitHub repo (e.g. `infoscale-demos`).
2. vercel.com → Add New → Project → import the repo. Framework preset: **Other**. No build command, output dir: `.`
3. Project → Settings → Domains → add `demo.infoscale.io` (or `infoscale.io` with a `/thehour` path).
4. DNS: CNAME `demo` → `cname.vercel-dns.com`.
