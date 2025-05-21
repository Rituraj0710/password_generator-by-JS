# 🔐 Password Generator

A powerful and customizable password generator built using **HTML**, **CSS**, and **JavaScript**. Users can generate secure passwords of custom lengths and choose whether to include uppercase letters, lowercase letters, numbers, and symbols.

---

## 🚀 Features

- Generate strong and random passwords
- Select password length using a slider
- Options to include:
  - Uppercase letters
  - Lowercase letters
  - Numbers
  - Symbols
- Visual password strength indicator
- Copy password to clipboard
- Auto-adjust password length to meet selection criteria
- Real-time UI updates and animations

---

## 🖼️ Interface Preview

> (You can add a screenshot here: Press `Print Screen`, paste in Paint, and upload to your GitHub repo)

---

## 📂 File Structure

```plaintext
📁 Password Generator
├── index.html       → Markup for the UI
├── styles.css       → Styling for the layout and design
└── script.js        → JavaScript logic for password generation

How to Use
-Clone or download the repository.
-Open index.html in your browser.
-Select the desired password length and character types.
-Click "Generate Password".
-Click the copy icon to copy the password.

⚙️ How It Works
User selects options: Choose length and what character types to include.

*JavaScript handles logic:
Functions generate random characters from selected types.
Ensures at least one character from each selected type is included.
Fills remaining characters randomly.
Uses Fisher-Yates shuffle to randomize password order.

*Password strength is calculated and color-coded:
Green: Strong
Yellow: Medium
Red: Weak