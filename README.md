# Secure Homelab Web Application
A self-hosted web application built in a homelab environment to study:
 - Backend development (Flask)
 - Linux server configuration
 - Reverse proxy with Nginx
 - Basic security hardening
 - Authentication and session handling

---

## Tech Stack
- Python 3
- Flask
- SQLite
- Nginx
- Ubuntu Server

---

## Architecture

Client (Browser)
      ↓
Nginx (Rever Proxy)
      ↓
Flask Application
      ↓
Database (SQLite)

---

## Security Features
- Password hashing (bcrypt)
- Parameterized queries
- Basic firewall configuration
- SSH root login disable
- -Environment variables for secrets

---

## Hot to Run
1. Clone the repository
2. Create virtual environment
3. Install dependencies:

pip install -r requirements.txt

4. Configure .env file
5. Run:

python run.py

---

## Learning Goals
This project was built to:
- Understand backend architecture
- Practice secure coding principles
- Study web vulnerabilities and mitigation
- Simulate a small production-like environment

---

## Future Improvements
- Docker containerization
- CI/CD pipeline
- PostgreSQL migration
- HTTPS with Let's Encrypt
- Rate limiting
- Logging system
