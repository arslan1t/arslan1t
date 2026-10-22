## Hi, I'm Arslan 👋

Full-stack developer from Uzbekistan. I build web products end to end — database
schema, API, admin panel and the interface people actually use — and I like
understanding the layer underneath: how a rate limiter decides, how a storage
engine survives a crash, how a path planner proves its route is optimal.

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,python,nextjs,react,tailwind,nestjs,nodejs,postgres,prisma,firebase,supabase,docker,cloudflare,vercel,githubactions&perline=8" alt="Tech stack" />
</p>

| Area | Tools I use |
| --- | --- |
| **Languages** | TypeScript, JavaScript, Python, SQL |
| **Frontend** | Next.js (App Router), React 19, Tailwind CSS, Zustand, React Query, Framer Motion, next-intl |
| **Backend** | NestJS, Fastify, Node.js, Next.js server actions, Auth.js |
| **Data** | PostgreSQL, Prisma, Firebase (Firestore, Auth), Supabase |
| **Infrastructure** | Docker, Cloudflare R2, Vercel, GitHub Actions |
| **Integrations** | Telegram login & bots, Google OAuth, Yandex Maps, YooKassa, Resend |

### Products in production

| Project | About |
| --- | --- |
| **[UBC — Uzbek Basketball Culture](https://github.com/arslan1t/ubc)**<br>[ubculture.uz](https://ubculture.uz) | Basketball platform for Uzbekistan: court map with reviews, open runs, 1v1 tournaments with a live bracket, player profiles, news and media. Next.js 15 + NestJS/Fastify monorepo, PostgreSQL + Prisma, Cloudflare R2, Telegram and Google sign-in, moderation panel. |
| **[UHA SHOP](https://github.com/arslan1t/uhashop)**<br>[uhashop.uz](https://uhashop.uz) | Website and back office for the UHA basketball brand: sneaker marketplace with player sets and promo codes, 3×3 league, youth academy with athlete, parent and coach portals. Next.js 15, Firebase, Cloudflare R2, Telegram bot login, three languages. |
| **[Kapibara](https://github.com/arslan1t/kapibara)** | Online store of personalised children's books: the customer picks a story, adds the child's name and photo and places an order. Customer account, admin panel, background job worker, YooKassa payments, pluggable storage and mail providers. |

### Libraries and engineering

| Project | About |
| --- | --- |
| **[ratekeeper](https://github.com/arslan1t/ratekeeper)** | Rate limiting for Node.js — token bucket, GCRA, fixed and sliding windows behind one interface, HTTP middleware, property-tested `retryAfterMs`. TypeScript. |
| **[logkv](https://github.com/arslan1t/logkv)** | Crash-safe log-structured key-value store (Bitcask design): checksummed records, torn-write recovery, compaction that survives a crash at any step. Pure Python. |
| **[uzbek-translit](https://github.com/arslan1t/uzbek-translit)** | Uzbek Latin ⇄ Cyrillic transliteration following the official spelling rules, with script detection and a CLI. TypeScript, zero dependencies. |
| **[robot-pathfinding-lab](https://github.com/arslan1t/robot-pathfinding-lab)** | A* and Dijkstra on occupancy grids, validated against an independent BFS oracle on seeded random maps. Python. |
| **[telemetry-quality-gate](https://github.com/arslan1t/telemetry-quality-gate)** | Quality checks for sensor CSV data — gaps, duplicates, ordering, invalid readings — with structured JSON reports. Python. |
