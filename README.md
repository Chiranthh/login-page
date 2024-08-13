Flask Email Application
Overview
This Flask application provides a simple email management interface where users can view, reply to, and delete emails. The interface supports keyboard shortcuts for enhanced usability:
•	"R" for replying to an email
•	"D" for deleting an email
Features
•	View Emails: Display a list of simulated emails.
•	Reply to Emails: Enter and send replies to selected emails.
•	Delete Emails: Remove emails from the list using keyboard shortcuts.
•	Keyboard Shortcuts: Use "R" to reply and "D" to delete emails.
Prerequisites
•	Python 3.x
•	Flask
Setup
1.	Clone the Repository
bash
Copy code
git clone <repository-url>
cd <repository-directory>
2.	Install Dependencies
Make sure you have Python installed. Then, install Flask using pip:
bash
Copy code
pip install Flask
3.	Run the Application
Navigate to the directory containing app.py and run:
bash
Copy code
python app.py
The application will start running on http://127.0.0.1:5000/.
4.	Access the Application
Open your web browser and go to http://127.0.0.1:5000/ to view the email dashboard.
Usage
1.	Viewing Emails
o	The main dashboard displays a list of emails with their subjects.
o	Click the "View" button next to an email to see its details.
2.	Replying to Emails
o	On the email detail page, type your reply in the text area and click "Send Reply".
o	Alternatively, press the "R" key to trigger the reply action.
3.	Deleting Emails
o	Use the "Delete" button next to an email to remove it from the list.
o	You can also press the "D" key to delete the currently selected email.
File Structure
/your-project-directory
│
├── app.py               # Main Flask application script
├── templates
│   ├── index.html       # Template for listing emails
│   ├── view_email.html  # Template for viewing an email
│   └── reply_sent.html  # Template for confirming reply
└── static
    └── styles.css       # Optional CSS file for styling
Troubleshooting
•	TemplateNotFound Error: Ensure that templates directory exists and contains index.html, view_email.html, and reply_sent.html.
•	JavaScript Issues: Verify that JavaScript code in HTML templates is correctly handling keypress events.

