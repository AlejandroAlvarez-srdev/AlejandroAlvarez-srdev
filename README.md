### Hi, I'm Alejandro 👋

I'm the CTO of [Mente Sana](https://mentesanapsicologia.com), an online psychology clinic in Spain (8,000+ patients, 150+ psychologists). I still write most of the code: the acquisition funnel, payments and booking, the CRM our sales and support team use every day, the psychologists' portal and the AI features around them.

I care about shipping things that move a number, and about not breaking what already works while doing it.

**What I've been working on lately**

- Moving purchase tracking server-side after finding the browser pixel had recorded zero purchases for months.
- Reusing the €9.99 first-session funnel to launch speech therapy and nutrition as new products, instead of building a new funnel each time.
- An LLM session summary that a clinician must approve before the patient ever sees it.
- Replacing a legacy WhatsApp monolith piece by piece (strangler fig) while the team kept using it.

### Mente Sana modules

These are extracted from the private production monorepo with their real commit history (secrets and personal data removed). Each README explains the problem, what I built and the trade-offs.

| Repo | What it is | History |
|---|---|---|
| [mentesana-diagnostic-funnel](https://github.com/AlejandroAlvarez-srdev/mentesana-diagnostic-funnel) | Landing → test → psychologist match → slot hold → Stripe checkout → booking | Apr–Nov 2026 · 203 commits |
| [mentesana-growth-engine](https://github.com/AlejandroAlvarez-srdev/mentesana-growth-engine) | A/B tests at the proxy, Pixel + Conversions API with dedup, consent mode, media-buyer dashboard | Apr–Nov 2026 · 120 commits |
| [mentesana-agent-console](https://github.com/AlejandroAlvarez-srdev/mentesana-agent-console) | Sales & support console: customer 360, bookings, attendance, pipelines | May–Nov 2026 · 312 commits |
| [mentesana-ai-video-studio](https://github.com/AlejandroAlvarez-srdev/mentesana-ai-video-studio) | Landing page → scripted, rendered and assembled vertical video ads | Apr–Nov 2026 · 268 commits |
| [mentesana-lifecycle-emails](https://github.com/AlejandroAlvarez-srdev/mentesana-lifecycle-emails) | Recovery and lifecycle messaging with throttling, dedupe and opt-out | Apr–Nov 2026 · 121 commits |
| [mentesana-clinical-reports](https://github.com/AlejandroAlvarez-srdev/mentesana-clinical-reports) | Psychologists' portal, LLM summaries with clinician approval, PDFs | May–Nov 2026 · 113 commits |
| [mentesana-whatsapp-inbox](https://github.com/AlejandroAlvarez-srdev/mentesana-whatsapp-inbox) | Multi-agent WhatsApp inbox built around a legacy monolith | May–Nov 2026 · 108 commits |
| [mentesana-meet-extension](https://github.com/AlejandroAlvarez-srdev/mentesana-meet-extension) | Chrome extension: Meet captions → draft clinical notes, de-identified in the browser ([Web Store](https://chromewebstore.google.com/detail/idiokgdfhladphbdfpkiedfboghkicfh)) | May–Nov 2026 |

Not public: the Mente Sana mobile app (Expo / React Native) and the B2B platform for companies.

### Side projects

Places where I go deeper on systems topics than my day job needs. Built with AI pair-programming, tested and run in CI.

- **Rust:** [vectrs](https://github.com/AlejandroAlvarez-srdev/vectrs) (HNSW vector search) · [ledgerlog](https://github.com/AlejandroAlvarez-srdev/ledgerlog) (segmented commit log) · [flowd](https://github.com/AlejandroAlvarez-srdev/flowd) (durable workflows) · [emergence](https://github.com/AlejandroAlvarez-srdev/emergence) (particle life in WebAssembly, [live demo](https://alejandroalvarez-srdev.github.io/emergence/))
- **Pulso**, a made-up delivery marketplace: [orders API](https://github.com/AlejandroAlvarez-srdev/pulso-orders-api) · [matching](https://github.com/AlejandroAlvarez-srdev/pulso-matching) · [saga](https://github.com/AlejandroAlvarez-srdev/pulso-saga) · [support agents](https://github.com/AlejandroAlvarez-srdev/pulso-support-agents) · [platform](https://github.com/AlejandroAlvarez-srdev/pulso-platform) · [experiments](https://github.com/AlejandroAlvarez-srdev/pulso-experiments)

### Client work

[adstack](https://github.com/AlejandroAlvarez-srdev/adstack) (my agency platform) · [kairos-platform](https://github.com/AlejandroAlvarez-srdev/kairos-platform) (membership SaaS) · [escala-cx](https://github.com/AlejandroAlvarez-srdev/escala-cx) · [novara](https://github.com/AlejandroAlvarez-srdev/novara) · [RTC-MicroSeviceLLM](https://github.com/AlejandroAlvarez-srdev/RTC-MicroSeviceLLM) (a technical test)

---

TypeScript, Next.js, React Native, Postgres/Supabase, MySQL, Stripe, Vercel, Meta and WhatsApp APIs, Python, and lately Rust.
