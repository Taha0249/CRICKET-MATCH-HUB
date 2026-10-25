Cricket Match Hub 🏏
A cricket-themed dashboard built with HTML and CSS. Cricket Match Hub brings key match information together in one place, with a featured scorecard, upcoming fixtures, a points table, and links to cricket resources. The project is currently a static front-end prototype, with interactive and data-driven functionality planned for future updates.
Project status: Front-end design in progress · Functionality coming soon

Overview
Cricket Match Hub is designed as a simple, easy-to-read interface for cricket fans. The page uses a dark maroon and gold colour palette, translucent panels, rounded corners, and hover effects to give the dashboard a consistent visual style.

The current version focuses on the page structure and styling. Scores, fixtures, and standings are displayed as sample/static content; they are not connected to a live cricket data source.
Features
Featured match scorecard
- Displays the teams playing in the featured match.
- Shows each team's score and overs.
- Includes match format, venue, and date.
- Uses separate team panels to make the scores easy to compare.
Upcoming matches
- Lists upcoming fixture examples in a dedicated section.
- Uses styled list items and hover effects to make the section easier to scan.
Points table
- Organises team standings in a table.
- Includes position, team name, matches played, wins, net run rate (NRR), and points.
- Uses contrasting table headers and row borders for readability.
- Includes a hover style to make rows easier to identify.
Navigation links
- Provides links to external cricket resources, including the International Cricket Council (ICC) website and ESPNcricinfo.
- Opens external links in a new browser tab.
Visual design
- A branded page header with a logo image.
- A cricket-themed background image.
- A consistent maroon, gold, and light-neutral colour scheme.
- Rounded panels, spacing, borders, transparency, and CSS transitions.
- A Flexbox layout for arranging the main sections.
Built With
- HTML5 — page structure and content.
- CSS3 — layout, colours, typography, backgrounds, borders, hover effects, and transitions.
- Visual Studio Code — development editor.
- Git and GitHub — version control and project hosting.
The current version does not require JavaScript, a backend, or a database.
Project Structure
Keep the following files in the project folder so the page can load its styles and images correctly:
Cricket Match Hub/
├── index.html
├── style.css
├── wclogo.jpg
└── moment of match.avif
- index.html contains the page content and links to the stylesheet.
- style.css contains the visual design and layout rules.
- wclogo.jpg is used for the header logo.
- moment of match.avif is used as the main content area's background image.
If you rename an image or move it into another folder, update its file path in the HTML or CSS accordingly.
Run Locally
No installation or build step is required.
1. Download or clone this repository.
2. Open the project folder in Visual Studio Code, or open index.html directly in a web browser.
3. Keep index.html, style.css, and the image assets in the expected locations.
4. Refresh the browser after making changes to the code.
For a smoother development experience, you can use the Live Server extension in VS Code to preview the page locally.
Current Limitations
- Match scores, overs, fixtures, and points-table values are static examples.
- The page does not fetch live scores or update match information automatically.
- Links to cricket websites are external resources, not integrated data feeds.
- Responsive styling for smaller screens is still to be improved and tested.
- There is no user login, database, API integration, or server-side functionality in the current version.
Roadmap — What's Coming Next
The next phase is to turn the static design into a more functional cricket dashboard. Planned improvements include:
- [ ] Responsive layout: improve the layout for phones, tablets, and desktop screens.
- [ ] JavaScript functionality: add behaviour beyond static HTML and CSS.
- [ ] Live match data: explore integrating a reliable cricket scores API, subject to its availability and terms.
- [ ] Dynamic fixtures and standings: display updated match schedules and points tables when a suitable data source is connected.
- [ ] Improved match details: provide clearer match status and additional score information.
- [ ] Usability and accessibility: refine keyboard navigation, contrast, labels, and overall readability.
These are planned enhancements, not features available in the current version. The project will be updated as development progresses.
Learning Goals
This project is helping develop practical front-end skills, including:
- Structuring a webpage with semantic HTML elements.
- Styling layouts with CSS and Flexbox.
- Working with images and relative file paths.
- Designing tables, lists, and content sections.
- Using hover states and CSS transitions.
- Organising a project and publishing it through GitHub.
Contributing and Feedback
This is a learning project and will continue to evolve. Suggestions for improving the layout, responsiveness, accessibility, or future functionality are welcome.
Disclaimer
Cricket Match Hub is an independent learning project and is not affiliated with the ICC, ESPNcricinfo, or any cricket board. Team names and cricket-related references are used for demonstration. The displayed match information and standings are static sample content and should not be treated as verified live data. Third-party names and logos remain the property of their respective owners.
More functionality is coming soon. The goal is to build on this front-end foundation and gradually turn Cricket Match Hub into a more useful, interactive cricket dashboard.

