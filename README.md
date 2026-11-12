# ScholarHire - Academic & Career Job Tracking System

A modern, responsive, role-based job tracking application designed with a soft **light blue** theme (`#0ea5e9` / Tailwind Sky palette) tailored for academic faculty, research institutions, and career tracking.

---

## 🌟 Key Features

### 1. 🔗 Share, Details & Apply Actions
Every job card now features 3 primary interactive buttons:
- **Share**: Enables instant sharing of the direct job link. Supports copying the URL with one click, native Web Share API on mobile, and quick sharing to Email, LinkedIn, X (Twitter), and WhatsApp.
  - Also supports direct URLs: appending `?job=job-1` automatically opens that opening's details.
- **Details**: Opens the full academic appointment dossier showcasing:
  1. **Teaching duties**: You will teach undergraduate and postgraduate students.
  2. **Research duties**: Conduct and publish original research in recognized peer-reviewed journals and international conferences.
  3. Key qualifications, salary scale, deadlines, and departmental overview.
- **Apply**: Opens an application form with resume/CV upload, portfolio/Google Scholar links, and research statements.

### 2. 📧 Automated Email Notification on Candidate Application
- **Instant Admin Alert**: Every time a candidate applies for an opening, an automated notification is created and addressed to the administrator email (defaults to `admin@scholarhire.edu`, easily customizable in the admin interface).
- **Notification Bell & Counter**: In-app bell icon in the top header with a real-time unread badge counter showing all incoming email dispatches.
- **Email Message Viewer**: Click any email notification to preview the exact email envelope, headers (`From`, `To`, `Date`), candidate qualifications, attached CV, and statement.
- **One-Click Email Reply**: Includes a `mailto:` shortcut button to directly draft a response to the applicant using your system's default email client.

### 3. 🛡️ Administrator & Recruiter Portal
- **Post Openings**: Publish faculty, researcher, and staff appointments with qualifications, teaching and research responsibilities, compensation, and deadlines.
- **Candidate Pipeline Tracker**: Review applicants per position, view experience, curriculum vitae, contact details, and update stages (`Applied` ➔ `Under Review` ➔ `Interviewing` ➔ `Offer Extended` ➔ `Rejected`).
- **Internal Committee Notes**: Record faculty feedback, seminar ratings, and salary benchmarks.

### 4. 👤 Scholar / Candidate Portal
- **Browse & Filter**: Search positions by academic discipline, research field, department, or job type.
- **Application Flow**: Submit applications with contact info, Google Scholar / LinkedIn URLs, CV upload, and research statements.
- **"My Applications" Tracker**: Track application progression with visual progress steppers.

### 5. 🎨 Design & Experience
- **Primary Color**: Light Blue (`brand-500` / `#0ea5e9` with soft sky blue accents `#e0f2fe`).
- **Instant Role Switcher**: One-click toggle in the top-right navbar between **Candidate** and **Admin**.
- **Local Persistence**: State, jobs, and notifications are saved in browser `localStorage`. Includes a **"Reset Demo Data"** action in the footer.

---

## 🚀 How to Open

Open [index.html](file:///c:/Users/User/Desktop/Antigravity%20demo/index.html) directly in any modern web browser (Chrome, Edge, Firefox, Brave).
