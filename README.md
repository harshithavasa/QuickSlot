# QuickSlot
QuickSlot: Real-Time Booking &amp; Calendar Orchestration (API Based)

QuickSlot is a front-end real-time slot booking system that allows users to log in, view provider availability, 
and book time slots using a synchronized internet clock. 
The application is designed for demo and academic submission purposes and runs entirely on the client side.

Features

- Login & Signup (Frontend Authentication)
- Real-time slot availability
- Internet time synchronization (IST)
- Dynamic provider roster
- Slot booking with conflict prevention
- Dummy email confirmation on booking
- Persistent bookings using LocalStorage
- Modern responsive UI (Bootstrap 5)

---

Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**
- **Bootstrap 5**
- **LocalStorage (for auth & bookings)**

---

Authentication (Demo)

- Login and Signup are implemented using **LocalStorage**
- No backend is required
- User must log in before accessing booking functionality
- Credentials are not encrypted (demo purpose only)

---

Booking Workflow

1. User logs in or signs up
2. Selects a provider
3. Selects a date
4. Available slots are fetched
5. User books a slot
6. Slot is saved locally and marked unavailable
7. Dummy email confirmation is triggered

---

APIs Used

### Provider Roster (Fake API)
