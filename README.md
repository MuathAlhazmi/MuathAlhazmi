## Muath Alhazmi

Mobile and web developer. I build **Flutter** apps and **Next.js** platforms —
mostly Arabic-first, RTL, and shipped to real users.

I have been writing code and putting it on GitHub since **December 2018**.

---

### Featured work

| Project | What it is | Stack |
|---|---|---|
| **[Mula](https://github.com/MuathAlhazmi/pulsespend)** | Offline-first personal finance app. Bank CSV import, category budgets, and AI assistance behind a Cloudflare Worker so the API key never ships in the binary. **~22,000 lines.** | Flutter · Riverpod · Isar · Cloudflare Workers |
| **[New Knowledge](https://github.com/MuathAlhazmi/newknowledge)** | Arabic learning platform — timed pre/post exams, assignments, grading, attendance, coursework chat. 24 database models, three roles. **~16,500 lines.** [Live ↗](https://newknowledge-beige.vercel.app) | Next.js 16 · React 19 · Prisma · Supabase |
| **[Workflow](https://github.com/MuathAlhazmi/Workflow)** | Team collaboration app built around shared task lists — group chat with voice notes and waveforms, in-chat polls, push notifications. **Started July 2022.** | Flutter · Firebase · flutter_sound |
| **[CoffeeLeaf](https://github.com/MuathAlhazmi/CoffeeLeaf)** | Café ordering app — menu, cart, table booking, order tracking, biometric confirmation at checkout. **Commit history from July 2021.** | Flutter · Firebase · local_auth |
| **[Lin Babak](https://github.com/MuathAlhazmi/lin-babak-case-study)** | On-demand laundry marketplace, shipped to beta. Commercial work — case study with screenshots and architecture, source private. | Flutter · Firebase · Google Maps |

---

### The long version

Most of what I know came from building things badly and then building them
again. The repositories below are kept deliberately, dates and all.

| Year | | |
|---|---|---|
| **2018** | [HTML Tutorial](https://github.com/MuathAlhazmi/HTML-tutorial-2) | Ten lines of heading tags. My first commit. |
| **2019** | [Login System](https://github.com/MuathAlhazmi/Login-System-using-python) · [Number Game](https://github.com/MuathAlhazmi/Number-game-using-python) | First Python. The login README warned that it stored passwords in plaintext — I could name the flaw before I could fix it. |
| **2021** | [Weather Website](https://github.com/MuathAlhazmi/Weather-Website) | Vanilla JS — geolocation, `fetch`, no framework. |
| **2021** | [CoffeeLeaf](https://github.com/MuathAlhazmi/CoffeeLeaf) | First real Flutter app. 8,000 lines, 40 packages, still maintained. |
| **2022** | [Workflow](https://github.com/MuathAlhazmi/Workflow) | Realtime chat with voice messages and polls, on Firebase. |
| **2026** | [Mula](https://github.com/MuathAlhazmi/pulsespend) · [New Knowledge](https://github.com/MuathAlhazmi/newknowledge) · Lin Babak | Production apps, a deployed platform, and commercial client work. |

Everything up to and including **Workflow (July 2022)** was written before
ChatGPT existed. I mention it because the dates are checkable, and because the
habits formed then — reading documentation, and writing down what I knew was
still wrong — are the ones I still rely on.

---

### How I work

- **Arabic-first, not translated.** RTL layouts built directionally from the
  start, with typefaces designed for Arabic rather than Latin fonts carrying
  Arabic glyphs.
- **Secrets do not belong in a binary.** Anything shipped to a device is
  readable, so keys live behind a proxy I control.
- **Write down what is still wrong.** My READMEs carry a *Known weaknesses*
  section. Client-trusted order totals, missing tests, unhashed passwords in
  2019 — a limitation you have named is a limitation someone can fix.

---

### Tech

**Mobile** Flutter · Dart · Riverpod · go_router · Isar
**Web** TypeScript · Next.js · React · Prisma · Tailwind
**Backend** Firebase (Auth, Firestore, Storage, Messaging, Functions) · Supabase · PostgreSQL · Cloudflare Workers
**Other** Arabic/English localisation · Google Maps · CI on Vercel

---

📫 [muath.anas106@gmail.com](mailto:muath.anas106@gmail.com)
