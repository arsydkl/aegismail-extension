# Requirements

## Functional Requirements
* **FR1**: The system shall allow users to register an account and log in via the browser extension.
* **FR2**: The system shall extract text from the currently open email in the Gmail web interface.
* **FR3**: The system shall classify the extracted email text as safe, suspicious, or phishing using a machine learning model.
* **FR4**: The system shall display the threat classification result and a brief warning description within the extension panel.
* **FR5**: The system shall log past scanned threats and their classification results in a local database.
* **FR6**: The system shall provide a dashboard interface for users to view their historical scan logs.

## Non-Functional Requirements
* **NFR1 (Performance)**: The threat classification result shall process and load within 3 seconds of initiating the scan.
* **NFR2 (Security)**: The system shall not store the full body content of scanned emails permanently; only metadata and the classification result shall be logged.
* **NFR3 (Usability)**: A user shall be able to initiate an email scan in 2 clicks or fewer from the Gmail interface.
