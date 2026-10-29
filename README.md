# Michael Ijisonuwe

Software developer in Manchester, UK. First-Class BSc in Computer Science (Manchester Metropolitan University, 2025).

I build web applications, CRM automation and AI tools that remove manual work. I like systems where nothing gets lost: every input is checked, tracked and ends somewhere useful.

## How I got here

I wanted to understand computers from the foundations up, so I started with the hardware. During my degree I built my first PC from components: a Ryzen 9 5900X with an RTX 3090 (24GB), 64GB of memory, liquid cooling and 3TB of NVMe storage. It runs at 60°C or below under load, and it is still my development workstation. [See the build](https://uk.pcpartpicker.com/b/2F8J7P).

A month later I tested what I had learned. With no guide, I built a second machine for about £400 from used and spare parts, working out for myself what was compatible and where the limits were. It runs games at 1080p at 170 to 200 frames a second. [See the budget build](https://uk.pcpartpicker.com/b/R2mkcf).

Knowing how the machine works underneath is what drew me further into computer science and into writing software. That first workstation now runs the AI models behind my Assessment Record Generator, so recordings never have to leave the machine.

## Projects

### Assessment Record Generator

A Python web app that turns two audio recordings of a spoken English assessment into a drafted assessment record for each learner, ready for the assessor to review and edit.

- Python, Streamlit, Whisper, pyannote, Claude API, SQLite
- About 21,000 lines of application code and over 480 automated tests
- Security reviewed with an AI-assisted audit, then fixed: no default PIN, sign-in lockout, local-only server and complete data erasure
- Linting and tests run on every change through GitHub Actions
- Cut a 4 hour task to about 30 minutes

The code is private because it was built around real assessment work. Read how it works here: [assessment-record-generator](https://github.com/Gloggs/assessment-record-generator). I am happy to walk through the code in an interview.

### Here.

A phone-first class register for teachers and tutors. It began as my dissertation project, and I rebuilt it with private accounts, a security review, tests and a Zoho CRM integration.

- Next.js, React, PostgreSQL (Neon), Drizzle ORM, Kinde authentication, Vercel, GitHub Actions
- Takes a register in about ten seconds, flags persistent absence below 90%, and exports reports
- Each user connects their own Zoho CRM through OAuth, with keys encrypted with AES-256-GCM: import students from Contacts, send attendance back as notes or fields, and turn suggested check-ins into Zoho tasks only after approval
- About 8,000 lines of code, 32 API routes and 37 automated tests run on every change
- Live at [here.guilduk.com](https://here.guilduk.com), with a demo that needs no sign-up. Code: [Gloggs/here](https://github.com/Gloggs/here)

### Health

A health and fitness tracker my family of seven uses every day: sleep, water, weight, workouts, meals and mood. The first version worked on paper but was slow in daily use, so I rebuilt it to log anything in a tap or two, keep every screen one tap or one search away, and keep each person's data private unless they choose to share it.

- Next.js, React, PostgreSQL (Neon), Drizzle ORM, Kinde authentication, Vercel, GitHub Actions
- Multi-family by design: every record belongs to a family, and each person has 8 settings for what the others can see
- One log sheet for everything, with your usual amounts first, and Undo instead of "are you sure"
- Installable on a phone from the browser, light and dark modes
- About 26,000 lines of code, 38 API routes and 8 versioned database migrations; tests and a production build run on every change
- Live at [health.guilduk.com](https://health.guilduk.com), with a demo on sample data that needs no sign-up. Code: [Gloggs/health](https://github.com/Gloggs/health)

### Abbi Community UK website and contacts system

A complete system for a community organisation, built as a freelance client project: a 20-page website, 8 forms, live chat, a CRM, a help desk and domain email.

- JavaScript, HTML and CSS on Cloudflare Workers
- A server-side form endpoint with 7 validation and security checks
- 100 out of 100 on Google Lighthouse mobile tests, grade A for security headers
- Live at [abbicommunityuk.com](https://abbicommunityuk.com)

The code belongs to the client and is private.

### University projects

Six write-ups from my BSc (Hons) Computer Science at Manchester Metropolitan University, covering machine learning, a full-stack dissertation, a cross-platform mobile app, network design and more. Each one explains the brief, what I built and what I would do differently.

[See all university projects](https://github.com/Gloggs/university-projects)

## Skills

- **Languages:** Python, JavaScript, C#, SQL, HTML, CSS
- **Frameworks and tools:** React, Next.js, Node.js, .NET 8 MAUI, XAML, Streamlit, PostgreSQL, SQLite, pytest, GitHub Actions
- **Platforms:** Cloudflare Workers, Vercel, Zoho CRM (including its REST API and OAuth), Microsoft 365
- **Practice:** automated testing, security checks on user input, technical documentation, AI-assisted development with review and testing before release

## Contact

- LinkedIn: [linkedin.com/in/michael-ijisonuwe-944657254](https://uk.linkedin.com/in/michael-ijisonuwe-944657254)
- Email: ijisonuwe@outlook.com
