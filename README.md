# Secure-Password-Toolkit
A powerful, web-based and CLI-enabled tool designed for **password strength analysis** and **custom wordlist generation** — perfect for ethical hacking, security testing, and password research.

website : https://securepass0.lovable.app/

# 🔐 Secure Password Toolkit
Built with **React, TypeScript, and Vite** (for web UI) and **Python** (for CLI version).  
It provides real-time password entropy analysis, crack-time estimation, and advanced wordlist generation based on user inputs like names, dates, and patterns.

## 🚀 Features

### 🧩 Password Strength Analyzer
- Real-time strength analysis with **entropy calculations**
- Uses **zxcvbn** or custom entropy logic
- Strength scoring: *Weak → Very Strong*
- Crack-time estimation based on entropy and attack method
- Requirement checks:
  - Minimum length (8+ characters)
  - Uppercase / lowercase mix
  - Numbers and special characters
  - Common-pattern detection

### 🧰 Custom Wordlist Generator
- Accepts multiple input sources: name, birthdate, pet name, custom words
- Generates 12+ variation patterns:
  - Capitalized, lowercase, UPPERCASE, aLtErNaTiNg cAsE  
  - **Leetspeak** transformations (`l33t sp34k`)
  - Prefix / suffix patterns (`_-.~`)
  - Append **years** (30 back → 5 forward)
  - Append **numbers** (0 – 999)
  - Special-character additions (`!@#$%&*`)
  - Reverse / double-character patterns
  - Combined-word permutations
- **Live preview** of generated variations
- **Export** complete wordlists to `.txt` format for password-cracking tools
- Batch generation with thousands of permutations

---

## 🧠 Technologies Used

### 🌐 Web Application
- **Language:** TypeScript (v5.8.3)  
- **Framework:** React (v18.3.1) + Vite (v5.4.19)  
- **Styling:** Tailwind CSS (v3.4.17)  
- **UI Components:** shadcn/ui + Radix UI Primitives  
- **Routing & State:** React Router DOM (v6.30.1), TanStack Query (v5.83.0)  
- **Form Handling:** React Hook Form (v7.61.1) + Zod (v3.25.76)  
- **Icons & Utilities:** Lucide React, clsx, tailwind-merge, class-variance-authority  
- **Charts & Visuals:** Recharts, Embla Carousel  
- **Theming:** next-themes (Dark/Light mode support)  
- **Notifications:** Sonner (v1.7.4)

### 🐍 CLI / Backend (Optional)
- **Language:** Python 3.x  
- **Libraries:**  
  - `argparse` – Command-line interface  
  - `zxcvbn-python` – Password strength estimation  
  - `nltk` – Natural language processing for tokenization  
  - `itertools` – Pattern generation and combinations

### ⚙️ Build & Deployment
- **Build Tools:** Vite, ESLint, TypeScript  
- **Deployment Options:** Vercel, Netlify, GitHub Pages, or any static host  
- **Version Control:** Git + GitHub


⚠️ Disclaimer

This project is provided as-is for educational and authorized security testing purposes only. The authors and contributors are not responsible for any misuse, damage, or legal consequences arising from the use of this tool. You are solely responsible for ensuring you have permission to test any target systems and comply with applicable laws.
