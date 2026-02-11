### OpenTask: Privacy-First Local Task Tracker
OpenTask is a lightweight, high-performance task management and time-tracking tool designed to run entirely in your browser. No databases, no logins, and zero data ever leaves your machine.

>#### Privacy & Security (The Core Principle)
>This application is built with a Local-Only philosophy:
>
>Zero Connectivity Required: Works 100% offline. You don't even need an internet connection to track time or generate reports.
>
>No Tracking/Analytics: No telemetry, no "phone home" scripts, and no third-party cookies.
>
>Your Data, Your Files: Your data is stored in your browser's memory while you work. To keep it permanently, use the Save button to export a .json file that you control.
>
>Open Source: Transparent code ensures you know exactly how your data is handled.

>#### Key Features
>Live Time Tracking: Accurate to the second with a real-time "ticking" dashboard.
>
>Singletasking Mode: Automatically stops overlapping tasks to ensure focus and log accuracy.
>
>Intelligent Reporting: * Generates clean .txt reports with total hours, task descriptions, and manual notes.
>
>Smart calendar logic: Automatically detects if you need "Last Week" or "Current Week" based on today's date.
>
>Drag-and-Drop: Easily reorder your task priority list.
>
>Persistence: Save and load multiple project files easily.

>### Installation & Usage
>Since OpenTask is a single-file application, there is no "installation" process.
>
>Download the index.html file.
>
>Open it in any modern web browser (Chrome, Firefox, Safari, Edge).
>
>Start Tracking.
>
>Tip: You can bookmark the file in your browser or keep it on a USB drive to carry your workspace with you.

>#### Reporting Logic
>The report generator uses Local Calendar Boundaries:
>
>Last Week: If today is Thursday or later, it assumes you want to report on the current work week (Mon–Sun). Otherwise, it generates a report for the previous full week.
>
>Last Month: If today is the 20th or later, it targets the current month. Otherwise, it pulls the previous full month.

>#### Technical Stack
>HTML5/CSS3: Using CSS Variables for instant theme switching and Flexbox for a responsive layout.
>
>Vanilla JavaScript (ES6+): No frameworks, no dependencies, no npm install. Just clean, readable code.
>
>Blob API: Used for generating local file downloads for reports and data backups.

>#### License
>This project is open-source and available under the MIT License. Feel free to fork, modify, and share.