# Accounting SmartClass

Premium academic event landing page for accounting students and lecturers.

## Current state
- Responsive bilingual (Bahasa Indonesia / English) public landing page.
- Event cards seeded from the three sample events supplied for the project.
- Event detail / registration-form visual preview.
- Navy, white, charcoal, and electric-blue design system.
- No backend or database is connected yet. The registration form is explicitly a demo and does not transmit or store personal data.

## Preview locally
Open `index.html` in a browser.

## Deploy with GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`, then Save.
4. Wait for the Pages deployment and open the URL shown in Settings → Pages.

## Planned production integration
Connect Supabase (PostgreSQL, Auth, and Storage) for:
- Admin authentication and role-based access.
- Event CRUD, bilingual descriptions, poster uploads, registration windows, capacity, and publication state.
- Secure participant registration, duplicate prevention, capacity enforcement, and registration references.
- Participant search, filtering, and CSV export.

Do not collect real participant data until the backend, privacy notice, access policies, and server-side validation are implemented.
