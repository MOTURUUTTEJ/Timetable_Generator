# Timetable_Generator
# Advanced Multi-Branch Timetable Generator

This is a powerful, zero-dependency web application built with vanilla JavaScript to generate complex, coordinated timetables for multiple university departments. It intelligently handles shared resources and faculty assignments to create conflict-free schedules.

![Timetable Generator Screenshot](https://via.placeholder.com/1280x720.png?text=Timetable+Generator+Screenshot)

> 📸 **Screenshot setup:**
> 1. Take a screenshot of the app after generating a timetable.
> 2. Save it in this repository as `assets/screenshot-placeholder.png` (or update the path above).
> 3. Commit the image so it renders correctly on GitHub.

---

## ✨ Key Features

* **Multi-Department Coordination**: Generate schedules for multiple branches (e.g., CSE, ECE, MECH) simultaneously, ensuring all constraints are met across the board.
* **Smart Faculty Allocation**: Automatically resolves scheduling conflicts for faculty, especially those teaching across different departments or sections.
* **Shared Resource Management**: Efficiently schedules shared resources like computer labs, electronics labs, and the library to prevent overlaps.
* **Dynamic & Customizable**: Easily add or remove sections, subjects, and faculty through an interactive user interface before generation.
* **Cross-Branch Assignments**: A dedicated UI allows you to assign faculty from one department to teach subjects in another, with clear visual indicators.
* **Dual View Mode**: View generated timetables from both a **student** (section-wise) and **faculty** perspective. Includes a search function for faculty schedules.
* **Export & Print**: Export the final timetable data as a JSON file or use the browser's print functionality to save it as a clean, print-friendly PDF.

---

## 🛠️ Tech Stack

* **Frontend**: HTML5
* **Styling**: Tailwind CSS (via CDN)
* **Logic**: Vanilla JavaScript (ES6+)
* **Dependencies**: None!

---

## 🚀 How to Use

1.  Clone the repository or download the `Final_Timetable_Generater.html` file.
2.  Open the HTML file in any modern web browser.
3.  That's it! No build steps, dependencies, or servers are required.

The application will guide you through a simple 3-step process:
1.  **Select** the departments you want to schedule.
2.  **Configure** the number of sections, subjects, and faculty assignments for each selected department.
3.  **Generate** the coordinated timetables and view the results.

---

## ✅ Setup Verification & Testing

Since this is a single-file web app, there is no test runner setup. Use this quick verification checklist after any change:

1. Open `Final_Timetable_Generater.html` in a browser.
2. Select at least two branches and configure sections.
3. Generate timetables and confirm section-wise output appears.
4. Open faculty view and search for a faculty member.
5. Use **Export JSON** and verify a file is downloaded.
6. Use browser print preview to confirm print-friendly formatting.

---

## 🌐 Browser Compatibility

This application is tested for modern evergreen browsers:

- Google Chrome (latest)
- Microsoft Edge (latest)
- Mozilla Firefox (latest)
- Brave (latest)

> Safari should work for core functionality, but print/export rendering should be verified on your target version.

---

## ⚡ Performance Notes

- Best experience on desktop/laptop screens due to dense timetable layout.
- Generation time increases with more branches, sections, and cross-branch faculty constraints.
- For very large configurations, generate once and use JSON export/print instead of repeated runs.
- The app runs fully client-side; performance depends on browser and machine resources.

---

## 🧰 Troubleshooting

**Problem:** Page opens but styles are missing.  
**Fix:** Ensure internet access is available for the Tailwind CDN.

**Problem:** Timetable generation fails or shows an error.  
**Fix:** Verify every subject has an assigned faculty and required fields are not empty.

**Problem:** Print layout looks compressed.  
**Fix:** Use landscape mode and disable browser headers/footers in print settings.

**Problem:** Exported JSON is not downloading.  
**Fix:** Allow downloads/pop-ups for the site and retry.
