# SmartCare Hospital Management — starter prototype

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a browser. On a phone, use a code editor or upload to GitHub Pages.
3. Switch language (English/Marathi) and demo role from the top-right controls.

## Included in this prototype
- Admin, Doctor, Receptionist and Patient demo views
- English/Marathi interface toggle
- Patient registration and search
- Doctor directory
- Appointment booking
- Basic billing entries
- Medicine stock list
- Summary dashboard and reports

## Important limitations
This is a front-end demonstration only. Data stays in the current browser page and is not securely stored or shared between users. Demo role switching is NOT authentication or access control. Do not enter real patient names, phone numbers, diagnoses, prescriptions, reports, or other personal/medical information.

Before real hospital use, add:
- Supabase Auth with verified accounts and role-based access
- PostgreSQL tables with Row Level Security (RLS) policies
- Server-side validation, audit logs, backups and secure file storage
- HTTPS, privacy notice, consent workflows and applicable legal/security review
- Proper clinical workflows reviewed by qualified hospital staff

## Free hosting
GitHub Pages can host this static prototype for free. It cannot by itself provide a secure multi-user database or login. A backend such as Supabase has a free tier, subject to its current limits and terms.
