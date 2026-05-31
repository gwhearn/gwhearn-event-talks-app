# gwhearn-event-talks-app: Technical Talks Event Schedule

A simple, single-page web application to display the schedule for a 1-day technical talks event, featuring talk details and a category-based search functionality.

## Features

*   **Dynamic Schedule Display:** Shows a clear, time-ordered schedule of all technical talks.
*   **Talk Details:** Each talk displays its title, speaker(s), categories, duration, and a brief description.
*   **Lunch Break Integration:** A dedicated 1-hour lunch break is integrated into the schedule.
*   **Category Search:** Users can easily search and filter talks by category keywords.
*   **Single-Page Application:** All content is loaded on a single HTML page for a streamlined user experience.
*   **Serverless Deployment Ready:** The entire application is self-contained in a single `index.html` file, making it easy to deploy on any static file host.

## Technologies Used

*   **Frontend:**
    *   HTML5 (Structure)
    *   CSS3 (Styling, Responsive Design)
    *   JavaScript (Dynamic Content, Search Functionality)

*   **Build Tool (Conceptual):**
    *   Node.js (used to conceptually assemble the `index.html` file by combining HTML, CSS, and JS, but not required at runtime).

## How to Run Locally

To view and test this website on your local machine:

1.  **Clone the Repository (if not already done):**
    ```bash
    git clone https://github.com/gwhearn/gwhearn-event-talks-app.git
    cd gwhearn-event-talks-app
    ```
2.  **Ensure you have Python installed.**
3.  **Start a simple Python HTTP server** from the project root directory (where `index.html` is located):
    *   For Python 3:
        ```bash
        python3 -m http.server
        ```
    *   For Python 2:
        ```bash
        python -m SimpleHTTPServer
        ```
4.  **Open your web browser** and navigate to `http://localhost:8000` (or the address displayed in your terminal).

## Customization

You can easily customize the event details by modifying the `talkData` array directly within the `index.html` file.
*   Add, remove, or edit talk objects.
*   Adjust event start time, talk durations, or lunch break timings within the JavaScript `generateSchedule` function.
*   Update the `Date: May 31, 2026` in the `header` section.
*   Modify the CSS styles to match your branding.