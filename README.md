# Password Hash Generator

**Password Hash Generator** is an enterprise-grade web application for analyzing password security and generating cryptographic hashes. Designed for professional and personal use, it combines password strength analysis, secure password generation, and multi-algorithm hash calculation in a modern, responsive, and installable (PWA) interface.

## Features

- **Password Analysis:**  
  - Enter any password to receive a detailed analysis including strength indicators, entropy calculation, character type breakdown, and tailored security recommendations.
  - Identifies weaknesses such as short length, lack of character variety, repeated or common patterns, and dictionary words.

- **Password Generation:**  
  - Generate secure passwords of configurable length (8–128 characters).
  - Select character sets: lowercase, uppercase, numbers, and symbols.
  - Ensures generated passwords meet industry security standards.

- **Cryptographic Hash Functions:**  
  - Instantly computes hashes for MD5, SHA-1, SHA-256, SHA-384, and SHA-512.
  - Uses the Web Crypto API for security on HTTPS; robust JavaScript fallbacks for HTTP environments.
  - Copy hash results easily to the clipboard.

- **Security Recommendations:**  
  - Provides actionable tips to improve password security based on analysis.
  - "Secure Password" button automatically strengthens a weak password to professional standards (length, complexity, randomness).

- **Progressive Web App (PWA):**  
  - Fully installable on desktop and mobile devices.
  - Offline support via Service Worker and caching.
  - Custom manifest and icons for app-like experience.
  - Install prompt and status indicator.

- **Modern UI:**  
  - Responsive, accessible design with dark-light contrast and clear visual feedback.
  - Easy mode switching between password analysis and generation.
  - Copy buttons for both passwords and hashes.

## Technologies

- **HTML5, CSS3, JavaScript (Vanilla)**
- **Web Crypto API** for cryptographic operations (with pure JS fallbacks)
- **Service Worker** for offline capability
- **PWA Manifest** and dynamic icons (SVG embedded)
- No external dependencies or frameworks

## Usage

1. **Analyze Password:**  
   - Enter a password in "Analyze Password" mode.
   - View analysis, entropy, character types, and security tips.
   - Copy password or strengthen it with "Secure Password".

2. **Generate Password:**  
   - Switch to "Generate Password" mode.
   - Configure length and character sets.
   - Generate and copy a secure password.

3. **View Hashes:**  
   - After analysis or generation, view cryptographic hashes in all supported algorithms.
   - Copy any hash value.

4. **Install as App:**  
   - Click "Install App" if prompted, or use your browser’s install option.
   - Works fully offline once installed.

## Security Notes

- All hashing and password operations are performed locally in the browser.
- No data is sent to any server.
- For best security and full cryptographic support, use over HTTPS.

## Author

Developed by **NetIRC**

---

> _Enterprise-grade password security analysis and cryptographic hashing.  
> Modern, fast, secure, and installable as a PWA._
