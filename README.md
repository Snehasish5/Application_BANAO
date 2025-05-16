# Application_BANAO

🩺 **User Authentication Web App (Patient & Doctor Portal)**
This is a Flask-based web application that supports user registration and login for two types of users: Patients and Doctors. After login, each user is redirected to their personalized dashboard that displays their profile details.

🔧 **Features**

🧑‍⚕️ Role-based signup for Patients and Doctors
🔐 Login and session management
📸 Profile picture upload
🏠 Responsive user dashboard showing profile info
📍 Address input (line, city, state, pincode)
✅ Password confirmation and frontend validation
🎨 Clean, modern UI with custom CSS
💾 In-memory storage (can be extended to database)

📁 **Folder Structure**

project/
├── app.py
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── scripts.js
│   └── uploads/         # Profile pictures stored here
├── templates/
│   ├── index.html
│   ├── signup.html
│   ├── login.html
│   └── dashboard.html
└── README.md

🖥️ **Technologies Used**
1. Python 3
2. Flask
3. HTML5 & CSS3
4. JavaScript (basic form validation)
5. Werkzeug (for secure file uploads)

🚀 **How to Run**
Clone the repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

**Install dependencies**
pip install flask

**Run the application**
python app.py

**Visit in browser**
http://127.0.0.1:5000/
