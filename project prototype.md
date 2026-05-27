# Quick Start Guide

## Simple Method (Recommended)

### 1. **Double-click RUN.bat**
   - Automatically installs dependencies
   - Starts the Flask server
   - Opens on `http://127.0.0.1:5000/`

---

## Manual Method

### 1. Install Dependencies
```cmd
pip install -r requirements.txt
```

### 2. Run the App
```cmd
python app.py
```

### 3. Open in Browser
```
http://127.0.0.1:5000/
```

---

## Login Credentials
- **Username:** `farmer`
- **Password:** `agro123`

---

## Features
✓ Login page with agriculture theme  
✓ Dashboard with plant health metrics  
✓ Real-time sensor data visualization  
✓ Leaf image upload module  
✓ Disease detection (sample predictions)  
✓ Admin panel for monitoring  
✓ Responsive design (mobile-friendly)  

---

## Troubleshooting

### Page won't load?
- Make sure Flask is running (check terminal for `Running on http://127.0.0.1:5000/`)
- Try opening in a different browser
- Clear browser cache (Ctrl+Shift+Delete)

### Missing dependencies?
```cmd
pip install Flask==3.0.0 mysql-connector-python==8.1.0 python-dotenv==1.0.0
```

### Port 5000 already in use?
Kill the existing process and restart:
```cmd
python app.py
```

---

## Stop the Server
Press `Ctrl+C` in the terminal window running Flask

---

## Project Structure
```
leaf_disease_iot_prototype/
├── app.py                 # Main Flask application
├── requirements.txt       # Python dependencies
├── schema.sql            # MySQL database schema (optional)
├── templates/            # HTML pages
│   ├── login.html
│   ├── dashboard.html
│   ├── upload.html
│   ├── result.html
│   └── admin.html
├── static/               # CSS, JS, images
│   ├── css/style.css
│   ├── js/main.js
│   └── images/
└── README.md
```

---

## Next Steps
- Upload test leaf images
- Try the disease detection feature
- View admin panel for monitoring
- Check IoT sensor dashboard for real-time data
