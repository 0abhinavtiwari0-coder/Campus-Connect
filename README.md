# Campus Connect — interactive frontend prototype

## Run Locally
You can run the prototype using either of the following methods:

### Method 1: Local Server (Node.js)
Start the local HTTP server:
```bash
node server.js
```
Then open in your browser:
[http://localhost:3000/](http://localhost:3000/)

### Method 2: Direct File Open
Simply double-click `index.html` to open it directly in any modern web browser.

---

## Demo Sign-in
Any non-empty email and password will work, or use the quick role pills on the login screen:
- Student (`student@campus.edu`)
- Teacher / Faculty (`faculty@campus.edu`)
- College Administration (`admin@campus.edu`)
- Placement Cell (`placement@campus.edu`)
- Parent (`parent@campus.edu`)

## Included Features
- Role-specific navigation and dashboards
- Official circulars and announcements (with category filters and broadcast tool)
- Timetable (day-wise schedule for students & teaching slots for faculty)
- Attendance (interactive marking for teachers, threshold margins & bunk calculator for students)
- Assignments & CT-1 Results (file submission modal & marks review)
- Campus events (category filters & RSVP tracking)
- Placement & Internship matches (interactive AI skill-matching engine & drive scheduler)
- Discussion community forum (persisted posts, likes & replies)
- Fee portal (fee component breakdown, payment modal & receipts)
- Grievance helpdesk (ticket logging with real-time status tracker)

## Important Limitations
This is a front-end demonstration prototype with interactive client-side state. It does not connect to a production backend or real payment gateway. Do not enter real sensitive credentials or payment cards.
