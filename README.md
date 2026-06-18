A lightweight, dependency-free password generator built with plain HTML, CSS, and JavaScript. Generates cryptographically secure passwords with adjustable length and character sets, plus a live strength meter.

- Cryptographically secure randomness via the Web Crypto API (`crypto.getRandomValues`), not `Math.random()`
- Adjustable length from 8–30 characters
- Toggle uppercase, lowercase, numbers, and symbols independently
- Guarantees at least one character from every selected category
- Live strength meter (Weak / Medium / Strong)
- Show / hide password toggle
- One-click copy to clipboard, with toast feedback and a fallback for browsers without Clipboard API access
- Fully responsive, keyboard-accessible, zero build step or dependencies

Clone the repo and open `pass.html` in any modern browser:

```bash
git clone https://github.com/Haseena2006/Password_Generator.git
cd Password_Generator
open pass.html  
```

No build tools, package managers, or servers required.


- HTML5 / CSS3
- Vanilla JavaScript (ES6+)
- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts – Poppins](https://fonts.google.com/specimen/Poppins)

MIT — feel free to use, modify, and share.
