# 🔐 ThreatModeller: Automated Threat Modeling for Open Source

ThreatModeller is a lightweight, open-source tool designed to automatically generate basic threat models from public GitHub repositories and websites. Built with simplicity and zero-cost infrastructure in mind, ThreatModeller provides open-source projects and startups with immediate insights into security risks and common vulnerabilities related to their technology stacks.

## ✨ Features

- **Automated Technology Stack Detection**
  - Extracts programming languages, dependencies, and frameworks directly from GitHub repositories.
  - Identifies website technologies through advanced fingerprinting techniques.

- **Instant Threat Mapping**
  - Matches detected technologies against known threats (OWASP Top 10, CWE).
  - Provides actionable recommendations and remediation guidelines.

- **Simple Reporting**
  - Generates clean, readable threat model reports in Markdown and PDF formats.

- **Completely Open Source & Free**
  - Built entirely on free, open-source software and APIs.
  - Hosted on GitHub and Streamlit Cloud, ensuring zero cost for users.

## 🚀 Quick Start

### Requirements

- Python 3.8+

### Installation

Clone this repository:

```bash
git clone https://github.com/yourusername/threatmodeller.git
cd threatmodeller
```

Install dependencies:

```bash
pip install -r requirements.txt
```

### Usage

**Analyze a GitHub Repository:**

```bash
python threatmodeller.py --github https://github.com/exampleuser/exampleproject
```

**Analyze a Website:**

```bash
python threatmodeller.py --website https://example.com
```

Your generated threat model will be saved as `threat_report.md` and optionally as a PDF file.

## 🛠️ Technology Stack

- **Python**
- **PyGithub** (GitHub API integration)
- **python-Wappalyzer** (Website stack detection)
- **WeasyPrint** (PDF generation)

## 🌟 Future Roadmap

- Integration with vulnerability databases (NVD, OSV)
- Interactive web-based interface (using Streamlit)
- Automated dependency vulnerability checks

## 🤝 Contributing

Contributions are highly encouraged! To contribute:

1. Fork this repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Submit a Pull Request.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Made with ❤️ for open-source communities.

