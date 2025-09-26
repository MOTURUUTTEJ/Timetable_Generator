# Timetable_Generator

Advanced Multi-Branch Timetable Generator
This is a powerful, self-contained, single-file web application for generating coordinated academic timetables across multiple university departments. It is built with vanilla JavaScript and Tailwind CSS, requiring no server or build process.

The application is designed to handle complex scheduling scenarios, including shared faculty between departments, limited lab resources, and section-specific configurations.


#✨ Core Features
📅 Multi-Branch Coordination: Select multiple departments (e.g., CSE, ECE, MECH) and generate a single, cohesive timetable that resolves conflicts for shared resources and faculty.

#👨‍🏫 Smart Conflict Resolution: The generation algorithm automatically prevents scheduling conflicts for:

  Faculty: Ensures a single faculty member is not assigned to two different classes at the same time, even across different departments.

  Shared Resources: Manages shared labs (e.g., "Computer Lab 1", "Electronics Lab") to prevent double-booking.

#🔗 Cross-Department Assignments: Easily assign a faculty member from one department to teach a subject in another, with clear visual indicators in the timetable.

🔧 Interactive Configuration: Before generation, you can fully customize each department's setup:

Add or remove sections.

Rename sections and assign section in-charges.

Add, remove, or edit subjects and labs.

Assign specific faculty to subjects on a per-section basis.

📊 Dual-View Timetables: View the generated schedules from two perspectives:

Student View: A traditional timetable for each section of each department.

Faculty View: A personal timetable for every faculty member, showing all their assigned classes. Includes a search function to quickly find a specific faculty member.

🚀 Self-Contained & Portable: The entire application is in a single .html file. No dependencies, no installation, no server required. It runs directly in any modern web browser.

#🖨️ Export and Print:

Export the complete timetable data (student schedules, faculty schedules, resource utilization) as a single JSON file.

A print-friendly stylesheet allows for clean printing or saving of timetables as PDFs.

#🚀 How to Use

Open the file in a modern web browser (like Chrome, Firefox, or Edge).

Follow the on-screen steps:

Select the departments you want to schedule.

Configure the sections, subjects, and faculty for each selected department.

Generate the coordinated timetables.

View, print, or export the results.

#🛠️ Technology Stack
Front-end: HTML5, Vanilla JavaScript (ES6+)

Styling: Tailwind CSS (via CDN), with custom inline styles for theming and print.

Architecture: The application is a state-driven Single Page Application (SPA) without any framework. A central state object holds all the data, and a render() function updates the UI whenever the state changes.
