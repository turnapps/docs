# Systems Architecture
The TurnApps web ecosystem is designed to be a high-performance, secure, and developer-centric platform. Unlike standard template-based websites, our infrastructure is custom-built to support the integration of software distribution, community forums, and technical documentation.
## 🏗 Backend Architecture
The core of `turnapps.f5.si` and its subdomains is built with a focus on stability and speed, leveraging Intel-based hardware for efficient processing.
Custom Web Stack
- Language & Logic: Built using PHP and structured SQL for robust data management and fast response times.
- Database Management: Optimized relational databases designed to handle forum threads, user authentication, and project metadata with minimal latency.
- Server Environment: Hosted on environment-specific configurations to ensure 24/7 availability for TurnEdit 2.0 installers and documentation.
- Hosting: We are using "Shin Cloud for Free" and Github Pages, it is provided by XServer and GitHub.
## 🛡 Security & Integrity
Security is not an afterthought at TurnApps; it is integrated into the system's DNA.
1. Data Integrity
We utilize SHA-256 hashing algorithms for verifying software integrity. This ensures that every byte of `turnedit-setup.exe` downloaded from our systems is identical to the original build.
2. Defensive Programming
Our backend implements strict protection against common web vulnerabilities, including:
- Path Traversal Protection: Preventing unauthorized access to the server's file system.
- Input Validation: Strict sanitization of all user-provided data within the TurnApps forum.
## 🌐 Subdomain Infrastructure
TurnApps utilizes a multi-layered subdomain strategy to keep services organized and scalable:
| Subdomain | Purpose |
| --- | --- |
| `turnapps.f5.si` | Main portal, News, and Community Forums. |
| `docs.turnapps.f5.si` | Documentation and references (Powered by MkDocs). |
| `github.com/turnapps` | Source code hosting and Release distribution. |
## 🚀 Automation & Deployment
To maintain our goal of reaching 1 Million subscribers by 2026, we automate our technical workflows to focus on content and development:
- **CI/CD Pipeline**: Documentation is automatically built and deployed via GitHub Actions whenever changes are pushed to the main repository.
- **Static Site Generation**: We use MkDocs to convert Markdown into high-speed, SEO-friendly static pages, ensuring that Google can index our technical updates instantly.
