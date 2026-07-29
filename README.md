### Harshit Pandey

Final-year CS student in Lucknow. I spend most of my week inside a production codebase.

Since June 2026 I've been an engineering intern on **SoundCare**, a live aged-care ERP used by facilities in New Zealand — 50+ modules, originally architected by senior Microsoft engineers. I work tickets end to end: SQL migration → Express route → React component → nav wiring. 20+ shipped so far.

That codebase is private, so it isn't here. What's here is everything I've built on my own.

---

**Currently**

- Shipping features and fixing production bugs on SoundCare — React 19, TypeScript, Node, MySQL, AWS S3, Socket.io
- Building evaluation tooling for **CyberShield**, an AI-security tool: an 80-prompt hand-verified adversarial dataset and a benchmark across 4 detector configs, quantifying the recall / false-positive frontier for a detector nobody had measured
- Working through Striver's A2Z sheet, one problem a morning → [striver-a2z](https://github.com/HarshitPandey-2021/striver-a2z)

**Stack**

`TypeScript` `JavaScript` `React` `Next.js` `Node.js` `Express` `MySQL` `MongoDB` `Tailwind` `AWS S3` `Socket.io` `JWT` `Python`

---

**Selected work**

| Project | What it is | Stack |
|---|---|---|
| [LittleLearners](https://github.com/HarshitPandey-2021/la-english-atelier) | Enrollment platform built end to end for a paying client — 23 registered families | Next.js 14, TypeScript, Express, MongoDB |
| [Campus Complaint Management](https://github.com/HarshitPandey-2021/ccms-test) | Complaint-lifecycle system — 5 admin roles, 30+ endpoints, transitions enforced at the API layer | MERN, JWT + OTP, Recharts |
| [TeaTalks](https://github.com/HarshitPandey-2021/teatalks) | Anonymous campus platform with a 4-layer content moderation pipeline | Next.js 14, MongoDB |
| [SpendWise](https://github.com/HarshitPandey-2021/SpendWise) | Full-stack expense tracker | Node, Express, SQLite |

---

**A few bugs that taught me more than any tutorial**

- A SQL comment (`--`) inside a JS template string. MySQL parsed it as literal SQL and the query died **silently** — nothing in the browser, nothing in the network tab. The real error was in the terminal the whole time.
- `ER_NO_REFERENCED_ROW_2` on staff creation, no documentation anywhere. A foreign key pointing at a legacy table that had been empty for years.
- An entire module broken because a richer version of the code shipped but its migration never ran. Code ahead of schema — now the first thing I check when a whole feature is dead rather than one endpoint.

---

**How I work with AI**

I use it. Everyone does. But I use it to *accelerate* thinking, not to skip it — try first, get stuck, ask for the concept, then reproduce it myself. After every fix I write down, in my own words, what broke and why.

If I can't write it, I didn't learn it.

---

📫 pandey6051172@gmail.com · [LinkedIn](https://www.linkedin.com/in/harshitpandey-dev)
