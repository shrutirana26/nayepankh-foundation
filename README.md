🕊️ NayePankh Foundation — Website Redesign
> **Web Development Internship Project**  
> A modern, responsive redesign of [nayepankh.com](https://nayepankh.com) built with pure HTML, CSS, and JavaScript — no frameworks, no dependencies, just clean code.
![NayePankh Foundation](https://images.unsplash.com/photo-1488521787991-ed7bbaae773c?w=1200&q=80)
---
🌐 Live Demo
🔗 https://shrutirana26.github.io/nayepankh-foundation/
> Hosted on GitHub Pages — no build step, instant deploy.
---
📋 Project Overview
This project is a complete UI/UX redesign of the NayePankh Foundation website as part of a web development internship.  
NayePankh is a UP Government registered, 80G & 12A certified NGO based in Kanpur, India — one of the largest student-led organizations in the country, having helped over 2,00,000 underprivileged individuals.
Why a Redesign?
The goal was to create a professional, modern website that:
Clearly communicates NayePankh's mission and impact
Converts visitors into volunteers and donors
Works beautifully on every device
Loads fast with zero external framework overhead
---
✨ Features
UI / UX
Feature	Details
📱 Responsive Design	Mobile-first, works on all screen sizes
🌙 Dark Mode Toggle	Persists via `localStorage`
🎨 Modern Design System	Saffron & sky-blue palette, Playfair Display + Inter typography
⚡ Smooth Scrolling	Native CSS `scroll-behavior: smooth`
🎞️ Scroll Animations	`IntersectionObserver`-powered reveal effects
🖱️ Hover Effects	Cards, gallery, buttons, nav links
🔝 Scroll-to-Top Button	Appears after 400px scroll
Sections
Responsive Navbar — transparent on hero, solid on scroll, hamburger menu on mobile
Hero Section — full-screen with mission statement, animated counters, program cards
Media Strip — press/recognition logos
Impact Statistics — animated counter (2L+ beneficiaries, 30K+ interns, etc.)
About NayePankh — story, certifications (UP Govt, 80G, NITI Aayog)
Programs & Initiatives — 6 program cards (Food, Education, Hygiene, Clothing, Internships, Health)
Image Gallery — CSS Grid bento layout with hover overlays
Volunteer Registration — full form with client-side validation & success state
Donation Section — 3 tiered donation cards with dark glassmorphism theme
Contact Section — contact info + contact form with validation
Footer — 4-column layout, social links, quick links
JavaScript (Vanilla)
Navbar scroll detection
Hamburger menu toggle
Dark mode toggle with `localStorage` persistence
`IntersectionObserver` for staggered reveal animations
Animated number counters (smooth easing)
Full form validation with inline error messages
Success state on form submission
---
🛠️ Tech Stack
```
HTML5       — Semantic markup, accessibility attributes
CSS3        — Custom properties (tokens), Grid, Flexbox, animations
JavaScript  — Vanilla ES6+, IntersectionObserver API, localStorage
Fonts       — Google Fonts (Playfair Display, Inter)
Icons       — Font Awesome 6.5
Images      — Unsplash (replace with real NGO photos)
```
No React. No Vue. No Tailwind. No Bootstrap.  
Just clean, well-structured vanilla code — perfect for understanding fundamentals.
---
📂 File Structure
```
nayepankh-redesign/
│
├── index.html          ← Entire website (single-file)
└── README.md           ← This file
```
> The project is intentionally a single HTML file for simplicity and easy deployment.  
> CSS and JS are embedded in `<style>` and `<script>` tags respectively.
---
🚀 Deployment
Option 1 — Netlify (Recommended, ~1 min)
Go to netlify.com → Sign up free
Drag and drop your `index.html` onto the Netlify dashboard
You'll get a live URL instantly (e.g. `https://nayepankh-xyz.netlify.app`)
Optional: Add a custom domain in Site Settings
Option 2 — Vercel (~2 min)
```bash
# Install Vercel CLI
npm i -g vercel

# From the project folder
vercel

# Follow prompts → your site is live!
```
Option 3 — GitHub Pages (~3 min)
Create a new GitHub repository (e.g. `nayepankh-redesign`)
Upload `index.html` and `README.md`
Go to Settings → Pages
Source: Deploy from a branch → `main` → `/ (root)`
Save → Your site is live at `https://yourusername.github.io/nayepankh-redesign`
---
🖥️ Local Development
No build step needed:
```bash
# Clone the repo
git clone https://github.com/yourusername/nayepankh-redesign.git
cd nayepankh-redesign

# Open directly in browser
open index.html

# Or use a local server (recommended)
npx serve .
# or
python3 -m http.server 8080
```
---
🎨 Design Decisions
Color Palette
Token	Hex	Usage
`--saffron`	`#F47B20`	Primary CTA, accents
`--saffron-d`	`#D4610A`	Hover states
`--sky`	`#1A78C2`	Secondary elements
`--leaf`	`#2E7D52`	Success, certifications
`--gold`	`#E5A500`	Logo gradient
`--ink`	`#1A1A2E`	Body text
Typography
Display: Playfair Display (800 weight) — warmth, trust, Indian editorial tradition
Body: Inter (300–700) — clarity, readability at all sizes
Design Signature
The saffron-to-dark gradient hero, inspired by the Indian flag's colors, grounds the NGO's identity in national pride while the glassmorphism card cluster communicates modern, youth-led energy.
---
📸 Replacing Images
All images currently use Unsplash placeholders. To use real NayePankh photos:
Find `<img src="https://images.unsplash.com/...">` in `index.html`
Replace the `src` with your actual image path or URL
Update the `alt` text to describe the real photo
---
♿ Accessibility
All images have descriptive `alt` attributes
Buttons have `aria-label` attributes
Color contrast meets WCAG AA
Keyboard navigable (focus states visible)
`prefers-reduced-motion` respected
---
📝 Customization
To update NGO details, search for and replace these in `index.html`:
Find	Replace with
`+91 83185 00748`	Your phone number
`info@nayepankh.com`	Your email
`Kanpur, Uttar Pradesh`	Your location
Counter target numbers	Your real stats
---
🤝 About NayePankh Foundation
NayePankh Foundation is a UP Govt. registered NGO (80G & 12A certified, NITI Aayog listed)  
working to uplift India's underprivileged communities through:
🍱 Food distribution to the homeless & stray animals
📚 Free education for underprivileged children
🌸 Sanitary napkin distribution & hygiene awareness
👕 Clothing drives for poor families
💻 Internship programs for 30,000+ students
🏥 Free health camps
Website: nayepankh.com  
Phone: +91 83185 00748  
Featured in: The Pioneer · Dainik Jagran · Hindustan
---
👨‍💻 Internship Project Info
Field	Details
Project Type	Web Development Internship
Organization	NayePankh Foundation
Technology	HTML · CSS · JavaScript
Duration	[Your internship duration]
Intern	[Your Name]
Intern ID	[Your ID]
---
📄 License
This project is built for NayePankh Foundation's web development internship program.  
All original code is open for educational use. NGO branding belongs to NayePankh Foundation.
---
<p align="center">
  Made with ❤️ for a better India<br/>
  <strong>NayePankh Foundation — Giving Wings to the Underprivileged</strong>
</p>
