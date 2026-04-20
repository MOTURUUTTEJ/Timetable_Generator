# Timetable_Generator

## Advanced Multi-Branch Timetable Generator

A zero-dependency web application (HTML + Tailwind + Vanilla JavaScript) to generate coordinated, conflict-aware timetables for multiple departments.

![Timetable Generator UI](https://github.com/user-attachments/assets/983b0f67-2450-4aee-b1ca-d593f69dd4d8)

---

## ✨ Features

- Multi-department timetable generation
- Faculty conflict handling across branches
- Shared resource scheduling (labs/library)
- Configurable sections, subjects, and faculty mapping
- Cross-branch faculty assignment support
- Student view and faculty view with search
- JSON export and print-friendly output

---

## 🛠️ Tech Stack

- **Frontend:** HTML5
- **Styling:** Tailwind CSS (CDN)
- **Logic:** Vanilla JavaScript (ES6+)
- **Build tools:** None required

---

## 🚀 Quick Start

1. Clone/download this repository.
2. Open `./Final_Timetable_Generater.html` in a browser.
3. Configure departments and generate timetables.

---

## ⚙️ Configuration Options

You can configure these in the app before generation:

- **Departments/Branches** to include
- **Section count and section names** per department
- **Section in-charge names**
- **Subjects offered** per section/branch
- **Faculty mapping** for each subject
- **Cross-branch faculty assignments**
- **View mode** (Student/Faculty)
- **Faculty search** in generated schedules

---

## 🌐 Browser Compatibility

Tested/expected to work on modern browsers:

- Google Chrome (latest)
- Microsoft Edge (latest)
- Mozilla Firefox (latest)
- Brave (latest)

> Recommended: keep browser updated for best JavaScript and print behavior.

---

## 🧪 Testing

This repository currently has no automated test framework.

### Manual test checklist

1. Open the app and select multiple departments.
2. Add/edit sections, subjects, and faculty assignments.
3. Add at least one cross-branch assignment.
4. Generate timetable and confirm no obvious conflicts.
5. Switch between student and faculty views.
6. Search for a faculty member.
7. Export JSON and verify file content is downloaded.
8. Use browser Print Preview and confirm layout readability.

---

## 💡 Examples / Use Cases

- **College timetable planning:** Generate section-wise and faculty-wise schedules across departments.
- **Department-level planning:** Simulate subject/faculty changes before finalizing.
- **Shared lab allocation:** Avoid overlapping usage for common resources.
- **Quick printable schedules:** Generate and print timetables for notice boards.

---

## 🛠️ Troubleshooting

### 1) Page does not load correctly
- Ensure internet access is available (Tailwind is loaded from CDN).
- Hard refresh the page (`Ctrl+F5` / `Cmd+Shift+R`).

### 2) Timetable generation error or empty output
- Check that each selected branch has sections, subjects, and faculty mapped.
- Remove conflicting or incomplete cross-branch assignments and regenerate.

### 3) Faculty timetable missing entries
- Verify faculty names are mapped consistently (spelling/case).
- Re-run generation after configuration updates.

### 4) Print output not formatted as expected
- Use browser Print Preview.
- Disable browser-added headers/footers if needed.
- Prefer latest Chrome/Edge for best print CSS support.

---

## 🤝 Contributing

Please read [`CONTRIBUTING.md`](./CONTRIBUTING.md) before submitting changes.

## 📜 License

This project is licensed under the MIT License - see [`LICENSE`](./LICENSE).

## 📝 Changelog

Project updates are tracked in [`CHANGELOG.md`](./CHANGELOG.md).
