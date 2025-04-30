# <p align="center">Google Dorking: An In-Depth Guide</p>

<p align="center"></p>

---

## 🧠 Introduction

**Google Dorking** — also known as **Google hacking** — is a powerful search technique that leverages advanced Google operators to find sensitive, hidden, or specific information across publicly indexed websites.

> ⚠️ This guide is intended for **ethical and educational use only**. Do not exploit or misuse the information you discover.

Professionals and researchers use Google Dorking for:

- 🔍 Open Source Intelligence (OSINT)
- 🛡️ Reconnaissance during penetration testing
- 🧠 Competitive and market analysis
- 🕵️ Research and investigative journalism

---

## 🛠️ Understanding Google Dorking

At its core, Google Dorking is about asking the right questions using the right filters.

By combining keywords with search operators, you can uncover:

- 📂 Exposed directories and backup files  
- 📝 Misconfigured or forgotten documents  
- 🔐 Login portals or admin panels  
- ⚙️ System configuration files  
- 📸 Public IP camera feeds  

> These results come directly from Google’s search index — meaning they are **publicly accessible** and have **not** been hacked or illegally obtained.

---

## 🔍 Common Google Dorking Operators

| Operator       | Description                                 | Example                                 |
|----------------|---------------------------------------------|-----------------------------------------|
| `site:`        | Search within a specific website or domain  | `site:example.com`                      |
| `filetype:`    | Find specific file types (e.g., PDF, DOCX)  | `filetype:pdf site:.edu syllabus`       |
| `intitle:`     | Pages with certain words in the title tag   | `intitle:"login"`                       |
| `inurl:`       | URLs that contain specific terms            | `inurl:admin`                           |
| `intext:`      | Search for specific words in page content   | `intext:"confidential"`                 |
| `cache:`       | View Google's cached version of a page      | `cache:example.com`                     |
| `ext:`         | Same as filetype: — file extension filter   | `ext:sql`                               |
| `* (wildcard)` | Match any keyword or phrase                 | `intitle:"index of" *.log`              |

💡 *Tip: Combine multiple operators to increase search precision and effectiveness.*

---

# 📁 Discover Open Directories

The following advanced Google Dorking queries can help identify open directories, exposed files, and other sensitive information:

- **Backup Files**: `intitle:"index of" "backup"`
- **Database Passwords**: `filetype:env intext:DB_PASSWORD`
- **View Index Pages**: `inurl:"view/index.shtml"`
- **Admin Panels**: `site:example.com inurl:admin filetype:php`
- **SQL Files**: `intitle:"index of" "*.sql"`
- **LinkedIn Profiles**: `site:linkedin.com/in "cybersecurity analyst" "Nashville"`

These queries are useful for:
- OSINT investigations
- Social engineering assessments
- Job prospecting

> **Note**: Please use these techniques responsibly.

---

## ⚖️ Legal and Ethical Considerations

Although Google Dorking queries access publicly indexed content, it’s essential to use them ethically and within legal boundaries.

### Risks:
- **Private or Sensitive Data**: You may come across data that was posted unintentionally, such as personal info, credentials, or backups.
- **Exposed Credentials**: Google Dorking can help reveal exposed passwords or misconfigured systems.

### Potential Legal Violations:
Misusing Google Dorking techniques may violate laws, including:
- **Computer Fraud and Abuse Act (CFAA)**
- **Privacy Laws** (e.g., **GDPR**, **HIPAA**)
- **Terms of Service** for websites and platforms

### Best Practices:
- ✅ **Get authorization** before performing assessments.
- ✅ **Avoid exploiting vulnerabilities** without permission.
- ✅ **Report findings ethically** to inform, educate, or resolve issues.

---

## 📚 Resources

Here are some helpful resources to learn more about Google Dorking and its ethical use:

- 🔍 [Google Hacking Database (Exploit-DB)](https://www.exploit-db.com/google-hacking-database)
- 📘 [Google Search Operators (Google Support)](https://support.google.com/websearch/answer/2466433?hl=en)
- 🛡️ [Infosec Institute Guide](https://www.infosecinstitute.com/)
- 🖼️ [SANS Google Hacking Poster](https://www.sans.org/posters/google-hacking)

---

## 👤 Author

**Giuseppe Scalzo**  
Cybersecurity Enthusiast & Learner

- 📧 [GScalzo21@gmail.com](mailto:GScalzo21@gmail.com)  
- 🌐 [GitHub: GScalzo21](https://github.com/GScalzo21)

⭐ If you found this guide helpful, consider starring the GitHub repo or connecting!
