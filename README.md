This project converts markdown meeting notes into a formatted Google Doc using the Google Docs API in Google Colab.

Setup Instructions
1. Install Dependencies
Run the following command in Colab to install required libraries:

python
Copy
Edit
!pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib
2. Authenticate in Google Colab
Run the script.
Authenticate using your Google account when prompted to allow access to the Google Docs API.
3. Run the Script
Provide the markdown meeting notes in the markdown_notes variable or read from a .md file.
The script will create a new Google Doc with formatted content based on the markdown.
4. Output
After running the script, the link to the newly created Google Doc will be displayed.

Requirements
Google Docs API
Google Drive API
Google authentication in Colab
How to Run
Open a new Google Colab notebook.
Paste the script into a code cell.
Run the cell.
Authenticate when prompted.
The Google Doc will be created, and a link will be shown.
