ABANDONED, NOT FORGOTTEN — PROJECT GUIDE

FILES
- index.html      Homepage with animated meteor / star background
- explorer.html   Searchable and filterable story explorer
- archive.html    All stories
- story.html      Individual story page (opens with ?id=...)
- lab.html        Interactive quiz and learning facts
- sources.html    NASA reference links
- admin.html      Demo admin login and content editor
- data.js         Default story data
- app.js          Site behavior, animations, local storage and admin functions
- styles.css      Dark space design and responsive layout

HOW TO RUN
1. Extract the ZIP to a normal folder (do not open files from inside the ZIP).
2. Open index.html in Chrome or Edge.
3. Click "Admin access" in the footer or open admin.html.
4. Demo credentials:
   Username: admin
   Password: space2026
5. Add/edit/delete stories, add an image URL or upload an image (up to 2 MB), and press Save story.

IMPORTANT LIMITATION
This is a static HTML/CSS/JavaScript demo intended to work by double-clicking index.html.
Admin edits are saved in the current browser's localStorage. They do not sync to other devices,
do not update the source files, and are not secure server-side authentication. Clearing browser
data may remove saved changes. For a public website with secure login and shared changes, use
a backend such as Flask/Node plus a database and upload storage.

NOTES
- The page uses remote Unsplash image URLs and Google Fonts, so those images/fonts need internet.
- The NASA links are reference starting points. Verify exact mission details against primary sources
  before presenting the project as a scientific archive.
- The English/Arabic button translates the main navigation labels as a small demo; full bilingual
  story content can be added through the admin content fields or future localization work.
