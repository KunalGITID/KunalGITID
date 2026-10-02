# Hi, I'm Kunal

CS (Data Science) student at SRM Institute of Science and Technology, Kattankulathur.
I build tools I use every day and try to ship them properly: tests, CI, releases.

### What I'm working on

**[AcadKit](https://github.com/KunalGITID/Acadkit)**: a personal academic companion PWA for SRM KTR.
Attendance margins, marks and grade targets, the Day Order timetable, deadlines, and a synced study folder.
Works offline and syncs across devices.
React · TypeScript · TanStack Query · Supabase (Postgres, RLS, Edge Functions) · Vite PWA · Playwright
→ [acadkit.vercel.app](https://acadkit.vercel.app)

**[ATLER](https://github.com/KunalGITID/ATLER)**: a local-first expense and subscription tracker.
Plans, expenses, imports from bank SMS and statements, push reminders before each charge, and on-device insights.
React 19 · TypeScript · Dexie · Supabase with row-level security
→ [kunalgitid.github.io/ATLER](https://kunalgitid.github.io/ATLER/)

**[atler-ml](https://github.com/KunalGITID/atler-ml)**: does machine learning beat ATLER's hand-written rules?
Benchmarks ATLER's own TypeScript against scikit-learn on synthetic Indian bank statements, then ships what wins
back to the app as small JSON models: category suggestions that work from the first expense (54% → 88% accuracy
after 10 filed expenses), a subscription finder (F1 96), and unusual-spend alerts that learn from your answers.
Python · scikit-learn · pandas

### Open source

- [OCA/server-tools](https://github.com/OCA/server-tools): documentation fixes in `upgrade_analysis`
  ([#3751](https://github.com/OCA/server-tools/pull/3751), [#3752](https://github.com/OCA/server-tools/pull/3752) merged; more in review)

### Next up

- A Postgres-backed job queue in Go (retries, idempotency, metrics, load tests)
- Retrieval over my study files with page citations, and an evaluation set to measure it

### Stack

TypeScript, React, Python (scikit-learn, pandas), Java, SQL/Postgres, Supabase.
