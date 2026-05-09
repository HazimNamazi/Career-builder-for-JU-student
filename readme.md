
# 🎓 Career Building for JU Students

> منصة توظيف متكاملة تربط طلاب جامعة جازان بأصحاب العمل في المملكة العربية السعودية ومنطقة الخليج.

🔗 **Live Demo**: [careerbuildingforjustudents.netlify.app](https://careerbuildingforjustudents.netlify.app)

---

## 📸 Preview

![Career Builder Preview](.<img width="1469" height="831" alt="Screenshot 2026-05-09 at 12 03 07 PM" src="https://github.com/user-attachments/assets/3e648262-11e3-4f48-b74f-a7bebc7da07b" />
)
)

---

## ✨ Features

- 💼 **Job Listings** — Real job postings with company, location, salary, and department
- 🔍 **Smart Filtering** — Filter jobs by department/major (e.g. CS, Business, Engineering)
- 👤 **User Authentication** — Student and employer registration & login
- 📤 **CV Upload** — Students can upload their resumes directly through the platform
- 🌐 **Bilingual** — Full Arabic and English support
- 📱 **Responsive Design** — Works on desktop, tablet, and mobile

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, JavaScript |
| Icons | Font Awesome 6.4.0 |
| Job Database | Neon (Serverless PostgreSQL) |
| File Storage | Supabase Storage (CV uploads) |
| Hosting | Netlify |
| Backend | Netlify Functions (Serverless) |

---

## 📁 Project Structure

```
Career-builder-for-JU-student/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── pages/
│   ├── jobs.html         # Browse & filter job listings
│   ├── login.html        # User login
│   ├── signup.html       # User registration
│   ├── about.html        # About the platform
│   └── contact.html      # Contact page
├── netlify/
│   └── functions/        # Serverless API functions
├── database/             # DB schema & queries
├── netlify.toml
└── package.json
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js installed
- Netlify CLI (optional)

### Run Locally

```bash
# Clone the repo
git clone https://github.com/HazimNamazi/Career-builder-for-JU-student.git

cd Career-builder-for-JU-student

npm install

# Open index.html with Live Server in VS Code
```

### Environment Variables

Create a `.env` file locally (never commit this file):

```
DATABASE_URL=your_neon_postgresql_url
SUPABASE_URL=your_supabase_url
SUPABASE_ANON_KEY=your_supabase_anon_key
```

For deployment, add these variables in **Netlify → Site Settings → Environment Variables**.

---

## 🗄️ Database Architecture

**Neon (PostgreSQL)** — Job & user data:
- `users` — Student and employer accounts
- `jobs` — Job listings with department filtering
- `applications` — Submitted job applications

**Supabase Storage** — File management:
- Stores student CV files (PDF)
- Secure per-user file access

---

## 📋 Roadmap

- [x] Job listings with real data
- [x] Department-based job filtering
- [x] Bilingual support (AR / EN)
- [x] Responsive design
- [x] Live deployment on Netlify
- [x] PostgreSQL database (Neon)
- [x] CV file storage (Supabase)
- [ ] Student dashboard
- [ ] Employer dashboard
- [ ] Email notifications for new jobs
- [ ] Ratings and reviews system
- [ ] Mobile app (React Native)

---

## 👨‍💻 Author

**Hazim Namazi**
- 🐙 GitHub: [@HazimNamazi](https://github.com/HazimNamazi)
- 💼 LinkedIn: [your-linkedin-url]
- 📧 Email: Namazihazim@gmail.com

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Built with ❤️ to make job hunting easier for JU students*
