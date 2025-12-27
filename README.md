# TurnApps Documentation Repository
This repository hosts the source files for the official TurnApps documentation, accessible at [docs.turnapps.f5.si](https://docs.turnapps.f5.si). 
Our goal is to provide a transparent, centralized, and high-performance technical resource for all TurnApps projects, ranging from custom web infrastructures to competitive gaming research.
## 🏗️ Architecture
The documentation is built using **MkDocs** with the **Material theme**, ensuring a lightweight, SEO-friendly, and mobile-responsive experience.
- **Source Format**: Markdown (.md)
- **Deployment**: Automated via GitHub Actions
- **Hosting**: GitHub Pages with a custom subdomain (`docs.turnapps.f5.si`)
## 📂 Repository Structure
```text
.
├── docs/               # Markdown source files
│   ├── index.md        # Ecosystem overview
│   ├── systems/        # Web infrastructure and backend docs
|   |── turnedit/       # TurnEdit documentation
├── mkdocs.yml          # Configuration for the documentation site
└── .github/workflows/  # CI/CD deployment scripts
```
## 🚀 Development & Contribution
To run the documentation locally for testing, ensure you have Python installed:
1. Install dependencies
```
pip install mkdocs-material
```
2. Serve the site locally:
```
mkdocs serve
```
The site will be available at `http://127.0.0.1:8000/`.
## 🛡️ Technical Philosophy
Everything hosted here follows the core TurnApps principles:
- **Privacy by Default**: No tracking or telemetry in our documentation or software.
- **Performance Optimized**: Built and tested on Intel Inside architectures to ensure stability.
- **Transparency**: Detailed technical specifications for all our custom-built systems.
## 📈 Road to 1 Million
This documentation hub is a critical part of the TurnApps infrastructure as we work towards our milestone of 1 million subscribers by December 2026. By providing professional-grade documentation, we aim to build a community founded on technical trust.  
© 2025 TurnApps. Built with passion and precision.
