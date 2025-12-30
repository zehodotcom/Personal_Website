# 🛡️ Hardened Personal Portfolio & DevSecOps Workflow
This repository contains the source code for my professional website: [angel-garcia-soc.netlify.app](https://angel-garcia-soc.netlify.app/).

Unlike a conventional static portfolio, this project has been developed under a **Security by Design** methodology, applying security controls and hardening techniques that are often overlooked in simple web deployments.

## 👨‍💻 About the Project
The goal of this website is to centralize my career as a **Junior SOC Analyst**, my cybersecurity projects, and Blue Team laboratory write-ups (Spear Phishing, PCAP analysis, SIEM, etc.).

## 🔐 Security Features (Hardening)
As a cybersecurity professional, I have implemented the following controls on this site:

* **Secure Coding:** Developed following best practices to prevent common vulnerabilities.
* **DevSecOps Workflow:** Security analysis integrated into the deployment pipeline.
* **SAST (Static Application Security Testing):** Code scanning for exposed secrets and security misconfigurations.
* **Secure Deployment:** Configured on Netlify with optimized security headers and a secure proxy for form handling.

## 🛠️ Tech Stack
* **Frontend:** HTML5 & Tailwind CSS.
* **Security & Ops:** Netlify (Hosting & Forms), Git for version control.
* **Design:** Responsive Design focused on User Experience (UX).

## 📂 Repository Structure
├── _headers            # Security rules (CSP, HSTS, X-Frame-Options)
├── index.html          # Main website structure
├── netlify.toml        # Deployment and redirection configuration
├── README.md           # General project documentation
└── SECURITY.md         # Vulnerability Disclosure Policy (VDP)