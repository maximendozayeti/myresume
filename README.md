# HTML Resume Project
A simple single-page HTML resume for **Maximiliano Mendoza Gonzalez**, styled with a basic external CSS file.
## Project Structure
- `index.html` – Main resume page (this file)
- `public/`
  - `contact.html` – Contact page
  - `hobbies.html` – Hobbies page
- `images/`
  - `IMG_8672.JPG` – Profile picture
- `styles.css` (or similar) – External stylesheet referenced from the `<head>` (see notes below)
## Features
- **Profile section**
  - Name, resume title, and profile image
- **Two-column layout**
  - Left column: profile picture and quick link to Contact
  - Right column: main resume content
- **Sections included**
  - Summary
  - Education
  - Experience (detailed descriptions and responsibilities)
  - Skills
  - Hobbies (linked page)
- **Footer**
  - Copyright notice
## How to Use
1. Make sure the CSS file from your notes (e.g. `styles.css`) is saved in the same folder as `index.html` or in your preferred structure.
2. Link it in `index.html` inside the `<head>`:
   ```html
   <link rel="stylesheet" href="styles.css">
Open index.html in any modern web browser.
Click:
Contact in the left column to open the contact page.
Hobbies at the bottom of the main content to open the hobbies page.
Technologies Used
HTML5 – Structure and content
CSS3 – Basic layout and styling (external stylesheet)
No JavaScript required
Customization Ideas
Update text content (summary, experience, skills) as your career progresses.
Adjust layout and colors in the CSS file (e.g. fonts, spacing, column widths).
Replace the profile picture in images/IMG_8672.JPG with a new one.
Add more sections (e.g. Projects, Certifications, Languages).
