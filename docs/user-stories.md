# User Stories

* **US1**
  * **User Story**: As an everyday user, I want to scan my current email for threats, so that I can know if it is a phishing attempt before interacting with it.
  * **Linked Requirement**: FR2, FR3, FR4
  * **Acceptance Criteria**: (1) Clicking the 'Scan' button extracts the email text. (2) The extension displays a clear "Safe", "Suspicious", or "Phishing" badge based on the text.

* **US2**
  * **User Story**: As a user, I want to view my past scan history, so that I can keep track of how many malicious emails I receive over time.
  * **Linked Requirement**: FR5, FR6
  * **Acceptance Criteria**: (1) The dashboard shows a list of previously scanned emails with their date and threat level. (2) The history persists even after closing and reopening the browser.

* **US3**
  * **User Story**: As a privacy-conscious user, I want the system to process my emails without saving the private text, so that my personal communications are not exposed.
  * **Linked Requirement**: NFR2
  * **Acceptance Criteria**: (1) The local database only contains the email subject, timestamp, and threat score, with the main body text excluded from the permanent log.
