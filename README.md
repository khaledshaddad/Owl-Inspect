# Owl-Inspect

### 🦉 Description

Owl-Inspect is a GUI-based reconnaissance tool that performs passive security inspection on web targets. It detects missing headers, outdated libraries, mixed content, and exposed data, helping security researchers quickly analyze website configurations.

---

## Key Features

* GUI-based web inspection using Tkinter.
* Detects missing security headers (CSP, HSTS, X-Frame-Options, etc.).
* Scans for outdated JS/CSS libraries.
* Finds mixed content and insecure links.
* Identifies hidden input fields and sensitive data in HTML comments.
* Performs basic directory and server fingerprinting.
* Passive subdomain discovery.

---

## Requirements

* Python 3.8+
* Modules: `requests`, `beautifulsoup4`
* Tkinter (system package may be required)

Install dependencies:

```bash
pip install requests beautifulsoup4
```

---

## Usage

1. Run the GUI:

```bash
python3 owl_inspect.py
```

2. Enter the target URL and click **Run Full Inspection**.
3. Explore scan results using the GUI buttons:

   * HTML Structure
   * Inspect Sensitive Data
   * Network/Security Headers
   * External Sources
   * Console/CSP/CORS
   * Advanced Recon (4 in 1)

---

## License

MIT License
