# Timetable_Generator

## Advanced Multi-Branch Timetable Generator

A zero-dependency, single-file web app that generates coordinated timetables for multiple departments while balancing section, faculty, and shared-resource constraints.

![Timetable Generator UI](https://github.com/user-attachments/assets/e4bf7098-6f3a-4ffa-9c02-4464e1201295)

---

## ✨ Features

### For Students / Section Coordinators
- Generate section-wise timetables for multiple branches in one run.
- View clear period/day tables for each section.
- Support for theory, labs, sports, and library periods.
- Regenerate timetables quickly when configuration changes.

### For Faculty / Department Teams
- Dedicated **Faculty Timetables** view with branch-wise grouping.
- Faculty search to quickly find an individual teaching schedule.
- Cross-branch assignment support for shared/visiting faculty.
- Conflict-aware scheduling across selected branches.

### Export & Print
- **Export JSON** for record keeping, analytics, or later processing.
- **Print / Save as PDF** for distribution and notice-board usage.
- Print styles optimize readability in black-and-white output.

---

## 🧰 Tech Stack

- **Frontend:** HTML5
- **Styling:** Tailwind CSS (CDN)
- **Logic:** Vanilla JavaScript (ES6+)
- **Build tools:** None

---

## 🚀 Setup & Run (Detailed)

### Prerequisites
- A modern browser (Chrome, Edge, Firefox, Safari).
- Internet access on first load (for Tailwind and Google Fonts CDNs).

### Option 1: Run from Git
1. Clone the repository:
   ```bash
   git clone https://github.com/MOTURUUTTEJ/Timetable_Generator.git
   ```
2. Open the project folder.
3. Open `Final_Timetable_Generater.html` in your browser.

### Option 2: Run from Downloaded File
1. Download `Final_Timetable_Generater.html`.
2. Double-click the file (or open it with your browser).

No installation, package manager, or server setup is required.

---

## 📖 How to Use

1. Click **Get Started**.
2. Select one or more branches.
3. Configure branch details:
   - Section names and incharges
   - Subject list
   - Faculty assignments
   - Cross-branch assignments (optional)
4. Use **Save & Next Branch** until all selected branches are configured.
5. Click **Generate Coordinated Timetables**.
6. Switch between:
   - **Student Timetables**
   - **Faculty Timetables** (with faculty search)
7. Use:
   - **Export JSON** for data export
   - **Print / Save as PDF** for printable output
   - **Regenerate** to generate a new arrangement

---

## 🌐 Browser Compatibility

Tested/recommended on latest versions of:
- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

For best results, keep the browser updated.

---

## 🛠️ Troubleshooting

### App opens but looks unstyled
- Cause: CDN resources (Tailwind/Google Fonts) did not load.
- Fix: Check internet connection and refresh the page.

### Generate button does not produce expected output
- Verify each selected branch has valid section/subject/faculty values.
- Ensure you saved branch configuration using **Save & Next Branch**.

### Faculty timetable appears empty for a person
- Check spelling consistency in faculty names across assignments.
- Confirm the faculty is assigned to at least one subject/section.

### Print/PDF layout issues
- Use browser print settings:
  - Paper size: A4/Letter
  - Scale: Default or Fit to page
  - Margins: Default/Minimum
- Prefer Chrome/Edge for consistent print rendering.

### JSON export not downloading
- Browser may block automatic downloads.
- Allow downloads for the page and try again.

---

## ⚡ Advanced Tips

- Use **Faculty Timetables** + search to quickly audit individual load distribution.
- Use **Regenerate** multiple times and compare outputs to choose the best distribution.
- Use **Start Over** to reset all state cleanly when doing a fresh planning cycle.
- Keyboard/browser productivity:
  - `Ctrl/Cmd + P`: Print dialog (alternative to Print button)
  - `Ctrl/Cmd + F`: Find text on the page

---

## ❓ FAQ

### Is there a backend/database?
No. The app runs entirely in-browser as a standalone HTML file.

### Can I deploy this on hosting platforms?
Yes. Since it is static, you can host it on GitHub Pages, Netlify, Vercel, or any static host.

### Does this guarantee zero conflicts in every scenario?
The generator is conflict-aware and designed to minimize collisions across branches/resources, but very constrained custom inputs can still require manual review.

### Can I customize default branches and subjects?
Yes. Edit the JavaScript configuration in `Final_Timetable_Generater.html`.

---

## 🤝 Contributing

Contributions are welcome. Please see `CONTRIBUTING.md` for development and PR guidelines.

## 📄 License

This project is licensed under the MIT License. See `LICENSE` for details.
