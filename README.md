# 🔐 SQL Injection – Security Demo

An educational project demonstrating how **SQL injection attacks** work and how to understand and defend against them. Built with HTML for the front-end interface.

> ⚠️ **Disclaimer:** This project is strictly for **educational purposes**. The code is intended to demonstrate vulnerabilities in a controlled learning environment. Do **not** use this on any real system or application without authorization.

## 📋 About

SQL Injection is one of the most common and dangerous web security vulnerabilities. This project demonstrates:

- How a vulnerable login/input form can be exploited via SQL injection
- What the attack looks like from a front-end perspective
- How developers can recognize and protect against these attacks

## 🛠️ Built With

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

## 📁 Project Structure

```
SQL-injection/
├── frontend.html    # Vulnerable login/input form UI
└── code             # Backend logic demonstrating the vulnerability
```

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/sofsof23/SQL-injection.git
   ```
2. Open `frontend.html` in your browser to view the demo interface.

## 🛡️ How to Prevent SQL Injection

- Use **parameterized queries / prepared statements**
- **Validate and sanitize** all user inputs
- Apply the **principle of least privilege** to database accounts
- Use an **ORM** (Object-Relational Mapper) where possible

## 🧠 What I Learned

- How attackers can manipulate SQL queries through unsanitized input
- The importance of input validation in secure web development
- Best practices for building secure back-end systems

## 📌 Status

> ✅ Complete – educational demo finished.

---

*Made by [@sofsof23](https://github.com/sofsof23)*
