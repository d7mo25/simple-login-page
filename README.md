# Login Form | Dan Aleko

A simple, responsive login page built with HTML and CSS, featuring email/password validation and icon integration via Boxicons.

## 🔗 Live Demo

👉 [View Live Demo]((https://d7mo25.github.io/simple-login-page/)) 

## 📋 Overview

This project is a modern **glassmorphism-style** login form UI, featuring a frosted-glass card over a full-screen background image. It includes client-side validation for email format and password length, along with a "Remember Me" checkbox, a "Forgot Password" link, and a link to a registration page.

## 🗂️ File Structure

```
project/
├── index.html        # Main login page markup
├── styles.css        # Stylesheet (glassmorphism design)
└── background.jpg    # Background image (add your own)
```

## ✨ Features

- **Glassmorphism design** — Frosted-glass card (`backdrop-filter: blur`) over a full-screen background image.
- **Email validation** — Enforces a valid email format using a regex pattern.
- **Password validation** — Requires a minimum of 8 characters.
- **Remember Me checkbox** — Lets users opt to stay logged in.
- **Forgot Password link** — Placeholder link for password recovery flow.
- **Register link** — Placeholder link for new users to sign up.
- **Icon integration** — Uses [Boxicons](https://boxicons.com/) for the email and lock icons.
- **Custom typography** — Uses the "Poppins" font family throughout.
- **Fully responsive card** — Centered on screen at any viewport size via flexbox.

## 🛠️ Technologies Used

- HTML5
- CSS3 (external stylesheet: `styles.css`) — glassmorphism effects, flexbox layout
- [Boxicons](https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css) — icon library (loaded via CDN)
- **Poppins** font (Google Fonts — not yet linked in HTML, see Notes below)

## 🚀 Getting Started

1. Clone or download this repository.
2. Make sure `styles.css` is in the same directory as `index.html`.
3. Add a `background.jpg` image to the same directory (referenced by `styles.css`), or update the `background` property to point to your own image.
4. Open `index.html` in your browser — no build steps or dependencies required.

## 🔧 Customization

- **Form action** — Update the `action=""` attribute on the `<form>` tag to point to your backend login endpoint.
- **Validation rules** — Adjust the `pattern` and `minlength` attributes on the inputs to change validation requirements.
- **Styling** — Edit `styles.css` to customize colors, fonts, and layout.

## ⚠️ Notes

- This is a **front-end only** template — form submission logic (authentication, backend handling) is not included and must be implemented separately.
- The email regex pattern only supports lowercase input matching; consider using the `i` flag equivalent or a more permissive pattern if mixed-case emails should be accepted without browser normalization issues.
- `styles.css` sets `font-family: "Poppins"`, but the Google Fonts link isn't included in `index.html` yet — add this to the `<head>` for the font to actually load:
  ```html
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  ```
- A `background.jpg` file is required in the project root for the background image to display; without it, the background will appear blank.

![Screenshot 2025-03-28 165123](https://github.com/user-attachments/assets/0be20553-a80a-4653-a455-a36356dcedd1)

