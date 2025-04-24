# Rocket-delivery-final
# Rocket-Delivery – Online Food Ordering System
Rocket-Delivery is a full-stack web application that allows customers to order food
from the app and have it delivered as soon as possible.
---
## 🍔 Project Overview
This system provides a convenient way for users to:
- Register and log in
- Place food orders online
- Select quantity and delivery schedule
- Track order status
Admins can:
- Add, edit, or delete food entries
- Manage food types and stock
- View and manage all orders and users
---
## 🍟 Tech Stack
- **Backend**: Flask (Python)
- **Database**: SQLite
- **Frontend**: HTML, CSS, Bootstrap
- **Tools**: PyCharm, DB Browser, GitHub
---
## 🍔 Features
- ordering from multiple restaurants at once
### 🍔 Customer
- Register & Login
- Order Food (with live total calculation)
- Select delivery time slot
- View past orders
- Cancel orders (if pending)
### Admin
- Dashboard with total stats
- Manage orders (cancel / mark delivered)
- Add/update/delete food orders
- Manage food types
- View users
---
## 🍔 How to Run
1. Clone the repository:
```bash
git clone https://github.com/yourusername/fuelnow.git
cd fuelnow
```
2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate # On Windows: venv\Scripts\activate
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```
4. Run the app:
```bash
python app.py
```
5. Visit [http://localhost:5000](http://localhost:5000) in your browser.
---
## Folder Structure
```
fuelnow/
├── app.py
├── templates/
│ ├── user/
│ └── admin/
├── models/
├── static/
├── instance/
│ └── db.sqlite
├── requirements.txt
└── README.md
```
---
## 🍔 Developed With SDLC
This project followed the **Software Development Life Cycle (SDLC)**:
- Planning
- Requirements Gathering
- Design
- Development
- Testing
- Deployment
- Maintenance
---
## 🍔 Author
- **Name**: [Amir Yousef, Marco Aguirre]
- **Date**: [04/24/2025]
---
## 🍔 License
This project is for educational purposes only.
