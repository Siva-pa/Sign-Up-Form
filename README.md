# ✨ Sign-Up & Login System

A complete User Authentication System built using HTML, CSS, JavaScript, and Excel as a lightweight storage method.
This project includes Sign-Up, Login, Forgot Password (OTP-based), and Post-Login navigation pages.

# 📌 Overview

This project demonstrates a simple frontend-based authentication flow. Users can create an account, log in using stored credentials, reset passwords via OTP, and access a personalized welcome page with external links.

# 🚀 Features
# 🔐 Account Creation

Users can create a new account with Name, Email, Password

Details are stored in an Excel (.xlsx) file using JavaScript

# 🔑 Login System

Email + Password verification

Login succeeds only if credentials match previously stored data

# 🛠️ Forgot Password with OTP

User enters email → OTP is generated

On correct OTP, user can create a new password

Updated password is saved to Excel

# 🧭 Navigation Pages

Index Page

Account Creation Page

Login Page

Forgot Password Page

OTP Verification Page

Welcome Page (after login)

Join Page with useful links:

GitHub

LinkedIn

YouTube

And more…

# 🎨 UI & Styling

Built with CSS

Custom background image for clean UI

Styled buttons, forms, input fields

# 🛠️ Technologies Used
Technology	Purpose
HTML	Page structure
CSS	Styling, layout & UI
JavaScript	Validation, OTP generation, Excel handling
Excel (.xlsx)	Storing user records
# 📂 Project Structure
/project-folder
│── index.html
│── signup.html
│── login.html
│── forgot.html
│── otp.html
│── newpassword.html
│── welcome.html
│── join.html
│── script.js
│── style.css
│── users.xlsx
│── assets/
     └── background.jpg

# 🔎 How It Works

User enters details → Sign-Up

Data is saved into Excel

During Login, the script checks:

Is the email correct?

Does password match stored data?

If correct → redirect to Welcome Page

Password forgotten?

Enter email → receive OTP

Enter OTP → set new password

Updated automatically in Excel

After login → redirect to Join Page with useful external links

# 🚧 Future Improvements

Move from Excel → Database (Firebase / MongoDB / MySQL)

Add responsive mobile design

Add stronger validation (Regex)

Add session authentication (JWT / Cookies)

# 🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit pull requests.

# 📜 License

Open-source project – free to use & modify.
