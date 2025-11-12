# Mini Booking (Flask)

A simple mini booking system inspired by Airbnb, built using **Flask** and mostly **HTML templates**.  
This web app allows users to browse mock listings, view details, log in with a username, and book a stay through a basic form.

---

### ✨ Features
- Home page and listings grid displaying multiple mock properties
- Individual listing detail pages with images and descriptions
- Mock login (username only, no password)
- Simple booking form that confirms a reservation
- Navigation bar and footer links between pages
- Clean, minimal HTML and CSS layout

---

### ⚙️ Limitations
- No database or persistent data storage
- No real authentication or payment system
- Mock data only (stored in Python lists)
- Basic routing, no API integration

---

### 🧠 How to Run Locally
```bash
python3 -m venv .venv && source .venv/bin/activate
pip install flask
python app.py
