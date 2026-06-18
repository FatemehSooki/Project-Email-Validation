# [📧 Email Validation Form](https://fatemehsooki.github.io/Project-Email-Validation/)

A custom-built **Email Validation System** using vanilla JavaScript, focused on understanding **input validation, regex patterns, and basic security checks**.

This project was created as a learning exercise to manually implement email validation logic without relying on external validators or tools, in order to strengthen my understanding of how validation works under the hood.

<img src="Screenshot (1015).png">
---

## ✨ Features

* ⚡ Real-time email validation on submit
* 🔍 Regex-based pattern detection
* 🚫 Protection against script injection attempts (`<script>` detection)
* 📩 Ensures correct email structure (single `@` validation)
* ❌ Blocks invalid characters and non-standard formats
* 🎨 Dynamic UI feedback (error & success states)
* 💡 Clean and responsive form design

---

## 🧠 What I Learned

This project helped me improve my understanding of:

* Regular Expressions (Regex) in real-world validation
* Input sanitization and basic security considerations
* Detecting malicious input patterns (basic XSS prevention)
* DOM manipulation and class-based UI updates
* Form validation logic without external libraries

---

## 🛡️ Validation Rules

The email input is considered invalid if:

* It is empty
* It contains `<script>` or encoded script attempts
* It contains more than one `@`
* It contains invalid special characters
* It contains Persian/Arabic characters
* The `@` is placed in an invalid position

---

## 🛠️ Built With

* HTML5
* CSS3 (Modern UI + Glassmorphism-inspired design)
* Vanilla JavaScript
* Regular Expressions (Regex)

---

## 🎯 Purpose of This Project

The goal was to understand how email validation systems work internally and to practice writing validation logic manually without using external libraries or regex generators.

All validation logic was implemented from scratch without relying on tools like regex generators or pre-built validators.

---

## 🚀 Future Improvements

* More advanced RFC-compliant email validation
* Domain verification (DNS / MX check simulation)
* Debounced real-time validation
* Better accessibility support
* Multi-language error messages
* Visual validation indicators per rule

---

## 📌 Notes

This project focuses on learning and experimentation, not production-level validation security.

---

## 👩🏻‍💻 Developer

- Fatemeh Sooki
- Role - Frontend

- Created - 2026-06-18

- Mentor: [Parsa Ghorbanian](https://www.instagram.com/parsa_ghorbanian_web?igsh=MXQydDAxMW05ZjgyYg==)


- How to reach me : with my [instagram](https://www.instagram.com/fatemeh_sooki?igsh=MXM4ZHBrNW55bmF0cQ==) and [linkedin](https://www.linkedin.com/in/fatemeh-sooki-197060396?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
