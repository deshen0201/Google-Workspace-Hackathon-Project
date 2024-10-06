## Google Workspace Hackathon Project - Improve Confidential Mode on Gmail

### Overview
This project was developed for the Google Workspace Hackathon to enhance the confidentiality and privacy features of Gmail by introducing a "View Once" feature. The feature improves security for sensitive emails, limiting recipients to a single view, and adds a new layer of protection to Gmail's confidential mode.

### Features
- **View Once Feature**: Emails can be viewed only once by the recipient, preventing sensitive information from being re-accessed or forwarded.
- **Regular and Once-View Emails**: Users can choose between sending a regular email or a once-view email for added confidentiality.

### How It Works
The web application is built using Google Apps Script and HTML/JavaScript to create a custom UI for sending emails through Gmail. The core functionality includes:
- An interface for composing an email and selecting a view type (regular or once-view).
- Logic for rendering the email to the recipient, with once-view emails restricted to a single interaction.

### Technologies Used
- **Google Apps Script**: Backend logic for integrating with Gmail.
- **HTML/CSS/JavaScript**: Frontend development for the user interface.

### Project Files
- `.clasp.json`: Configuration for Google Apps Script project management.
- `Code.js`: Script that handles the server-side logic for the project.
- `index.html`: The HTML and JavaScript that creates the email interface.
- `appsscript.json`: Project settings for the Google Apps Script environment.
- `.gitignore`: Specifies which files or directories to ignore in the repository.

### How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/deshen0201/google-workspace-hackathon.git
   ```
2. Set up Google Apps Script integration using the provided `Code.js` file.
3. Deploy the script as a web app to start sending emails with enhanced confidentiality.

### License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
