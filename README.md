# 🧮 Calculator Suite

> A collection of five purpose-built calculators — from basic arithmetic to financial analysis and graphing — unified under a single polished landing page.

---

## Overview

Calculator Suite is a client-side web application built with vanilla HTML, CSS, and JavaScript. No frameworks, no dependencies, no build tools. Every calculator is a standalone `.html` file that works by opening it directly in a browser.

---

## Calculators

| Calculator | File | Key Features |
|---|---|---|
| Basic | `BasicCalculator.html` | Arithmetic, expression history, keyboard support |
| Desk (Multi-Function) | `Multi-FunctionCalculator.html` | Memory registers, GT, MU, √, % |
| Scientific | `ScientificCalculator.html` | sin/cos/tan, log/ln, π, e, xʸ, x², √, n! |
| Graphing | `GraphingCalculator.html` | Multi-function plot, zoom & pan, curve tracing, axis labels |
| Financial | `FinancialCalculator.html` | TVM, loan/amortization, compound interest, tip split, 33-currency converter |

---

## How to Use

No installation required.

1. Clone the repository:
   ```bash
   git clone https://github.com/WillSlowhike/calculator-suite.git
   ```

2. Open `index.html` in any modern browser:
   ```bash
   open index.html
   ```

3. Navigate to any calculator from the landing page.

All files are self-contained. No server, no build step, no internet connection required — except the Financial Calculator's currency converter, which fetches live rates from the [Frankfurter API](https://www.frankfurter.app/) (European Central Bank data, free, no key needed). A fallback with reference rates is used if the fetch fails.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts (Orbitron, DM Mono, Syne, Playfair Display, Fraunces, JetBrains Mono, IBM Plex Mono, Lora) |
| Currency API | [Frankfurter](https://www.frankfurter.app/) — free, no key, ECB data |

---

## File Structure

```
calculator-suite/
├── index.html                    # Landing page
├── BasicCalculator.html          # Basic 4-function calculator
├── Multi-FunctionCalculator.html # Desk-style calculator with memory
├── ScientificCalculator.html     # Scientific calculator
├── GraphingCalculator.html       # Graphing calculator
├── FinancialCalculator.html      # Financial calculator
├── README.md
└── screenshots/                  # (add your own)
```

---

## Roadmap

Potential additions for future versions:

- [ ] Unit converter (length, weight, temperature, volume)
- [ ] Matrix calculator
- [ ] Statistics calculator (mean, median, standard deviation)
- [ ] Dark/light mode toggle on each calculator
- [ ] PWA support (installable, offline-ready)
- [ ] Mobile-optimized layouts

---

## Contributing

Contributions are welcome for bug fixes and improvements. To contribute:

1. Fork the repository
2. Create a new branch: `git checkout -b fix/your-fix-name`
3. Make your changes
4. Submit a pull request with a clear description of what changed

Please do not submit pull requests that copy or redistribute the design or code to a separate project — see the license section below.

---

## License

© 2026 WillSlowhike. All Rights Reserved.

This project and all its source code, design, and assets are the intellectual property of WillSlowhike. You may view and fork this repository for personal, non-commercial reference only.

**You may not:**
- Redistribute, resell, or republish this project or any part of it
- Use the design or code as the basis for a public or commercial product
- Remove or alter the copyright notices in any file

For licensing inquiries, open an issue or contact via GitHub.

---

## Author

**WillSlowhike**
GitHub: [@WillSlowhike](https://github.com/WillSlowhike)
