# 🎓 CampusEvents - College Event Registration System

An intuitive, responsive web application for exploring campus events, reserving seats in real time, and managing participant registrations through an administrative dashboard.

---

## 🌟 Key Features

### 👨‍🎓 For Students & Participants
- **Event Discovery & Filtering:** Browse technical symposiums, hackathons, workshops, cultural fests, design challenges, and contests. Filter by category or search instantly by title.
- **Detailed Event Overviews:** Interactive modal popups displaying event schedules, categories, descriptions, and real-time available seat counts.
- **Instant Registration Form:** Streamlined form collecting Student Name, Register Number, College, Department, Year, Email, and Phone number.
- **Duplicate Prevention:** Automatically checks register numbers to prevent duplicate registrations for the same event.
- **Digital Registration Pass:** Instant confirmation screen showing a unique Registration Pass ID (`CE######`), student details, and event confirmation.

### 🛡️ For Organizers & Administrators
- **Dedicated Admin Portal:** Secure password-protected dashboard (accessible via the navigation bar or `#admin`).
- **Live Seat Tracking:** Real-time calculation and tracking of remaining seats per event with automated seat limits.
- **Registration Management:** Review participant records in an organized card layout.
- **Edit & Delete Records:** Update student contact details or cancel registrations, which automatically frees up seats in real time.
- **CSV Data Export:** One-click export of all participant records into a formatted `.csv` file (`Campus_Registrations_YYYY-MM-DD.csv`) for spreadsheets and record keeping.
- **Admin Password Management:** Update admin passkey directly from the dashboard.

---

## 🚀 Getting Started

This project is built as a self-contained single-page web application with no external build tools or backend dependencies required.

### Prerequisites
- Any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari, Opera).

### Running Locally
1. Clone or download this repository to your local computer.
2. Locate the [index.html](file:///c:/Users/srohi/OneDrive/Desktop/Event%20organizer%20website/index.html) file.
3. Open [index.html](file:///c:/Users/srohi/OneDrive/Desktop/Event%20organizer%20website/index.html) directly in your browser:
   - Double-click the file, **OR**
   - Right-click and choose **Open With** &rarr; Your preferred browser, **OR**
   - Run a local server (e.g., using VS Code Live Server or Python `python -m http.server 8000`).

---

## 🔐 Admin Access Credentials

To access the administrator controls:
1. Navigate to the **Admin Portal** section in the navigation menu or scroll to `#admin`.
2. Enter the administrator credentials:
   - **Default Admin Password:** `rohith23` *(or fallback `admin123`)*
3. Once logged in, you can change your password anytime using the **Change Password** button in the dashboard.

---

## 📂 Project Structure

```text
Event organizer website/
│
├── index.html        # Complete single-page application (HTML5, Vanilla CSS, JavaScript)
└── README.md         # Project documentation and guide
```

---

## 🛠️ Technologies Used

- **HTML5:** Semantic markup, accessible structure, responsive viewport configuration.
- **CSS3:** Responsive Grid & Flexbox layouts, CSS variables, glassmorphic modals, and smooth animations.
- **Vanilla JavaScript (ES6+):** Client-side state handling, dynamic filtering, real-time seat limit math, modal workflows, CSV generation, and storage synchronization.
- **Storage Layer:** Dual-layer storage using standard `localStorage` with fallback support for custom window storage environments.

---

## 📋 Available Events & Seat Capacities

| Event Name | Category | Seat Capacity |
| :--- | :--- | :--- |
| **Tech Hackathon** | Technical | 50 |
| **Technical Symposium** | Technical | 40 |
| **Cultural Fest** | Cultural | 60 |
| **Code Debugging** | Technical | 40 |
| **Web Design Challenge** | Technical / Design | 35 |
| **Quiz Competition** | Non-Technical | 50 |
| **Dance Competition** | Cultural | 30 |
| **Singing Competition** | Cultural | 30 |
| **Paper Presentation** | Academic / Tech | 40 |
| **AI Workshop** | Workshop | 50 |
| **Web Development Workshop** | Workshop | 45 |
| **Debate Competition** | Non-Technical | 30 |
| **Coding Contest** | Technical | 50 |
| **Photography Contest** | Creative | 35 |
| **Cyber Security Workshop** | Workshop | 45 |
| **Business Quiz** | Non-Technical | 40 |
| **Short Film Contest** | Creative | 30 |
| **UI UX Design Workshop** | Workshop | 40 |

---

## 📄 License

This project is developed for educational and campus event management purposes. Feel free to modify and customize it for your institution.
