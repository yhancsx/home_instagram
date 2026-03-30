# Project Overview
This project is a simple static web application designed to display the 2026 season schedule for the "Home_Instagram" baseball team. The schedule is rendered dynamically using JavaScript from a JSON data source. It also includes functionality to download the rendered schedule as an image.

# Directory Structure & Key Files
*   `README.md`: Basic project title.
*   `2026/`: Contains the files for the 2026 season.
    *   `2026/index.html`: The main web page. It contains the HTML structure, CSS styling, and JavaScript to fetch the schedule data and render it into a table. It uses `html2canvas` to provide image download functionality.
    *   `2026/schedule.json`: The data source containing the list of baseball games, including dates, categories, opponents, and results.

# Building and Running
As a static web project, there is no build step required.
To view the site:
1.  Open `2026/index.html` directly in any modern web browser.
2.  Alternatively, serve the project using a local development server (e.g., `npx serve`, `python3 -m http.server`) from the project root.

# Development Conventions
*   **Data Updates:** The schedule and game results are updated by modifying the `2026/schedule.json` file. The frontend automatically reflects these changes.
*   **Technologies:** Plain HTML, CSS, Vanilla JavaScript, and the `html2canvas` library (via CDN).
