# Forecast-Calamity
Offline Landslide Alert and Response System with USSD-style interface for real-time safety reporting.

This is an offline demonstration of the System.

The system simulates a USSD-based communication and alert network that can operate even when internet connectivity is poor or unavailable.

**HOW TO RUN THE PROJECT LOCALLY**

* Step 1: Open the backend

Open Command Prompt or Terminal.

Navigate to the project folder (the one containing this README file).

Example:

cd OLARSystem

Start the backend server:

node OLARSystem\_Backend.js

You should see this message:

OLAR USSD backend listening at http://127.0.0.1:3000

* Step 2: Open the frontend

Open a new Command Prompt or Terminal window.

From the same project folder, run:

npx serve .



When it says “Serving!”, note the local URL (example: http://localhost:57889

).



* Step 3: Open the system in a browser



Open the local URL shown in the previous step (e.g., http://localhost:57889

).



You will see the OLAR System Frontend.


**HOW TO TEST THE FEATURES**

Simulate USSD:

Enter Session ID (for example: s1)
Enter Phone Number (for example: +919876543210)

Leave Text Input empty and click “Send USSD”
Follow the menu prompts as displayed

View Reports:

Click “View Reports” or “Refresh Reports” to see the collected responses

Trigger Alerts:
Enter alert level (for example: high)
Enter message (for example: Heavy rain)
Enter area (for example: VillageA)

Click “Send Alert” to simulate a system alert

**EXPECTED OUTPUTS**
Backend console shows request logs such as:
ALERT triggered: high Heavy rain VillageA
Received USSD session inputs
Frontend shows:
USSD message responses
Alert confirmation messages

Reports count increasing when users respond

**NOTES**

Requires Node.js (version 18 or higher).
Internet connection not required once installed.
Works entirely offline.
Do not close either the backend or frontend terminal windows while testing.

**PROJECT INFORMATION**

* Project: Offline Landslide Alert and Response
* Type: Local Demo
* Frontend: HTML, CSS, JavaScript
* Backend: Node.js (Express.js)
