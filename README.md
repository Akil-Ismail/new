<img src="./readme/title1.svg"/>

<br><br>

<!-- project overview -->
<img src="./readme/title2.svg"/>

> **FreelanceReach – The AI-Powered Outreach Automation Suite**
>
> FreelanceReach is a smart web platform that automates the entire client outreach process for freelancers — from discovering relevant job posts to crafting personalized proposals, following up intelligently, tracking engagement, and even booking calls.  
>  
> Acting as a personal sales and communication assistant, it is tailored for solo professionals, remote workers, and freelance teams who want to scale their outreach while saving time.

<br><br>

<!-- System Design -->
<img src="./readme/title3.svg"/>

### High-Level Architecture

- **Frontend:** React, TailwindCSS, Framer Motion, Recharts
- **Backend:** Laravel, MySQL
- **AI/ML Layer:** GPT-4 for proposals, replies, and skill diagnostics; Custom ML for job matching
- **Integration Layer:** APIs for job feeds, calendaring, emails, and learning platforms

<br><br>

<!-- Project Highlights -->
<img src="./readme/title4.svg"/>

### Heavy & Sexy Features

1. **AI Proposal Generator**  
   - Generates tailored cover letters & proposals based on scraped job descriptions.
   - Tone selection: *formal*, *friendly*, *persuasive*.
   - Focus options: design, dev, writing, etc.  
   - **Tech:** GPT-4, Laravel backend, React frontend wizard.

2. **Job Feed Scraper + Matcher**  
   - Aggregates freelance jobs across platforms (Upwork, Fiverr, LinkedIn).  
   - Uses NLP for skill-based job matching.  
   - **Tech:** Puppeteer/Cheerio, RapidAPI, custom ML engine.

3. **Smart CRM for Clients & Leads**  
   - Track campaigns, lead status, opens, and replies.  
   - Auto follow-ups with reminders.  
   - **Tech:** React Kanban board UI, Laravel backend, Mailgun/SendGrid.

4. **Portfolio + Testimonial Auto-Insert**  
   - Injects best portfolio items into proposals dynamically.  
   - AI relevance scoring based on job type.  
   - **Tech:** AI scoring model, Cloudinary/AWS S3.

5. **Meeting Scheduler + Auto-Reply Bot**  
   - Clients book meetings directly via proposal link.  
   - GPT-powered DM/inquiry auto-responder.  
   - **Tech:** Calendly API/custom scheduler, Google Calendar sync.

6. **Analytics Dashboard**  
   - Proposal performance metrics, win rate, client behavior tracking.  
   - **Tech:** Recharts/D3.js, Laravel analytics API.

7. **Freelancer AI Coach**  
   - Weekly performance analysis & skill improvement tips.  
   - Suggests courses via Coursera/Udemy API.  
   - **Tech:** GPT-4, e-learning platform APIs.

📦 **Extra Goodies**
- Role-based authentication (Freelancer / Team)
- Export proposals to PDF
- Multilingual proposal generation
- Push/email alerts for hot leads
- Cloud sync & autosave

<br><br>

<!-- Demo -->
<img src="./readme/title5.svg"/>

### User Screens (Mobile)

| Login screen                            | Job Feed screen                       | Proposal Wizard                       |
| --------------------------------------- | -------------------------------------- | -------------------------------------- |
| ![Landing](./readme/demo/mobile1.png)   | ![JobFeed](./readme/demo/mobile2.png)  | ![ProposalWizard](./readme/demo/mobile3.png) |

### Admin Screens (Web)

| Dashboard                               | CRM Lead Board                        |
| --------------------------------------- | -------------------------------------- |
| ![Dashboard](./readme/demo/admin1.png)  | ![CRM](./readme/demo/admin2.png)       |

<br><br>

<!-- Development & Testing -->
<img src="./readme/title6.svg"/>

### Development & Testing Tools

| Services                                | Validation                             | Testing                                |
| --------------------------------------- | --------------------------------------- | --------------------------------------- |
| Laravel Backend + REST APIs             | Laravel Form Requests & Yup (React)    | PHPUnit, Laravel Dusk, Jest (React)    |
| Puppeteer/Cheerio Job Scraper           | AI/ML Proposal Quality Scoring         | Postman API Collections                |
| Mailgun/SendGrid Email Engine           | Auth & Role Permissions                | Cypress End-to-End Testing              |

<br><br>

<!-- Deployment -->
<img src="./readme/title7.svg"/>

### Deployment Strategy

- **Backend:** Laravel deployed via Forge/Vapor or Docker on AWS EC2.
- **Frontend:** React build hosted on Vercel or Netlify.
- **Database:** MySQL on AWS RDS.
- **AI/ML Layer:** GPT-4 API, custom ML services hosted on AWS Lambda.
- **Monitoring:** Laravel Telescope, Sentry, and Google Analytics.

| Postman API 1                            | Postman API 2                          | Postman API 3                          |
| ---------------------------------------- | --------------------------------------- | --------------------------------------- |
| ![API1](./readme/demo/api1.png)          | ![API2](./readme/demo/api2.png)         | ![API3](./readme/demo/api3.png)         |

<br><br>

---

## 🧱 Tech Stack Summary

| Layer       | Tools/Frameworks |
| ----------- | ---------------- |
| Frontend    | React, TailwindCSS, Framer Motion, Recharts |
| Backend     | Laravel, MySQL |
| AI/ML       | GPT-4 (proposals, replies), Custom ML (job matching) |
| Integrations| Puppeteer/Cheerio, RapidAPI, Mailgun/SendGrid, Calendly API |
| Hosting     | AWS (EC2, RDS, S3, Lambda), Vercel/Netlify |

---

## 🚀 Getting Started

### Prerequisites
- Node.js (>= 18)
- PHP (>= 8.1)
- Composer
- MySQL
- API keys for GPT-4, Mailgun/SendGrid, Calendly

### Installation
```bash
# Clone the repo
git clone https://github.com/yourusername/freelancereach.git

# Backend setup
cd backend
composer install
cp .env.example .env
php artisan key:generate

# Frontend setup
cd frontend
npm install
