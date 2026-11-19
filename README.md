# Youth Elite Clubs Monitoring System (2026–2027)

A self-contained, zero-backend web application designed for monitoring the **14 Youth Elite Clubs** across Hong Kong, ready for immediate deployment on **GitHub Pages**.

## Monitored Youth Elite Clubs (14)
1. Eastern
2. EDSA
3. Hong Kong Football Club
4. Kitchee
5. Konter
6. Kowloon City
7. Kowloon Cricket Club
8. Lee Man
9. Lucky Mile
10. Rangers
11. South China
12. Southern
13. Tai Po
14. Yuen Long

## Core Sections & Features
1. **Spot Check Report Submission**:
   - Club selection, inspection date (auto-matched to 1st Funding Period `Sep 2026 – Jan 2027` or 2nd Funding Period `Feb 2027 – Jun 2027`), Age Group (`U14`, `U16`, `U18`).
   - Venue, Training Time, Spot Check Time, Field Players & Goalkeepers attendance.
   - Coaching & Technical Staff attendance (`Head Coach`, `Assistant Coach`, `Academy Goalkeeping Lead Coach`, `Academy Physical Lead Coach`).
   - Remarks & Extra Staff notes, plus multi-photo upload with automatic client-side compression.
2. **Training Schedule & Officer Booking**:
   - Upload per-club schedules in **Excel (`.xlsx`, `.xls`, `.csv`)**, **Word (`.docx`)**, or **PDF (`.pdf`)** to automatically populate the club calendar.
   - Click any date on a club's calendar to book a Spot Check and insert the Officer's name.
3. **Spot Check Calendar & Master Compliance Table**:
   - Real-time `0 / 2` tracking per club for both funding periods and a unified Master Calendar across all 14 clubs.
4. **Report Approval (Admin Portal)**:
   - Protected by Admin login (`tamkayin2012@gmail.com`).
   - Approve pending submissions to update Master Table counts, review the Two-Spot-Check Summary per club, and export to **Excel (`.xlsx`)**.
5. **Static JSON Data Sync**:
   - Built-in **Export JSON Backup**, **Merge Officer JSON**, and **Restore** tools allow officers and administrators to synchronize field submissions seamlessly on static GitHub Pages hosting.

## Deploying to GitHub Pages
1. Create a new repository on GitHub (e.g., `youth-elite-clubs-monitoring`).
2. Upload `index.html`, `README.md`, and `.nojekyll` to the root of the `main` branch.
3. Navigate to **Settings → Pages → Build and deployment**.
4. Under **Source**, choose **Deploy from a branch**, select `main` and `/ (root)`, and click **Save**.
5. Your live portal will be published at `https://<your-username>.github.io/<repo-name>/`.
