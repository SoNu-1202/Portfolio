# 🎓 Student Developer Portfolio

A modern, responsive, and interactive personal portfolio website designed specifically for a **first-year Computer Science undergraduate and beginner developer**.

Built with **pure HTML5 and CSS3** (no JavaScript dependencies or frameworks required).

---

## 📁 File Structure

```text
/Users/sonu/nst/AI/
├── portfolio.html   # Primary HTML portfolio document (complete structure)
├── portfolio.tml    # Identical copy as specified in requirements
├── styles.css       # Full stylesheet (responsive, dark theme, animations)
└── README.md        # Guide & documentation for easy personalization
```

---

## ✨ Features & Included Sections

1. **Header & Navigation Bar**:
   - Sticky navbar with frosted glassmorphism effect (`backdrop-filter: blur`).
   - Quick navigation links with dedicated Font Awesome icons.
   - Pure CSS mobile hamburger drawer (no JavaScript needed).

2. **Hero Section (Introduction & Overview)**:
   - Live availability status indicator ("🟢 Open to Projects & Internships").
   - Catchy headline, title, bio, and quick metadata pills.
   - Interactive profile card with animated glowing ring, stats counters, and floating tech pills.
   - Direct call-to-action buttons ("Get In Touch", "Explore Portfolio").

3. **Personal Details & About Me**:
   - First-year student story and technical aspirations.
   - Quick facts grid (Name, Level, Languages, Location, Email Status, Availability).
   - 4 focus highlight cards (Web Craftsmanship, DSA, Teamwork, AI Curiosity).

4. **Education Journey**:
   - Interactive vertical timeline with glowing institution markers.
   - University / Undergraduate degree with CGPA and foundational coursework chips.
   - Higher Secondary (12th) & Secondary (10th) school credentials with percentages and honors.

5. **Work Experience & Leadership**:
   - Tailored specifically for freshmen (Student Tech Society Trainee, Club Coordinator, Hacktoberfest Contributor).
   - Key responsibilities, impact metrics, and tech stack tags.

6. **Achievements & Certifications**:
   - 6 recognition cards featuring icons for hackathon finalists, certifications (freeCodeCamp, Python), competitive programming streaks (100+ LeetCode problems), and academic scholarships.

7. **Skills & Proficiencies**:
   - Categorized cards:
     - Frontend & Web Design (with animated progress bars)
     - Programming Languages (Python, C, C++, SQL)
     - Developer Tools & Workflow (Git, GitHub, VS Code, Linux, Figma, DevTools)
     - Core Fundamentals & Soft Skills

8. **Communication & Contact Details**:
   - Direct contact channel cards (Email, Phone/WhatsApp, LinkedIn, GitHub, Location).
   - Interactive styled contact message form.

9. **Footer**:
   - Clean branding, quick links, and a smooth "Back to Top" button.

---

## 🚀 How to View Your Portfolio

### Option 1: Direct File Opening
Double-click `portfolio.html` in your file manager (Finder) or right-click and select **Open With > Google Chrome / Safari / Edge / Firefox**.

### Option 2: Live Server via Terminal
From your terminal, run:
```bash
cd /Users/sonu/nst/AI
python3 -m http.server 3000
```
Then visit `http://localhost:3000/portfolio.html` in your browser.

---

## ✏️ How to Customize Your Details

Open `portfolio.html` in any text editor (VS Code, Sublime, etc.):

- **Name & Title**: Search for `Sonu` or `Hi, I'm` and replace with your name.
- **Email & Phone**: Search for `sonu.cs28@example.com` or `+91 98765 43210` to replace with your contact information.
- **Social Handles**: Update the `href` values inside the `<a class="social-link" ...>` and `channel-card` tags with your actual LinkedIn and GitHub URLs.
- **Education & Grades**: Update the institution name, graduation year, and GPA in the `<section id="education">` block.
- **Icons**: Icons are powered by [Font Awesome 6](https://fontawesome.com/icons). You can swap any icon class (e.g. `fa-solid fa-trophy`) with another icon anytime!
