# Michael Ijisonuwe

CRM developer in Manchester, UK. Zoho CRM automation, API integrations and the web apps that connect to them.

Since 2021 I have built the Zoho CRM workflows behind a regulated education provider: enrolment, lead follow-up and email campaigns for 500+ learners. Through my own company, Guild UK, I build complete CRM systems for small organisations. First-Class BSc in Computer Science (Manchester Metropolitan University, 2025).

I like systems where nothing gets lost: every input is checked, tracked and ends up somewhere useful.

## CRM work

### Guild UK: a complete Zoho One sales system

Websites, email and CRM systems for charities, community groups, faith groups and small businesses, set up in the client's own name.

- Deal pipelines, 50+ email templates built by script through the Zoho API, automated follow-ups, booking and a newsletter
- Zoho Flow with Deluge custom functions where the standard tools fall short
- Website forms connected to Zoho CRM Leads, Tasks, Contacts and Deals over OAuth 2.0, with seven server-side checks on every submission. Any failed call is queued and retried, so no enquiry is lost.
- A Stripe Checkout integration, in test mode before launch, that writes each payment to Zoho CRM deals and Zoho Books invoices
- The site and back end run on Cloudflare Workers and D1 (SQLite). Six test suites run on every pull request.

The code is private because it is the company's own system. I am happy to walk through it in an interview.

### Abbi Community UK: website and contacts system

The first client project, live and in its final stage: a 20-page website, 8 forms, live chat, Zoho CRM, SalesIQ, Desk and domain email with SPF, DKIM and DMARC, with user guides for the people who run it. Final images and search engine set-up are next.

- Live at [abbicommunityuk.com](https://abbicommunityuk.com)

The code belongs to the client and is private.

## Projects

### [Here](https://github.com/Gloggs/here): a class register that syncs with Zoho CRM

A phone-first class register for teachers and tutors. It began as my dissertation project, and I rebuilt it with private accounts, a security review, tests and a Zoho CRM integration.

- Each user connects their own Zoho CRM through OAuth, with keys encrypted with AES-256-GCM: import students from Contacts, send attendance back as notes or fields, and turn suggested check-ins into Zoho tasks only after approval
- A register in about ten seconds, persistent-absence flags below 90%, and reports
- 32 API routes and 37 automated tests run on every change
- Next.js, React, PostgreSQL, Drizzle, Kinde, Vercel, GitHub Actions
- Live at [here.guilduk.com](https://here.guilduk.com), with a demo that needs no sign-up

### [Health](https://github.com/Gloggs/health): a family health and fitness tracker

A tracker my family of seven uses every day for sleep, water, weight, workouts, meals and mood, so anything logs in a tap or two.

- Multi-family by design: every record belongs to a family, and each person has 8 settings for what the others can see
- 38 API routes and 8 versioned database migrations; tests and a production build run on every change
- Next.js, React, PostgreSQL, Drizzle, Kinde, Vercel
- Live at [health.guilduk.com](https://health.guilduk.com), with a demo on sample data

### [Assessment Record Generator](https://github.com/Gloggs/assessment-record-generator): in development

A local Python web app that transcribes a spoken English assessment, works out who is speaking and drafts each learner's record. The assessor checks, edits and approves every record, and the code will not generate a draft until they have confirmed what they heard.

- Python, Streamlit, Whisper, Claude API, SQLite, pytest
- 500+ automated tests run on every change
- Audio stays on the computer

The source code is private for now. The README explains how it works.

### [University projects](https://github.com/Gloggs/university-projects)

Six write-ups from my degree, including a machine-learning project (97% accuracy on chest X-rays), a cross-platform mobile app in C# and .NET MAUI, and a two-site network design. Each explains the brief, what I built and what I would do differently.

## Skills

- **CRM and business systems:** Zoho CRM (fields, layouts, pipelines, workflows, templates, REST API), Zoho Books API, Zoho Flow and Deluge, SalesIQ, Desk, Bookings, Mail
- **Integration:** REST APIs, OAuth 2.0, webhooks with signature checks, retry queues, Stripe Checkout
- **Languages:** JavaScript, TypeScript, Python, SQL, HTML, CSS
- **Web and data:** Node.js, Next.js, React, Cloudflare Workers, D1 (SQLite), PostgreSQL
- **Delivery:** requirements from non-technical clients, user guides and training, automated tests, pull-request workflow

I keep building and publishing new projects here to keep my skills current. I built my own development workstation from components, which runs AI models locally.

## Contact

- LinkedIn: [michael-ijisonuwe-944657254](https://www.linkedin.com/in/michael-ijisonuwe-944657254/)
- Email: ijisonuwe@outlook.com
