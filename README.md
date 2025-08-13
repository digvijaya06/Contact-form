# 📩 Contact Form with Client-Side Validation

A responsive contact form built with **HTML**, **CSS**, and **JavaScript** that includes real-time validation for **Name**, **Email**, and **Message** fields.
It prevents invalid submissions, provides **instant feedback** to users, and shows a success message without actually sending the data.

---

## 🚀 Features

* ✅ **Real-time validation** for:

  * **Name**: Cannot be empty
  * **Email**: Must follow valid email format (checked via regex)
  * **Message**: Cannot be empty, has a **250-character limit**
* ✅ **Error messages** appear below inputs if invalid
* ✅ **Shake animation** for invalid fields
* ✅ **Character counter** for message box
* ✅ **Success message** on valid submission (simulated, no backend)
* ✅ **Reset button** clears form and feedback styles
* ✅ **Data persistence** via `localStorage` (form retains input on refresh)
* ✅ **Loader effect** on submit (`Sending...` then success message)

---

## 📂 Project Structure

```
contact-form/
│
├── index.html     # HTML structure
├── style.css      # CSS styles (embedded in HTML for this version)
├── script.js      # JavaScript validation logic (embedded in HTML for this version)
└── README.md      # Project documentation
```

---

## 🛠️ How It Works

1. **HTML Form** — Contains three fields (`Name`, `Email`, `Message`) and two buttons (`Submit`, `Reset`).
2. **CSS Styling** — Styles for valid/invalid states, error messages, shake animation, and responsive design.
3. **JavaScript Validation**

   * Validates inputs in real-time and on submit
   * Uses regex for email validation
   * Disables submit button until all inputs are valid
   * Shows loader effect before displaying success message
   * Clears input styles and messages after reset

---

## 🔍 Email Validation Regex

```javascript
const emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
```

This ensures:

* No spaces in the email
* At least one `@` symbol
* At least one `.` after the `@`


## 📦 How to Use

1. Clone or download the project
2. Open `index.html` in **Chrome** or any modern browser
3. Fill in the form — you’ll see validation feedback instantly
4. Press **Submit** to see success message
5. Press **Reset** to clear the form



I can also **add GitHub-friendly badges** and a **live demo link** section if you plan to upload this to GitHub.
Do you want me to prepare that version?
