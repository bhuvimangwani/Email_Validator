# Email Validator

**Email Validator** is a simple and responsive web application that allows users to validate email addresses using the [emailvalidation.io](https://emailvalidation.io/) API. Built with **HTML**, **CSS**, and **JavaScript**, this tool fetches and displays detailed information about a given email's validity.

## 🚀 Features

- 🔍 Validates email addresses using the Email Validation API.
- 📋 Displays attributes such as domain, status, score, and validity checks.
- 🎯 Clean, responsive, and user-friendly interface.
- ⏳ Real-time feedback with a loading animation.

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **API**: [EmailValidation.io](https://emailvalidation.io/)  
- **Assets**: SVG icons (`email.svg`, `loading.svg`)

## 📁 Project Structure

```
.
├── index.html              # Main HTML file
├── css/
│   └── style.css           # Styling and layout
├── js/
│   └── index.js            # JavaScript for API interaction and UI updates
├── img/
│   ├── email.svg           # Email icon in the header
│   └── loading.svg         # Spinner shown during loading
├── settings.json           # Live preview configuration
└── README.md               # Project documentation
```

## ⚙️ How It Works

1. The user inputs an email address into the form.
2. On clicking **Submit**, the app:
   - Shows a loading animation.
   - Sends a request to the EmailValidation API.
   - Parses the JSON response.
   - Displays the email validity results on the page.

## 🧪 Sample Output

```
email: example@domain.com
score: 0.76
state: deliverable
domain: domain.com
format_valid: true
smtp_check: true
...
```

## 🖼️ Responsive Design

The application is responsive and adapts well to mobile screens using media queries in `style.css`.

