# OWASP MASVS v2 Checklist

An interactive tool for performing mobile application security audits following the **OWASP Mobile Application Security Verification Standard (MASVS) v2.0** and the **MASTG v1.7.0**.

🔗 **[Open the tool →](https://llucloh.github.io/masvs-web-checklist/)**

---

## What is this?

This checklist covers the 7 security domains of MASVS v2 along with all their associated controls and MASTG tests:

| Domain | Description |
|---|---|
| MASVS-STORAGE | Secure data storage (data-at-rest) |
| MASVS-CRYPTO | Cryptographic best practices |
| MASVS-AUTH | Authentication & authorization |
| MASVS-NETWORK | Secure network communication |
| MASVS-PLATFORM | Platform interaction & WebViews |
| MASVS-CODE | Code quality & update mechanisms |
| MASVS-RESILIENCE | Anti-reversing & tampering |

## Features

- **No installation required** — runs directly in your browser
- **Local progress** — data is securely saved in `localStorage`, no servers involved
- **Android & iOS** — filter tests dynamically by platform
- **Search functionality** — look up tests instantly by ID or name
- **Control-specific notes** — document evidences and findings
- **Flexible exporting** — download your assessment as JSON or Markdown
- **Print-ready** — generate high-quality PDF reports straight from the browser
- **Multi-project management** — easily save, load, and switch between different audits

## How to Use

1. Open the tool using the link above.
2. Enter your project name (the target application under audit).
3. Check off the MASTG tests as you complete them.
4. Add custom notes with evidence for each control.
5. Export the final results in Markdown to include them in your security report.

> Your progress is saved automatically in your browser. Each student maintains their own independent data.

## For Instructors

Every student works with their own local copy of the data. No accounts or logins are required. To submit the final audit, students can:

- Export the **JSON** file (raw data for verification)
- Export the **Markdown** file (human-readable format for reports)
- Use **Print → PDF** straight from the browser

## Reference Standards

- [OWASP MASVS v2.0.0](https://mas.owasp.org/MASVS/)
- [OWASP MASTG v1.7.0](https://mas.owasp.org/MASTG/)
- [mas.owasp.org](https://mas.owasp.org)

## Running Locally

No server required. Simply clone the repository, download the `index.html` file, and open it in any web browser:

```bash
git clone [https://github.com/llucloh/masvs-checklist.git](https://github.com/llucloh/masvs-checklist.git)
cd masvs-checklist
open index.html   # macOS
# or double-click index.html on Windows/Linux
