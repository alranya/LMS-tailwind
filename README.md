# 🏛️ Havad Engineering Library Portal

A modern, fully responsive multi-page web application designed for engineering colleges (B.Tech and M.Tech). Built entirely with HTML5 and styled with **Tailwind CSS**, this portal provides a clean interface for student catalog browsing, user authentication, personal book tracking, and administrative inventory management.

---

## 📄 Pages Included (8-Page Architecture)

1. **Member Login (`login.html`)** – Secure login portal.
2. **New Member Registration (`sign up.html`)** – Academic onboarding form capturing full name, college email, engineering department, and year of study.
3. **Student Member Dashboard (`dashboard.html`)** – Personal user hub displaying active profile details, currently issued books with due dates, renewal options, fine status, and a textbook purchase request form.
4. **Public Library Catalog (`viewbook.html`)** – Searchable repository of engineering textbooks, journals, and technical manuals with branch filtering and copy availability trackers.
5. **Admin Control Center (`admin dashboard.html`)** – Centralized administrative hub featuring real-time statistical overview cards (total catalog books, active checkouts, overdue returns, and pending student requests).
6. **Add Book Management (`addbook.html`)** – Inventory entry form for librarians to register new books, ISBN/accession numbers, and branch allocations.
7. **Issue Book Counter (`issuebook.html`)** – Checkout desk interface linking physical textbooks directly to verified student roll numbers.
8. **Return Book Counter (`returnbook.html`)** – Check-in desk interface for processing book returns, inspecting textbook condition, and recording overdue fine penalties.

---

## 🛠️ Tech Stack

* **Markup:** Semantic HTML5
* **Styling & Responsiveness:** Tailwind CSS (loaded via CDN)
* **Icons & UI Elements:** Clean SVG icons and emoji indicators for intuitive navigation

---

## 🚀 Getting Started & Installation

1. **Clone or Download** this repository to your local machine.
2. Ensure all 8 HTML files are in the same root directory.
3. Open any of the pages (such as `login.html` or `admin dashboard.html`) directly in your web browser, or run it using a local development server like **Live Server** in VS Code.

```bash
# Example structure
/library-portal
│── login.html
│── sign up.html
│── dashboard.html
│── viewbook.html
│── admin dashboard.html
│── addbook.html
│── issuebook.html
│── returnbook.html
