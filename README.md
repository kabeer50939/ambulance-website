# Ambulance Institution - Emergency Medical Services
Website Project for a 5-Person Team

This website is structured so that **5 team members** can work independently without overwriting each other's work or having git conflicts.

---

## 👥 Task Allocation for the 5 Team Members

| Member | Assigned Pages | Assigned CSS File | Responsibilities |
| :--- | :--- | :--- | :--- |
| **Person 1** | `index.html` | `css/home.css` | **Home Page**: Hero banner, 24/7 emergency dispatch strip, stats counter, core features, call to action. |
| **Person 2** | `about.html`, `team.html` | `css/about.css` | **About Us & Our Team**: History, mission/vision, leadership & paramedic staff profiles. |
| **Person 3** | `services.html`, `facilities.html` | `css/services.css` | **Services & Facilities**: Emergency care, ICU transfers, pediatric transport, command center & decontamination bays. |
| **Person 4** | `ambulances.html`, `gallery.html` | `css/ambulances.css` | **Ambulances & Gallery**: Fleet showcase (ALS, BLS, Air Ambulance), specifications, photo/media gallery. |
| **Person 5** | `contact.html` | `css/contact.css` | **Contact Us**: Contact & booking form, emergency hotline callout, station addresses, operating hours. |

---

## 📁 Project Folder Structure

```
GAS/
├── index.html           # Person 1 (Home)
├── about.html           # Person 2 (About Us)
├── team.html            # Person 2 (Our Team)
├── services.html        # Person 3 (Services)
├── facilities.html      # Person 3 (Facilities)
├── ambulances.html      # Person 4 (Ambulances Fleet)
├── gallery.html         # Person 4 (Photo Gallery)
├── contact.html         # Person 5 (Contact Us)
├── css/
│   ├── common.css       # SHARED: Header, Navbar, Footer, Buttons, Theme colors
│   ├── home.css         # Person 1 styles
│   ├── about.css        # Person 2 styles
│   ├── services.css     # Person 3 styles
│   ├── ambulances.css   # Person 4 styles
│   └── contact.css      # Person 5 styles
├── js/
│   └── main.js          # SHARED: Mobile nav toggle & active link script
├── images/
│   └── logo.svg         # Heartbeat Ambulance Institution logo
└── README.md            # Team guide & instructions
```

---

## 🛡️ Team Golden Rules to Avoid Merge Conflicts

1. **Only edit your assigned files**:
   - For example, if you are Person 2, edit only `about.html`, `team.html`, and `css/about.css`.
2. **Do NOT modify `css/common.css` or `images/` directly**:
   - Common styles (like the top navigation and footer) are shared so the website looks unified. If a change to the navbar or footer is needed, discuss it with the team first.
3. **Keep the Header and Footer unchanged**:
   - Each page has the exact same top header and bottom footer to ensure a consistent experience across all 8 pages.

---

## 🚀 How to Run and Test
1. Double click `index.html` in your file explorer to open it directly in any web browser (Chrome, Edge, Firefox).
2. Or in VS Code, right-click `index.html` and click **"Open with Live Server"**.
